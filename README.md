# Extension Privacy Policy

## Intro

Different extensions use personal data in different ways. This privacy policy encompasses general principles of how extensions I create collect and handle personal data. The privacy policy of individual extensions will be attached to each individual extension.

## Secure WhatsApp
### Purpose of the extension
Analyse messages, images, and hyperlinks received in the WhatsApp Web website to alert the user if they contain any malicious content. The messages are sent to an external API to determine this. The API can be changed by the user. The deafult API does not store any user information.

### Data Collection

This extension does not collect any data at all. Since no data is collected, it stands to reason, and is, indeed, the case, that none of your data can be sold to third parties.

That being said, there are a few other ways your data is used. For example, small chunks of unidentifiable information from your WhatsApp messages will be sent to different API's for checking their safety and possibility of malicious content.

### Chrome Storage API

This extension takes advantage of [Google Chrome's Storage API](https://developers.chrome.com/extensions/storage) to locally store minimal state information. This is similar to a [cookie](https://developer.mozilla.org/en-US/docs/Web/HTTP/Cookies). Examples of data stored this way include preferences you have for how the extension should work, like enabling or disabling password protection, or reseting your password. Google syncs this information across your various computers and Chrome installations. However, my extensions only access this data locally on your machine and they do not transmit it. 
Currently, the default API (which can be changes by the user), makes use of the following services:
- [Azure Content Moderator](https://learn.microsoft.com/en-us/azure/ai-services/content-moderator/overview) for checking the safety of text messages and images.
- [Virus Total](https://www.virustotal.com/gui/home/upload) for checking the safety of hyperlinks.

### Third-Party APIs

The extension requires the use of a third party API to check your WhatsApp messages. This API does not collect any identifiable information, nor stores the data that is being received. It simply checks the safety of the message and sends the response back to the user. 
The API endpoint to use for the safety checking can be changed at any time by the user in the extension pop-up. This allows users to build their own API's to check the safety of incoming messages.

## Changes to the Privacy Policy

If there are substantive changes made to this blanket privacy policy or to the individual privacy policies of any of my extensions, I will push out a new version of the affected extension(s) and ask you to agree to the amended privacy policy.

## Feedback and support
If you have questions or concerns about this privacy policy, feel free to [send me an email](mailto:mateusz.alicante@gmail.com) .
