# Developer setups

Settings and extensions files for Cursor.

## Cursor Profiles

Profiles for different development scenarios:

- **Minimal**: A base profile with essential editor settings and general-purpose extensions (TOML, GitLens, Material theme, Rainbow CSV, YAML).
- **Python-Minimal**: Extends the Minimal profile with Python-specific configurations, including Ruff formatter, Jupyter notebook support, and Python development extensions.

### Profile Hierarchy

```
    Minimal
      │
      ├── Base editor settings
      ├── General extensions
      │
      └── Python-Minimal
            │
            ├── Inherits all Minimal settings
            ├── Python-specific settings (Ruff, format on save)
            └── Python extensions (Jupyter, Python, Ruff, CursorPyright)
```
