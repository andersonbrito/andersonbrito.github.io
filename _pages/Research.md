---
title: "Research"
layout: splash
permalink: /_pages/Research/
date: 2016-03-23T11:48:41-04:00
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/goodsell-virology.jpg
#  cta_label: "Download"
#  cta_url: "https://github.com/mmistakes/minimal-mistakes/"
  caption: "Photo credit: [David S. Goodsell](http://mgl.scripps.edu/people/goodsell/)"
#excerpt: "Bacon ipsum dolor sit amet salami ham hock ham, hamburger corned beef short ribs kielbasa biltong t-bone drumstick tri-tip tail sirloin pork chop."
intro: 
  - excerpt: 'I am a biologist applying and developing computational tools to study molecular evolution. I hold a BSc degree in Biological Sciences from the University of Brasília (UnB), and a MSc in Microbiology from the University of São Paulo (USP), Brazil. Currently I am a last year PhD student in Computational Biology, based in the Theoretical Systems Biology Group at Imperial College London. My Bioinformatics research focuses on multiple aspects of Molecular Evolution, integrating Phylogenetics, Genomics and Protein structure data to better understand the evolution of pathogens from a systemic perpective.'

feature_row:
  - image_path: assets/images/unsplash-gallery-image-1-th.jpg
    alt: "placeholder image 1"
    title: "Placeholder 1"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder 2"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/unsplash-gallery-image-3-th.jpg
    title: "Placeholder 3"
    excerpt: "This is some sample content that goes here with **Markdown** formatting."

feature_row2:
  - image_path: /assets/images/Lorem-Ipsum.jpg
    title: "Bioinformatics"
    alt: "Placeholder Image Left Aligned"
    excerpt: 'Phasellus tempor quam nec ligula mattis, id imperdiet mi sagittis. Proin nec mauris vel velit pretium blandit eu sit amet sapien. Proin eu turpis quis sapien tempus scelerisque sit amet nec enim. Vestibulum efficitur ullamcorper augue eleifend tincidunt. Fusce porttitor diam porta enim laoreet molestie cursus non dolor. Praesent at porta leo, a accumsan lorem. Donec sollicitudin, dui ut rhoncus sodales, magna augue mollis libero, et ullamcorper nibh sem sed ante. Nulla egestas, ex pellentesque scelerisque luctus, nulla lectus dapibus turpis, at rhoncus nunc massa sed est. Vivamus gravida nisi eget enim finibus fringilla. Curabitur pellentesque ut lectus sed iaculis.'
    url: "/_pages/Publications/"
    btn_label: "Read More"
    btn_class: "btn--inverse"

feature_row3:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Right Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"

feature_row4:
  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
    alt: "placeholder image 2"
    title: "Placeholder Image Center Aligned"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}