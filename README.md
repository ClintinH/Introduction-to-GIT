# Introduction-to-GIT
## Learning to use GIT
This is my first attempt to use a **repo** with coding
I managed to create the **repo** and create a *SSH* link to be able to communicate with the **repo**.

## Upgrading my understanding of ***DEV*** Flow
### Repository
Storing your project on a “cloud server” which a group of people can access the project and work on their tasks locally. Pushing their task to the repo for final build.

Git Commands
1. Commit (save latest changes to local Repo)
2. Pull - The git pull command is used to fetch and download content from a remote repository and immediately update the local repository to match that content. Merging remote upstream changes into your local repository is a common task in Git-based collaboration work flows. [Reference](https://www.atlassian.com/git/tutorials/syncing/git-pull)  
3. Push - The git push command is used to upload local repository content to a remote repository. Pushing is how you transfer commits from your local repository to a remote repo. [Reference]( https://www.atlassian.com/git/tutorials/syncing/git-push)
4. Fetch (Check latest updates on the main Repositor)
5. Keeps History of changes / projects

### Github
It is a public repository for use. You can make projects that anyone can comment or make changes to or keep it private for personal or group use. 

### Control Systems
**GIT** – Git is a distributed version control system - which just means that when you do a git clone (+url of your repository) what you are actually getting is a complete copy of your entire history of that project. This means all your commits! Woot! [Reference](https://blog.hackbrightacademy.com/blog/svn-vs-git/)

**SVN** – Subversion (SVN) may be one of the most well known centralized version control systems. In Subversion or SVN, you are checking out a single version of the repository. With SVN, your data is stored on a central server. Having the entire history on your local repository just means that even when you are not connected to the Internet, you can still do commits, diffs, logs, branches, merges, file annotations, etc. [Reference]( https://blog.hackbrightacademy.com/blog/svn-vs-git/)

**What is difference between SVN and Git repository?**

The difference between Git and SVN version control systems is that Git is a distributed version control system, whereas SVN is a centralized version control system. Git uses multiple repositories including a centralized repository and server, as well as some local repositories. [Reference]( https://blog.hackbrightacademy.com/blog/svn-vs-git/)

**Gitignore** – file tells Git which files to ignore when committing your project to the GitHub repository. gitignore is located in the root directory of your repo. [Reference]( https://www.bmc.com/blogs/gitignore/#:~:text=gitignore%20file%20tells%20Git%20which,is%20a%20plain%20text%20document.)

### Difference between staged and unstaged commits
Unstaged changes are changes that are not tracked by the Git. For example, if you copy a file or modify the file. Git maintains a staging area(also known as index) to track changes that go in your next commit. The staging area is a file, in your Git directory, that stores information about what will go into your next commit. Staging the changes will put the files into the index. The next git commit will transfer all items from staging into your repository. [Reference]( https://www.testingdocs.com/questions/what-are-unstaged-and-staged-changes-in-git/)

### What is a Branch
A branch represents an independent line of development. Branches serve as an abstraction for the edit/stage/commit process. You can think of them as a way to request a brand new working directory, staging area, and project history. New commits are recorded in the history for the current branch, which results in a fork in the history of the project.The git branch command lets you create, list, rename, and delete branches. It doesn’t let you switch between branches or put a forked history back together again. For this reason, git branch is tightly integrated with the git checkout and git merge commands. [Reference]( https://www.atlassian.com/git/tutorials/using-branches#:~:text=A%20branch%20represents%20an%20independent%20line%20of%20development.) 
### What is a SSH key
SSH keys come in many sizes, but a popular choice is an RSA 2048-bit encryption, which is comparable to a 617 digit long password. SSH keys always come in pairs, and every pair is made up of a private key and a public key. Who or what possesses these keys determines the type of SSH key pair. If the private key and the public key remain with the user, this set of SSH keys is referred to as user keys.
If the private and public keys are on a remote system, then this key pair is referred to as host keys. Another type of SSH key is a session key. When a large amount of data is being transmitted, session keys are used to encrypt this information. [Reference]( https://jumpcloud.com/blog/what-are-ssh-keys)

### What license should be used for coding projects
GNU Public License
Always use a GPL-compatible license.

Perhaps the best-known license is the GNU Public License (GPL), which guarantees the freedom of users to use, copy, and modify code. Code released under a GPL-compatible license is code that can be incorporated into another GPL-licensed codebase without modification to the license. [Reference](https://www.astrobetter.com/blog/2014/03/10/the-whys-and-hows-of-licensing-scientific-code/)


# HTML helpful Information 

### Tags
An HTML tag is a piece of markup language used to indicate the beginning and end of an HTML element in an HTML document.
As part of an HTML element, HTML tags help web browsers convert HTML documents into web pages. For example, the >p> tag is used to organize text content into paragraph elements and the >img> tag is used to embed image elements.
Many tags, though not all, use an opening tag and closing tag to wrap around the content that they are used to modify. Closing tags are denoted with a backslash like this: </tag_name>. HTML tags are not visible in the browser.
The following diagram illustrates how tags are commonly used in HTML elements:
[Reference](https://www.digitalocean.com/community/tutorials/what-is-an-html-tag)

### Padding
An element's padding area is the space between its content and its border. Padding creates extra space within an element.
This property is a shorthand for the following CSS properties:
padding-bottom
padding-left
padding-right
padding-top
[Reference](https://developer.mozilla.org/en-US/docs/Web/CSS/padding)

### Margin
The margin property defines the space around an HTML element. It is possible to use negative values to overlap content.
The values of the margin property are not inherited by the child elements. Remember that the adjacent vertical margins (top and bottom margins) will collapse into each other so that the distance between the blocks is not the sum of the margins, but only the greater of the two margins or the same size as one margin if both are equal.
We have the following properties to set an element margin.
⦁	The margin specifies a shorthand property for setting the margin properties in one declaration.
⦁	The margin-bottom specifies the bottom margin of an element.
⦁	The margin-top specifies the top margin of an element.
⦁	The margin-left specifies the left margin of an element.
⦁	The margin-right specifies the right margin of an element.
[Reference](https://www.tutorialspoint.com/css/css_margins.htm#:~:text=The%20margin%20property%20defines%20the,negative%20values%20to%20overlap%20content.&text=The%20margin%2Dbottom%20specifies%20the,left%20margin%20of%20an%20element)

### The Body Tag 
The >body> tag in HTML is used to define the main content present inside an HTML page. It is always enclosed within >html>tag. The >body> tag is the last child of >html> tag. A body tag contains starting as well as an ending tag. [Reference](https://www.geeksforgeeks.org/html-body-tag/#:~:text=The%20tag%20in%20HTML,present%20inside%20an%20HTML%20page.&text=Attributes%3A%20There%20are%20many%20attributes,to%20set%20the%20background%20image)

### The Header Tag
The >header> HTML element represents introductory content, typically a group of introductory or navigational aids. It may contain some heading elements but also a logo, a search form, an author name, and other elements.
Usage: The >header> element is not sectioning content and therefore does not introduce a new section in the outline. That said, a >header> element is intended to usually contain the surrounding section's heading (an h1–h6 element), but this is not required.
[Reference](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/header)

### The DocType Tag
>!DOCTYPE html>
The HTML document type declaration, also known as DOCTYPE, is the first line of code required in every HTML or XHTML document. The DOCTYPE declaration is an instruction to the web browser about what version of HTML the page is written in. This ensures that the web page is parsed the same way by different web browsers.
[Reference](https://www.freecodecamp.org/news/what-is-the-doctype-declaration-in-html/#:~:text=The%20HTML%20document%20type%20declaration,way%20by%20different%20web%20browsers)

## HTML List Tags
>html>>/html>
>!DOCTYPE html>
>title> this is heading<\title>
>Body>this is the body>/body>
>div>>/div>
>span>>/span>
>a href="https://www.ggogle.com">google</a>.
>table>>/table>
>thead>>/thead>
>tr>>td>Value1>/td>>td>Value2>/td>>/tr>
?script>
>!-- javascript code -->
>/script>

>img src=https://bitarray.io/images.logo.png alt="bitarray logo">
>strong> this is strong text>/strong>

[Reference](https://www.bitarray.io/20-html-tags-you-need-to-know/)

### Code Reveiw
Code Review, also known as Peer Code Review, is the act of consciously and systematically convening with one’s fellow programmers to check each other’s code for mistakes and has been repeatedly shown to accelerate and streamline the process of software development like few other practices can. There are peer code review tools and software, but the concept itself is important to understand. Software is written by human beings. Software is therefore often riddled with mistakes. To err is, of course, human, so this is an obvious correlation. But what isn’t so obvious is why software developers often rely on manual or automated testing to vet their code to the neglect of that other great gift of human nature: the ability to see and correct mistakes ourselves.

### REVIEWER
is a person who reviews the pull request. A project owner can request review from any of the maintainers, They can even set an option so that the pull request can be merged only if it is reviewed by one of the maintainer with write access.

### ASSIGNEE 
is a person who is working on specific issues and pull requests. It is sometimes confused as a reviewer. It is actually meant to be used with issues rather than pull request so that when we receive a issue we can assign someone to fix it. In a pull request, an assignee refers to a person who's in charge of merging that pull request after getting comments and change requests from other maintainers.

### HTML: HyperText Markup Language
HTML (HyperText Markup Language) is the most basic building block of the Web. It defines the meaning and structure of web content. Other technologies besides HTML are generally used to describe a web page's appearance/presentation (CSS) or functionality/behavior (JavaScript).

"Hypertext" refers to links that connect web pages to one another, either within a single website or between websites. Links are a fundamental aspect of the Web. By uploading content to the Internet and linking it to pages created by other people, you become an active participant in the World Wide Web.

HTML uses "markup" to annotate text, images, and other content for display in a Web browser. HTML markup includes special "elements"[Reference](https://developer.mozilla.org/en-US/docs/Web/HTML)

### What Does HTML5 Mean?
Hypertext Markup Language revision 5 (HTML5) is markup language for the structure and presentation of World Wide Web contents. HTML5 supports the traditional HTML and XHTML-style syntax and other new features in its markup, New APIs, XHTML and error handling.
HTML5 is an effort is to bring order to web development chaos by organizing common practices, embracing implementations from various browsers. It is massive, with over 100 specifications as part of the HTML5 specs. Understanding this, you can simplify by thinking of HTML5 this way. HTML5 is simply just an umbrella term for the next generation of web apps an how functionality will be expanded with better markup (HTML), better style (CSS), and better interactivity (JavaScript). [Reference](https://www.techopedia.com/definition/1891/html5)

### HTML
- It didn’t support audio and video without the use of flash player support.
- It uses cookies to store temporary data.
- Does not allow JavaScript to run in browser.
- Vector graphics is possible in HTML with the help of various technologies such as VML, Silver-light, Flash, etc.
- It does not allow drag and drop effects.
- Not possible to draw shapes like circle, rectangle, triangle etc.
- It works with all old browsers.
Older version of HTML are less mobile-friendly.
- Doctype declaration is too long and complicated.
- Elements like nav, header were not present.
- Character encoding is long and complicated.
- It is almost impossible to get true GeoLocation of user with the help of browser.
- It can not handle inaccurate syntax.
Attributes like charset, async and ping are absent in HTML.

### HTML5
- It supports audio and video controls with the use of >audio> and >video> tags.
- It uses SQL databases and application cache to store offline data.
- Allows JavaScript to run in background. This is possible due to JS Web worker API in HTML5.
Vector graphics is additionally an integral a part of HTML5 like SVG and canvas.
- It allows drag and drop effects.
HTML5 allows to draw shapes like circle, rectangle, triangle etc.
- It supported by all new browser like Firefox, Mozilla, Chrome, Safari, etc
- HTML5 language is more mobile-friendly.
- Doctype declaration is quite simple and easy.
- New element for web structure like nav, header, footer etc.
- Character encoding is simple and easy.
- One can track the GeoLocation of a user easily by using JS GeoLocation API.
- It is capable of handling inaccurate syntax.
Attributes of charset, async and ping are a part of HTML 5.
[Reference](https://www.geeksforgeeks.org/difference-between-html-and-html5/)

### ESLint
 is a static code analysis tool for identifying problematic patterns found in JavaScript code. It was created by Nicholas C. Zakas in 2013.[1][2] Rules in ESLint are configurable, and customized rules can be defined and loaded. ESLint covers both code quality and coding style issues. ESLint supports current standards of ECMAScript, and experimental syntax from drafts for future standards. Code using JSX or TypeScript can also be processed when a plugin or transpiler is used
[Reference](https://en.wikipedia.org/wiki/ESLint)

### HTML Tag Properties
The html tag properties can be difined by adding atributes =.

### Atributes: 
HTML attributes provide additional information about HTML elements.
HTML Attributes
    All HTML elements can have attributes
    Attributes provide additional information about elements
    Attributes are always specified in the start tag
    Attributes usually come in name/value pairs like: name="value"
[Reference](https://www.w3schools.com/html/html_attributes.asp)