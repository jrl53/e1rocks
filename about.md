---
layout: default

reps:
  - name: Vihar Parikh
    title: Academic
    image: vihar-2.jpg
  - name: Mihran Khachkhechyan
    title: Academic
    image: mihran-1.jpg
  - name: Mavra Khan
    title: Career
    image: mavra-3.jpg
  - name: Timi Adelaja
    title: Carerr
    image: timi-4.jpg
  - name: Daniel Zachman
    title: Social
    image: daniel-6.jpg
  - name: Gabriel Alves
    title: Social
    image: gabriel-5.jpg
  - name: Jose Leon
    title: IT/Media
    image: jose-7.jpg


---


<!-- Page Heading/Breadcrumbs -->
<div class="row">
    <div class="col-lg-12">
        <h1 class="page-header">About
            <small>Subheading</small>
        </h1>
        <ol class="breadcrumb">
            <li><a href="index.html">Home</a>
            </li>
            <li class="active">About</li>
        </ol>
    </div>
</div>
<!-- /.row -->

<!-- Intro Content -->
<div class="row">
            <div class="col-md-6">
                <img class="img-responsive" src="{{ site.placeholderimagesbaseurl }}moments_3.jpg" alt="">
            </div>
            <div class="col-md-6">
                <h2>About this site</h2>
                <p>INSEAD is an intense experience. You know it.</p>
                <p>This site is a snapshot of the great times we had in Section 1 for just four months.</p>
                <p>You can think about it as a digital yearbook (four-month-book?) that you can visit anytime when you are old and wrinkly (provided the domain still exists)</p>
            </div>
        </div>
<!-- /.row -->

<!-- Team Members -->
<div class="row">
    <div class="col-lg-12">
        <h2 class="page-header">Meet the Reps</h2>
    </div>
    {% for rep in page.reps %}
    <div class="col-md-4 text-center">
        <div class="thumbnail">
            <img class="img-responsive" src="{{ site.placeholderimagesbaseurl }}{{ rep.image }}" alt="">
            <div class="caption">
                <h3>{{ rep.name }}<br>
                    <small>{{ rep.title }}</small>
                </h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iste saepe et quisquam nesciunt maxime.</p>
                <ul class="list-inline">
                    <li><a href="#"><i class="fa fa-2x fa-facebook-square"></i></a>
                    </li>
                    <li><a href="#"><i class="fa fa-2x fa-linkedin-square"></i></a>
                    </li>
                    <li><a href="#"><i class="fa fa-2x fa-twitter-square"></i></a>
                    </li>
                </ul>
            </div>
        </div>
    </div>
    {% endfor %}
</div>
<!-- /.row -->


