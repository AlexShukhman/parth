
# Parth™ [![npm version](https://badge.fury.io/js/parth_test.svg)](https://badge.fury.io/js/parth_test)
<img src="./logo/parth_long.png" height="45"/>

_A simplified testing framework for QA automation and continuous integration._

## Documentation

* [Smop docs for .parth usage](https://docs.smop.io/Owners/Getting_Started:_Parth_Files/)

## Install

```
npm install -g parth_test
```

## Requirements

* Parth™ currently supports PHP and vanilla HTML entry points (index.html and index.php).
* This CLI clones the git repository it is pointed to. This means that the git repo must be accessible through the given link to clone (best to use public github repos).
* In order to test, this CLI requires that the tests are written in the Parth™ language and that the file extension is `.parth` 

_For more help writing a .parth file, please see our documentation on the Smop docs for .parth usage._

## Run CLI

```bash
parth test -r <repo url> -e <entry point filepath> -t <html or php> -p <parth filepath>
```

* We define the entry point to be the file that is being tested. For example, if the page you would like to test is within the file `./views/page.html` use that page as your entrypoint. (Note that entrypoints are defined using the relative filepath to the base of the project, ie the folder that is cloned via the repo url).
* Please note that, while the only currently available languages are HTML and PHP, the Parth™ team does intend to expand the capabilities of this system in the future.
  
## Warranty and Liability

**_PLEASE NOTE:_** This software is offered for FREE with NO WARRANTY and LIMITED LIABILITY to the Parth™ team for the issues that may arise by using it under the [GNU General Public License](https://www.gnu.org/licenses/gpl-3.0.en.html). If you have any issues with our software, please report them in our [github issues page](https://github.com/smop-technologies/parth/issues), but we cannot guarantee that those issues will be fixed in a reasonible or timely manner. If you intend on using Parth™, you must assume all risks of doing so.