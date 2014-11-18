Brennanm.ME
============

Copyright (C) Brennan Macaig and Sant Bani School.

All Rights Reserved.

### Basics

This is the repository for my website. Here you can find the source code that is **live, right now** on my site.

This repository is open for contribution, but contributing to my repo is very limited.



### How to get my code

My site **requires** the following is true:

- The server is Appache.
- The server allows JavaScript / PHP to be sent to the client.
- The client allows JavaScript (SafeTyJS catch is in place.)
- The client allows redirects and downloads.

My site **requires these modifications**:

- The CNAME file *must* be altered.
- An "ORIGINAL_AUTH.md" file is provided (example is included in project).
- All images are removed, and all MySQL calls are removed.

Now that I've said all that, here's how to grab my stuff:

* **Git** use this clone URL: ```https://github.com/brennan-macaig/mygithubpage.git```

* **Linux/Mac/Git for Windows** use this command: ```bash $ git clone https://github.com/brennan-macaig/mygithubpage.git </path/to/storage>```

* **GitHub for Mac/Windows** follow instructions provided by this service. I'm not familiar with it enough to provide sufficient instructions.

* **Some Other Method** got another way to do it? Tell me about it!

#### Recommended Development Enviroment

My site is built with the following enviroment:

- **Brackets** lovely text editor for web development. I use the following plugins:

1. Code Folding - allows code folding.
2. Brackets Git - allows git inside git.
3. Brackets Icons - adds lovely icons for the file tree.
4. Brackets Terminal - allows a terminal inside brackets that uses Node.js and tty.js to run.
5. Emmet.io for Brackets - allows stuff like ``` div#footer>li*4 ``` to expand into valid HTML/CSS

### Project Structure

My repository / project is structured as such:

* GH-PAGES branch: This is the main branch for my repository. Everything is here that you need. The file tree is as such:
```
+gh-pages * BRANCH
|
+-+assets - assets folder.
| |
| +-+css - for CSS folder.
|   |
|   +-+front - CSS files only for the INDEX page.
|   |
|   +==files - some CSS files are stored here. Most unused.
+-+blogs - Some blogs.
| |
| +==files - HTML is available for blogs.
+-+files - Some downloads
| |
| +==files - Some files are here.
+-+imgs - Some images are available here.
| |
| +==files - Some images are here.
+==files - Main branch. HTML is here. Also jQuery
```
