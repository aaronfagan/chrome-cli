![HitCount](http://hits.dwyl.io/aaronfagan/browser-cli.svg)
# Browser CLI
By [Aaron Fagan](https://www.aaronfagan.ca/)

# Description
Browser CLI is a simple set of shell scripts designed to smooth out your development workflow.

# Installation
- Add your preferred Browser CLI file to your path. On macOS (OS X), this folder is located at `/usr/local/bin`. 
- Before using, be sure to update the files permissions to 755.

Alternatively, add your desired function to your `~/.bash_profile` and run `source ~/.bash_profile`.

If you would like to modify the default home page URL coded into these commands, open the desired file and modify the `HOME_URL` variable to suit your liking.

# Usage
Using Chrome as an example, in terminal run the following commands to achieve the described results:
- `chrome` If browser is already open, creates a new tab at the coded default home page URL. If browser not open, opens browser to your browser default home page.
- `chrome .` Opens a new browser tab at your current folder location.
- `chrome /some/folder` Opens a new browser tab at the specified folder location.
- `chrome /some/file.html` Opens a new browser tab at the specified file.

# License
This project is licensed under the [GNU General Public License](LICENSE).