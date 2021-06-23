# Realign- Eliminating-Div-Tags 
                                                                   Mentality
Getting my feet wet when it comes to coding. I'm someone who has a passion for gaming, but also found how intriguing coding is. However, as everytime I have time to practice I learn something new everytime. First of all let me breackdown the mental of this project before I tell you what I learn while doing this. When people say coding isn't for everyone they aren't lying to you if you're not patient and open minded to making mistakes. It comes with being patient and making a lot of mistakes. A lot of codes and techniques will not work, and one letter out of place and your entire web page is messed up. The ticket attempting and failing. We must come at projects or coding with an open mind and being ok with making mistakes. as much as its frustrating when codes don't work, its rewarding when find out dealing with coding with the vibe that youre going to achieve it. 

                                                                    Progress

There was nothing wrong with the how the live webpage looked, however it was the how the skeleton looked is where the issue lies. My instincts as writer tells me there are a lot of non-senametic div tags, in the new age of coding there is an alternative way to divide a web page in section. I replaced majority of the div tags with senametic tags like <nav>,<article>, <aside>,<figure> and <footer>. There is only one div tag in the skeleton for the navigation bar, so I'm guessing that's the necessary div tag because without it the content on navigation bar is out of place. To go back to writing one of my mentors told me to never repeat a word when starting a new line and the first think that pop out were the excessive div tags websites html. There were excessive div tags, but I have better understanding of when and not to use them. 
  
                                                                    Issues:
  
  Still having trouble with finding how to find out the issue of the search engine optim. alt attribution. All of the other attributes like
  
  
  
  
  <!DOCTYPE html>
<html lang="en-us">

<head>
    <meta charset="UTF-8" />
    <link rel="stylesheet" href="./assets/css/style.css">
    <title>Horisen website</title>
</head>

<body>
    <nav class="header">
        <h1>Hori<span class="seo">seo</span>n</h1>
        <div>
            <ul>
                <li>
                    <a href="#search-engine-optimization">Search Engine Optimization</a>
                </li>
                <li>
                    <a href="#online-reputation-management">Online Reputation Management</a>
                </li>
                <li>
                    <a href="#social-media-marketing">Social Media Marketing</a>
                </li>
            </ul>
        </div>
    </nav>
    <figure class="hero"></figure>
    <article class="content">
        <article class="search-engine-optimization">
            <img src="./assets/images/search-engine-optimization.jpg" alt="search-engine-optimization" class="float-left" />
            <h2>Search Engine Optimization</h2>
            <p>
                The dominance of mobile internet use means that users are searching for the right business as they travel, shop, or sit on their couch at home. Search Engine Optimization (SEO) allows you to increase your visibility and find the right customers for your business.
            </p>
        </article>
        <article id="online-reputation-management" class="online-reputation-management">
            <img src="./assets/images/online-reputation-management.jpg" alt="online rep management" class="float-right" />
            <h2>Online Reputation Management</h2>
            <p>
                The web is full of opinions, and some of these can be negative. Social media allows anyone with an internet connection to say whatever they want about your business. Online Reputation Management gives you the control over what potential customers see when they search for your business.
            </p>
        </article>
        <figure id="social-media-marketing" class="social-media-marketing">
            <img src="./assets/images/social-media-marketing.jpg" alt="social media marketing" class="float-left" />
            <h2>Social Media Marketing</h2>
            <p>
                Social media continues to have a sizable influence on buying habits. Social media marketing helps you determine which platforms are suited to your brand, using analytics to find the right markets and increase your lead generation.
            </p>
        </figure>
    </article>
    
     <aside class="benefits">
        <aside class="benefit-lead">
            <h3>Lead Generation</h3>
            <img src="./assets/images/lead-generation.png" />
            <p>
                Inbound strategies for lead generation require less work for your business, bringing customers directly to your website.
            </p>
        </aside>
        <aside class="benefit-brand">
            <h3>Brand Awareness</h3>
            <img src="./assets/images/brand-awareness.png" />
            <p>
                Users find your business through paid and organic searches, increasing the search ranking and visibility for your business.
            </p>
        </aside>
        <aside class="benefit-cost">
            <h3>Cost Management</h3>
            <img src="./assets/images/cost-management.png"></img>
            <p>
                As the search ranking for your business increases, your advertising costs decrease, and you no longer need to advertise your page.
            </p>
        </aside>
    </aside>
    <footer class="footer">
        <h2>Made with ❤️️ by Horiseon</h2>
        <p>
            &copy; 2019 Horiseon Social Solution Services, Inc.
        </p>
    </footer>
</body>

</html>

     

  
