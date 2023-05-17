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
  "version": "Why would I need a version?",
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
## Publishing
This section is incomplete.
