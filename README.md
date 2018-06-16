# Beginer For Programming
Should install Terminal
https://github.com/wesbos/Cobalt2-iterm
## Cobalt2 for iTerm2 and ZSH
<code>cobalt2.itermcolors</code> is for anyone who uses iTerm2 and wants the colours. The cobalt2.zsh-theme is the prompt layout for zsh users.

They work well together! You will need to install the patched powerline font as well: https://github.com/powerline/fonts

Step-by-step installation
Drop the cobalt2.zsh-theme file in to the <code>~/.oh-my-zsh/themes/ directory.</code>

Open up your ZSH preferences at ~/.zshrc and change the theme variable to ZSH_THEME=cobalt2.

Install Powerline and necessary fonts, one way is using PIP

For first time PIP users refer to this PIP installation guide
To install Powerline using pip
```
pip install --user powerline-status
```
Now install all necessary fonts by downloading or cloning git repository.
```
git clone https://github.com/powerline/fonts
cd fonts
./install.sh
```
In iTerm2 access the Preferences pane on the Profiles tab.
Under the Colors tab import the <code>cobalt2.itermcolors</code> file via the Load Presets drop-down.

Under the Text tab change the font for each type (Regular and Non-ASCII) to <code>'Inconsolata for Powerline'.</code> (Refer to the powerline-fonts repo for help on font installation.)

Refresh ZSH by typing source <code>~/.zshrc</code> on the command line.







# JavaScript 101
## TABLE OF CONTENTS
History Definition & properties Usages Basic syntax
Variables & Types Arrays Operators Type conversions Statements
Simple functions
Variable scope
Browser environment
Tools
Compatibility
Documentation & links
I know JavaScript - Show me!
JavaScript is a real language. Building a modern dynamic website without knowing it is nonsense. A lot of people working on web applications and web sites learnt the language on the job. Code written is often hard to understand and hard to maintain. It doesn't follow best practices or standard rules which provoke strange behaviours and bugs. Taking time to understand the fundamentals is really important! By doing so you can stop being a normal human and become a true web developer.

# Definition & properties




```js
// variable
let y = 20 // change everthing value
const z = 30 // constain value

console.log('send text in command line')
// if - else  condition
if (y > 30 || z === 30) {
  console.log('hello')
} else {
  console.log('not hello')
}

// switch case
let menu = z-y
switch (menu) {
  case 1 : console.log('menu 1')
  break
  case 2 : console.log('menu 2')
  break
  case 10 : console.log('result')
  break
}

// for loop

for (let i = 15; i <= 20; i++) {
  if (i % 2 === 1) {
    // console.log(`${i} x 2 = ???`)
    console.log(i, ' x 2 = ???')
  }
}

console.log('*')
console.log('* * ')
console.log('* * *')
console.log('* * * *')

console.log('================')


let total = 10
for (let i = total; i >= 1; i--) {
  let star = ''
  for (var j = i; j <= total; j++) {
    star += ' *'
  }
 console.log(star)
}

// while
```
