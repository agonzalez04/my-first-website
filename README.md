# my-first-website# 
during my first rest, wave detected 0 accessibility errors and 0 contrast errors with an aim score of 10/10 
to practice and correcting accessibilty problems i added three errors to my home page. 
my first error i added an image without an alt attribute making it inaccessible to users who rely on screen readers
i also added a link without text making it difficult for screen readers to undewrstand its purpose
then i adderd a button without text label making its purpose unclear to assist tech users

after adding these the wave page detected 3 accessibilty errors
to correct these problems i made the following changed
<img src="images/test.png">
<img src="https://cdn-icons-png.flaticon.com/512/25/25231.png"
     width="50"
     alt="GitHub logo">

<a href="about.html"></a>
<a href="about.html">Learn About Me</a>
<button type="button"></button>
<button type="button">Learn More</button>

For my IT porfolio website, i applied two Gestalt principles: proximitiy and similarity

Proximity: i used proximity by grouping related content inside sections using .content-box css class. I also added padding and marings to create space between the sections. I also used a css grid with a 16px gap to organize content and make the website easier to read. 
Similarity: i used similarity by keeping the headings, content boxes and navigation links styled consisntentyl. my h2 and h3 use the same dark purple color and roboto font. this creates consisntent appearance througyht my website.
