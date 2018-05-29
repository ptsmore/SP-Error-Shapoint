# sharepoint - edit web.config to show more error "An unexpected error has occurred."
if see this error just go to web.config of this port and set
1.debug = true at tag compilation batch="false" debug="true">

2.CustomError="Off" at tag customErrors defaultRedirect="" mode="Off">

3.CallStack="true" at tag SafeMode MaxControls="200" CallStack="true" DirectFileDependencies="10" TotalFileDependencies="250" AllowPageLevelTrace="false">
