<div align="center">
  <a href="https://www.npmjs.com/package/robofox-copyright-footer">
    <img alt="npm" src="https://badgen.net/npm/v/robofox-copyright-footer?color=2c139f" />
  </a>
  <a href="https://www.npmjs.com/package/robofox-copyright-footer">
    <img alt="" src="https://badgen.net/npm/dt/robofox-copyright-footer?color=2c139f" />
  </a>
  <a href="https://bundlephobia.com/result?p=robofox-copyright-footer">
    <img alt="" src="https://badgen.net/bundlephobia/min/robofox-copyright-footer?color=2c139f" />
  </a>
</div>

## React Web Copyright Footer

- I published this package to save myself a couple minutes, please feel free to use it in your own projects.
- Simply pass in the name of the owning company (companyName) and the developent compaany/individual (developerName)

## Installation

### npm
```sh
npm install robofox-copyright-footer
```

## Usage

```tsx
import Footer from "robofox-copyright-footer";

export const App = () => {
  return (
    <div>
      ...
      <Footer 
        companyName='Unicorns-R-Us'
        developerName='RoboFox LLC'
      />
};
```

## API

### `Footer` Props

| Name             | Type         | Default   | Description                                                                      |
| ---------------- | ------------ | --------- | -------------------------------------------------------------------------------- |
| companyName      | `string`     |           | The name of the sites owner                                                      |
| developerName    | `string`     |           | The name of the sites developer.                                                 |
| color            | `string`     |           | The color of the text & icon (rgba, hex, etc)                                    |

## License

Code released under the [MIT](https://github.com/robo-fox/website-copyright-footer/blob/main/LICENSE) license.
