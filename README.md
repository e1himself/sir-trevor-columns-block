Responsive File Manager plugin for Sir Trevor editor
====================================================

SirTrevor plugin that integrates [Responsive Filemanager](http://www.responsivefilemanager.com/) 
instead of standard file selection dialog for "Image" block.

---------------------------------------------------
Note: This plugin designed to work with modified forked version of SirTrevor: https://github.com/ansata-biz/sir-trevor-js


Installation
------------

You can use [Components](https://github.com/component/component) to install this plugin:

~~~ shell
component install ansata-biz/sir-trevor-responsive-filemanager
~~~

1. Install and configure [Responsive Filemanager](http://www.responsivefilemanager.com/) according 
    to [documentation](http://www.responsivefilemanager.com/#documentation-section).

2. Link SirTrevor Responsive Filemanager plugin script to your page:
    ~~~html
      <script src="sir-trevor-responsive-filemanager/image-block-responsive-filemanager.js"></script>
    ~~~
    
3. Configure path to Responsive Filemanager before initializing your SirTrevor instance:
    ~~~js
      // by default base_url is "/filemanager/dialog.php", so if you use default filemanager
      // installation instructions you do not need this line
      SirTrevor.DEFAULTS.Block.upload_options.filemanager.base_url = '/url_path/to/filemanager/dialog.php'
    ~~~
    
4. Image upload button is now managed by Responsive Filemanager.


Credits
-------

This plugin is brought to you by [Ansata Web Group](http://ansata.biz/).
