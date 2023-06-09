[![Copr build status](https://copr.fedorainfracloud.org/coprs/bhavin192/emacs-pretest/package/emacs/status_image/last_build.png)](https://copr.fedorainfracloud.org/coprs/bhavin192/emacs-pretest/package/emacs/)
This RPM recipe is forked from Bhavin's repo at https://gitlab.com/bhavin192/emacs-pretest-rpm.git.
## Pretest version builds of GNU Emacs
- [EmacsWiki: Emacs Pretest](https://www.emacswiki.org/emacs/EmacsPretest)
- [https://alpha.gnu.org/gnu/emacs/pretest/](https://alpha.gnu.org/gnu/emacs/pretest/)

This package is mostly aligned with the GNU Emacs package from
official Fedora repositories.
- [https://src.fedoraproject.org/rpms/emacs](https://src.fedoraproject.org/rpms/emacs)
<!-- - [https://src.fedoraproject.org/rpms/emacs/pull-request/4](https://src.fedoraproject.org/rpms/emacs/pull-request/4) -->

## Changes in Emacs 28.1
- [`NEWS` file from `emacs-28`
  branch](https://git.savannah.gnu.org/cgit/emacs.git/tree/etc/NEWS?h=emacs-28)

## Credits & Licensing
The repository
[https://gitlab.com/bhavin192/emacs-pretest-rpm](https://gitlab.com/bhavin192/emacs-pretest-rpm
"Repository containing build recipes for the emacs-pretest package")
containing build recipes for [Copr project
emacs-pretest](https://copr.fedorainfracloud.org/coprs/bhavin192/emacs-pretest/)
is a fork of
[https://src.fedoraproject.org/rpms/emacs](https://src.fedoraproject.org/rpms/emacs).

This fork as well as the original repository ([according to
FPCA](https://fedoraproject.org/wiki/Legal:Fedora_Project_Contributor_Agreement#Other_FAQs))
are licensed under MIT License. See
[LICENSE](https://gitlab.com/bhavin192/emacs-pretest-rpm/-/blob/master/LICENSE)
for the full license text.

## How to install/update
- Enable this copr repository,
  ```sh
  $ dnf copr enable bhavin192/emacs-pretest
  ```
- Install latest pretest,
  ```sh
   $ dnf install emacs
  ```
  or update the installed version,
  ```sh
  $ dnf update emacs
  ```

> **NOTE**: If the latest stable version is greater than the available
> pretest, then the stable version from official repositories will get
> installed or updated. For example when GNU Emacs `27.1` gets
> released and last pretest was `27.0.91`, then version `27.1` will
> get installed.

## Reporting issues
If you face any issues while installing or updating, please create an
issue on [GitLab repository
here](https://gitlab.com/bhavin192/emacs-pretest-rpm).
