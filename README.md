# Tictacly Grid
A fancy Tic Tac Toe game! It has multiple modes to play, changeable themes and saved played rounds in scoreboard.  
Explore more in demo: [Netlify Built](https://tictaclygrid.netlify.app/) | [github-pages](https://ceenayekta.github.io/tictacly-grid/).

### Features
**Setting Drawer**
- 6 color themes
- 3 different modes to play (3x3, 5x5, 7x7). Note that you need to score 4 fields to win in 5x5 and 7x7 modes.

**Scoreboard Drawer**
- After a players score or face a draw, earned scores and played rounds will be stored in Scoreboard drawer.

### Logic
When mode gets changed, grid view gets updated and `var winningConditions = []` will be generated by a pattern based on the chosen mode (`size: 3 | 5 | 7`) and needed cells to win (3 cells in 3x3 mode and 4 cells in other modes). Took hours to find the pattern :eyes:...

### Used Techs
<a href="https://www.w3.org/TR/html5/" title="HTML5"><img src="https://github.com/get-icon/geticon/raw/master/icons/html-5.svg" alt="HTML5" width="21px" height="21px"></a>
<a href="https://www.w3.org/TR/CSS/" title="CSS3"><img src="https://github.com/get-icon/geticon/raw/master/icons/css-3.svg" alt="CSS3" width="21px" height="21px"></a>
<a href="https://getbootstrap.com/" title="Bootstrap"><img src="https://github.com/get-icon/geticon/raw/master/icons/bootstrap.svg" alt="Bootstrap" width="21px" height="21px"></a>
<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" title="JavaScript"><img src="https://github.com/get-icon/geticon/raw/master/icons/javascript.svg" alt="JavaScript" width="21px" height="21px"></a>
<a href="https://jquery.com/" title="jQuery"><img src="https://github.com/get-icon/geticon/raw/master/icons/jquery-icon.svg" alt="jQuery" width="21px" height="21px"></a>
