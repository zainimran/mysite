+++
date = "2015-08-22"
title = "Blog"
+++

<!-- CSS-->
<style type="text/css">
    @charset "UTF-8";
    .blog .blog-post {
    margin-bottom: 40px;
    }
    .blog .blog-post header {
    position: relative;
    }
    .blog .blog-post header .date {
    background-color: #fdfdfd;
    position: absolute;
    padding: 10px;
    text-align: center;
    font-weight: 500;
    z-index: 9;
    color: #2c2c2c;
    }
    .blog .blog-post .blog-content {
    padding: 15px 28px;
    border: 1px solid #f5f5f5;
    }
    .blog .blog-post .blog-content h4 {
    margin: 20px 0;
    letter-spacing: 1px;
    }
    .blog .blog-post .blog-content h4 a {
    color: #333;
    }
    .blog .blog-post .blog-content .post-meta {
    text-transform: uppercase;
    margin-bottom: 18px;
    padding-bottom: 10px;
    font-size: 12px;
    border-bottom: 1px solid #F5F5F5;
    }
    .blog .blog-post .blog-content .post-meta span {
    color: #CCC;
    }
    .blog .blog-post .blog-content .post-meta span:first-child a {
    color: #848484;
    }
    .blog .blog-post .blog-content .post-meta span a {
    color: #CCC;
    border-bottom: 1px rgba(0, 0, 0, 0);
    }
    .blog .blog-post .blog-content .post-meta span a:hover {
    text-decoration: none;
    border-bottom-style: solid;
    border-color: inherit;
    }
    .blog .blog-post .blog-content .post-meta span {
    padding-right: 10px;
    border-right: 1px solid #CCC;
    margin-right: 10px;
    }
    .blog .blog-post .blog-content .post-meta span:last-child {
    margin-right: 0;
    border-right: 0;
    padding-right: 0;
    }
    .blog .blog-post .blog-content p {
    color: #67666a;
    line-height: 22px;
    }
    .blog .blog-post footer {
    border: 1px solid #DDD;
    padding: 0px 15px;
    }
    .blog .blog-post footer .comment-count {
    color: #000;
    position: relative;
    padding-left: 25px;
    }
    .blog .blog-post footer .comment-count:hover,
    .blog .blog-post footer .comment-count:focus {
    color: #000;
    }
    .blog .blog-post footer .read-more {
    color: #000;
    position: relative;
    padding-left: 25px;
    padding-right: 0;
    text-transform: uppercase;
    }
    .blog .blog-post footer .read-more:hover,
    .blog .blog-post footer .read-more:focus {
    color: #000;
    }

    @media (min-width: 768px) {
    .blog .blog-post header .image-slider-carousel .carousel-control.left {
        top: 200px;
        bottom: 5px;
        left: 220px;
    }
    .blog .blog-post header .image-slider-carousel .carousel-control.right {
        top: 200px;
    }
    }
    @media (min-width: 992px) {
    .blog .blog-post header .image-slider-carousel .carousel-control.left {
        top: 210px;
        bottom: 5px;
        left: 235px;
    }
    .blog .blog-post header .image-slider-carousel .carousel-control.right {
        top: 210px;
        right: 10px;
        bottom: 5px;
    }
    }
    .blog-standard .blog-post {
    margin-bottom: 80px;
    }
    .blog-standard .blog-post:last-child {
    margin-bottom: 0;
    }
    .blog-standard .blog-post .featured-image {
    margin-bottom: 30px;
    }
    .blog-standard .blog-post .post-title {
    margin-bottom: 15px;
    }
    .blog-standard .blog-post .post-title > a {
    color: #5c5c5c;
    }
    .blog-standard .blog-post .post-title > a:hover {
    color: #000000;
    text-decoration: none;
    }
    .blog-standard .blog-post .post-meta {
    color: silver;
    letter-spacing: 1px;
    text-transform: uppercase;
    font-size: 11px;
    margin-bottom: 30px;
    }
    .blog-standard .blog-post .post-meta a {
    color: #656565;
    }
    .blog-standard .blog-post .post-meta span {
    margin: 0 6px;
    }
    .blog-standard .blog-post .read-more {
    margin-top: 25px;
    }
    .blog-standard .blog-post .read-more a {
    text-transform: uppercase;
    color: black;
    transition: all 0.2s;
    }
    .blog-standard .blog-post .read-more a:hover {
    color: silver;
    text-decoration: none;
    }

    /*overriding bootstrap's default pagination */
    .pagination-lg > li:last-child > a, .pagination-lg > li:last-child > span {
    border-top-right-radius: 2px;
    border-bottom-right-radius: 2px;
    }

    .pagination-lg > li:first-child > a, .pagination-lg > li:first-child > span {
    border-top-left-radius: 2px;
    border-bottom-left-radius: 2px;
    }

    .pagination > li {
    display: inline-block;
    margin-right: 8px;
    }

    .pagination > .active > a, .pagination > .active > span, .pagination > .active > a:hover, .pagination > .active > span:hover, .pagination > .active > a:focus, .pagination > .active > span:focus {
    background-color: black;
    border-color: black;
    }

    .pagination > li > a, .pagination > li > span {
    color: #909090;
    }

    .sidebar {
    padding: 0 0 0 30px;
    }
    .sidebar .widget {
    margin-bottom: 60px;
    }
    .sidebar .widget.popular-posts .widget-content ul {
    padding: 15px 0 0 0;
    list-style: none;
    color: #b0b0b0;
    }
    .sidebar .widget.popular-posts .widget-content ul li {
    margin-bottom: 30px;
    }
    .sidebar .widget.popular-posts .widget-content ul .thumb {
    margin-right: 10px;
    margin-top: -10px;
    }
    .sidebar .widget.popular-posts .widget-content ul .title {
    color: gray;
    }
    .sidebar .widget.popular-tags a {
    margin-bottom: 6px;
    }
    .sidebar .widget.categories ul {
    list-style: none;
    padding: 0;
    }
    .sidebar .widget.categories ul li {
    line-height: 3em;
    }
    .sidebar .widget.categories ul li:before {
    content: "";
    font: normal normal normal 14px/1 FontAwesome;
    margin-right: 15px;
    }
    .sidebar .widget.categories ul li a {
    color: black;
    }
    .sidebar .widget.categories ul li a:hover {
    color: gray;
    }

    .left-sidebar .sidebar {
    padding: 0 30px 0 0;
    }

    .blog-grid .blog-element {
    max-height: 290px;
    overflow: hidden;
    }
    .blog-grid .blog-element img {
    width: 100%;
    }
</style>

<!-- Blog-->
<section class="section blog" id="blog">
    <div class="container">
        <!---->
        <header class="section-heading">
        <h2>From The Blog</h2><span>Awesome articles from the blog</span>
        </header>
        <!---->
        <div class="section-content" id="blogContent">
        <div class="row" id="jsonContent"></div>
        </div>
        <!-- /#blogContent-->
        <div class="text-center"><a class="btn btn-dark" id="loadBlogPosts" href="//medium.com/@zainimran">View All<span class="fa fa-angle-double-right"></span></a></div>
    </div>
    <!-- /.container-->
</section>
<!-- Blog-->

<script src="https://code.jquery.com/jquery-2.2.4.min.js"></script>
<script src="https://cdn.rawgit.com/phstc/jquery-dateFormat/master/dist/jquery-dateFormat.min.js"></script>
<script type="text/javascript">
    $(function () {
        var $content = $('#jsonContent');
        var data = {
            rss_url: 'https://medium.com/feed/@zainimran/'
        };
        $.get('https://api.rss2json.com/v1/api.json', data, function (response) {
            if (response.status == 'ok') {
                var output = '';
                $.each(response.items, function (k, item) {
                    var postCategories = response.items[k].categories
                    if(postCategories.length !== 0 ) {
                    var visibleSm;
                    if(k < 100){
                        visibleSm = '';
                    } else {
                        visibleSm = ' visible-sm';
                    }
                    output += '<div class="col-sm-6 col-md-4' + visibleSm + '">';
                    output += '<div class="blog-post"><header>';
                    output += '<h4 class="date">' + $.format.date(item.pubDate, "dd<br>MMM") + "</h4>";
                    var tagIndex = item.description.indexOf('<img'); // Find where the img tag starts
                    var srcIndex = item.description.substring(tagIndex).indexOf('src=') + tagIndex; // Find where the src attribute starts
                    var srcStart = srcIndex + 5; // Find where the actual image URL starts; 5 for the length of 'src="'
                    var srcEnd = item.description.substring(srcStart).indexOf('"') + srcStart; // Find where the URL ends
                    var src = item.description.substring(srcStart, srcEnd); // Extract just the URL
                    output += '<div class="blog-element"><img class="img-responsive" src="' + src + '" width="360px" height="240px"></div></header>';
                    output += '<div class="blog-content"><h4><a href="'+ item.link + '">' + item.title + '</a></h4>';
                    output += '<div class="post-meta"><span>By ' + item.author + '</span></div>';
                    var yourString = item.description.replace(/<img[^>]*>/g,"");
                    var maxLength = 120 // maximum number of characters to extract
                    //trim the string to the maximum length
                    var trimmedString = yourString.substr(0, maxLength);
                    //re-trim if we are in the middle of a word
                    trimmedString = trimmedString.substr(0, Math.min(trimmedString.length, trimmedString.lastIndexOf(" ")))
                    output += '<p>' + trimmedString + '...</p>';
                    output += '</div></div></div>';
                    return k < 100;
                    }
                });
                $content.html(output);
            }
        });
    });
</script>