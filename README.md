# A CSS clock, one of many ...

<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="bender-clock.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<bender-clock></bender-clock>
```

# Introduction

I saw this nice [article on CSS clocks](https://cssanimation.rocks/clocks/), when I was looking for some ideas for my magic mirror project.  
It uses CSS transitions to animate the analog clock.  

For me it's a nice project to sharpen my skills in; CSS3, Javascript, units tests, Polymer, Web Componenets and Raspberry Pi projects.

## Why CSS

The clock is animated using **CSS3 transform properties**. This means optimal browser performance. JavaScript is only used to set the start time, dimensions and Polymer Web Components.
