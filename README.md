#JS With Style

##Contribution Guide

Thanks for wanting to contribute! This document describes some points about the contribution process for the Guide.

## Table of Contents

  1. [Maintainers](#Maintainers)
  1. [Pull Requests](#Pull-Requests)
  1. [Filing Bugs](#Filing-Bugs)
  1. [Proposing Additions](#Proposing-Additions)
  1. [Implementing Additions](#Implementing-Additions)
  1. [Environment](#Environment)
  1. [Commit Message](#Commit-Message)

###Maintainers

 + [Ernie Casilla](https://github.com/ecasilla)


The project is being developed by the community. Maintainers merge pull-requests and fix critical bugs. All other features and patches are welcomed to be implemented by community members.

###Pull-Requests

If you fixed or added something useful to the project, you can send a pull-request. It will be reviewed by a maintainer and accepted, or commented for rework, or declined.

**Before submitting a PR**

*Please review our suggested commit message format.*

Nothing is worse than a project with hundreds of stale issues. To keep things orderly, the maintainers try to close/resolve issues as quickly as possible.

*PR/Issue closing criteria*

**We'll close your PR or issue if:**

1. It's a duplicate of an existing issue
1. Outside of the style-driven scope of the project
1. You are unresponsive after a few days
1. The feature request or rule modification request introduces too much complexity (or too many edge cases) to the tool
1. We weigh a request's complexity with the value it brings to the community.
1. Please do not take offense if your ticket is closed. We're only trying to keep the number of issues manageable.

**[⬆ back to top](#table-of-contents)**

###Filing-Bugs
If you found an `error, typo,` or any other flaw in the project, please report it using GitHub Issues. Try searching the issues to see if there is an existing report of your bug or feature request.

When it comes to bugs, the more details you provide, the easier it is to reproduce the issue and the faster it could be fixed.

###Proposing-Additions
If you've got an idea for a new feature, file an issue providing some details on your idea.

If it's a new `style rule` that you're proposing:

- Provide the possible configuration inputs
   - Look at the rules in the readme for examples
- You'll also have to think about (and implement) the reverse rule (Before|After) or (Require|Disallow)
- Provide snippets to show code that your rule deems as valid and invalid.
  - Check out the readme for examples
- If you'd like to modify the possible values for existing rules:
- Provide code snippets showing the need for additional configuration values.

**[⬆ back to top](#table-of-contents)**

###Implementing-Additions
It's likely that you'll have to implement feature requests or enhancements on your own. To do that, you'll need to be comfortable with `JavaScript, Promises, Node.js.` 


If you cannot implement the rule, but you feel that it would be helpful to others, you can create an issue on GitHub. If the maintainers feel that the issue satisfies our criteria for closing issues, your issue will be closed with a genuine thank you and an explanation for the closure.

###Environment
Use the editor of you choice and just 
 `git clone https://github.com/ecasilla/js-with-style`
 
 Heres some useful ones for different platforms
 
 + [MacDown] (http://macdown.uranusjr.com/)
 + [Atom for Linux](https://atom.io/)
 + [Atom for Windows](https://atom.io/)

**[⬆ back to top](#table-of-contents)**

###Commit-Message

We adhere to the [jQuery commit](http://contribute.jquery.org/commits-and-pull-requests/#commit-guidelines) message guidelines.

This format can be achieved via:

`git commit` to open your editor to create a multi-line commit message

```
<rulename>: short message
<emptyline>
Long description (if useful)
<emptyline>
Closes gh-<pullRequestNumber>
Fixes #<issueNumber>
```

**Example:**

```
validateIndentation: remove array and object indentation validation

Fixes #627 - issue
Closes gh-545 - pull request
```

**[⬆ back to top](#table-of-contents)**