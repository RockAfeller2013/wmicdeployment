#--------------------------------------------------
# Use Windows WMIC to install/remove software 
# https://docs.microsoft.com/en-us/previous-versions/windows/it-pro/windows-2000-server/bb742610(v=technet.10)?redirectedfrom=MSDN
#--------------------------------------------------
1. Runas /user:DomainAdminAccount@DOMAIN cmd
2. type wmic
3. /node::@c:\computers.txt product call install true,",c:\PathToYour\File.msi
