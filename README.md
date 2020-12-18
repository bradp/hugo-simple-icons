# hugo-simple-icons
Hugo module to easily use [Simple Icons](https://simpleicons.org/) anywhere in your site.

## Installation

First, [init](https://gohugo.io/hugo-modules/use-modules/#initialize-a-new-module) your project as Hugo Module.:

```
hugo mod init github.com/<your-user>/<your-project>
```

Then edit your config file to import the module:

```toml
# config.toml
[module]
  [[module.imports]]
    path = "github.com/bradp/hugo-simple-icons"
```

### Upating

To update all modules:
```
hugo mod get -u
```

You may need to run `hugo mod clean` if something isn't working right.


## Usage

To any layout file, simple use this partial (replacing 'hugo' with your chosen icon.)

```
{{ partial "simple-icons/icon" "hugo" }}
```

To view all the icons & their names, you can go to `<your-site>/simpleicons`.

Enjoy!
