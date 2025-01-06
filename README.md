# installDigiCert
installDigiCert

Steps to Launch the .ps1

Replace "C:\path\to\your\certificate.pfx" with the actual path to your .pfx file

Replace "YourPassword" with the password for your .pfx file.

Save the script as InstallSSL.ps1.

Open PowerShell with administrative privileges.

Run the script:
.\InstallSSL.ps1

This script will install the SSL certificate in the "Personal" store of the local machine. Adjust the $CertStoreLocation variable if you need to install it into a different store.
