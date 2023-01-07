# chocolateyPackages
Chocolatey is a windows package manager to install and update applications

My Software Packages are listed in install.ps1

To install (Open Powershell) 
# https://chocolatey.org/install#individual
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))

To find More packages:
# https://community.chocolatey.org/packages
