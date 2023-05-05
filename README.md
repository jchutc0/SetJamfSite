# SetJamfSite
A powershell script to set an extension attribute to the site of Jamf computers and 
devices

Current versions of Jamf do not allow reporting or criteria based on the Jamf site a 
device (computer or mobile device) belongs to. The script here can be run on a Jamf 
server to get information about a list of devices, find the Jamf site from that 
information, and set an extension attribute to the value of the site.

It connects using the Jamf REST API and requires an account with access to read and
write to computers and/or mobile devices, depending on usage.
