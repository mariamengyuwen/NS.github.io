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
- Change fonts and colors: modify `asset/style.css` by adding font-family and color
        [Website for font code](https://www.w3schools.com/css/css_font_websafe.asp)
        [Website for color code](https://www.w3schools.com/colors/default.asp)
  1. For section title, modify:  
          `h1, h2 {line-height:1.1;
                   font-family: 'Times New Roman', Times, serif;
                   margin:0 0 20px;}`
  2. For work title, modify:  
          `h3, h4, h5, h6 {color:#39c;
                           font-weight: 500;
                           line-height: 1.1;}`
  3. For content, modify:  
          `body {background-color: #fff;
                 padding:50px;
                 font: 14px/1.5 -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Fira Sans", "Droid Sans", "Helvetica Neue", Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
                 color:#595959;
                 font-weight:400;
                 text-align: justify;}`
- Further Markdown writing templates can be found in content folder. They are copied from Gautam Rao [GitHub Respository](https://github.com/gautamrao/gautamrao.github.io).  
