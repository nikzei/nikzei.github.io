# Nikki Zeichner

Hello :wave:

http://nikzei.github.io/


---

## Writing and Editing

**Note:** This site uses Markdown, a plain text formatting language.

- [Basic writing and formatting](https://docs.github.com/en/github/writing-on-github/basic-writing-and-formatting-syntax)
- [Mastering Markdown](https://guides.github.com/features/mastering-markdown/)

**The Home page** for this site is the `index.md` file in the root of the repo: https://github.com/nikzei/nikzei.github.io

**Pages** for this site are located in the `_pages` folder: https://github.com/nikzei/nikzei.github.io/tree/master/_pages

**Navigation** can be edited in the `_data/nav.yml` file: https://github.com/nikzei/nikzei.github.io/tree/master/_data

**Resume data** can be edited in the `_data/work.yml` file: https://github.com/nikzei/nikzei.github.io/tree/master/_data

## Images

**To add images in a markdown file**:
1. add the image to the `/assets/img/` folder
2. insert this bit of markdown into the body of page you're creating, 
```
![Photo: Nikki Zeichner](/assets/img/nikki-zeichner.jpg)
```

**To set an image as the featured image**:
1. add the image to the `/assets/img/` folder
2. insert this bit into the front matter of the page 
```
image: /assets/img/nikki-zeichner.jpg
image_layout: right
``` 
There are three layout options for the featured image `right`, `wide`, and `none`.

## Development

1. Clone this repo
1. run `npm install`
1. run `bundle install`
1. run `npm start`
1. view the site at [http://localhost:4000/](http://localhost:4000/)