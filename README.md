# bootstrap-tabs-portfolio

Showcasing clients or products can be one of the most effective ways to bring in more business to your website. A simple way to display all of your organization's hard work is by using Bootstrap tabs to show off these elements in an orderly fashion. Bootstrap tabs offer more than a clean look; they can even be subdivided using tabs to help your website visitors find a particular category that interests them. 		

## Tutorial		  
For detailed instruction's, view Solodev's [Using Bootstrap Tabs to Showcase Portfolio Elements](https://www.solodev.com/blog/web-design/using-bootstrap-tabs-to-showcase-portfolio-elements.stml) article.
 
## Demo
  		  
Try out a working example on [JSFiddle](https://jsfiddle.net/solodev/1c2yty3x/28/).

## HTML

The tutorial contains the following basic HTML markup.

```
<div class="container">
  <div class="row">
    <div class="col-sm-12">
      <ul class="nav justify-content-center" role="tablist" id="customersCats" >
        <li class="nav-item">
          <a class="nav-link active show" href="#featuredSection" id="featured" data-toggle="tab" role="tab" aria-controls="featuredSection" aria-selected="true">Feature</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#educationSection" id="education" data-toggle="tab" role="tab" aria-controls="educationSection" aria-selected="false">Education</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#healthSection" id="healthcare" data-toggle="tab" role="tab" aria-controls="healthSection" aria-selected="false">Healthcare</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#nonProfitSection" id="nonprofit" data-toggle="tab" role="tab" aria-controls="nonProfitSection" aria-selected="false">Non-Profit</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#privateSection" id="private" data-toggle="tab" role="tab" aria-controls="privateSection" aria-selected="false">Private Sector</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#publicSection" id="public" data-toggle="tab" role="tab" aria-controls="publicSection" aria-selected="false">Public Sector</a>
        </li>
      </ul>
    </div>
  </div><!-- row-->
  <div class="row">
    <div class="col-sm-12">
      <div class="tab-content" id="catsContent">
        <div class="tab-pane fade show active" id="featuredSection" role="tabpanel" aria-labelledby="featured">
          <div class="row">
            <div class="col-sm-6 col-md-4" onclick="location.href='#'">
              <a href="#">
                <img src="https://raw.githubusercontent.com/solodev/bootstrap-tabs-portfolio/master/1.jpg" alt="Portfolio Item" class="img-fluid"/>
              </a>
            </div>
            <div class="col-sm-6 col-md-4" onclick="location.href='#'">
              <a href="#">
                <img src="https://raw.githubusercontent.com/solodev/bootstrap-tabs-portfolio/master/2.jpg" alt="Portfolio Item" class="img-fluid" />
              </a>
            </div>
            <div class="col-sm-6 col-md-4" onclick="location.href='#'">
              <a href="#">
                <img src="https://raw.githubusercontent.com/solodev/bootstrap-tabs-portfolio/master/3.jpg" alt="Portfolio Item" class="img-fluid"/>
              </a>
            </div>
          </div><!-- row-->
        </div>
        <div class="tab-pane fade" id="educationSection" role="tabpanel" aria-labelledby="education">
          <div class="row">
            <div class="col-sm-6 col-md-4" onclick="location.href='#'">
              <a href="#">
                <img src="https://raw.githubusercontent.com/solodev/bootstrap-tabs-portfolio/master/2.jpg" alt="Portfolio Item" class="img-fluid"/>
              </a>
            </div>
            <div class="col-sm-6 col-md-4" onclick="location.href='#'">
              <a href="#">
                <img src="https://raw.githubusercontent.com/solodev/bootstrap-tabs-portfolio/master/4.jpg" alt="Portfolio Item" class="img-fluid" />
              </a>
            </div>
          </div><!-- row-->
        </div>
        <div class="tab-pane fade" id="healthSection" role="tabpanel" aria-labelledby="healthcare">
          <div class="row">
            <div class="col-sm-6 col-md-4" onclick="location.href='#'">
              <a href="#">
                <img src="https://raw.githubusercontent.com/solodev/bootstrap-tabs-portfolio/master/3.jpg" alt="Portfolio Item" class="img-fluid"/>
              </a>
            </div>
            <div class="col-sm-6 col-md-4" onclick="location.href='#'">
              <a href="#">
                <img src="https://raw.githubusercontent.com/solodev/bootstrap-tabs-portfolio/master/5.jpg" alt="Portfolio Item" class="img-fluid"/>
              </a>
            </div>
            <div class="col-sm-6 col-md-4" onclick="location.href='#'">
              <a href="#">
                <img src="https://raw.githubusercontent.com/solodev/bootstrap-tabs-portfolio/master/6.jpg"  alt="Portfolio Item" class="img-fluid"/>
              </a>
            </div>
          </div>
        </div>
        <div class="tab-pane fade" id="nonProfitSection" role="tabpanel" aria-labelledby="nonprofit">
          <div class="row">
            <div class="col-sm-6 col-md-4" onclick="location.href='#'">
              <a href="#">
                <img src="https://raw.githubusercontent.com/solodev/bootstrap-tabs-portfolio/master/1.jpg" alt="Portfolio Item" class="img-fluid" />
              </a>
            </div>
            <div class="col-sm-6 col-md-4" onclick="location.href='#'">
              <a href="#">
                <img src="https://raw.githubusercontent.com/solodev/bootstrap-tabs-portfolio/master/3.jpg"  alt="Portfolio Item" class="img-fluid"/>
              </a>
            </div>
          </div>
        </div>
        <div class="tab-pane fade" id="privateSection" role="tabpanel" aria-labelledby="private">
          <div class="row">
            <div class="col-sm-6 col-md-4" onclick="location.href='#'">
              <a href="#">
                <img src="https://raw.githubusercontent.com/solodev/bootstrap-tabs-portfolio/master/6.jpg"  alt="Portfolio Item" class="img-fluid"/>
              </a>
            </div>
            <div class="col-sm-6 col-md-4" onclick="location.href='#'">
              <a href="#">
                <img src="https://raw.githubusercontent.com/solodev/bootstrap-tabs-portfolio/master/7.jpg"  alt="Portfolio Item" class="img-fluid"/>
              </a>
            </div>
            <div class="col-sm-6 col-md-4" onclick="location.href='#'">
              <a href="#">
                <img src="https://raw.githubusercontent.com/solodev/bootstrap-tabs-portfolio/master/8.jpg"  alt="Portfolio Item" class="img-fluid"/>
              </a>
            </div>            
          </div>
        </div>
        <div class="tab-pane fade" id="publicSection" role="tabpanel" aria-labelledby="public">
          <div class="row">
            <div class="col-sm-6 col-md-4" onclick="location.href='#'">
              <a href="#">
                <img src="https://raw.githubusercontent.com/solodev/bootstrap-tabs-portfolio/master/2.jpg"  alt="Portfolio Item" class="img-fluid"/>
              </a>
            </div>
            <div class="col-sm-6 col-md-4" onclick="location.href='#'">
              <a href="#">
                <img src="https://raw.githubusercontent.com/solodev/bootstrap-tabs-portfolio/master/4.jpg"  alt="Portfolio Item" class="img-fluid"/>
              </a>
            </div>            
          </div>
        </div>
        </div>
    </div>
  </div><!--row-->
</div><!-- container-->
```

## CSS

All required CSS is contained with bootstrap-tabs-portfolio.css


## External Resources

This tutorial includes the following third party resources.

```
<link href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-alpha.6/css/bootstrap.min.css" rel="stylesheet">
<script src="https://code.jquery.com/jquery-3.2.1.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-alpha.6/js/bootstrap.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js"></script>
```

