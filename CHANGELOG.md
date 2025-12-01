# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.0] - 2024-12-01

### 🎉 Initial Release

#### Core (`@bw-ui/datatable`)

- **Sorting** - Click column headers, multi-column with Shift+click
- **Filtering** - Global search across all columns
- **Pagination** - Built-in controls with configurable page size
- **Inline Editing** - Double-click to edit cells (text, number, boolean, select)
- **Row Selection** - Single/multi-select with checkboxes
- **Keyboard Navigation** - Arrow keys, Enter, Escape, Tab
- **Custom Rendering** - Column render functions for custom cell content
- **Theming** - CSS custom properties for full customization
- **Zero Dependencies** - Pure vanilla JavaScript (~32KB minified)

#### Plugins

##### `@bw-ui/datatable-history` (~3KB)

- Undo/Redo functionality
- Keyboard shortcuts: Ctrl+Z, Ctrl+Y, Ctrl+Shift+Z
- Configurable max history size
- Track edits, sort, filter changes

##### `@bw-ui/datatable-export` (~2KB)

- Export to JSON file
- Export to CSV file
- Copy to clipboard (tab-separated for Excel)
- Selected rows only option
- Visible columns only option

##### `@bw-ui/datatable-url-state` (~2KB)

- Sync sort, filter, page to URL
- Shareable links
- Browser back/forward support
- Auto-restore state on page load

##### `@bw-ui/datatable-clipboard` (~3KB)

- Copy selected rows (Ctrl+C)
- Paste from Excel/Sheets (Ctrl+V)
- Smart type conversion on paste
- Append or replace mode

### 📦 Packages

| Package                      | Version | Size  |
| ---------------------------- | ------- | ----- |
| `@bw-ui/datatable`           | 1.0.0   | ~32KB |
| `@bw-ui/datatable-history`   | 1.0.0   | ~3KB  |
| `@bw-ui/datatable-export`    | 1.0.0   | ~2KB  |
| `@bw-ui/datatable-url-state` | 1.0.0   | ~2KB  |
| `@bw-ui/datatable-clipboard` | 1.0.0   | ~3KB  |
