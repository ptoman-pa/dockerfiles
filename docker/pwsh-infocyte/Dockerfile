
FROM demisto/powershell:7.3.0.49844

RUN pwsh -c "Set-PSRepository -Name PSGallery -InstallationPolicy Trusted -ErrorAction Stop"
RUN pwsh -c "Install-Module -ErrorAction Stop InfocyteHUNTAPI -Scope AllUsers"
