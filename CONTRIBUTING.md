# Contributing
# I want to add my application
To add your application you need to have `manifest-info.json` file. It is required to have link in *manifest-info*.
Here is an example of good *manifest-info*:
```jsonc
// Good `manifest-info` example
{
    "name": "informative_name",                                               // REQUIRED
    "description": "Here is my great application that I'm ready to publish.", // 
    "author": "informative_author_name",                                      // 
    "version": "1.0.0",                                                       // REQUIRED
    "agree": true,                                                            // REQUIRED
    "link": "https://...",                                                    // REQUIRED
    "company": ""                                                             // 
}
```
Here is a **BAD** example of *manifest-info*:
```jsonc
// BAD `manifest-info` example
{
  "name": "AmAZ%*ing.,/\aPPlICAT%!ion"
                    "author": "somebody",
"version": "Why would I need a version?",    // :D PLEASE aDd my apP:)
    "agree": false
}
```
## Name requirements
Your name must be from **a** to **z**, contain only lowercase characters. It can also contain these characters: `-_0123456789`.<br>
Here is a regex of name requirements: `[a-z0-9_\-]`.
## Version requirements
Regex: `(\d\.){2}\d{1,4}`
## Agreement
You have to set "`agree`" to `true` if you agree and you want to publish your application.
## Identation requirements
*manifest-info* should have at least 1 tabulation. Identation mustn't change.
## Publishing
Create an issue with the [following format](https://github.com/ProgramPack/hub/blob/main/ISSUE-TEMPLATE). Change the "`[]`" fields to your information. Submit an issue and wait for answer.
### Wrong format
You cannot sumbit your app with wrong format. Issue will be declined.
### As PR
PRs (*Pull Requests*) are not supported now. Only [these pulls](https://github.com/ProgramPack/hub/blob/main/CONTRIBUTING.md#i-want-to-correct-something-in-this-repository) are accepted.
### Owner
Owner also can create issues and accept them by himself.
# I want to correct something in this repository
Send a pull request. It will be reviewed by trusted members.
