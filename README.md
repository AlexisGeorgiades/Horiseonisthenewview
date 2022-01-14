<!DOCTYPE html>
<html lang="en-us">

<head>
    <meta charset="UTF-8" />
    <link rel="stylesheet" href="./assets/css/style.css">
    <title> A better SEO and Social Media Marketing tool- Horiseon a new view </title>
</head>

<!-- I use Safari as a default browser-->

<body>
    <header>
        <!--Horiseon's logo-->
        <h1>Hori<span class="seo">seo</span>n</h1>
        <nav>
            <ul>
                <li>
                    <!--Link for the SEO section-->
                    <a href="#search-engine-optimization">Search Engine Optimization</a>
                </li>
                <li>
                    <!--Link for the online reputation management section-->
                    <a href="#online-reputation-management">Online Reputation Management</a>
                </li>
                <li>
                    <!--Link for the social media marketing section-->
                    <a href="#social-media-marketing">Social Media Marketing</a>
                </li>
            </ul>
        </nav>
    </header>

    <section class="hero"></section>

    <!-- In the main content I renamed the classes for each section according to the subject they're related to and I tried to give a broad description of the images-->

    <main class="content">
        <section id="search-engine-optimization" class="search-engine-optimization">
            <img src="./assets/images/search-engine-optimization.jpg" alt="The word SEO is written in big at the center of an opened Notebook surrounded with pens, a laptop and a coffee cup." 
                 class="float-left" />
            <h2>Search Engine Optimization</h2>
            <p>
                The dominance of mobile internet use means that users are searching for the right business as they travel, shop, or sit on their couch at home. Search Engine Optimization (SEO) allows you to increase your visibility and find the right customers for your business.
            </p>
        </section>
        <section id="online-reputation-management" class="online-reputation-management">
            <img src="./assets/images/online-reputation-management.jpg" alt="Laptop with a chart and the word reputation is marked in capital letters at the top of the screen."
                 class="float-right" />
            <h2>Online Reputation Management</h2>
            <p>
                The web is full of opinions, and some of these can be negative. Social media allows anyone with an internet connection to say whatever they want about your business. Online Reputation Management gives you the control over what potential customers see when they search for your business.
            </p>
        </section>
        <section id="social-media-marketing" class="social-media-marketing">
            <img src="./assets/images/social-media-marketing.jpg" alt="Employees are using devices around a table where different icons linked to functionnalities, exploitation system and social media attributes are displayed"
                 class="float-left" />
            <h2>Social Media Marketing</h2>
            <p>
                Social media continues to have a sizable influence on buying habits. Social media marketing helps you determine which platforms are suited to your brand, using analytics to find the right markets and increase your lead generation.
            </p>
        </section>
    </main>

    <!-- For the section Aside I gave 3 differrent classes by adding one key word to the word benefit, regarding the images I tried to be as simple as possible for the description-->
    <aside class="benefits">

        <section class="benefit-lead">
            <h3>Lead Generation</h3>
            <img src="./assets/images/lead-generation.png" alt=" a gear is converted into a dollar sign through a funnel, with the setence lead generation at the top"/>
            <p>
                Inbound strategies for lead generation require less work for your business, bringing customers directly to your website.
            </p>
        </section>
        <section class="benefit-brand">
            <h3>Brand Awareness</h3>
            <img src="./assets/images/brand-awareness.png"
                 alt="a lightbulb is vibrating with the sentence brand awareness at the top"/>
                 
            <p>
                Users find your business through paid and organic searches, increasing the search ranking and visibility for your business.
            </p>
        </section>
        <section class="benefit-cost">
            <h3>Cost Management</h3>
            <img src="./assets/images/cost-management.png" alt="a gear with 3 different dollar signs with the sentence benefit cost upward"/>
                
            <p>
                As the search ranking for your business increases, your advertising costs decrease, and you no longer need to advertise your page.
            </p>
        </section>

    </aside>

    <footer>
        <h2>Made with ❤️️ by Horiseon</h2>
        <p>
            
            
            
            
            &copy; 2019 Horiseon Social Solution Services, Inc.
        </p>
    </footer>
</body>

</html>




/* Universal style*/

* {
    box-sizing: border-box;
    padding: 0;
    margin: 0;
}

/*Body Style with the font used*/

body {
    background-color: #d9dcd6;
    color: #ffffff;
    font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif ;
    font-size: 20px;
}

/*Elemant styles with color and font used*/

a {
    color: #ffffff;
    text-decoration: none;
}

p {
    font-size: 16px;
}

/* Header elements of style*/

header {
    padding: 20px;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    background-color: #2a607c;
}

header h1 {
    display: inline-block;
    font-size: 48px;
}

header h1 .seo {
    color: #d9dcd6;
}

/*Still the header but this is the Navigation bar section*/

header nav {
    padding-top: 15px;
    margin-right: 20px;
    float: right;
    font-size: 20px;
}

header nav ul {
    list-style-type: none;
}

header nav ul li {
    display: inline-block;
    margin-left: 25px;
}

/* Hero class section*/

.hero {
    height: 800px;
    width: 100%;
    margin-bottom: 25px;
    background-image: url("../images/digital-marketing-meeting.jpg");
    background-size: cover;
    background-position: center;
}

/* Utility class style*/

.float-left {
    float: left;
    margin-right: 25px;
}

.float-right {
    float: right;
    margin-left: 25px;
}

/*Elements and classes of the Main section, You'll notice that I renamed the first class to search-engine-optimization and that I've put the 3 different classes alignes*/

.content {
    width: 75%;
    display: inline-block;
    margin-left: 20px;
}

.search-engine-optimization, .online-reputation-management , .social-media-marketing {
    margin-bottom: 20px;
    padding: 50px;
    height: 300px;
    background-color: #0072bb;

}

.search-engine-optimization img, .online-reputation-management img, .social-media-marketing img {
    max-height: 200px;
}

.search-engine-optimization h2, .online-reputation-management h2, .social-media-marketing h2 {

    margin-bottom: 20px;
    font-size: 36px;  
}

/*Elemants and classes for the Aside section*/

.benefits {
    margin-right: 20px;
    padding: 60px;
    clear: both;
    float: right;
    width: 20%;
    height: 100%;
    background-color: #2589bd;
}

.benefit-lead, .benefit-brand, .benefit-cost {
  margin-bottom: 32px;
}

.benefit-lead h3, .benefit-brand h3, .benefit-cost h3 {
    margin-bottom: 10px;
    text-align: center;
}

.benefit-lead img, .benefit-brand img, .benefit-cost img {

    display: block;
    margin: 10px auto;
    max-width: 100px;
}

/*footer elements*/

footer {
    padding: 30px;
    clear: both;
    color: #000;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    text-align: center;
}

footer h2 {
    font-size: 20px;
}
