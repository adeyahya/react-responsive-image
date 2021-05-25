# React Responsive Picture

## Installation

```bash
yarn add @adeyahya/rrp

# or

npm install @adeyahya/rrp --save
```

## Usage

```tsx
import * as React from 'react';
import * as ReactDOM from 'react-dom';
import { Provider, ResponsiveImage } from '../.';

const App = () => {
  return (
    <Provider>
      <ResponsiveImage src="https://res.cloudinary.com/dt2mntbmf/image/upload/v1597818712/image-20200819133002593_qqtn6b.png">
        <img width="100%" />
      </ResponsiveImage>
    </Provider>
  );
};

ReactDOM.render(<App />, document.getElementById('root'));
```

### license

MIT
