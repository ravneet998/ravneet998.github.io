# ravneet998.github.io-
<!DOCTYPE html>
<html>

<!--container for the metadata of an html document-->
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width">
  <title>Portfolio Web Page</title>
  <link href="style.css" rel="stylesheet" type="text/css" />
</head>


<!--has all of the content for the document-->
<body>
  <h1> <!--header-->
  Ravneet Sidhu - Software Engineering Student
  <script src="script.js"></script>
</h1>

<!--main container has all of the main content of a web page-->
<main>

    <article <!--good for news stories, blog posts, comments, and forum posts-->
			<h2>Introduction</h2>
			<p>Hi, I’m Ravneet and am currently a software engineering student at Thinkful. I am located in Burlington, New Jersey. I graduated from Rutgers University Camden this past May with a bachelors in business administration. 
</p> <!--for paragraphs-->

<hr> <!--horizontal rule used to divide content-->
    <h2>About Me</h2><!--smaller header than h1-->
  <p>I’ve been taking this course for a few weeks now and have learned a lot of information. Web development is interesting because the code one is creating shows up as all of the visuals and elements that run a website. Collaborating with others is important on larger projects. It’s great to know everyone who does their part in a project is important. 
</p>

  <p>Some interests I have outside of web development are mostly online. I like watching videos of late night hosts, such as Stephen Colbert and Seth Meyers. I like standup comedians. My favorite ones (including comedians) are: 
    <ol> <!--creates an ordered list-->
    <li>John Mulaney</li> <!--items in the list-->
    <li>Bill Burr</li>
    <li>Bill Hader</li>
    <li>Conan O'Brien</li>
</ol>
      
<p>I also like watching shows and seeing what others have to say about it on social media. </p>
      
		</article>

  
	</main>

  <footer> <!--container for links, legal details, or about the web page content-->
    <h3>Contact Information</h3>
    <p> 
<ul>    <li> <a href/"https://www.linkedin.com/in/ravneet-sidhu-57a48b168">LinkedIn</a> </li> </p>
        <p> <li> <a href="https://github.com/ravneet998">GitHub</a </li> <!--create a link and use pseudo-classes-->
</ul> 
    </p>

<img src="Burlington.png" width="30%"/> <!--inserts image-->
    
</footer>
  
  <script src="https://replit.com/public/js/replit-badge.js" theme="blue" defer></script> 
</body>

</html>

_____________________________________________________________________________________________________
CSS
html, body {
  height: 100%;
  width: 100%;
}

/*pseudo-class selector showing the normal state of a text link*/
a:link{
  color:blue /*assigns the link text as blue */
}

/*pseudo-class selector showing a link that has already been clicked on */
a:visited{
  color:darkgrey
}

main{
  background-color:#f5f0f3 /*sets background to main container*/
}

footer{
  background-color:#E6E6FA
  padding-top: 50px;
  padding-right: 30px;
  padding-bottom: 50px;
  padding-left: 80px;
  height:auto
}
/*padding is for space around the text */

p{
  margin: 50px 110px;
  font-family:Arial, Helvetica, sans-serif; /*sets font for the paragraphs*/
}

li{
  margin: 50px; /*margin for listed items*/
}

h1{
  text-align: center; /*center text alignment for h1*/
}

h2{
  font-size: 28px;
  color:#663399 /*text color for h2*/
}

footer{
  font-size:20px
  color:#663399
}
