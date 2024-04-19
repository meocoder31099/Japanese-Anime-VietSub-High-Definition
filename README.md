# Japanese-Anime-VietSub-High-Definition
Download Japanese Anime VietSub High Definition (Free)

Paste this script in Devtool of browers (If you understand, you will understand)
```javascript
const link = document.querySelector("div.jplayer__poster.jplayer__layer > img").src.replace('thumbs', 'contents').replace('-p/', '/').split('/thumbs')[0].split('/images')[0];
const final_link = link.split('contents')[1]
console.log(`
HD: ${link}/videos${final_link}_hq.mp4
SD: ${link}/videos${final_link}_med.mp4
`)
```
