---
layout: post
title: django-tinymce + django-filebrowser + django-blog-zinnia
---

How to make django-tinymce to use django-filebrowser for django-blog-zinnia posts.
If you want to use tinymce widget to edit zinnia blog posts
you also may want to use filebrowser to insert / edit images
using your media django media folder. It does not work out of the box.

What to do:

* install [zinnia](http://django-tinymce.readthedocs.org/en/latest/)
* install [filebrowser](https://django-filebrowser.readthedocs.org/en/latest/)
* install [django-tinymce](http://django-tinymce.readthedocs.org/en/latest/)

After that zinnia will use tinymce, but filebrowser won't work to insert images. Look carefully at
<http://docs.django-blog-zinnia.com/en/latest/getting-started/configuration.html#tinymce>

And create your own file ``admin/zinnia/entry/tinymce_textareas.js`` with content:

<script src="https://gist.github.com/iutinvg/5705267.js"></script>
