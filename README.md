# My personal site

powered by [Hexo](http://github.com/hexojs/hexo) - a fast, simple and powerful blog framework.

## Installation of Hexo
``` bash
$ npm install hexo-cli -g
```
Other requirements
- Nodejs
- Git

## Setup blog (folder)
Syntax:
``` bash
$ hexo init [folder]
```
Example:
``` bash
$ hexo init blog
$ cd blog
```

## Start server (default port 4000)
``` bash
$ hexo server -p 5000
```

## Write new post
Three default layouts: post, page and draft, the files created from each layout will be saved at
- `source/\_posts`
- `source`
- `source/\_drafts`

Syntax:
``` bash
$ hexo new [layout] <title>
```

Example:
``` bash
$ hexo new "Hello World!"
```
## Publish new post
This call will move the specified post in `source/\_drafts` to `source/\_posts`
Syntax:
``` bash
$ hexo publish [layout] <filename>
```

Example:
``` bash
$ hexo publish "Hello World!"
```

## Generate static files
A folder named `public` will be populated with all html files needed to host the site on third party web server.
Syntax:
``` bash
$ hexo generate <filename>
```
