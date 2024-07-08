<p align="center" style="padding-top:20px">
 <h1 align="center">Minimal Marketing</h1>
 <p align="center">This is a simple website that is optimized for converting traffic to a marketing goal. It costs only $10/year to host, hence minimal marketing.</p>
</p>
  <p align="center">
    <a href="https://gohugo.io/">
      <img src="https://img.shields.io/badge/Hugo%20-0.110.0%20-gray.svg?colorA=c9177e&colorB=FF4088&style=for-the-badge"/>
    </a>
    <a href="https://tailwindcss.com/">
      <img src="https://img.shields.io/badge/TailwindCSS%20-V3-gray.svg?colorA=0284c7&colorB=38bdf8&style=for-the-badge"/>
    </a>
  </p>

  <p align="center">
    <a href="https://minimal-marketing.pages.dev/">View Demo</a>
    ·
    <a href="https://github.com/letItCurl/minimal_marketing/issues">Report Bug</a>
    ·
    <a href="https://github.com/letItCurl/minimal_marketing/discussions/categories/ideas">Request Feature</a>
    ·
    <a href="https://github.com/letItCurl/minimal_marketing/discussions/categories/q-a">Q&A</a>
  </p>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/letItCurl/minimal_marketing/main/images/tn.png" alt="Minimal Marketing" style="margin: 25px auto; max-width: 830px" width="100%" height="" />
</p>

# Getting started

## Clone repo
`git clone git@github.com:letItCurl/minimal_marketing your-new-marketing-website-name`

## Install dependencies
#### Install with NPM
`npm install`
#### Install with Yarn
`yarn`


## Start local server
##### Develop with NPM
`npm run start`
##### Develop with Yarn
`yarn start`

## Build static website for production
##### Build with NPM
`npm run build`
##### Build with Yarn
`yarn build`

## Form
To use the form, you could use those services:
- [https://zapier.com/](https://zapier.com/)
- [https://formsubmit.Co](https://formsubmit.co/)
- [https://developers.cloudflare.com/workers/](https://developers.cloudflare.com/workers/)

## Content

Important to follow the installation instructions above, consider installing Homebrew package manager.

To edit the main page, go to the index.html file located in the folder called public. There you can modify the main structure of your static website.

To create a new post within the minimal marketing theme, first configure the view of your new post, correctly pointing out the path or url of the destination page that you want to show in the address. The minimal marketing theme is configured to create 3 column post views, if you consider adding a new post view for a new page, it will automatically load in a new row below, creating an order in the code structure.

To create a view of a new post you can follow the same creation pattern as the first, otherwise you can modify and create a new structure to your liking by assigning custom style sheets.

It is important to consider that each post view points to a destination route, this will be the page that is related to that post. Each page of posts is created independently, each in a folder to generate order in the structure and make a page with unique content for each new page. Just create a new folder, create a new index.html file and start working on your new page. By containing the name of index.html, it will default to the file as the main file, if you need to create another name, it has to be specified in the post path as detailed in the comments within the code.

Everything is customizable and the styles are tailored to the needs of each project.

Thank you.

## Credits
4044ever - Original Theme
https://github.com/4044ever/Hugo-Tailwind-3.0.git

Jan Heise - Alpine.js Navbar
https://github.com/jan-heise/responsive-navbar-with-dropdown

Nusser Studio - Blog structure
https://github.com/nusserstudios/tailbliss

Made with ❤️ by [this guy](https://twitter.com/afrodudeonabike)
