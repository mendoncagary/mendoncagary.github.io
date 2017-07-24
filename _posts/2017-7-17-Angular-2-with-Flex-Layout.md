---
layout: post
title: Angular 2 with Flex Layout
---

Learn how to develop responsive sites with Angular 2 Flex layout 

![_config.yml]({{ site.baseurl }}/images/config.png)

  Flex Layout is a layout engine that is used for developing responsive websites with Angular 2 material. It uses FlexBox CSS and CSS Media Queries to provide layouts that can fit to different sizes. For the official repository head over to the [Angular Flex Layout](https://github.com/angular/flex-layout) on GitHub.
  
  ## Installation
  
  ```bash
  npm install --save @angular/flex-layout
  ```
  
  ```html
  <div class="container"
     fxLayout
     fxLayout.xs="column"
     fxLayoutAlign="center"
     fxLayoutGap="10px"
     fxLayoutGap.xs="0">
  <div class="item item-1" fxFlex="15%">Item 1</div>
  <div class="item item-2" fxFlex="20%" fxFlexOrder="3">Item 2</div>
  <div class="item item-3" fxFlex>Item 3</div>
</div>

<div class="container"
     fxLayout
     fxLayout.xs="column"
     fxLayoutAlign="center"
     fxLayoutGap="10px"
     fxLayoutGap.xs="0">
  <div class="item item-4" fxFlex fxFlexOffset="50px"  fxFlexOffset.xs="0">Item 4</div>
  <div class="item item-5" fxFlex="200px">Item 5</div>
</div>
  
  ```
