# BBCode Img URL Stripper

A quick tool I threw together to extract the URL from a BBCode image link so I could copy/paste it to my blogsite.

Before I'd need to copy the complete link, paste it into a notepad/markdown file, then grab the image URL to then enter into my blogsite. Now I can paste the BBCode link into this tool and it'll automatically strip the URL into the ouput field. Clicking on the output field automatically copies the URL to your clipboard. Clicking back on the input field will select all so all you have to do is paste the next BBCode link to be stripped.

## Example:

We want to extract the URL between the ```[img][/img]``` tags

BBCode:

```[url=https://flic.kr/p/26GSiyJ][img]https://live.staticflickr.com/833/41812950910_44d9fd09a1_b.jpg[/img][/url][url=https://flic.kr/p/26GSiyJ]37638130_2155764767992921_6120481740017369088_o[/url] by [url=https://www.flickr.com/photos/99696952@N08/]Simplistic Photography[/url], on Flickr```

After stripping:

```https://live.staticflickr.com/833/41812950910_44d9fd09a1_b.jpg```
