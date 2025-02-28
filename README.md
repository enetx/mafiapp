# Installation

Mafi can be installed via Homebrew using one of the following methods:

### Via tap

```bash
 brew tap enetx/tap
 brew install mafi
```

### Direct Installation

```bash
 brew install enetx/tap/mafi
```

# Ignore Rules

Mafi supports ignore rules similar to .gitignore. You can create a .ignore file in your home directory to exclude specific files and folders from processing. The format follows standard ignore file syntax:
### Example .ignore:

```bash
# Ignore hidden files and directories
.*

# Allow ~/.config/
!/.config/

# Ignore system directories
node_modules/
target/
build/

# Ignore temporary files
*.log
*.tmp
*.lock
*.pyc

# Ignore sensitive files
config.json
secrets.env
db.sqlite
```

Place this file in your home root, and Mafi will automatically exclude the specified files and directories.



# Additional Resources

For more information and guides on using the application, visit the [official project page](https://mafiapp.com).
