<h1>Angular Gulp Boilerplate</h1>

<b>Quickly start</b> your angularJS project,<br>develope with flexibility using <b>dev command line tools</b> and<br>build a deploy version with <b>source minification</b>.<br><br>
<br>

<h2>Installing on local machine</h2>

<h4>Please make sure you have node.js installed on your machine</h4>
If you don't have, <a href="https://nodejs.org/" >click here...</a>
<br><br>


<b>1. check if you have it installed or not</b>,

	npm -v

and,

	node -v

you should see some version info in return.<br><br>

<b>2. install global packages</b>(run on any directory)

	npm install -g gulp node-gyp

in case of mac or linux, you might need to mention "sudo"<br><br>


<b>3. now go to the directory where you want to place the project files using git bash (terminal for mac or linux)</b><br>
run the command

	git clone URL

here URL is the http url you get from the repository page, <a href="https://github.com/tanmoythander/angular-gulp-boilerplate">Click here to clone</a><br><br>

<b>4. now navigate to the project directory with cmd (terminal for mac or linux)</b><br>
run the command

	npm install
	
wait for it to be completed. It usually takes 5-10 minutes to complete.<br>
It will download all the dependencies, build the project and serve the build on browser<br><br>

<h2>Using the gulp commands</h2>

<b>1. Serve from source (<b>./</b>) with watch (Development Mode)</b>

	gulp

you should see the browser window opening address http://localhost:3000 (opens another port if unavailable)<br><br>

<b>2. Build the source (Deployment Mode)</b>

	gulp build

it will delete previous build !!!<br>
build files will be saved under <b>./_build</b> directory<br><br>

<b>3. Serve from source (<b>./</b>) without watch (Source Testing Mode)</b>

	gulp server

you should see the browser window opening address http://localhost:3000 (opens another port if unavailable)<br><br>

<b>4. Serve from build (<b>./_build/</b>) without watch (Build Testing Mode)</b>

	gulp server-build

you should see the browser window opening address http://localhost:3000 (opens another port if unavailable)<br><br>

<h2>Developer Hint</h2>

Please change your editor configuration like below before you start development

<b>Indent character</b>: "\t" (tab)

<b>Indent size</b>: 2

<b>Line endings</b>: LF (unix)

