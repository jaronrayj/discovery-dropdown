# discovery-dropdown

Simple discovery page setup!

There is a section in the [index.html](https://github.com/jaronrayj/discovery-dropdown/blob/master/index.html) that you will need to edit to your specific domain and authentication type.

Also, you can set up your own logo by replacing "replaceMeWithUrl" with your logo url. 

Within the Script tags near the top of the page - 

    `// Student / Teacher Url
    var studentTeacherUrl = "https://DOMAIN.instructure.com/login/saml"`
    *Replace DOMAIN with your Canvas url domain
    *Replace saml with whatever authentication you want to utilize. You can ask your Customer Success Manager if you are uncertain.

    `// Parent Url
    var parentUrl = "https://DOMAIN.instructure.com/login/canvas"`
    *Replace DOMAIN with your Canvas url domain

    `// Change this to your icon if you want your logo on the discovery page
    var imgPlaceholder = "replaceMeWithUrl"`
    *Replace replaceMeWithUrl with your logo url

For more information you can check these resources - 
[Discovery Page Info](https://community.canvaslms.com/docs/DOC-14067-why-a-discovery-page-also-what-is-a-discovery-page)


[More information](https://docs.google.com/document/d/1BYNVvp2HO4zGWMAHm5rKcCXzdcfAASQGmHGPUXOQxjQ/edit?ts=5e6f9b77)