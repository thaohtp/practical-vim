```
.blog, .news { background-image: url(/sprite.png); }
.blog { background-position: 0px 0px }
```
We’re going to duplicate the last line and make two small modifications to it: replace the word “blog” with “news,” and change “0px” to “-180px.” 

```
.blog, .news { background-image: url(/sprite.png); }
.blog { background-position: 0px 0px }
.news { background-position: -180px -180px }
```
