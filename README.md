<h1 align="center">Welcome to ngx-electronify 👋</h1>
<p>
  <img alt="Version" src="https://img.shields.io/badge/version-1.0.2-blue.svg?cacheSeconds=2592000" />
  <a href="https://twitter.com/abampakos" target="_blank">
    <img alt="Twitter: abampakos" src="https://img.shields.io/twitter/follow/abampakos.svg?style=social" />
  </a>
</p>

> Angular CLI builder that runs your application in the desktop using Electron

The builder runs your Angular application in `serve` mode and loads the serving URL in an Electron window.

### 🏠 [Homepage](https://github.com/bampakoa/ngx-electronify)

## Install

```sh
npm install -D ngx-electronify
```

## Usage

To use the builder, first you need to add a new architect entry in the **angular.json** file.

```
"desktop": {
  "builder": "ngx-electronify:electron"
}
```
`ng run [project-name]:desktop`

## Author

👤 **Aristeidis Bampakos**

* Website: http://www.medium.com/@abampakos
* Twitter: [@abampakos](https://twitter.com/abampakos)
* Github: [@bampakoa](https://github.com/bampakoa)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](https://github.com/bampakoa/ngx-electronify/issues). 

## Show your support

Give a ⭐️ if this project helped you!
