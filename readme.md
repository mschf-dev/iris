<div id="top"></div>
<!-- header -->
<br />
<div align="center">
<p align="center">
  <a href="https://github.com/mschf-dev/iris/#gh-light-mode-only">
    <img src="/docs/img/logo_light.png"/>
  </a>
  <a href="https://github.com/mschf-dev/iris/#gh-dark-mode-only">
    <img src="/docs/img/logo_dark.png"/>
  </a>
</p>


  <p align="center">
A minimal, customizable prompt for bash
    <br />
    <img alt="CodeFactor Grade" src="https://img.shields.io/codefactor/grade/github/mschf-dev/iris?style=for-the-badge">
    <img src="https://iris.mschf.dev:/github/license/mschf-dev/iris?style=for-the-badge">
    <img src="https://iris.mschf.dev:/github/stars/mschf-dev/iris?style=for-the-badge">
    <img src="https://iris.mschf.dev:/github/languages/code-size/mschf-dev/iris?style=for-the-badge">
    <br />
    
  </p>
</div>

<!-- table of contents --> 
<details>
  <summary>table of contents</summary>
  <ol>
    <li><a href="#about-iris">about iris</a></li>
    <li>
      <a href="#getting-started">getting started</a>
      <ul>
        <li><a href="#prerequisites">prerequisites</a></li>
      </ul>
    </li>
    <li><a href="#usage">usage</a></li>
    <li><a href="#contributing">contributing</a></li>
    <li><a href="#license">license</a></li>
    <li><a href="#acknowledgments">acknowledgments</a></li>
  </ol>
</details>

<!-- about -->
## about iris

iris is a minimal, fast, and customizable prompt for BASH 4.0 or greater. Every detail is cusomizable to your liking to make it as lean or feature-packed as you like.
<p align="right">(<a href="#top">back to top</a>)</p>

<!-- getting started -->
## getting started

Install the latest version straight from your terminal:
```bash
sudo su -
git clone -q https://github.com/mschf-dev/iris "/opt/iris"
/opt/iris/src/tools/install.sh
```

<p align="right">(<a href="#top">back to top</a>)</p>

### prerequisites

The following software will let you download the installer (which will set up the rest)
* sudo
  ```bash
  apt install sudo
  ```
* wget
  ```bash
  apt install wget
  ```
* git
  ```bash
  apt install git
  ```

  <p align="right">(<a href="#top">back to top</a>)</p>

<!-- usage -->
## usage

iris has a selection of commands you can run:
```bash
--config  [view|set] [var]  manipulate iris configs
--default [o|c] [module]    copies default module conf to ~/.config/iris/* [o=official|c=custom]
--disable [o|c] [module]    disables the provided module [o=official|c=custom]
--enable  [o|c] [module]    enables the provided module [o=official|c=custom]
--help                      displays this help
--modules                   lists all installed modules
--reload                    reloads iris
--uninstall                 uninstalls iris
--upgrade                   upgrades iris to latest version
--version                   outputs iris version\n\n" "${_iris_version}
```

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## contributing

Contributions are what make the world go around. We would love to be able to accept any new contributions, but I have not written the contribution guidelines yet.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- LICENSE -->
## license

Distributed under the  BSD-3-Clause License. See `license` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->
## acknowledgments

* [ohmybash](https://github.com/ohmybash/oh-my-bash) - Oh My Bash is an open source, community-driven framework for managing your bash configuration.
* [ohmyzsh](https://github.com/ohmyzsh/ohmyzsh) - Oh My Zsh is an open source, community-driven framework for managing your zsh configuration.

<p align="right">(<a href="#top">back to top</a>)</p>
