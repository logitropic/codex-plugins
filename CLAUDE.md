# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

This is a **plugin marketplace registry** for Claude Code. It does not contain plugin source code directly. Instead, it provides a `marketplace.json` manifest that points to plugins hosted in external repositories.

## Structure

- `.claude-plugin/marketplace.json` - The plugin registry manifest. Defines available plugins, their categories, and source locations.

## Plugin Sources

Plugins listed here are sourced from external repositories:

- **conductor** - https://github.com/Logitropic/conductor (path: `plugins/conductor`)

## Marketplace Schema

The marketplace uses Anthropic's plugin marketplace schema (`https://anthropic.com/claude-code/marketplace.schema.json`). Each plugin entry includes:
- `name`, `description`, `category`
- `source` with `url` and `path` to the plugin directory within that repo
- `homepage` for documentation links
