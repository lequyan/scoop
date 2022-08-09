# PowerShell - right click - run as admin

cd ~

Set-ExecutionPolicy RemoteSigned -scope CurrentUser

A

iwr -useb get.scoop.sh -outfile 'install.ps1'

.\install.ps1 -RunAsAdmin

scoop install gow
