---
name: Application request template
about: Request an application
title: "[APP REQUEST] "
labels: app request
assignees: ''

---

**[Required] Please put content of `manifest-info` here**
```jsonc
{
    "name": "informative_name",                                               // REQUIRED
    "description": "Here is my great application that I'm ready to publish.", // 
    "author": "informative_author_name",                                      // 
    "version": "1.0.0",                                                       // REQUIRED
    "agree": false,                                                           // SET TO "TRUE" IF YOU AGREE
    "link": "https://...",                                                    // REQUIRED
    "company": "",                                                            // 
    "image": ""                                                               // OPTIONAL: BASE64-ENCODED IMAGE DATA (you can use the website https://base64.guru/converter/encode/image). Set output format to "Data URI".
}
```
**[Required] Are you sure that you want to publish this app?**
No, I do not want to publish this app.
**[Optional] Please put long description here**
*Not given*
**[Optional] Do you need an image for this app? If so, please put it in "`image`" category.**
**If not, don't put it and left this field unfilled.**
No, I don't have it.
