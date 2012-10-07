# Roots CLI

A light, super fast, and intuitive build system meant for rapid advanced front end development.

### Installation

Currently there is no install script, but there will be. To test the project quickly, hit `./run` from the terminal.

### Usage

Roots' main interface is it's command line tool. There are just a couple of commands that do more or less what you would expect.

`$ roots new project-name`: Creates a new project template in the current directory, called `project-name`. Just a really simple scaffold of folders as well as some basic settings, a custom html boilerplate, and the roots css library linked. Good way to get off the ground quickly with the right structure.

`$ roots watch`: The bulk of roots' usefulness is here. This command compiled your project, opens it up in your browser, then continues watching all your files for changes. As soon as one of them changes, roots will recompile the project and immediately refresh the browser. So no more command tab.

`$ roots compile`: Compiled your project once to the public folder.

`$ roots deploy project-name`: Deploys your project to heroku as `project-name`. If you don't add a name, heroku will generate one automatically. This command depends on the heroku toolbelt - if you don't have it, the command will instruct you on how to install it.

### Features

- jade, stylus, and coffeescript default stack
- coffeescript requires available
- fastest live reload in the land
- default and custom override layouts
- partials with no need to pass locals
- intuitive settings file
- global variables and view helpers
- also supports ejs and straight html, css, and javascript
- easy to extend with whatever languages you like best
- this section needs work

### Love/Hate

Do you love and/or hate this? Maybe you even want to help, or suggest an improvement. Tell us all about it. Email hello@jenius.me or file an issue. <3