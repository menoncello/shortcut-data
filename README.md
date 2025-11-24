# Shortcut Data Repository

This repository contains keyboard shortcuts data for the Shortcuts Learning App.

## Structure

```
apps/
├── neovim/
│   ├── navigation/
│   │   └── navigation.yaml
│   ├── editing/
│   │   └── editing.yaml
│   └── search/
│       └── search.yaml
└── aerospace/
    ├── window-management/
    │   └── window-management.yaml
    └── workspace/
        └── workspace.yaml
```

## Data Format

Each shortcut is defined in YAML format with the following structure:

```yaml
shortcuts:
  - keys: "Ctrl+C"
    description: "Copy selected text"
    context: "General"
    difficulty: "beginner"
  - keys: "Ctrl+V"
    description: "Paste copied text"
    context: "General"
    difficulty: "beginner"
```

## Contributing

1. Follow the existing directory structure
2. Use YAML format for data files
3. Include proper descriptions for shortcuts
4. Test data with the validation tools provided in the main application