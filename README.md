# Color
A collection of color schemes which are not included in the core distribution.  

## Deploying

```bash
git clone https://github.com/platframe/platframe-color.git
```
Copy the `schemes` folder into `<project>/src/style/_/modules/color/`

## Usage

Change the project's primary scheme:
```stylus
// modules/color/index.styl
active_scheme = nebula
```

Inject into a specific component instance:
```stylus
footer-1(nebula)
```

Use `schemer()` to override the primary scheme on a specific sub-section:
```stylus
schemer(nebula)
```

More information on managing color in Platframe can be found in the  [documentation](http://platframe.com/docs/#style-color).

## Contributing
Contributions welcome, please use the [guide](CONTRIBUTING.md).

---

Released under the [MIT](LICENSE) license.
