# bs-extrawidth.css

## About This Project

This stylesheet allows you to change div widths based on Bootstrap 5 Breakpoints. It is very useful for resizing widths at specified breakpoints.

## Getting Started

Import using HTML: `<link rel="stylesheet" href="https://rawcdn.githack.com/gtgtcode/bs-extrawidth/afcd9e2cf9f86ced07c7e422bfef3c452b356aa7/bs-extrawidth.css">`

Import using CSS: `@import url("https://rawcdn.githack.com/gtgtcode/bs-extrawidth/afcd9e2cf9f86ced07c7e422bfef3c452b356aa7/bs-extrawidth.css");`

## Usage

Add an extrawidth class to a div with a Bootstrap 5 `w` class and have the Bootstrap class be overwritten when your desired breakpoint is reached.

Example:
`<div class="w-50 sm-w-100"></div>`

bs-extrawidth contains 5 sizes (x-small, small, medium, large, and x-large) that you can use to change the width breakpoint.

To specify a breakpoint that has a width you would like to override, add the size of the breakpoint in the beginning of the class. (Ex: `sm-w` for small devices, like a smartphone.) Then, you can specify the width you would like at that breakpoint. (Ex: `sm-w-75` for a width of 75 on a small display.) bs-extrawidth, like the regular Bootstrap 5 width class, has four width options: 25, 50, 75, 100.
