
#steps

1> clone the git project in your workspace
2> move to that workspace on command promt
3> perform
npm install
4> run as 'node app.js'
5> Access the running app in a browser at http://localhost:6001


#development points

1> jade is interprested langauge so need to tak care of spaces and tabs.
2> in your VS code make following changes to avoid syntax errors:

By default, VSCode will try to guess your indentation options depending on the file you open.

You can customize this easily in File > Preferences > User Settings with:

// Controls the rendering size of tabs in characters.
// If set to auto, the value will be guessed based on the opened file.
"editor.tabSize": 4,

// Controls if the editor will insert spaces for tabs.
// If set to auto, the value will be guessed based on the opened file.
"editor.insertSpaces": false