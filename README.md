# Vim & Terminal Configuration

This repository contains my basic Vim and terminal settings, including:

- `.vimrc` - Configuration file for Vim
- `.bashrc` - Bash shell configuration file

## Installation

To apply these configurations to your system, follow these steps:

### **1. Clone the Repository**
```sh
cd ~  # Navigate to your home directory (or wherever you prefer)
git clone https://github.com/your-username/repo-name.git
cd repo-name
```

### **2. Backup Existing Config Files (Recommended)**
Before applying the new settings, create backups of your current configuration files:
```sh
cp ~/.vimrc ~/.vimrc.backup
cp ~/.bashrc ~/.bashrc.backup
```

### **3. Copy the Files to the Correct Location**
```sh
cp .vimrc ~/.vimrc
cp .bashrc ~/.bashrc
```

### **4. Apply the Changes**
For `.bashrc`, apply changes immediately by running:
```sh
source ~/.bashrc
```

For Vim settings, simply restart Vim, or use:
```sh
vim +PlugInstall  # If using Vim-Plug for plugins
```

## Customization
Feel free to modify these configuration files according to your needs. You can make changes directly in your local repo and push them to GitHub.

## Updating Configurations
If you update your local `.vimrc` or `.bashrc`, you can push the changes to GitHub:
```sh
git add .vimrc .bashrc
git commit -m "Updated configurations"
git push origin main
```

## License
This project is open-source under the MIT License.

