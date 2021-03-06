## Lesson 3: Publishing the Codelab

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
    "description": "<lab description>"
  }
```

Alternatively, you could send an email to iodev@adobe.com with some introduction and codelab details as above, and we will take care of publishing it for you.  

[Next](/lessons/welldone.md)
