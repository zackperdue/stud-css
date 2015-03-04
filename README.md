# Stud CSS Grid

A very simple non opinionated css grid framework for building highly customized website layouts. Stud grid makes no assumptions over gutters, padding or margins.

![Stud CSS Grid](example/grid.png)

## Why?

This is the css grid that I created for my personal/client projects because I found that all other css frameworks made too many assumptions about how my applications should look.

Instead of placing margins or padding on the columns themselves, I propose that you place any margin or padding on your important components that are inside of the columns, giving you more control over your grid and layout and less customization of the framework.

## How to use

This is the markup for the test above.

```
<div class="container">
  <div class="row">
    <div class="column one">1</div>
    <div class="column eleven">11</div>

    <div class="column two">2</div>
    <div class="column ten">10</div>

    <div class="column three">3</div>
    <div class="column nine">9</div>

    <div class="column four">4</div>
    <div class="column eight">8</div>

    <div class="column five">5</div>
    <div class="column seven">7</div>

    <div class="column six">6</div>
    <div class="column six">6</div>

    <div class="column seven">7</div>
    <div class="column five">5</div>

    <div class="column eight">8</div>
    <div class="column four">4</div>

    <div class="column nine">9</div>
    <div class="column three">3</div>

    <div class="column ten">10</div>
    <div class="column two">2</div>

    <div class="column eleven">11</div>
    <div class="column one">1</div>

    <div class="column twelve">12</div>
  </div>
</div>
```
