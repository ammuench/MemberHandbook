# CDSA Handbook Website
An online reference for all of CDSA's guidlines, rules, and more!

## Development Setup

To start developing for the CDSA website, you'll need a few basic things setup on your machine.

**If you use LINUX or OSX:**

Install NodeJS (I recommend using [NVM to install it](https://github.com/creationix/nvm)--it takes all the hassle out of weird sudo problems and makes it easy to version manage in the future if needed)

**If you use WINDOWS**

If you use Windows, I would strongly suggest you install the [Windows Subsystem for Linux](https://docs.microsoft.com/en-us/windows/wsl/install-win10).  It gives you an Ubuntu/Debian/OpenSUSE shell in your Windows environment, and saves a lot of headache dealing with NodeJS in CMD Prompt issues.  You can follow the above instructions for Linux/OSX to finish the install from there.

If you cannot do that, I would recommmend installing [Git Bash](https://git-scm.com/downloads), installing [NodeJS](https://nodejs.org/en/) manually.

### Running a Watch Server

Once you've setup your prerequisite installations--go ahead and move into the project root, run `npm install` to install all needed project packages and then `npm run watch` to boot up a local server.  You can access the development site at [http://localhost:3000](http://localhost:3000).  Live reload is enabled and the site will update every time you save a file.  If there are any compile errors in JS or SASS your terminal/command prompt will throw an error for you.
