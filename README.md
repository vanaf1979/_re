## Restyle
Restyle is my personal take on a reset stylesheet. Taking [Eric Meyer's](https://meyerweb.com/) advise to not take his reset css as is, but rather create your own. My Restyle aims to have as little design opinion as possible, but rather create a minimalist and uniform visual appearance for elements across different browsers, thus creating a starting point for styling html markup.

Restyle is a work in progress and by no means the only/best way of doing things. Feel free to take parts of Restyle or use the whole thing, but i would second the opinion that it would be best to take the learning opportunity and create your own from scratch or starting with Eric Meyer's [Reset Css](https://meyerweb.com/eric/tools/css/reset/)

#### Basic elements
The basic element section is largely based on reset css and is rewritten to conform to the rest of the styles and to remove duplicates. It takes care of basic resetting of margins, paddings.

#### Typography
The font/typography in Restyle is rem and em based using relative sizes from the root html/body font-size. This allows for font resizing by adjusting the base font-size on the html/body element. Restyle uses almost no functional styling of typography except for a few useful extra classes like succes/warning/danger boxes, blockquotes and coloured ul bullets. It also defaults to a recommended 17px font-size for mobile devices ( < 568px ). [View demos here](https://Restyle.vanaf1979.nl.com/typo.html)

#### Forms elements
Restyle sets a minimal white with grey border style to form elements and tries to create a uniform look and feel across browsers. It defaults to 17px font-sizes on mobile ( < 568px ) preventing zooming by the browser. it also has some wrapper classes and alignment classes for labels. [View demos here](https://Restyle.vanaf1979.nl.com/forms.html)

#### Utility classes
For convenience i added a couple of utility classes for common development tasks. Some basic clear fixes and alignment switching stuff based on Flexbox. [View demos here](https://Restyle.vanaf1979.nl.com/util.html)

#### Grids
Restyle does not include a grid system because there are enough grid flavors out there, and specific functionality is not the goal of Restyle. I would recommend using [PureCss](https://github.com/yahoo/pure) or [GridZilla](https://github.com/teefouad/gridzilla) for these tasks.

#### Demo
To see an example of Restyle check this heroku demo site. [Restyle demo](https://nameless-refuge-49303.herokuapp.com/)

#### Comments / suggestions
Please feel free to send any comments or suggestions my way. Any chance to improve, and there are lots, are always welcome.

#### About Vanaf1979.nl
While experimenting with new programming languages and frameworks i often end up with stuff that could be useful later on, or reusable parts of larger projects. I could throw it in the bin, but why not share with others, and maybe get some suggestions for improvements. [Vanaf1979.nl](http://vanaf1979.nl)
