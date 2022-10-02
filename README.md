# ash-dropdown
A small JS module for handling navbar dropdown menus. It uses a class-based system. The style of these classes can be modified using an external CSS file.

# How to use

1- Install using `npm install @ashkanarabim/dropdown`

2- Import module by adding `import ashDropdown from "@ashkanarabim/dropdown";` at the top of your JS file.

3- Use the function `ashDropdown(<variable for navbar>, <array variable of navbar dropdown buttons>)`;
This function will add a class of "clicked" to the navbar when user clicks anywhere on the navbar; this class is removed when user clicks elsewhere. It will also give a class of "open" to each dropdown menu button that is hovered. **Style your CSS such that the menu is shown only when the navbar has a class of "clicked" AND the navbar menu buttons have a class of "open"**.

# Contribution

If you are interested in contributing, [send me an email](mailto:ashkan.arabim@gmail.com) first. I'm not expecting a lot of contributors.
