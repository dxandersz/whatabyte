01/13/21 23:21
browser-sync isn't recognized as a command. For some reason, CLI isn't recognizing the path.

temporary fix: reference the entire path instead of browser-sync when executing

example: ./node_modules/.bin/browser-sync start --config bs-config.js

resolved: no. will likely become an issue in the future. figure out how to deal with the issue. likely an issue with the npm install configuration?

01/13/21 23:50
NavButton class isn't working

resolved: no. the actual element displays but isn't rendering CSS. pored over layout.pug and style.css and haven't found what the issue is
update: NavButton works on other pages.