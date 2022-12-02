# Random files

le random files

## Dashless

Replace dashes in Discord channel names with spaces

```css
@font-face {
    font-family: "Dashless";
    src: url("https://vendicated.github.io/random-files/Dashless.woff2") format("woff2");
}

[data-list-item-id^=channels___], /* channel list */
[class^=titleWrapper] > h1, /* top bar with topic */
[class^=resultChannel], /* channel name in search */
[class^=placeholder][class*=slateTextArea] /* "Send a message in #blah" */
{
    font-family: "Dashless", var(--font-primary);
}
```

![image](https://user-images.githubusercontent.com/45497981/205343718-4f7e10f5-c797-41c6-8794-a601495ea0b1.png)
