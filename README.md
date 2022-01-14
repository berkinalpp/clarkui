# clarkui

> Made with create-react-library

[![NPM](https://img.shields.io/npm/v/clarkui.svg)](https://www.npmjs.com/package/clarkui) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

## Install

```bash
npm install --save clarkui
```

## Usage

```jsx
import React, { Component } from 'react'

import {Button} from 'clarkui'
import 'clarkui/dist/index.css'

class App extends Component {
  render() {
    return (
      <div className="App">
        <Button text="Glow Button" effect='glow'></Button>
        <Button text="Door Button" effect='door'></Button>
        <Button text="Shutter Up Button" effect='shutterUp'></Button>
        <Button text="Shutter Down Button" effect='shutterDown'></Button>
        <Button text="Double Button" effect='double'></Button>
      </div>
    ) 
  }
}
```

## License

MIT © [berkinalpp](https://github.com/berkinalpp)
