* You can follow series of command to setup React environment once you are in your project-name folder:

* Follow the steps below to install and use Node.js version 18.20.3 using nvm:
	- Install nvm:
		curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash

	- Set up nvm environment:
		export NVM_DIR="$([ -z "${XDG_CONFIG_HOME-}" ] && printf %s "${HOME}/.nvm" || printf %s "${XDG_CONFIG_HOME}/nvm")" && [ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"

	-Verify nvm Installation:
		command -v nvm

	- Install Node.js Version 18.20.3:
		nvm install 18.20.3

	- Set the installed Node.js version as active:
		nvm use 18.20.3

	npm install -> Will install all dependencies -> takes 10 to 15 min

	npm run start -> To compile and deploy the project in browser. You can press <Ctrl> key while clicking on localhost:8080/8081 to open project in browser -> takes 2 to 3 min

	npm run test -> to run all test cases. It is mandatory to run this command before submission of workspace -> takes 5 to 6 min  

* You may also run “npm run test” while developing the solution to re-factor the code to pass the test-cases.

* To ensure your code is saved and available for later use, remember to use the CTRL+Shift+B command on your code IDE.
   This will push or save the updated contents in the internal git/repository.
   It is also important to use CTRL+Shift+B before the final submission to evaluate the code quality.
