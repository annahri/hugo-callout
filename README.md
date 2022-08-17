# hugo-callout
Notion-style callouts for your hugo site!

![image](https://user-images.githubusercontent.com/30897918/185045001-d9cf9d05-a220-4eb0-ae96-5b0dba4087ea.png)

Simply invoke the following shortcode in your `.md` Hugo content files to use these beautiful callouts:

```
{{< callout emoji="💯" >}} 
This is the text that will show up in the callout. It can be as long as you like, and supports basic html tags.<br>
This line will be in the new line.
{{< /callout >}}
```

or use `{{% callout %}}` tag to allow markdown syntaxes:

```
{{% callout %}}
This *word will be bold*, and this _one is italic_.

Also this supports lists:
1. one
1. two
1. three
{{$ /callout %}}
```

To install: simply download the `callout.html` file from this repo, it's also in the `releases` section. Place this file in your `themes/[THEME-NAME]/layouts/shortcodes` or `layouts/shortcodes` folder.

The style code is included in that same file for convenience, but you can move it to your own `.css` file and modify as you wish 👍🏻 
