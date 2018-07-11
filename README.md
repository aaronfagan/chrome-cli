![HitCount](http://hits.dwyl.io/aaronfagan/chrome-cli.svg)
# Chrome CLI
Chrome CLI is a simple shell binary/bash function designed to smooth out your development workflows using Google Chrome. Designed for macOS (OS X) and Linux based operating systems.

## Installation
If you would like to modify the default home page URL coded into these commands, open the desired file and modify the `HOME_URL` variable to suit your liking.

### Binary
- Add the [Chrome CLI binary](chrome) file to your path. On macOS (OS X), this folder is located at `/usr/local/bin`. 
- Before using, be sure to update the binary file permissions to `755` to allow it to run.

### Bash Profile
Add the code outlined in [bash_profile.md](bash_profile.md) to your `~/.bash_profile` file and run `source ~/.bash_profile`.

## Usage
In your terminal of choice, run the following commands to achieve the described results:
- `chrome` If browser is already open, creates a new tab at the coded default home page URL. If browser not open, opens browser to your browser default home page.
- `chrome .` Opens a new browser tab at your current folder location.
- `chrome /some/folder` Opens a new browser tab at the specified folder location.
- `chrome /some/file.html` Opens a new browser tab at the specified file.

## Authors
- Aaron Fagan - [www.aaronfagan.ca](https://www.aaronfagan.ca/)

## License
This project is licensed under the [GNU General Public License](LICENSE).