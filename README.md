<h1 align="center"> 
	<a href="https://Simsaladoo.github.io/">Simsaladoo.github.io</a> - v2.0
	<p align="center">
		<img alt="HTML5" src="https://img.shields.io/badge/-HTML5-E44D26?style=flat&logo=html5&logoColor=white"/>
		<img alt="CSS3" src="https://img.shields.io/badge/-CSS3-2965f1?style=flat&logo=css3&logoColor=white"/>
		<img alt="JavaScript" src="https://img.shields.io/badge/-JavaScript-F0DB4F?style=flat&logo=javascript&logoColor=white"/>
		<img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-007ACC?style=flat&logo=typescript&logoColor=white"/>
		<img alt="Bootstrap" src="https://img.shields.io/badge/Bootstrap-563D7C?style=flat&logo=bootstrap&logoColor=white"/>
		<img alt="Angular" src="https://img.shields.io/badge/Angular-DD0031?style=flat&logo=angular&logoColor=white"/>
		<img alt="NodeJS" src="https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white"/>
		<img alt="Docker" src="https://img.shields.io/badge/Docker-0db7ed?style=flat&logo=docker&logoColor=white"/>
		<img alt="Open Source? Yes!" src="https://badgen.net/badge/Open%20Source%20%3F/Yes%21/blue?icon=github"/> 
	</p>
</h1>

<br/>

<div align="center">
	<a href="https://github.com/Simsaladoo/Simsaladoo.github.io">
		<img src="src/screenshots/icon.png" alt="Logo" width="80" height="80"/>
	</a>
	<h3 align="center">David Miller (Simsaladoo)'s Personal Portfolio</h3>
	<p align="center">
		This is the source code for my Personal Portfolio.
		<br/>
		<a href="https://github.com/Simsaladoo/Simsaladoo.github.io"><strong>Explore the docs »</strong></a>
		<br/>
	</p>
</div>

<br/>


## How to run locally? :dart:

- Install the dependencies:

  ```bash
  npm install -f
  ```
	- Installs all the dependencies required by the project.


- Fire up a development server:

  ```bash
  ng serve
  ```
    - Runs the app in the `development` mode.
    - Open [http://localhost:4200/](http://localhost:4200/) to view it in the Default Browser.
    - The page will reload if you make edits.
    - You will also see any lint errors in the console.


- Deploy code to GitHub Pages (gh-pages):
  
  ```bash
  ng deploy --base-href="/"
  ```
    - Builds the application for production to the `build` folder & deploys application on `GitHub Pages`.
    - It correctly bundles Angular in production mode and optimizes the build for the best performance.
    - The build is minified and the filenames include the hashes.
  



## Folder Structure :open_file_folder:

<pre>
|   .all-contributorsrc
|   .browserslistrc
|   .dockerignore
|   .editorconfig
|   .gitignore
|   angular.json
|   Dockerfile
|   karma.conf.js
|   ngsw-config.json
|   package-lock.json
|   package.json
|   README.md
|   tsconfig.app.json
|   tsconfig.json
|   tsconfig.spec.json
|   
+---.github
|   +---lighthouse
|   |       budget.json
|   |       lighthouserc.json
|   |       
|   \---workflows
|           publish-docker.yml
|           pull-request-deploy-and-audit.yml
|           fork_star.yml
|           
\---src
    |   apple-touch-icon.png
    |   browserconfig.xml
    |   favicon-16x16.png
    |   favicon-32x32.png
    |   favicon.ico
    |   index.html
    |   LICENSE
    |   main.ts
    |   manifest.webmanifest
    |   polyfills.ts
    |   README.md
    |   robots.txt
    |   sitemap_index.xml
    |   styles.min.css
    |   
    +---app
    |   |   app-routing.module.ts
    |   |   app.component.css
    |   |   app.component.html
    |   |   app.component.ts
    |   |   app.module.ts
    |   |   loadExternalResource.ts
    |   |   
    |   +---about
    |   |       about.component.css
    |   |       about.component.html
    |   |       about.component.ts
    |   |       
    |   +---achievement
    |   |       achievement.component.css
    |   |       achievement.component.html
    |   |       achievement.component.ts
    |   |       
    |   +---application
    |   |       application.component.css
    |   |       application.component.html
    |   |       application.component.ts
    |   |       application.module.ts
    |   |       
    |   +---contact
    |   |       contact.component.css
    |   |       contact.component.html
    |   |       contact.component.ts
    |   |       
    |   +---footer
    |   |       footer.component.css
    |   |       footer.component.html
    |   |       footer.component.ts
    |   |       
    |   +---home
    |   |       home.component.css
    |   |       home.component.html
    |   |       home.component.ts
    |   |       
    |   +---navbar
    |   |       navbar.component.css
    |   |       navbar.component.html
    |   |       navbar.component.ts
    |   |       
    |   +---page-not-found
    |   |       page-not-found.component.css
    |   |       page-not-found.component.html
    |   |       page-not-found.component.ts
    |   |       page-not-found.module.ts
    |   |       
    |   +---portfolio
    |   |       portfolio.component.css
    |   |       portfolio.component.html
    |   |       portfolio.component.ts
    |   |       
    |   +---quote
    |   |       quote.component.css
    |   |       quote.component.html
    |   |       quote.component.ts
    |   |       
    |   +---social
    |   |       social.component.css
    |   |       social.component.html
    |   |       social.component.ts
    |   |       
    |   +---training
    |   |       training.component.css
    |   |       training.component.html
    |   |       training.component.ts
    |   |       
    |   \---waifu
    |           Model.ts
    |           waifu.component.css
    |           waifu.component.html
    |           waifu.component.ts
    |           
    +---assets
    |   |   data.min.js
    |   |   
    |   +---css
    |   |       animate.min.css
    |   |       font-awesome.min.css
    |   |       
    |   +---fonts
    |   |       BlackOpsOne.eot
    |   |       BlackOpsOne.svg
    |   |       BlackOpsOne.ttf
    |   |       BlackOpsOne.woff
    |   |       BlackOpsOne.woff2
    |   |       fa-brands-400.eot
    |   |       fa-brands-400.svg
    |   |       fa-brands-400.ttf
    |   |       fa-brands-400.woff
    |   |       fa-brands-400.woff2
    |   |       fa-regular-400.eot
    |   |       fa-regular-400.svg
    |   |       fa-regular-400.ttf
    |   |       fa-regular-400.woff
    |   |       fa-regular-400.woff2
    |   |       fa-solid-900.eot
    |   |       fa-solid-900.svg
    |   |       fa-solid-900.ttf
    |   |       fa-solid-900.woff
    |   |       fa-solid-900.woff2
    |   |       
    |   +---images
    |   |   |   404.webp
    |   |   |   about-bg.svg
    |   |   |   background-image.jpg
    |   |   |   bgimg.webp
    |   |   |   footer-cloud.svg
    |   |   |   frame-desktop.webp
    |   |   |   frame-mobile.webp
    |   |   |   monkey.webp
    |   |   |   moon-dark.svg
    |   |   |   moon.svg
    |   |   |   mstile-144x144.png
    |   |   |   mstile-150x150.png
    |   |   |   mstile-310x150.png
    |   |   |   mstile-310x310.png
    |   |   |   mstile-70x70.png
    |   |   |   Profile-pic-144x144.png
    |   |   |   Profile-pic-192x192.png
    |   |   |   Profile-pic-384x384.png
    |   |   |   Profile-pic-512x512.png
    |   |   |   Profile-pic.webp
    |   |   |   quote-img.webp
    |   |   |   safari-pinned-tab.svg
    |   |   |   
    |   |   +---achievement
    |   |   |       DataScience.webp
    |   |   |       HackerRank.webp
    |   |   |       Hacktoberfest.webp
    |   |   |       
    |   |   \---portfolio
    |   |           A-Social-Media.webp
    |   |           AI-Image-Caption-Bot.webp
    |   |           AI-Music-Generation.webp
    |   |           E-Commerce-Site.webp
    |   |           School-Donation-Analysis.webp
    |   |           URL-Shortner.webp
    |   |           
    |   +---js
    |   |       live2d.min.js
    |   |       particles.min.js
    |   |       vanilla-tilt.min.js
    |   |       wow.min.js
    |   |       
    |   \---model
    |       |   README.md
    |       |   
    |  	    \---<a href="src/assets/model/" target="_blank">model</a>
    |                       
    +---environments
    |       environment.prod.ts
    |       environment.ts
    |       
    \---screenshots
            color-loader-404.png
            color-main.png
            font-awesome-icon.png
            font.png
            icon.png
            PageSpeedInsight Desktop.png
            PageSpeedInsight Mobile.png
            screenshot.gif
</pre>


## Search engine optimization(SEO) :spider:

Search engine optimization (SEO) is the process of improving the quality and quantity of website traffic to a website or a web page from search engines.
Add the below code snippet to `src/index.html` with your site info. This step is not mandatory.

```html
<meta itemprop="name" content="--- YOUR TITLE ---">
<meta itemprop="description" content="--- SITE DESCRIPTION ---">
<meta itemprop="url" content="--- YOUR SITE URL ---"/>
<meta itemprop="image" content="--- YOUR IMAGE ---">
<link rel="image_src" href="--- YOUR IMAGE ---">

<meta name="author" content="--- YOUR NAME ---">
<meta name="description" content="--- SITE DESCRIPTION ---">
<meta name="keywords" content="--- SITE KEYWORDS ---">

<meta property="og:image" content="--- YOUR IMAGE ---">
<meta property="og:image:width" content="--- YOUR IMAGE WIDTH ---">
<meta property="og:image:height" content="--- YOUR IMAGE HEIGHT ---">
<meta property="og:image:alt" content="--- YOUR TITLE ---">
<meta property="og:title" content="--- YOUR TITLE ---">
<meta property="og:description" content="--- SITE DESCRIPTION ---">
<meta property="og:url" content="--- YOUR SITE URL ---">
<meta property="og:type" content="website">

<meta name="twitter:title" content="--- YOUR TITLE ---">
<meta name="twitter:description" content="--- SITE DESCRIPTION ---">
<meta name="twitter:site" content="@--- YOUR USERNAME ---">
<meta name="twitter:creator" content="@--- YOUR USERNAME ---">
<meta name="twitter:image:src" content="--- YOUR IMAGE ---">
<meta name="twitter:image" content="--- YOUR IMAGE ---">
<meta name="twitter:card" content="summary_large_image">

<script type="application/ld+json">
    {
        "@type": "Person",
        "@context": "https://schema.org",
        "url": "--- YOUR SITE URL ---",
        "description": "--- SITE DESCRIPTION ---",
        "name": "--- YOUR NAME ---",
        "image": "--- YOUR IMAGE ---",
        "email":"--- YOUR EMAIL ---",
        "address": "--- YOUR LOCATION ---",
        "sameAs":[
            "https://github.com/--- YOUR USERNAME ---/",
            "https://www.linkedin.com/in/--- YOUR USERNAME ---/",
            "https://gist.github.com/--- YOUR USERNAME ---/",
            "https://www.hackerrank.com/--- YOUR USERNAME ---",
            "https://www.instagram.com/--- YOUR USERNAME ---/",
            "https://www.facebook.com/--- YOUR USERNAME ---/",
            "https://twitter.com/--- YOUR USERNAME ---/",
            "https://dev.to/--- YOUR USERNAME ---",
            "https://wa.me/--- YOUR MOBILE NUMBER ---"
        ]
    }
</script>
```


## PageSpeed Insights

PageSpeed Insights (PSI) reports on the performance of a page on both mobile and desktop devices, and provides suggestions on how that page may be improved.

- **Desktop**

	[![PageSpeed Insight Desktop](src/screenshots/PageSpeedInsight%20Desktop.png)](https://googlechrome.github.io/lighthouse/viewer/?psiurl=https%3A%2F%2Fjayantgoel001.github.io%2F&strategy=desktop&category=performance&category=accessibility&category=best-practices&category=seo&category=pwa)

- **Mobile**

	[![PageSpeed Insight Mobile](src/screenshots/PageSpeedInsight%20Mobile.png)](https://googlechrome.github.io/lighthouse/viewer/?psiurl=https%3A%2F%2Fjayantgoel001.github.io%2F&strategy=mobile&category=performance&category=accessibility&category=best-practices&category=seo&category=pwa)



<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->


<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->


## 📝 License

This project is [MIT](https://opensource.org/licenses/MIT) licensed.<br/>
Copyright &copy; 2024 David Miller. All rights reserved. 
