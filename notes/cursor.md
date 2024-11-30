# Using the Cursor IDE



## Fixes & tips

### Increasing font sizes in Cursor chat & composer

I followed [these instructions](https://forum.cursor.com/t/changing-chat-panel-font-size-line-height-easily/375/7)

1. Installed the [APC Customize UI extension](https://marketplace.visualstudio.com/items?itemName=drcika.apc-extension)
2. Used the following (note `apc.stylesheet`) settings:

    ```json
    {

        "apc.stylesheet": {
            ".explorer-viewlet .mac": "font-size: 12px !important; overflow: auto; border-left:none!important",
            ".aislash-editor-input": "font-size: 14px !important; line-height: 1.5 !important;",
            ".anysphere-markdown-container-root": "font-size: 14px !important; line-height: 1.5 !important;",
            ".view-line": "font-size: 14px !important;"
        },
        "*.fontSize": 14,
        "*.fontFamily": "MonacoLigaturized Nerd Font",
        "window.zoomLevel": 1
    }
    ```

### Removing intrusive popup suggestions

Example of an intrusive popup suggestion:
![intrusive popup suggestion](../assets/suggestion_popup.png)

Example of an unintrusive inline suggestion:
![unintrusive inline suggestion](../assets/suggestion_inline.png)
