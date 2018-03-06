---
date: 2018-03-06T10:54:32Z
title: "jx create issue"
slug: jx_create_issue
url: /commands/jx_create_issue/
---
## jx create issue

Create an issue on the git project for the current directory

### Synopsis

Creates an issue in a the git project of the current directory

```
jx create issue [flags]
```

### Examples

```
  # Create an issue in the current project
  jx create issue -t "something we should do"
  
  
  # Create an issue with a title and a body
  jx create issue -t "something we should do" --body "
  some more
  text
  goes
  here
  ""
  "
```

### Options

```
  -b, --batch-mode          In batch mode the command never prompts for user input
      --body string         The body of the issue
      --dir string          The source directory used to detect the git repository. Defaults to the current directory
      --headless            Enable headless operation if using browser automation
  -h, --help                help for issue
  -l, --label stringArray   The labels to add to the issue
  -t, --title string        The title of the issue to create
      --verbose             Enable verbose logging
```

### SEE ALSO

* [jx create](/commands/jx_create/)	 - Create a new resource

###### Auto generated by spf13/cobra on 6-Mar-2018