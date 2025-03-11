
# Bouncing Ball Website

## Overview
Developed for the higher diploma in computer sciende at SETU. using only HTML and Css.\n
Project based on the boucing ball created for the programming assignment where can be foung here:[Bouncing Ball](https://github.com/villaca13/BouncingBall).
Html concepts: use of Divisions, Sections , IDs, Classes, naming of folder and files, Appropriate use of semantics.
Css concepts: Flexbox, Grid, Sizing, formatting elements, multiple stylesheets
Nunjucks: templating, layouts, partials, DRY/WET. 
Site Generator: Eleventy. 
Deployment: Netlify.

---

## Features
- 7 html pages :  Home, About, instructions, settings, pricing and contact. 
- Responsive design for desktop.
- website to present and show intructions on how to play the Bouncing ball game and its features. 
- Flexbox for navigation 

---

## Technologies Used

- **Frontend**: HTML, CSS, eleventy, Node 
- **Backend**: Netlify for hosting
- **Database**: Not Implemented
- **API**: Not Implemented

---

## Usage

1. Open command prompt and select the folder where you saved the files. Example: C:\Users\USER\BouncingBallWebsite
2. When inside the folder use the eleventy command below ( [Eleventy](https://www.11ty.dev/docs/) needs to be installed)
```
eleventy --serve
```
3. Open your browser and visit `http://localhost:8080`.
4. Home webpage will open and then use the navigation bar to go through the pages. 

---

## Project Structure

```
BouncingBallWebsite/
├── _includes/
│   ├── footer.njk
│   ├── header.njk
│   └── mainLayout.njk
├── _site/
├── css/
│   ├── aboutMe.css
│   ├── contact.css
│   ├── index.css
│   ├── instructions.css
│   ├── mainLayout.css
│   ├── navbar.css
│   ├── pricing.css
│   ├── ranking.css
│   └── settings.css
├── images/
├── node_modules/
├── videos/
├── .elenventy.js
├── aboutMe.njk
├── contact.njk
├── index.njk
├── instructions.njk
├── package-lock.json
├── package.json
├── pricing.njk
├── ranking.njk
├── README.md
├── settings.njk
├── index.njk
└── reflection.pdf
```

---

## Contributors
- **Tiago Linhares Villaca** - HDIP in computer science Student with a passion for coding.

---

## Acknowledgments - next

- "Contact" page inspiration and code from [CarPoolVenom](https://www.youtube.com/watch?v=nwEB3Wxh5N0).
- "About Me" page inspiration from [Nicepage](https://nicepage.com/ht/1362604/creative-designer-profile-html-template).
- "Pricing" page inspiration and code from [dcode](https://www.youtube.com/watch?v=jfh0ZJFhj2w).
- Nunjucks Conditional Statement Examples for Eleventy from [design2seo](https://design2seo.com/blog/web-development/11ty/nunjucks-if-statement-for-eleventy/).
- Readme template from [comp1800](https://github.com/comp1800/web_template).
- Creating table in HTML from [w3schools](https://www.w3schools.com/html/html_tables.asp).
- Profile avatar from [freepik](https://www.freepik.com/).

- Weather data sourced from [OpenWeatherMap](https://openweathermap.org/).
- Code snippets for ___ algoirthm were adapted from resources such as [Stack Overflow](https://stackoverflow.com/) and [MDN Web Docs](https://developer.mozilla.org/).
- Icons sourced from [FontAwesome](https://fontawesome.com/) and images from [Unsplash](https://unsplash.com/).

---

## Limitations and Future Work
### Limitations

Example:
- Currently, the app only supports city-based weather searches.
- Limited to basic weather parameters like temperature, humidity, and conditions.
- The user interface can be further enhanced for accessibility.

### Future Work

Example: 
- Add support for location-based weather detection using GPS.
- Implement additional weather parameters like wind speed and UV index.
- Create a dark mode for better usability in low-light conditions.
- Integrate user accounts for saving favorite locations.

---

## License

Example:
This project is licensed under the MIT License. See the LICENSE file for details.
