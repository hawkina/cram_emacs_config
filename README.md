# cram_meacs_config

My personal config for Emacs and CRAM. Loads a dark default theme, has some custom highlighting for prolog, TODO's and draws a line at 80 chars. A few other functions added aswell from http://cram-system.org/doc/emacs-config

## Usage
Follow the installation and IDE setup guide from http://cram-system.org/ .
Then download this repo and copy the files into your local roslisp_repl installation. (You can get there by performing **roscd roslisp_repl**). You will need sudo priviliges to do so. 
Then add the following line to your **repl-config.el**

	(require 'main)
	
This should load all the necessary functions.
Have fun and happy coding!
