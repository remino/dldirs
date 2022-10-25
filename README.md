dldirs
======

By Rémino Rem <https://remino.net/>

Manage download directories.

[Code & Download](https://github.com/remino/dldirs/)

- [Getting Started](#getting-started)
	- [Installation](#installation)
		- [Using Homebrew on macOS](#using-homebrew-on-macos)
		- [Using git](#using-git)
		- [Using cURL](#using-curl)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)



## Getting Started

### Installation

#### Using Homebrew on macOS

```sh
brew tap remino/remino
brew install dldirs
dldirs -h
```
#### Using git

```sh
git clone https://github.com/remino/dldirs.git
cd dldirs
./dldirs -h
```

#### Using cURL

```sh
curl -L https://github.com/remino/dldirs/raw/main/dldirs > dldirs
chmod +x dldirs
./dldirs -h
```

[Back to top](#dldirs)



## Usage

```
dldirs 1.1.0

USAGE: dldirs [<options>] <command> [<args>]

Manage download directories.

COMMANDS:

	deploy      Deploy public files to DEPLOY_DEST in .env via rsync.
	init <dir>  Initialize new parent directory.
	new <dir>   Create new public dldirs directory.
	parent      Show parent directory path.
	help        Show this help screen.
	version     Show version number.

OPTIONS:

	-h          Show this help screen.
	-p          Proceed with actual deployment instead of a default dry-run.
	-v          Show version number.

```

[Back to top](#dldirs)



## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

[Back to top](#dldirs)



## License

Distributed under the ISC License. See `LICENSE.txt` for more information.

[Back to top](#dldirs)
