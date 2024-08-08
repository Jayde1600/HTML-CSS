# HTML-CSS
Capaciti HTML &amp; CSS Project

NOTES:

HTML:
1) HTML is everywhere, it is used on websites, apps and various software whenever web tech is involved. It serves as a channel for different types of content like words, images, videos, audio, forms, and interactive experiences
2) HTML Is short for HyperText Markup Language it is responsible for structuring/marking up a website. HTML has a straightforward structure without any programming logic, loops, or functions and because of this it is known as a declarative language.
3) The great thing about HTML lies in its simplicity, which gives it resilience and robustness, even if something is wrong with the HTML code, such as missing or misspelled elements, HTML will take a guess and fix it and will display this page anyway. HTML is a language that can handle a lot of abuse and still manage to deliver a functional result.

CSS: 
5) CSS is short for Cascading Style Sheets, CSS is basically like the stylist of a web page. It is responsible for how everything looks this means the colors, fonts, and sizes but is not limited here, since it can also add cool animations and interactions to spice things up.
6) CSS unlike HTML is very sensitive and very powerful at the same time. When there is a mistake in the CSS code, the browser is smart enough to skip that part and move on to the rest.

JAVASCRIPT:
7) JavaScript is a programming language that allows you to create really cool and interactive stuff, it is capable of doing this HTML and CSS can't even think of doing. The downside of this is that it is very fragile as a programming language if there is a mistake in the code or the browser is outdated then the browser will also give up and not even attempt to fix or display the code 

8) The Web runs on various platforms like Mac, Windows, iOS, Android, Linux, and more. It even runs on devices like e-book readers, game consoles, televisions, and watches.

HTML Syntax:
9) HTML is a language used to structure web pages. It uses tags, which are enclosed in less-than and greater-than symbols, to mark different elements. Tags come in two types: opening tags and closing tags. For example, the opening tag for a paragraph is <p>, and the closing tag is </p>

10) Browsers pay attention to this structure and builds a big family tree which shows how everything is related. This family tree is called a DOM tree, which stands for Document Object Model. The DOM tree becomes important when you are working with CSS or JavaScript.

11) Example of some HTML Code:
<article>
  <h1> This is the article heading </h1>
    <p> Hello, this is a test drive </p>
    <p> More test words, in here </p>
</article>

13) The HTML elements used for marking up headlines/headings come in six different types: h1 being the largest one, h2, h3, h4, h5, and h6 being the smallest. The headings get smaller as you go up in numbers but only up to 6.

14) HTML Bold and Italics, there are four HTML elements related to this, two for bold and two for italic. For bold it is <strong> and <b> and for italics it is <i> and <em>

15) A Unordered lists is the most commonly used type of list. Each item in the list is enclosed in an <li> element, which represents a list item. When you view it in the browser, notice that a dot or marker appears before each item. To define the entire list and specify its type, it will be wrapped in a <ul> element, which stands for an unordered list.
16) There is another type of list called the "definition list" or "description list. To create a definition list, we use specific elements. The term or key is enclosed in a <dt> which is called a definition term and the <dd> tag is which stands for definition description
17) To attritube a quote to Jemery we use the <cite> tag in order to make it look like this - Jemery and the whole text will get wrapped in <blockquote> text here <cite> Mr Jemery </cite> </blockquote>. In order to get our text to be wrapped with quotion marks we use <q> Hello, I'm Aphiwe </q> results = "Hello, I'm Aphiwe"
  
18) HTML attributes provide additional information to HTML elements. In this case, the datetime attribute allows us to specify the date or time in a format that computers can understand. We write it like this: <time datetime="2025-05-08">May 8, 2025</time>.
19) To show a specific moment or time for the computer to understand we use this for example, we can use it like this: <time>May 8th</time> or <time>May 8th 2025</time>

HTML Superscripts, Subscripts and Small Text:
20) This is usually used for when you need to display a math sign like for e.g. 5 to the power of 8

21) The "dir" attribute solely indicates the direction in which the text flows, using "LTR" which means left-to-right scripts and "RTL" means right-to-left scripts. These attributes, "lang" and "dir," are considered Global Attributes and can be used on any HTML element.

22) ARIA Accessible Rich Internet Applications (ARIA) is a set of roles and attributes that define ways to make web content and web applications (especially those developed with JavaScript) more accessible to people with disabilities.

23) When there's a URL like http://www.awesomedogs.com/people, it is actually looking for a file called index.html inside the folder called people. In web development, when a browser is given a URL that points to a folder, it automatically looks for an index.html file and loads it. 

24) There are four attributes that need to be accompanied with every image: The First one, we have the source attribute (SRC), this tells the browser which image file to load. 
Then we have the alt attribute (ALT), this one provides a text description of the image. Lastly, we have the width and height attributes, which determine the size of the image. So, every image should have all four of these attributes.

25) GIFs are great for compressing short illustrations but it falls short when it comes to photography and it only supports 256 colors. SVGs are perfect for logos, icons and other illustrations and unlike GIFs, SVGs are vector files that contain instructions for drawing rather than having individual pixels. This means that it can be scaled to any size and not lose image quality and the file size will also relatively remain small.

26) JPG are one of the most popular image formats, as digital cameras default to having their images to JPG. But when uploaded on the internet it needs to be compressed and resized in order to keep the images original quality.

27) PNG is a newer format that works well when you need transparency in a photograph. PNG can sometimes outperform both GIF and JPG in compressing certain types of images. When manually compressing files, try different options to find the smallest file size.
28) Audio code: <audio controls src=""></audio> There are other attributes that can be used with the audio element too. For example, "loop" will make the file repeat from the beginning once it reaches the end. "Autoplay" can automatically play the audio as soon as the page loads. In detail audio code: <audio controls src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/10558/birds.mp3"></audio>

29) MP3s are widely supported in modern browsers, while OGG had some advantages but did not gain much popularity. There is also AV1 video file format, but not widely available yet.
30) Video code: <video controls><source src=""></source> For this example, a video file has been created with 480p resolution, compressed using the H.264 codec, and delivered as an MP4 file. 480p means the video has 480 lines of resolution and is 720 pixels wide by 400 pixels tall. It is not HD or 4K, just standard quality. The H.264 codec was chosen because it is widely supported by browsers.

31) PNG, JPEG, GIF, or SVG, there are different codecs that can be used to encode video files. Video files contain a lot of data, and if not compressed, they become too large to be efficiently transmitted over the internet.
32) There have been various codecs developed over the years, such as Real Video, Sorenson, Windows Media, Flash, and H.263. From 2015 to 2020, H.264 was the dominant codec that most people used, the problem is that it is not open source so every platform, device, system that uses H.264 get's charged for using it.

33) Answers: 1. How do you create a video element that specifies different resolutions of video that browsers can choose from when loading the video? You can't do this. Instead, the browser adapts to circumstances as needed. 2. What should you do to create an audio player with controls? Use the audio element with the controls attribute set to yes. 3. What is the drawback of using the HTML video player shown in the image below? It does not permit adaptive bitrate streaming. 4. You can add chapter divisions to videos by _____. referencing a VTT file listing chapters

34) HTML Content Identification: The lang attribute is used to specify the language of a webpage. If the whole page is in one language, it is quite simple. Set the language on the main element that wraps everything else, which is usually the HTML element. It may only be required to set it once.
    
35) Once the HTML file is built, there are a few crucial parts that every web page needs. Firstly, the file should begin with a doctype statement, which indicates the era of this HTML file. In the past, there were different doctype declarations for older HTML versions. By including this one, we are saying, "Hey, this is a modern web page, so follow modern best practices and treat it accordingly." 
Next, we enclose everything else on the page within an HTML element, which means an element named HTML. It tells us that all the content within it is HTML. Place the opening HTML tag at the top and the closing HTML tag at the bottom.
36) One common use is to inform the browser that the layout has been adjusted to fit small screens, making it a responsive website. Without this meta tag, the browser assumes the page follows an older layout technique designed for desktops, which needs to be scaled down for mobile devices.
37) Answers: 1. Which tag must you use within a video element to tell the player where to look for captions? <track> 2. How can you mark a quotation as being in a different language from its surrounding text? Create a < blockquote > element with a lang attribute indicating the language for its contents. 3. What is the difference between the usage of the following?
<div> and <span>: <div> is used for blocks, and <span> is used for a part of a line. 4. Why do you need to specify the desired language for HTML content? So that the correct dictionaries and pronunciations are used
5. What are the best uses for the following HTML elements? <div> and <span>: To group elements, or mark text within an element. 

38) Once the HTML file is built, there are a few crucial parts that every web page needs. Firstly, the file should begin with a doctype statement, which indicates the era of this HTML file. In the past, there were different doctype declarations for older HTML versions. By including this one, we are saying, "Hey, this is a modern web page, so follow modern best practices and treat it accordingly." 
Next, we enclose everything else on the page within an HTML element, which means an element named HTML. It tells us that all the content within it is HTML. Place the opening HTML tag at the top and the closing HTML tag at the bottom. 

39) Inside the head of a webpage, you put important information that the browser needs to know about the website. The HTML head serves as a central hub for connecting and setting up various components, ensuring that all assets are loaded and sharing page information with other sites and platforms. In a way, it is like the headquarters for getting the page off to a good start.
40) 1. Main: The main element is used once per webpage and tells the browser where the main content is located. 2. Header: The header and footer elements mark the header and footer areas on the page. Do not confuse header with head though. Head is where the file's metadata lives and is not displayed to users. Header is used for site headers, article headers, and headers within the content. A header is usually found at the top of most web pages and may include a logo, site name, and navigation. 3. Footer:
The footer signifies that there are extra things to convey, regardless of its position on the page. 4. Article: An article often starts with a title, subtitle, author's name, and publication date, which can also be considered a header. Many web pages end with a footer at the bottom, containing links, copyright information, and additional details about the company. However, footers can also appear elsewhere. Some articles begin with metadata like hashtags or share buttons, which are suitable for a footer element. The article element wraps around any type of content unit, whether it is a long written article, a short snippet, a teaser card, a tweet, or even an app element. It represents a standalone unit of content. 5. Section: The section element is used to mark sections of content. For example, in a long essay with subheadings, each segment can be wrapped in a section element. It is also useful for dividing different topic zones on a website. Each section typically starts with its own headline. 6. Aside: Lastly, the aside element is for content that is off to the side, like sidebar information or additional details that accompany an article but are not part of its main flow. Advertisements can also be marked as an aside. Although the position on the page does not matter, the semantic meaning of these elements is crucial. The visual layout often conveys meaning, and these HTML elements help transfer that meaning from the design to the content.
41) the main element is used once per page to wrap the main content, while the header, footer, article, section, and aside elements are the five sectioning elements in HTML. They are combined and nested to structure the content of a webpage.
