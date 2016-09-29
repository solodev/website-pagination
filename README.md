# website-pagination
In this article, [Solodev](https://www.solodev.com/) will teach you how to add pagination, an excellent way to navigate large amounts of content, to your website using a jQuery Bootstrap Plugin. Pagination allows you to make large amounts of content easy to find and breaks up several entries or web content into multiple pages, allowing you to toggle through content with ease.

## Tutorial

View detailed instructions in Solodev's [Adding Pagination to your Website](https://www.solodev.com/blog/web-design/adding-pagination-to-your-website.stml) article.

## Demo

Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/yw7y4wez/).

## HTML

The website pagination example contains the following HTML markup.

```
<div class="container">
   <div class="jumbotron page" id="page1">
      <div class="container">
         <h1 class="display-3">Hello, World</h1>
      <p class="lead">Cras justo odio, dapibus ac facilisis in, egestas eget quam. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa justo sit amet risus.</p>
      <p><a class="btn btn-lg btn-success" href="#" role="button">Learn More</a></p>
      </div>
   </div>
   <div class="jumbotron page" id="page2">
      <h1 class="display-3">Not Another Jumbotron</h1>
      <p class="lead">Cras justo odio, dapibus ac facilisis in, egestas eget quam. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa justo sit amet risus.</p>
      <p><a class="btn btn-lg btn-success" href="#" role="button">Sign up today</a></p>
   </div>
   <div class="jumbotron page" id="page3">
      <h1 class="display-3">Data. Data. Data.</h1>
      <p>This example is a quick exercise to illustrate how the default responsive navbar works. It's placed within a <code>.container</code> to limit its width and will scroll with the rest of the page's content.</p>
      <p>
         <a class="btn btn-lg btn-primary" href="../../components/navbar" role="button">View navbar docs »</a>
      </p>
   </div>
   <div class="jumbotron page" id="page4">
      <h1 style="-webkit-user-select: auto;">Buy Now!</h1>
      <p class="lead" style="-webkit-user-select: auto;">Cras justo odio, dapibus ac facilisis in, egestas eget quam. Fusce dapibus, tellus ac cursus commodo, tortor mauris condimentum nibh, ut fermentum massa justo sit amet.</p>
      <p style="-webkit-user-select: auto;"><a class="btn btn-lg btn-success" href="#" role="button" style="-webkit-user-select: auto;">Get started today</a></p>
   </div>
   <div class="jumbotron page" id="page5">
      <h1 class="cover-heading">Cover your page.</h1>
      <p class="lead">Cover is a one-page template for building simple and beautiful home pages. Download, edit the text, and add your own fullscreen background photo to make it your own.</p>
      <p class="lead">
         <a href="#" class="btn btn-lg btn-primary">Learn more</a>
      </p>
   </div>
   <ul id="pagination-demo" class="pagination-lg pull-right"></ul>
</div>
```
## CSS

All required CSS is in pagination.css

## External Includes

This tutorial requires the following third party resources.

 ```
<link href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
<link href="pagination.css">

<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.4/jquery.min.js"></script>
<script src="https://www.solodev.com/assets/pagination/jquery.twbsPagination.js"></script>
 ```
