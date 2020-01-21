# <img src=".pics/lexx_headshot_clear.png" width="100px"/> Lexxeous's Web to BibTex: <img src=".pics/w2b.png" width="150px"/>

> Web to BibTeX is a generic (reference manager and browser independent) solution for semi-automatically citing web pages.

### Instructions:
 1. Create a new bookmark in the bookmark panel of your browser.
 2. Name the bookmark whatever you want.
 3. In the URL textbox, insert all of the code contained within `web_to_bibtex.js`, and confirm the creation of the bookmark.
 4. Load the page you want to cite and click on the `<web_to_bibtex>` bookmark.
 5. Copy generated BibTeX that is selected to your clipboard and paste where you like.
 6. Repeat steps 4 & 5 for any additional web pages you want to cite, as long as the bookmark exists

### Sample output:

```tex
@Online {BlockchainTechnologyExplained2HourCourseYouTube-2020-01-21,
  title = {Blockchain Technology Explained (2 Hour Course) - YouTube},
  date = {2020-01-21},
  file = {:./references/watch.html:html},
  url = {https://www.youtube.com/watch?v=qOVAbKKSH10&t=1560s},
  urldate = {2020-01-21}
}
```

### Credit
Credit goes to `dmstern` from the original Tex StackExchange question [here](https://tex.stackexchange.com/questions/32955/tool-for-generating-a-websites-bibtex-using-the-url) and the accompanying GitHub repository [here](https://github.com/dmstern/html2biblatex).