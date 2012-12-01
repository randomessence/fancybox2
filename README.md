fancybox2
=========

fancybox2 from attachments and the IMG bbcode tag, based on Stoker4.0 prettyphoto mod.

This is pretty much a clone of [Stoker4.0 prettyphoto mod](http://www.phpbb3bbcodes.com/viewforum.php?f=31) that has been made to work with [fancyapps Fancybox2](http://fancyapps.com/fancybox/)

It also hase been made to automatically work and resize images that use the stock [IMG] bbcode.

For attachments you need to have already enabled the creation of thumbanils via the ACP.

General Tab:

Attachment Settings.

##Unique to this Version

This Version of fancy box has a couple of small tweaks to the defaukt settings.

CSS: min image width and height set to 5px for lightbox

added [youtube-nocookie](https://github.com/fancyapps/fancyBox/pull/460) support.

##Instructions

Quite simple. The mod is automod 1.0.* compatible so you can install it that way.

Or open the xml file and do the edits manually. There are only a few small edits.

Don't forget to upload the files to your forum root.

##BBCODES

This mod also works with custom bbcodes.

In its simplest form bbcodes take this format

`<a class="fancybox-media" href=" "> </a>`

**Youtube**
```
[youtubefb]{URL}[/youtubefb]
```
```
<a class="fancybox-media" href="{URL}">{URL}</a>
```

**Vimeo**

```
[vimoefb]{URL}[/vimoefb]
```
```
<a class="fancybox-media" href="{URL}">{URL}</a>
```

**But for more advanced Youtube embed options these work**

Privacy, https, autoplay, no captions and more.
```
[youtubefb]{IDENTIFIER}[/youtubefb]
```
```
<a class="fancybox-media" href="https://www.youtube-nocookie.com/embed/{IDENTIFIER}?autoplay=1&autohide=1&border=0&egm=0&showinfo=0&iv_load_policy=3">https://www.youtube.com/watch?v={IDENTIFIER}</a>
```

Same as above but with a thumbnail
```
[youtubefbthumb]{IDENTIFIER}[/youtubefbthumb]
```
```
<a class="fancybox-media" href="https://www.youtube-nocookie.com/embed/{IDENTIFIER}?autoplay=1&autohide=1&border=0&egm=0&showinfo=0&iv_load_policy=3"><img style="width: 100px; border:1px solid black;" src="http://i.ytimg.com/vi/{IDENTIFIER}/default.jpg" alt="YouTube" /></a>
```


