# Alpha-Launch-Demo
Project files used in the the Alpha Anywhere Demo and Q&amp;A on May 5, 2021

## What's in this Repository

3 components:
 
 - basic.a5w: a basic UX that displays a message. ControlBar contains the Exit App Button.
 - ajax.a5w: a basic UX that makes an ajax callback to display a message. ControlBar contains the Exit App Button.
 - dependencies.a5w: a basic UX that contains two embedded components, basic.a5w and ajax.a5w. Does *not* contain an Exit App button because the embedded components include them. Also uses a tabband subtheme called "primary", which is set in the PanelNavigator properties.


1 **POWER**point presentation:
 
 - powerpoint/AlphaLaunch.pptx: The slides from the webinar presented on May 5, 2021
 - powerpoint/AlphaLaunch.pdf: PDF version of the slides from the webinar presented on May 5, 2021

A README.md:
 
 - The file that defines this text

.gitignore:
 
  - A list of files to NOT commit to this repo

## Try it out!

[Following these instructions](http://alpha-shell-qrcode.s3.amazonaws.com/alphalaunch/AlphaLaunch_6077b1e193cb4262a6e71be9b5d0816d.html) to install the apps in this repository in Alpha Launch.

![image](https://user-images.githubusercontent.com/17854599/117205047-15246e80-adbf-11eb-8a67-92c946ac1b23.png)

## Further Reading

Alpha Cloud:
- [Publishing to Alpha Cloud](https://documentation.alphasoftware.com/documentation/index?search=getting%20started%20deployment)

Application Server for IIS:
- [IIS Getting Started Guide](https://documentation.alphasoftware.com/documentation/index?search=iis%20getting%20started%20guide)

Classic Application Server:
- [How to Configure and Publish an Alpha Anywhere Application to a server Using HTTP Publishing](https://documentation.alphasoftware.com/documentation/index?search=publishing%20to%20a%20remote%20server%20using%20http)
- [How to Publish Multiple Web Projects Using Subfolders on the Classic Server](https://documentation.alphasoftware.com/documentation/index?search=publish%20multiple%20web%20projects%20and%20use%20subfolders)
- [How to Test Connection Strings on the Classic Application Server](https://documentation.alphasoftware.com/documentation/index?search=test%20connection%20string%20on%20server)
- [How to Publish an Alpha Anywhere Application to a Remote Server Using FTP](https://documentation.alphasoftware.com/documentation/index?search=publishing%20to%20a%20remote%20server%20using%20ftp)
