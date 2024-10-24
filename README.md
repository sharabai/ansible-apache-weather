# Ansible Apache Weather

## Description
This project automates the installation and configuration of Apache on both Windows and Linux using Ansible. It includes custom templates for a landing page and opens the HTTP port for web access. The landing page template is generated using the OpenWeather API.

Sensitive data, such as the OpenWeather API key and user credentials for different groups, is securely encrypted with Ansible Vault. 

The script is designed for fresh installations on Windows Server and Ubuntu Server, with basic SSH configuration set up for Windows. It assumes that SSH is used with PowerShell as the default shell. Additionally, the script fetches weather data from the control node, which is specified as the host in the main group (this group should contain only one host).

## License
This project is licensed under a custom restrictive license. All rights are reserved. You may not use, modify, or redistribute this code without explicit permission. Use by automated systems, including AI, is strictly prohibited.

For more details, refer to the [LICENSE](./LICENSE) file.
