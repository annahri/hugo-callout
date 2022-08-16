# hugo-callout
Notion-style callouts for your hugo site!

![desktop screenshot](callout-desktop.png)

Simply invoke the following shortcode in your `.md` Hugo content files to use these beautiful callouts:

```
{{< callout emoji="💯" >}} 
This is the text that will show up in the callout. It can be as long as you like, and supports basic html tags.<br>
This line will be in the new line.
{{< /callout }}
```

To install: simply download the `callout.html` file from this repo, it's also in the `releases` section. Place this file in your `themes/[THEME-NAME]/layouts/shortcodes` or `layouts/shortcodes` folder.

The style code is included in that same file for convenience, but you can move it to your own `.css` file and modify as you wish 👍🏻 
