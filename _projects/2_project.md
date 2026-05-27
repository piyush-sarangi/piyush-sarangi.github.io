---
layout: page
title: IIT KGP Courses Review
description: This is a list of reviews of some of the courses we have taken at IITKGP
img: assets/img/IIT-KGP.jpg
importance: 2
category: resources and reviews
giscus_comments: true
---

These set of reviews serve two purposes,

1. Firstly, they are very helpful for me to revise stuff later! 
2. Secondly I hope that they are useful for other students when taking up a course!
   
These set of reviews also feature two amazing MITOCW course reviews. I hope I can take more of those courses!

MITOCW is a big inpsiration for me and probably this idea of creating and sharing course reviews is somehow inspired by them!

> “Some of you might remember that in the late nineties when the first internet boom was happening, there was a lot of talk about online education. And most of the talk back then about online education, actually not too different from now, was either about how to profit from it, how to make money off of it, OR as some institutions were thinking, about how to defend against it or at least sit on the sidelines and see how everything played out.
>
> And all of a sudden MIT jumped into the mix in 2001, and announced MIT OpenCourseWare — that it was going to take knowledge and resources that used to be behind the walls of elite institutions and not charge for them but give them away for free to the world.
>
> And instead of saying ‘how can we profit off of this?’ MIT said, well there are some things that are higher than that.”
> 
> -- Sal Khan at Massachusetts Institute of Technology (2012)

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
