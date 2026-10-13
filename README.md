# redLatido

redLatido is a static website made for the class project "Código con causa" (2nd year of DAW, CEI, 2026-2027). The topic is voluntary donations: medical centres publish the blood or plasma they need, and people can see the requests and go donate if they can.

Live site: https://project-blooddonation.vercel.app

The texts of the website are in Spanish. The code and the file names are in English.

## Pages

- `index.html` and `index.css`: home page, with the 4 flip cards that turn on hover or with the keyboard.
- `what-to-donate.html` and `what-to-donate.css`: what can be donated (blood and plasma) and how the donation day goes.
- `requests.html` and `requests.css`: example requests from medical centres, with a "Cómo llegar" button that opens Google Maps.
- `for-centres.html` and `for-centres.css`: form where a centre can publish a request.
- `styles.css`: styles shared by all pages (navbar, footer, buttons, titles and sections). Each page loads it first and then its own CSS.

## Folder structure

```
codigo-con-causa/
  index.html
  what-to-donate.html
  requests.html
  for-centres.html
  styles.css
  index.css
  what-to-donate.css
  requests.css
  for-centres.css
  files/
    favicon.svg
  README.md
```

## How to open it

There is nothing to install. Download or clone the repository and open `codigo-con-causa/index.html` in the browser. The navbar links go to the other pages.

The photos are loaded from Cloudinary with their URL, so an internet connection is needed to see them. The only local file in `files/` is the tab icon.

## What we used

- HTML5 with semantic tags (header, nav, main, section, footer), `lang="es"` and `alt` text in all images.
- CSS3 with Flexbox for the layouts and 3D transforms for the flip cards. There is no JavaScript.
- Google Fonts: Red Hat Display for titles and Red Hat Text for the rest.
- Figma for the design, Trello for the tasks and sprints, and GitHub for the code, with one branch per part and pull requests to `main`.

## Notes

The data of the requests and the medical information are examples written by hand in the HTML.

## Photos

Photos by National Cancer Institute, LuAnn Hunt, Cherisse Jane Quinico, Nguyễn Hiệp, Olga Kononenko, CDC, YANGHONG YU and Tim Marshall on Unsplash.

## Team

Brandon, Manuel and Nacho.
