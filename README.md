# downsizing-js-css
Demo project implementing "Sitecore.Foundation.Assets" with some changes 
The DLL are pointing to Sitecore 9.01, but I tested on Sitecore 9.02 and it worked as well


1)Changes on Web.config

on the node <@runtime>
Copy the follow and Replace @ for Empty and # for Empty strings as well

@<dependentAssembly #>
@    <@assemblyIdentity name="WebGrease" publicKeyToken="31bf3856ad364e35" culture="neutral" #/>
@    <bindingRedirect oldVersion="0.0.0.0-1.5.1.25624" newVersion="1.6.5135.21930" #/>
@</dependentAssembly #>

2)Sync your TDS projects
3)Create and Simple Item,
3.1)Change the Layout to use "Rendering asset Layout",
3.2)Add the demo rnedering called "RenderingAssets"


