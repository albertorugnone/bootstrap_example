
#Environment refinement and bootstrap learning
##sab 22 feb 2014 09:21:58 CET  installing sublime text 3
- installed chrome http://www.cyberciti.biz/faq/how-to-install-google-chrome-in-ubuntu-linux-12-xx-13-xx/ 
- how to install sublime text http://www.unixmen.com/install-sublime-text-3-ubuntu-13-04-13-10/
**note** sublime test is linked to subl command (however to create it http://askubuntu.com/questions/273034/lauching-sublime-text-from-command-line sudo ln -s /opt/sublime/sublime_text /usr/bin/subl)
- installed package control https://sublime.wbond.net/installation
- install generator-bootstrap https://www.npmjs.org/package/generator-bootstrap npm install generator-bootstrap
- installed markdown editing package
- installed markdown toc (not used again :-( it looks as if it doesn't work)
- start bootstrap-example git project
- created bower.json 
- push first commit
**note** here some notion about git
    - http://stackoverflow.com/questions/13148066/warning-push-default-is-unset-its-implicit-value-is-changing-in-git-2-0
    - http://git-scm.com/docs/git-config.html
    - set for soundness <code>git config --global push.default simple</code>
- created bootstrap_example.sublimeproject 
- installed Emmet https://github.com/sergeche/emmet-sublime#how-to-install
- see also http://docs.emmet.io/abbreviations/syntax/

##dom 23 feb 2014 10:04:43 CET
- followed this blog Configure Sublime Text 2 for BootStrap & PHP
    + installed GIst
    + Insatlled Emmet
    + Installed HTML5
    + Installed Bootstrap Snippet
- TODO : account per Gist

##dom 23 feb 2014 11:05:27 CET
- installed AdvanceNewFile
- installed grunt-init
- add package.json by npm init https://www.npmjs.org/doc/init.html http://nodejs.org/api/modules.html
- TODO : non riesco ad aggiungere automaticamente grunt via script ho fatto npm install grunt --save-dev ma non è il verso giusto. Da leggere meglio grunt.


##dom 02 mar 2014 02:20:51 CET 
- try to create GruntFile properly
    + reading
        * http://www.codingcolor.com/javascript/setting-up-a-boilerplate-gruntfile-js/
        * http://gruntjs.com/project-scaffolding
        * http://gruntjs.com/getting-started
    + installed
        * Grunt for sublime-text https://github.com/tvooo/sublime-grunt
        * Grunt snippet
- How to add dependencies to package.json
    + follow this http://stackoverflow.com/questions/21198977/difference-between-grunt-and-bower-package-json-vs-bower-json to add programmatically a dependencies to package.json
    + *NB* --save-dev add dependencies to devDependencies --save to devependencies
 - TODO - effettuare il revert al commit precedente. In quanto ho committao anche node_modules. vedi http://stackoverflow.com/questions/4114095/revert-to-previous-git-commit
 
##mer 05 mar 2014 17:39:46 CET 
- installed apache2
    + deploy directory is /var/wwww
-  TODO read [Berkshelf](http://berkshelf.com/) e installare le sue recipe per uno sviluppo JS puro


#dom 16 mar 2014 23:01:30 CET


#ven 18 apr 2014 12:18:37 CEST
     avviato branch CH1_BOOTSTRAP_SCAFFOLDING
     installed sublime trimmer
     installed sublime git
     installed sublimediff pro
     installed sublime Aligment
     see [Emmet cheat](http://docs.emmet.io/cheat-sheet/)
     see [Sublime Text Side Bar](http://sublime-text-unofficial-documentation.readthedocs.org/en/latest/file_management/file_management.html)


**Todos** for the next:

- delve into [RequireJS](http://requirejs.org/). *It implements the AMD (Asynchronous Module Definition) spec, which means we can write our own modules and load them with RequireJS, allowing it to manage dependencies for us. *
     read [tutorial introduction](http://javascriptplayground.com/blog/2012/07/requirejs-amd-tutorial-introduction/)
     look for node plugin like [bower-requirejs](https://www.npmjs.org/package/bower-requirejs)
    
-Other:
     http://sublime-text-unofficial-documentation.readthedocs.org/en/latest/reference/keyboard_shortcuts_osx.html
     http://www.cheatography.com/njovin/cheat-sheets/sublime-text-2-keyboard-shortcuts-windows/
