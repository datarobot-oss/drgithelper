# drgithelper

Git credentials helper binary for DataRobot Notebooks & Codespaces

## Environment Variable Configuration

These are environment variable values respected by the binary:

 - `GITHELPER_LOGGER_ENABLE` (default: `true`) - Enable/Disable logging to file
 - `GITHELPER_LOGGER_PATH` - Path to log file. By default its ${HOME}/.drgithelper.log
 - `GITHELPER_LOGGER_LEVEL` (default: `DEBUG`) - Log level
 - `GITHELPER_REGISTER_CREDS_HELPER` (default: `true`) - Register git credentials helper
 - `GITHELPER_CONFIG_AUTHOR_INFO` (default: `true`) - Setup git author info (user name & email) based on the DataRobot user information
 - `GITHELPER_CONFIG_URLS` (default: `true`) - Setup git to redirect SSH to HTTPS
 - `GITHELPER_CONFIG_GITIGNORE` (default: `true`) - Setup global git ignore
 - `GITHELPER_GITIGNORE_PATH` - Global gitignore file. By default its ${HOME}/.drgithelper_gitignore
 - `GITHELPER_GITIGNORE_FILES` (default: `.bash_history`) - Comma separated git ignored files
