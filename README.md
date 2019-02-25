# Tools

Prerequisites:
- `nodejs`, version 10+
- `npm`, version 6+
- `python`, version 3+

Install:
- `npm install -g truffle`, install version 5+
- `npm install -g ganache-cli`, install version 6+.
- (optional) install [ethnode](https://github.com/vrde/ethnode), an alternative to `ganache-cli` I'm currently developing.

Browser extension:
- [MetaMask](https://metamask.io/)


# Suggestions and troubleshooting

## Update Node.js
If you use a *nix system, try out [n, the Node.js version management](https://github.com/tj/n). Check out also [n-install](https://github.com/mklement0/n-install) if you need to install Node.js from scratch.

## I'm on Windows and I have troubles with `truffle`
AFAIK `truffle` needs your `python` executable to resolve to Python 3. If you are on Windows 10, you can install a [GNU/Linux subsystem](https://docs.microsoft.com/en-us/windows/wsl/install-win10).
