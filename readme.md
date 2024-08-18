# Heading
## Overview
This is a portfolio website to show off my progress in HTML and CSS via Coder Academy. This website conforms to the design brief outlined in the assessment ensuring strict adherance to syntactically and semantically valid HTML and CSS utilising Flexbox. Extra care has been taken in ensuring accessibility such as using semantic elements and I have ensured consistent visual styling by utilising a 4px spacing theme within a cohesive visual theme.  

## Components

### Header
Header has the logo and name of the company along with the navigation bar to different pages such as Home, My Journey, My Studies, My Life and Contact Me. The logo also has a spinning animation to create a engaging user experience. 

```html
    <header>
        <div class="logo spin-on-hover">
            <a href="#">
                <img src="https://media.discordapp.net/attachments/1271030796857249845/1271030871260139560/bgc-logo-transparent.png?ex=66bd1b7e&is=66bbc9fe&hm=daa1100b5ff436fe4c17e29bc93ed350730c3777c5e3c4ffc0250e33f99c83a1&=&format=webp&quality=lossless&width=437&height=437"
                    alt="BGC Logo">
            </a>
        </div>
        <input type="checkbox" id="check" class="checkbox">
        <label for="check" class="checkbtn">
            <i class="fas fa-bars"></i>
        </label>
        <nav class="nav-main">
            <a href="#">Home</a>
            <a href="pages/myjourney.html">My Journey</a>
            <a href="pages/mystudies.html">My Studies</a>
            <a href="pages/mylife.html">My Life</a>
            <a href="pages/contactme.html">Contact Me</a>
            </a>
        </nav>
    </header>
```

### Footer
The footer has my best method of contacts for potential employers. It has been adjusted to always sit at the bottom of the page, regardless of where the user is scrolling. 

```HTML
    <footer>
        <a href="https://github.com/BenGormanCode" target="_blank">
            <i class="fa-brands fa-github"></i>
        </a>
        <a href="https://www.linkedin.com/in/ben-gorman-bb705a323" target="_blank">
            <i class="fa-brands fa-linkedin"></i>
        </a>
        <a href="pages/contactme.html" target="_blank">
            <i class="fa-solid fa-envelope"></i>
        </a>
    </footer>
```

### Articles
The articles make use of flexbox so that the format on smaller screens and makes best use of the space available. 
```html
    <article>
        <section class="journey-image">
            <a href="https://www.telstra.com.au/careers" target="_blank">
                <img src="https://cdn.discordapp.com/attachments/1273189259481710644/1273189495155724431/images.png?ex=66bdb59e&is=66bc641e&hm=ddce1995de3a03fcae555faa8a1bfa388e41ed2b7fab8214dcaa10c285429809&"
                    alt="telstra-logo">
            </a>
        </section>
        <section class="journey-info">
            <h2>2017 - 2019</h2>
            <h2>Telstra</h2>
            <h3>Customer Consultant</h3>
            <li>Retail Sales and Upselling</li>
            <li>Cold Call Phone Sales</li>
            <li>Relationship Management of B2B Clients</li>
            <li>Samsung Elite Product Specialist</li>
            <li>Mentoring and Training New Staff</li>
            <li>Visual Merchandising</li>
        </section>
    </article>
```

### Drawer
The drawer makes use of the checked psuedo class on a checkbox to be able to show and hide the links dynamically on smaller screens. This UI is hidden on large screens where we have the space to show the nav links. This is an industry standard pattern known as a hamburger menu. 

```html
    <input type="checkbox" id="check" class="checkbox">
    <label for="check" class="checkbtn">
        <i class="fas fa-bars"></i>
    </label>
    <nav class="nav-main">
        <a href="#">Home</a>
        <a href="pages/myjourney.html">My Journey</a>
        <a href="pages/mystudies.html">My Studies</a>
        <a href="pages/mylife.html">My Life</a>
        <a href="pages/contactme.html">Contact Me</a>
        </a>
    </nav>
```

