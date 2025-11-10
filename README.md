# dietpdf

![Stars](https://img.shields.io/github/stars/Inc44/dietpdf?style=social)
![Forks](https://img.shields.io/github/forks/Inc44/dietpdf?style=social)
![Watchers](https://img.shields.io/github/watchers/Inc44/dietpdf?style=social)
![Repo Size](https://img.shields.io/github/repo-size/Inc44/dietpdf)
![Language Count](https://img.shields.io/github/languages/count/Inc44/dietpdf)
![Top Language](https://img.shields.io/github/languages/top/Inc44/dietpdf)
[![Issues](https://img.shields.io/github/issues/Inc44/dietpdf)](https://github.com/Inc44/dietpdf/issues?q=is%3Aopen+is%3Aissue)
![Last Commit](https://img.shields.io/github/last-commit/Inc44/dietpdf?color=red)
[![Release](https://img.shields.io/github/release/Inc44/dietpdf.svg)](https://github.com/Inc44/dietpdf/releases)
[![Sponsor](https://img.shields.io/static/v1?label=Sponsor&message=%E2%9D%A4&logo=GitHub&color=%23fe8e86)](https://github.com/sponsors/Inc44)

Reduce PDF file size.

## 🚀 Installation

```bash
git clone https://github.com/Inc44/dietpdf.git
cd dietpdf-bin # dietpdf
makepkg -si
```

## 📦 Publish

```bash
mkdir ~/aur
mkdir ~/aur/dietpdf-bin # dietpdf
cd ~/aur/dietpdf-bin # dietpdf
```

Create:

```bash
cp ~/github/dietpdf/dietpdf-bin/PKGBUILD . # dietpdf
makepkg --printsrcinfo > .SRCINFO
git -c init.defaultBranch=master init
git add PKGBUILD .SRCINFO
git commit -m "dietpdf-bin" # dietpdf
git remote add aur ssh://aur@aur.archlinux.org/dietpdf-bin.git # dietpdf
git push aur master
```

Update:

```bash
git clone ssh://aur@aur.archlinux.org/dietpdf-bin.git ~/aur/dietpdf-bin # dietpdf
cp ~/github/dietpdf/dietpdf-bin/PKGBUILD . # dietpdf
makepkg --printsrcinfo > .SRCINFO
git add PKGBUILD .SRCINFO
git commit -m "dietpdf-bin" # dietpdf
git push
```

## 🙏 Thanks

Creator of:

- [dietpdf-haskell](https://github.com/Zigazou/dietpdf-haskell)

## 🤝 Contribution

Contributions, suggestions, and new ideas are heartily welcomed. If you're considering significant modifications, please initiate an issue for discussion before submitting a pull request.

## 📜 License

[![BSD-3-Clause](https://img.shields.io/badge/License-BSD_3--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)

This project is licensed under the 3-Clause BSD License. See the [LICENSE](LICENSE) file for details.

## 💖 Support

[![BuyMeACoffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-ffdd00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/xamituchido)
[![Ko-Fi](https://img.shields.io/badge/Ko--fi-F16061?style=for-the-badge&logo=ko-fi&logoColor=white)](https://ko-fi.com/inc44)
[![Patreon](https://img.shields.io/badge/Patreon-F96854?style=for-the-badge&logo=patreon&logoColor=white)](https://www.patreon.com/Inc44)