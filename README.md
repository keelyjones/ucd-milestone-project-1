# Reverend Blue - Band Website
#### Project Purpose

The purpose of this website to fulfil the criteria for the or the first Milestone Project in the Code Institute Full-Stack Web Development Course. I have created static (front-end only) website displaying technologies I have learnt throughout the User Centric Frontend Development module of the Code Institute Course.
I have chosen to adapt the example brief provided, and have instead created a website for the band Reverend Blue.

Reverend Blue is a London based band that plays original music inspired by blues, funk, soul, and rock.

## UX

The site is targeted at fans of the band Reverend Blue, music-lovers discovering the band, and those interested in booking the band for gigs. I anticiplate users visiting the site though mobile mainly, but also desktop.

#### User Stories
> As an individual just discovering the band, I would like to be able to learn more about the members and the music they make. I want to be able to listen to RB's music from the website, watch videos, and to be able to download tracks.
>
> As a booker, I want to be easily able to contact Reverend Blue, using a dedicated contact page.
>
> As a fan, I want to be able to keep up to date on RB's music, via a website which is simple and user friendly, with navigation aids. I want to be able to easily see when RB's upcoming gigs will be, and to book tickets.
>
> As a mobile user, I want to be able to scroll through the content easily, without the need to zoom in and out.
>
> As a desktop user, I want to see asthetically pleasing content, with lots of images.

#### Design Process
This wireframe maps out my initial ideas and design process: [MockFlow Wireframe](https://wireframepro.mockflow.com/view/M4532df4913ed1f6161b71fee797dafb71547727432927#/page/74c6bb192bf4439f9137bca0833f3745)

---------------------
## Features
#### Existing Features
The website allows the user to:
- Find out more about the band and the band members
- Listen to Reverend Blue's music
- Watch Reverend Blue's videos
- Visit the band's social media sites (Facebook, Twitter, Youtube, Pinterest, Linkedin, Instagram)
- Events listing - allows users to see upcoming events and book tickets
- Contact form - allows users to get in touch with Reverend Blue with enquiries, by filling out a user-friendly contact form
- Mailing list box - allows users to sign up to the band's mailing list, for news and updates, by filling in their name and email address

#### Features Left to Implement
- Add a calendar view as part of the events page (see wireframe). This is a feature I will add when I have become more experienced with Javascript, and when the band have more upcoming events to add to this.
- Link contact form and mailing list through to a database
- Add GDPR pop-up and unsubscribe page for data protection

## Technologies Used

- [HTML5](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5) & [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS3) - This project is executed primarily using **HTML5** and **CSS3**.
- [Javascript](https://www.javascript.com/) - I have used Javascript within the Navigation bar
- [Cloud9 IDE](http://c9.io/) - This website was built using **Cloud9 IDE**, an online integrated development environment developed by AWS.
- [Bootstrap](http://getbootstrap.com/) - **Bootstrap** is used here to create a simple, responsive structure.
- [Google Fonts](https://fonts.google.com/) - *Raleway* and *Playfair Display* are imported from **Google Fonts**, a library of 900 libre licensed fonts, with interactive web directory and APIs.
- [Font Awesome](https://fontawesome.com/) - **Font Awesome** (CSS/LESS icon toolkit) used for the social media icons.
- [Hover.css](http://ianlunn.github.io/Hover/) - Hover effects for Nav bar are imported from from **Hover.css**, a collection of CSS3 powered hover effects.

---------------------
## Testing

**1)** I have run the website in different browsers and devices to ensure all the features render correctly.

*Devices: Macbook Air, Desktop PC, iPhone SE, iPhone7, iPad, Huawei Honor x8 (Andriod), Asus Transformer Book T100.*

*Browsers: Chrome, Firefox, IE, Edge, Safari*


**2)** I have tested all of the internal hyperlinks, to ensure none are broken.

**3)** I have tested the responsive features of the website by checking the website on different screen sizes and by using [Chrome DevTools](https://developers.google.com/web/tools/chrome-devtools/).

*The website was built to be both user-centric and aesthetically pleasing:*

- *When viewing on mobile devices or small screens: pages span one column only to enable easy scrolling; fonts are large enough to view clearly; all icons/buttons are large enough to click easily.*

- *When visting the site from a desktop: pages incorportate aesthetically pleasing layouts (some features running alongside others); images are large and striking; the features of the site are all spaced-out evenly.*

- N.B. I made used of Bootstrap `card` classes (content containers) for the profiles on my about page. The cards span only the height of the content, and therefore were not all equal height.
Thanks to djibe's fix on [StackOverflow](https://stackoverflow.com/questions/35868756/how-to-make-bootstrap-4-cards-the-same-height-in-card-columns), I was able to make all of the cards the height of the tallest card, whilst still being responsive.

**4)** I have utilised [Cloud9 IDE](http://c9.io/)'s inbuilt [Language Analysis](https://docs.c9.io/docs/language-analysis) feature and [Debugger](https://docs.c9.io/docs/debugging-your-code) to automatically idenfity issues.

*To learn more about these features, click the above hyperlinks to view Cloud9's documentation.*

**5)** I have run my code through an HTML validator to check the validity and syntactical correctness of my HTML.

HTML validator brought up some errors, which where mostly small syntactical errors and typos. Some of these are listed below.
- Error 1: 1 In my footer, there were mispelt elements (`<\br>` instead of `<br>`) and an extra `</i>` tag, which was easily rectified.
- Error 2: In my Newsfeed (`index.html`), `hr` elements are not allowed as a child of `ul` elements. In order to rectify this, I simply changed the instances of `ul` and `li` to `div`.
- Error 3: The character encoding was not declared. Added `<meta charset="utf-8"/>` to head.
- Error 4: The scrolling attribute on the iframe element is obsolete. Use CSS instead. I targeted the iframe with `overflow: hidden;` and specified the width within my CSS stylesheet.

HTML Validator Results: "#"

## Deployment

I have deployed my code to Github pages, through the following steps:

1. Login to Github account. Create 'New Repository'. Named the repository: `ucd-milestone-project-1.git`
2. Copy the link generated https://github.com/keelyjones/ucd-milestone-project-1.git
3. Type `git remote add origin https://github.com/keelyjones/ucd-milestone-project-1.git` into command line
4. Push branch to Github using `git push origin master`
5. On GitHub, navigate to the new repository. Click `Settings`
6. Select source drop-down menu to select `master` as your GitHub Pages publishing source.
7. Click Save.

---------------------
## Credits

#### Content
- All content is original, adapted from information from the band, with some creative licence.

#### Media
- The photos, videos and audio files used in this site were obtained directly from Reverend Blue, and may not be used without express permission.

#### Acknowledgements
