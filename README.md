# AVDLevelup
# In an Azure VDI environment using FSLogix for profile creation, it is necessary to create an FSLogix Group Policy Object (GPO) in Active Directory. Since the FSLogix GPO is not built-in, it needs to be downloaded and certain procedures must be followed.
# The provided files here have simplified these procedures. After downloading the FSLogix_Gpo.zip file, please unzip it.
   1. Once you have extracted the files, execute the "Create-GPO-FSlogix.ps1" script.
   2. After running Group Policy Management, please check if there is a 'Machine-FSLogix' policy under 'Group Policy Objects'.
