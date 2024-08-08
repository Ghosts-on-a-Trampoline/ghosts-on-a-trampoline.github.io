---
title: Shortcodes
categories: Showcase
draft: true
---
## Shortcodes

*Youtube*
{{< youtube nLAVanlu5js >}}


*Highlight*
{{< highlight js "linenos=table,hl_lines=3-4,linenostart=1080" >}}
// Enjoy your work
if (!tired()) {
    keepCoding();
} else {
    drinkCoffee();
}
{{</ highlight >}}

{{< highlight html "linenos=table,hl_lines=2 ,linenostart=1080" >}}
<!-- Generated Youtube source code for video -->
{{</* youtube nLAVanlu5js */>}}
<!-- Output -->
{{< youtube nLAVanlu5js >}}
{{</ highlight >}}

{{<divider>}}
{{<markdown>}}
{{%markdown%}}

Inline shortcodes disabled in security.yaml by default
{{< reuse.inline >}}

Reused _content_ here       
{{< /reuse.inline >}}       
  
{{< reuse.inline />}}
{{% reuse.inline /%}}       