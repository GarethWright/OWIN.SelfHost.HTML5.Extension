# OWIN.SelfHost.HTML5.Extension
Extension methods and helper for no conflict self hosting html5mode apps with routing
It took a lot of searching and trial and error to get a simple way of doing this, so posting my final working code to Github so you don't have to go through the pain I did!

I.e using http://localhost/Dashboard will route to /index.html and javascript based routing will handle rendering without throwing a 404 response.

Ideal for using with Client Builds of Meteor or Angular Apps.

` appBuilder.UseHTML5Server(Settings.Default.clientFolder, "/index.html");`

 `appBuilder.UseHTML5Server(@"c:\wwwDocs", "/index.html");`
