# sparta-weekend-hw1
Min. 3 page website incorporating all learned material so far. This project also allowed me to practice proper git workflow, creating a branch for each feature.


# The Task

Your task for this weekend is to consolidate everything you've learned this week by building a 3-page (or more, if you're feeling up to it) website. Be creative! This could be your own personal portfolio where you can display a hobby, or something entirely irrelevant.

It can be on a topic of your choosing, but must include:

	* Navbar
	* Jumbotron
	* Lists
	* Tables
	* Image gallery
	* Videos (NOT embedding from YouTube, Vimeo etc)
	* Carousel
	* Pagination OR Modal
	* Profile section (photo, name, job title, description etc.)
	* Footer with common links (eg. Sitemap)

  ## The website
  The website I designed is a template media portfolio where the user can view an image gallery of the site owner's photos. The user can also navigate to the videos page using the navbar to watch any videos the site owner displays. The footer contains links to popular social media.

  ### What I'm most pleased with
  The responsiveness of all elements. even the navbar becomes a collapsible menu on a smaller screen.

  ### The biggest challenge
  Deciding how the website would look - wireframing would have helped a lot.

## Navbar
```html
<nav class="navbar navbar-default">
	<div class="container-fluid">
		<!-- Brand and toggle get grouped for better mobile display -->
		<div class="navbar-header">
			<button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#navbar-collapse" aria-expanded="false">
				<span class="sr-only">Toggle navigation</span>
				<span class="icon-bar"></span>
				<span class="icon-bar"></span>
				<span class="icon-bar"></span>
			</button>
			<a class="navbar-brand" href="index.html">
				<img id="sgthumb" src="./img/sparta-media.png" alt="Logo"> SPARTA MEDIA
			</a>
		</div>

		<!-- Collect the nav links, forms, and other content for toggling -->
		<div class="collapse navbar-collapse" id="navbar-collapse">
			<ul class="nav navbar-nav navbar-right">
					<li><a href="./pages/imgGallery.html">Gallery</a></li>
					<li><a href="./pages/videos.html">Videos</a></li>
			</ul>
		</div><!-- /.navbar-collapse -->
	</div><!-- /.container-fluid -->
</nav>
```
The
