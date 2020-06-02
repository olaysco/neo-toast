# neo-toast

> Highly customizable, Beautiful Toasters for React. only ~2kbb file size

[![NPM](https://img.shields.io/npm/v/neo-toast.svg)](https://www.npmjs.com/package/neo-toast) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

## Install

```bash
npm install --save neo-toast
```

## Usage

```jsx
import React from 'react'
import Toast from 'neo-toast'

const Toaster = ()=> (
  <button onClick={()=>Toast({
            position: 'topLeft',
            type: 'success',
            text: 'created successfully'
        })}>Toast success top left</button>
)

```

## License

MIT © [olaysco](https://github.com/olaysco)
