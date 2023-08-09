#

# A copy from electron-quick-start

This is a clone copy from [COVAIL/electron-quick-start](https://github.com/COVAIL/electron-quick-start).
See original repository for more information.

# Packages and R-Portable Win

Most packages are up-to-date as of 24/07/2023.

The [R-Portable](https://sourceforge.net/projects/rportable/files/R-Portable/) Windows has been updated to R-4.2.0.

# To Use

To clone and run this repository you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line:

```bash
# Clone this repository
git clone https://github.com/jeromecy/Electron-Shiny-Template
# Install Electron Packager (if first time)
npm install electron-packager -g 
# Go into the repository
cd Electron-Shiny-Template
# Install dependencies
npm install
```

Replace `app.R` with your own App file. Then:

```bash
# Run the app
npm start
```

Bundle your desktop App
```bash
npm run package-win
```

# Debug

Try `npm start` to check if the App runs properly. If the error is about packages, go to *R-Portable-Win\bin* folder and run `R.exe` as administrator. Update packages or re-install the required packages.

If the screen is blank, click "View" and "Force Reload". 