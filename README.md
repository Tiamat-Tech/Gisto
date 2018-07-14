# { Gisto } 



> Snippets made awesome

[![Current Gisto version](https://img.shields.io/badge/dynamic/json.svg?query=$.version&uri=https://cdn.rawgit.com/Gisto/Gisto/next/package.json&label=version&colorB=3F84A8&style=flat-square)](https://github.com/Gisto/Gisto)
[![GitHub license](https://img.shields.io/github/license/Gisto/Gisto.svg?style=flat-square)](https://github.com/Gisto/Gisto/blob/master/LICENSE)
[![Coveralls github branch](https://img.shields.io/coveralls/github/Gisto/Gisto/next.svg?style=flat-square)](https://github.com/Gisto/Gisto/)
[![Code Climate](https://img.shields.io/codeclimate/maintainability-percentage/Gisto/Gisto.svg?style=flat-square)](https://codeclimate.com/github/Gisto/Gisto)
[![OSX build](https://travis-badge-per-job.herokuapp.com/?repo=Gisto/Gisto&job=1&style=flat-square&label=OSX%20build)](https://travis-ci.org/Gisto/Gisto)
[![Linux build](https://travis-badge-per-job.herokuapp.com/?repo=Gisto/Gisto&job=2&style=flat-square&label=Linux%20build)](https://travis-ci.org/Gisto/Gisto)
[![AppVeyor branch](https://img.shields.io/appveyor/ci/sanusart/Gisto/next.svg?style=flat-square&label=Windows%20build)](https://ci.appveyor.com/project/sanusart/gisto)


## About

Gisto is a code snippet manager that runs on GitHub Gists and adds additional features such as searching, tagging and sharing gists while including a rich code editor. 
All your data is stored on GitHub and you can access it from GitHub Gists at any time with changes carrying over to Gisto

## Future and Status

Current released copy is always on the branch [master]([next](https://github.com/Gisto/Gisto/tree/master))

Gisto next version is in the works, work can be tracked via [next](https://github.com/Gisto/Gisto/tree/next) branch

Please see [next](https://github.com/Gisto/Gisto/tree/next) branch for upcoming version currently in development.

change.log of current version for more detailed info regarding new features, bug fixes and releases.

## Screenshots

<details>
  <summary>Dashboard</summary>
	![Dashboard](https://i.imgur.com/s4d0uHL.png)
</details>

<details>
  <summary>Gist view</summary>
	![Gist view](https://i.imgur.com/DCR1zTK.png)
</details>

## "Nightly" builds

"Nightly" builds triggered by commits.

[Downloads](https://gisto-releases.s3.amazonaws.com/index.html)

## Issues, bug reporting and pull requests

Please feel free to add a bug / feature request / suggestions to the issue tracker.

Please state that target is Gisto branch "**next**"

Pull requests are welcome as well.

## Privacy/authentication

**Gisto authenticates to GitHub by using one of the following methods:**

- **Oauth2** - the default option on the log-in screen

- **Basic authentication** over SSL and retrieving an oAuth2 token. Thus the need for your GitHub user and password

- **Access token** - If you would rather to supply your own access token without providing Gisto your login details you may manually create an access token from the account settings at GitHub and login using the generated token 

Gisto only saves the oAuth2 token received after authenticating and nothing else.

This token will be saved permanently until you log out.

You can find out more at the [F.A.Q.](http://www.gistoapp.com/faq/) section


## License

[**MIT**](https://github.com/Gisto/Gisto/blob/master/LICENSE)
