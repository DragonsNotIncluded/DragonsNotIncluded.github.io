---
title: "Test"
date: 2000-04-11T18:48:45+01:00
draft: false
---

Hello and welcome to the Dragons Not Included podcast.

We are a group of friends with a mutual love of tabletop roleplaying games. We wanted to bring the experience of playing a game with us around the table to you at home.

So we hope you will join us with the action, the drama and the laughs through the Wrath of the Righteous adventure path.
So we hope you will join us with the action, the drama and the laughs through the Wrath of the Righteous adventure path.
something new


# Examples in Markdown
*The above is a Level 1 Title*

Hello, Dungeon Master. I have added a lot of Markdown examples to this document. 

\- Kind regards, your webmaster [Darren](https://robot-one.github.io)

To edit Markdown, you can use any text editor, but I recommend one with a preview, for example (also, this is how you do links):

- [Ghostwriter](https://github.com/wereturtle/ghostwriter/releases)
- [MarkdownPad 2](http://markdownpad.com/)
- [Notepad++](https://notepad-plus-plus.org/), with [this plugin](https://github.com/VinsWorldcom/NppMarkdownPanel/releases)
- [Sublime Text 3](https://www.sublimetext.com/3), with [this plugin](https://github.com/SublimeText-Markdown/MarkdownEditing/releases)
- [Marktext](https://github.com/marktext/marktext/releases) (very similar to the commercial [Typora](https://typora.io/))

## This is a subtitle (Level 2)
(and some basic examples of text formatting and lists)

*italic* 

**bold** 

***bold & italic***

unordered list:
- hello
- what's up?
- not much
  - sub-bullet
	 - sub-sub-bullet

Ordered list:

1. Shaka, when the walls fell
2. Temba, his arms wide
3. Darmok and Jalaad, at Tanagra
	- Mixed bullet types (and this is from a famous Star Trek TNG episode, Darmok [Wikipedia]) 


- [x] checklist item 1
- [ ] checklist item 2
- [ ] cheese
- [ ] fruit

### This is a subtitle (Level 3)
Subtitles can go many levels deep (infinite?); treat Level 4 as the absolute limit, and normally, you won't need any more than Level 2 or 3.

Below is a line divider. Don't put text directly above a line, or it's understood as a Level 1 Title

------------------------------

## (Messy) table example, and other special characters

| This | Is | How | You | Make |
|---|---|---|---|---|
| a | table | in | Markdown |
| It | is | fairly | forgiving
| if | you |don't|get|formatting
| perfect |

You also need to type `backticks` to write as code, 

```
multiple backticks for code blocks
```
or <key>Key indicators</key> for keyboard buttons, e.g. <key>Ctrl</key>+<key>Alt</key>+<key>Delete</key> (these don't render on your website theme **yet**)

If you need to type a designated character, use a backslash to escape its function, for example bullets usually render from short dashes, but here's a short dash I typed using \- (I typed it thusly `\-`)

## Quote block example

> or, how about a quote block?
> 
>\- anon#1234 @ 4:20pm
>> fake
>>
>> \- anon#69 @ 4:69pm
>>> No, it's real, I promise
>>>
>>> \- anon#1234 @ 4:30pm


## Podcast Embedding examples

Example of how to embed a PodBean episode **(NB `forwardslash-asterisk`, only visible in the source code, is just to prevent Hugo from rendering the shortcode; normally anything between those funny triple brackets is rendered)**

`{{</* podbean 49suk-105448b */>}}`
{{< podbean 49suk-105448b >}}

How to embed a HearThis.at [1] audiobook (quite good for hosting unlimited audio)

`{{</* hearthis 6405965 */>}}`
{{< hearthis 6405965 >}}

[Deezer] music (available media types: `album`, `playlist`, `track`, `artist`, `podcast`, `episode` ). Theme can (optional) be dark, light, or have specified height in pixels

`{{</* deezer track 3083380 dark 150 */>}}`
{{< deezer track 3083380 dark 150 >}}

How to embed a [Spotify] playlist (available mediatypes: `track`, `artist`, `album`, `playlist`, `episode`, `show`

`{{</* spotify media="mediatype" id="37i9dQZF1DX59NCqCqJtoH" theme="dark" */>}}`

`{{</* spotify playlist 37i9dQZF1DWZd79rJ6a7lp dark */>}}`
{{< spotify playlist 37i9dQZF1DWZd79rJ6a7lp dark >}}

## Example for embedding images

Here's how you embed a remote image from somewhere else (this is called "hotlinking" - it's bad practice because it puts load on other people's servers and they could delete/rename/replace-with-p0rn their content at any time, so best to use unchangeable local images, see below):

Wikipedia logo from Wikipedia, The Free Encyclopaedia:
![Wikipedia logo](https://en.wikipedia.org/static/images/project-logos/enwiki.png)

To render local images, put the images anywhere in `[website folder]/static/img/optionalFolder` and embed them thusly:

![Custom Wallpaper image embed](/img/customWallpaper.png)

## Google Docs/Drive
and other miscellaneous new examples

{{< google forms 1FAIpQLSdqRDjIhpvL1QTk_tnfzQ-KinpnykdcdpZsI9raxQgYBdxEnA medium >}}

{{< google docs 2PACX-1vRbMhPNvB2UrcR91LquW50yGuOc1GiVHx8fxFeYk7e9voUdJ3GixKXt0Ibl2DE0uYBI2xRKLuG2-omt small >}}

hello

{{< google sheets 2PACX-1vSGxyqlVTF4h3IWmE-9qZ-XDxwmui9oYkPsEnlz9zWPNSbjF6KYc26xgDrtmPhTbo5XTrRdeIsZfQod small >}}

{{< google slides 2PACX-1vRHHaawI-GBqV1IPMCk21k6aVCb90vqQI728iq5swPVLc7qE3DBpAH2VS6xKJueMJ8u9l75wHCpViDe medium >}}
{{< google drawings 2PACX-1vSA3jr0M_WncpW-WEybOzL_VQ96vN_f5c3aq8BfGFp9T_kZF1KUMYkRHNqtwt0VDPHi7UAHGzAzdTdJ small >}}

{{< google drive 13RQADLIapSkgvetN9ia9UYcuGwb7CAay medium >}}


{{< imgur HgI7jNC  >}}

{{< funge contractAddress="0xd1e5b0ff1287aa9f9a268759062e4ab08b9dacbe" tokenId="105497419635294095894519942330270477445331529530180169464364453130971299318396" >}}

Reference-style links below this line in the source code (invisible on rendered site, they are rendered as direct links):

----------

[1]: https://hearthis.at/

[Spotify]: https://open.spotify.com/
[Deezer]: https://www.deezer.com/en/
[Wikipedia]: https://en.wikipedia.org/wiki/Darmok
[Wikipedia]: https://en.wikipedia.org/wiki/Darmok
