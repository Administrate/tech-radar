---
layout: details
filename: cssinjs
name: CSS in JS
image: /tech-radar/assets/images/languages-frameworks/cssinjs.png
category: languages-frameworks
ring: Trial
---

# What is it ?
CSS-in-JS refers to a collection of ideas to solve complex problems with CSS. Example libraries are JSS (partial used) or Linaria.

# Why ?
Using a CSS in JS has multiple benefits, 
- Reduces the load time of our application over "react with styles". Options include run-time vs build-time.
- Removes the complexity of styling through our various applications to a single source.
- CSS in JS is scoped, if it's used in Weblink it means it won't be affected by customer stylesheets.

# History
## 2021
The Design System started using react-jss (part of JSS) in the Design System for new components. It was picked by Chris Beswick due it being adopted by Material UI.

## 2022
We have a productionised proof of concept with JSS whereby we can pass in branding variables from a client application to th Designs System and JSS adjusts the colours where allowed.

# Resources
- [Airbnb usecase](https://medium.com/airbnb-engineering/airbnbs-trip-to-linaria-dc169230bd12)
- [react-jss](https://cssinjs.org/react-jss?v=v10.9.2)
- [Linaria](https://github.com/callstack/linaria)

