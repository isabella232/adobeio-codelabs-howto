# Lesson 3: Publishing the codelab

As mentioned in lesson 2, your codelab is accessible publicly via this URL: `https://<repo-name>-<repo-owner>.project-helix.page`.  

In order for your codelab to be available in the Adobe I/O CodeLabs website, please open a PR to [the CodeLabs website repository](https://github.com/AdobeDocs/adobeio-codelabs), with following data in the `/actions/index.json` file.

```json
{
    "repo": "<URL of your repo>",
    "url": "<URL of your lab, if it is published in github page>",
    "author": "<your name>",
    "published": "<date of PR creation>",
    "thumbnail": "<URL of the lab thumbnail, if necessary>",
    "duration": <estimated duration of the lab in minutes>,
    "title": "<lab title>",
    "description": "<lab description>",
    "type": "lab"
  }
```

Alternatively, you could send an email to adobeio@adobe.com with some introduction and the above details, and we will take care of publishing the lab for you.  

This is the end of the codelab. We hope you enjoyed it!