# Portfolio site

The purpose of my portfolio site is to establish a personal brand, and allow prospective employers and clients to establish who I am, the skills I possess and the kind of work I have done. Particularly in the growing digital world, a personal site is an extension of your resume. It is a practical example of what you are capable of, and gives you a chance to express yourself creatively and in a way that represents you.

[Check out the website here](http://www.rhysgeary.com) <br>
[View the repo](https://github.com/RhyG/portfolio_site)

### Contents

* [Functionality / features](#features)
* [Development and design process](#dev)
* [Considerations](#considerations)
* [Sitemap](#map)
* [Screenshots](#screens)
* [Target audience](#audience)
* [Tech stack](#tech)
* [Internet questions and answers](#questions)

<a id="features"></a> 
# Functionality / features

My portfolio site is a very simple, static site. It functions as most websites do, with a navbar at the top allowing navigation between pages. There is also a contact button containing a mailto link with my email, and the footer contains links to my Github and Linkedin as well as another mailto link. 

The site features my projects thus far, as well as a list of my current and future skills. The about page features a short blurb about me and my setup. The website is responsive, and displays well on all devices tested including mobile, tablet and desktop.

<a id="dev"></a> 
# Development and design process

The development process was broken into three stages:

1. Design phase
    * Create a wireframe of the site
    * Moodboard and decide on colour and aesthetic
    * Mockup designs in Sketch

2. Development phase
    * Complete HTML for the website
    * Apply styling
    * Test throughout build

3. Deployment
    * Deploy website
    * Monitor for any issues that may arise

### Design phase

The design phase was completed during the first day of the assignment. It started with getting inspiration from other developers and their portfolio sites, and it was during this phase that I got a good idea of what I like and don't like in a portfolio site. A lot of the sites I came across while looking for inspiration were immense, beautiful and impossibly creative adventures that a clearly talented person put a lot of effort into, and so often I barely saw half their site because there was no simple navigation, or it hijacked my scrolling and make it so tedious to get from element to element.

I knew I wanted to create a simple, minimal website with bright but subtle colours and clean lines. I also wanted to avoid using things I didn't know, such as javascript, as the concept of authenticity was important to me in the design. I wanted users to get an accurate idea of my abilities, and I didn't want to implement anything I wasn't able to explain, update or maintain.

Here are some examples of websites I took inspiration (and 'borrowed' styling) from.

![Website inspiration](https://raw.githubusercontent.com/RhyG/portfolio_site/master/docs/images/website_inspo.jpg "Website inspiration")

Once I knew the layout I wanted it was time to start wireframing. As my design was simple and I didn't plan to put too much content on the site, this was fairly straightforward. I created both mobile and desktop wireframes, as I intended for the layout to change depending on the device.

[Click here to view the full desktop wireframe](https://raw.githubusercontent.com/RhyG/portfolio_site/master/docs/images/desktop_wireframe.jpg)

[Click here to view the full mobile wireframe](https://raw.githubusercontent.com/RhyG/portfolio_site/master/docs/images/mobile_wireframe.jpg)

![Wireframe mockups](https://raw.githubusercontent.com/RhyG/portfolio_site/master/docs/images/wireframe_mockups.jpg "Wireframe mockups") 

Once the wireframe was complete it was onto the design. It was during this phase I finalised the colour palette, I used the site [Coolors](http://coolors.co/) to help decide on a palette, and the site [Color.review](https://color.review/) to determine accessibility for the colours used. I wanted colours that stood out, and brightened up the site as it will otherwise be a fairly simple and flat site. 

I also decided on a font by using Google Fonts and browsing until I found something I liked, other than not wanting anything too dated or ugly I wasn't after anything specfic. 

Finally was coming up with a logo. For this I used a similar logo I have used in the past, and had the designer who made it make some modifications.

![Design choices](https://raw.githubusercontent.com/RhyG/portfolio_site/master/docs/images/font_colours.jpg "Design choices") 

It was then onto doing up the designs. For this project I used Sketch, a popular Mac program used to create software designs. I started by laying out the wireframe on the artboard, and and then went on to assemble the elements and apply the styling. 

I only designed for desktop and mobile as I believed the design wouldn't change from desktop to tablet, simply scale, and it wouldn't be until mobile that the layout would change.

[Click here to view the full desktop design](https://raw.githubusercontent.com/RhyG/portfolio_site/master/docs/images/desktop_design.png)

[Click here to view the full mobile design](https://raw.githubusercontent.com/RhyG/portfolio_site/master/docs/images/mobile_design.png)

![Design mockups](https://raw.githubusercontent.com/RhyG/portfolio_site/master/docs/images/design_mockups.jpg "Design mockups") 

Finally it was time to actually build the site. I used VS Code and everything was made with HTML and CSS/SASS. As mentioned before I wanted to avoid using any technologies outside my scope, such as Javascript, as I wanted the site to be an accurate representation of my skills, as well as remaining something I can easily understand and maintain.

# Considerations
<a id="considerations"></a> 

When building the site I had four main considerations, responsiveness, accessibility, performance and SEO. I believe these are four key components of a modern site, and are the baseline for an acceptable standard if you intend for the site to be viewable to more people than yourself.

### Responsiveness

These days a majority of internet users are mobile, with most people using their handheld devices to surf the net rather than using a desktop. This means it is important to build a site that can be accessed from any device and still display as intended. To satisfy this criteria, I developed with a mobile friendly approach. This meant building the site to function correctly on portable devices, and from there building the desktop version. 

### Accessibility

Accessibility was one of my primary considerations when developing the site. The internet can be accessed from everywhere in the world, and shouldn't be reserved for the physically able. I wanted my site to be usable for any user no matter how they access it. Being a static HTML/CSS site achieving a high accessibility score wasn't too hard as long as my colour contrasts were high enough and my HTML was semantic.

I used the site [Color.review](https://color.review/) to choose my colours, and went with a dark text color on light colours. My highlight colour (#07889b) is only AA but being that it is scarcely used I thought that was acceptable. All other text is an almost-black that scores AAA across the board. I made sure the markup contained all the tags it needed so that screen readers and other accessibility devices could browse it without issue. 

### Performance

Performance is incredibly important to me, as a fast site says a lot to the user about the skill of the developer. [Research has also shown](https://www.marketingdive.com/news/google-53-of-mobile-users-abandon-sites-that-take-over-3-seconds-to-load/426070/) that users will leave a site if it takes over three seconds to load, which is not much time at all. As a result I was sure to keep images to a minimum, and optimised any I did have to load as quick as possible.

### SEO

Search engine optimisation was the final major consideration I made while developing the site. The importance of SEO is self-evident, especially in an industry as saturated as web development with people competing for the eyes of the user. Fortunately being a static HTML/CSS website it was simple enough to use good semantic code and give everything appropriate values and alt tags. This means that when I am ready to deploy the site properly it should rank well.

### Audits

Using the Google Chrome audits tool I was able to audit the site in these three areas.

![Google Chrome Audits](https://raw.githubusercontent.com/RhyG/portfolio_site/master/docs/images/audits.png "Google Chrome Audits")

As can be seen in the image the site has perfect scores across those three key areas, and a 93 in best practices which tests that the site is up to modern web development standards. 

<a id="map"></a>
# Sitemap

Here is a detailed overview of the complex structure of my website.

![Sitemap](https://github.com/RhyG/portfolio_site/blob/master/docs/sitemap.png "Sitemap")

The sitemap.xml file can be viewed [here](https://github.com/RhyG/portfolio_site/blob/master/sitemap.xml).

<a id="screens"></a>
# Screenshots 

### Trello

Screenshots of my Trello board during the development of the site are available [at this link](https://github.com/RhyG/portfolio_site/tree/master/docs/images/trello).

[Screenshot of home page](https://github.com/RhyG/portfolio_site/blob/master/docs/home.png) <br>
[Screenshot of about page](https://github.com/RhyG/portfolio_site/blob/master/docs/about.png)

<a id="audience"></a>
# Target audience

The target audience for this site is primarily potential employers. The goal of the website is for them to be able to get a good idea of my skills, abilities, style of work and overall personality just by browsing the site.

Other potential users include co-workers, recruiters and anyone who wants to get to know me.

<a id="tech"></a>
# Tech stack

The website is a static website built using HTML for the markup and CSS/SASS for the styling. The website is hosted on Github pages as well as my [personal domain](http://rhysgeary.com). On my personal domain the site components were uploaded to cPanel.

<a id="questions"></a>
# Internet questions

## Key events in the development of the internet from the 1980s to today.

In 1983 what was the proto-internet moves to TCP/IP, or the internet as we know it. The idea of a domain name system (DNS) emerges in 1983, which gives names to addresses rather than having to use numerical addresses.

In March of 1989 Tim Berners-Lee proposes what will become the world wide web. It was at this time he came up with HTML, as well as creating the first browser. 

In 1991 Tim Berners-Lee launched what was the first website, a site describing the web and HTML allowing others to contribute and create pages. 

1993 Mosaic is created at University of Illinois, this allows web pages to display graphics along with text.

1994 Online advertising is begins appearing, and begins what will be one of the largest methods of advertising ever.

2000 The Dot-Com bubble bursts and with it many major online businesses go bust.

## Define and describes the relationship between fundamental aspects of the internet such as: domains, web servers, DNS, and web browsers

Each system on a network has a unique address, or IP (internet protocol) address. The internet, being a big network, allows these systems to connect to each other and transmit data in packets. Many of these systems host web servers, which contain software and the components of a website so that it can be accessed by other systems. These web servers will reserve a name, or domain, as an address from which this data can be accessed. These names exist on domain name servers (DNS) which is a directory of names and their associated IP address. When a domain is entered into a URL bar the internet service provider checks the associated DNS and translates it into an IP address that the browser, software which translates those packets of data into a website the user can engage.

## Reflect on one aspect of the development of internet technologies and how it has contributed to the world today (max. 150 words)

Modern search engines are incredibly sophisticated technologies that allow users to access almost any part of the internet they can search for. Search engines have come along way since they were first proposed however, and are one of the major contributors to the rapid growth and pervasion of the internet. In 1991 as Tim Berners-Lee proposed the first iterations of the web, he also setup a virtual library which contains links to various academic topics. In 1993 the first web robot is created which scans and measures the size of the web. W3Catalog almost emerged, which didn't crawl the internet but used a list of websites which it scanned frequently. As the technology evolved, and search engines began to crawl the web rather than rely on an existing catalog of sites. This was fundamental as it opened the entirety of the internet to more and more people.
