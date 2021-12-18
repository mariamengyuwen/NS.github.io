# How to Edit Each Section
Please nagivate to the gh_pages branch to edit the website

## Sidebar

Sidebar is controlled by the file `_config.yml` and `/layouts/default.html`.

### In `_config.yml`:
- `title` is the title of the website.
- `description` is the text displayed right under the title.
- `logo` is the path of the picture. The file is placed in `content/`. You can get the path by clicking the picture, and clicking `...`, and clicking `Copy path`.  

### In `default.html`:
- Resize the image: change the percentage in line 19 `img {width: 80%;}`
- Change toggle line spacing: change the number in line 20 `p.sidebar {line-height: 0.5;}`
- Add toggle for a new section: add a line after line 27 with format of  
    `<p class="sidebar"><a href="./#sectionwithoutspacing">Section with Spacing</a></p>`

## Bio, Publications, Work in Progress

Those three sections are controlled by index.md. 
- Add links: `[Github](https://www.github.com)`
- Add documents：
  1. Upload documents in content
  2. `[document](path to the document)`
- Change fonts
- Change colors: <span style="color:blue">some *blue* text</span>.
- Further Markdown writing templates can be found in content folder. They are copied from Gautam Rao [GitHub Respository](https://github.com/gautamrao/gautamrao.github.io).  
