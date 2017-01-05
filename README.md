# ckeditor-html5-video

## Introduction
ckeditor-html5-video is simple HTML5 video plugin for CKEditor that is transformed version of [ckeditor-html5-audio](https://github.com/iametza/ckeditor-html5-audio).

If you want to add the plugin manually, you will need to:

1. Extract the html5audio folder into the plugins folder of your CKEditor installation. Example:

    ```
    http://example.com/ckeditor/plugins/html5video
    ```

2. Enable the plugin by using the extraPlugins configurations setting. Example:

    ```
    config.extraPlugins = 'html5video';
    ```

3. Download and configure all its dependencies, too (e.g. widget, widgetselection, clipboard, lineutils). Moreover, if you use a GNU/Linux distro you need to set the right permissions for the folders and files.

### Add-on Dependencies

[Widget](http://ckeditor.com/addon/widget)

For more information, please look through ckeditor-html5-audio's documentation on
* **[Github](https://github.com/iametza/ckeditor-html5-audio)**
* **[CKEditor's plugin page](http://ckeditor.com/addon/html5audio)**

I'd like to give special thanks to **[@aldatsa](https://github.com/aldatsa)** and other contributors of **ckeditor-html5-audio team**.
