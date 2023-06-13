# PocketBaseService
Installer to run PocketBase as a Windows service.

Uses WinSW to run PocketBase as a service - https://github.com/winsw/winsw

## Quick Start

Run the installer as admin and PocketBase will be available on http://localhost:8090

See PocketBase documentation for further setup and configuration - https://pocketbase.io/docs/

## Installer UI

![image](https://github.com/ope-nz/PocketBaseService/assets/26259049/15b4031b-3600-46ce-a12e-45925111ffc3)

![image](https://github.com/ope-nz/PocketBaseService/assets/26259049/76a259e7-1e55-4148-af98-5000340b19c0)

Which will deploy a windows service called PocketBase

![image](https://github.com/ope-nz/PocketBaseService/assets/26259049/32f85358-e2de-48b6-81a8-45fdaa82971a)

## Alternate Setup

The installer is a WinRAR self-extracting archive so if you prefer you can simply unzip the files using WinRAR. To register PocketBase as a service run "install_service.bat" as admin.

## To Remove Service

To remove the service run "delete_service.bat" as admin.
