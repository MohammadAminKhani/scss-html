# scss-html
98.12.19 tiny project

## features
1. web server: clickOnHtml (no need httpster or express-nodmon)
2. compiler: scss (no need webpack or compass-compile)

## Run
1. terminal
```
cd Desktop/scss-html
scss sass/screen.scss stylesheets/screen.css
scss --watch sass/screen.scss:stylesheets/screen.css
```
2. then click on scss-html/index.html and enjoy watching your hand working result :open_mouth: like this:

[what browser shows](https://archive.org/download/981219scsshtml1/981219scsshtml1.png)

## more info
sass/screen.scss
```

/*@import 'module/hello';
  reads module/_hello.scss local file */
@import 'hello';
/* reads _hello.scss local file */

@import "compass/reset";
/* compass/reset makes all h2 big size and ... from html to be same as p tag!
for compass/reset use '$ compass compile' or '$ compass watch'  */

@import 'susy';
/* gem install susy */

/*
@import 'breakpoint';
@import 'bootstrap';
@import '~bootstrap';

 address should be write in grunt,gulp or webpack to read bootstrap!
 compiler: scss --watch scss:css
 */

```