# React

React is a JavaScript library for building user interfaces.

## Installation
```
npm install react
```

## Example
```
import { createRoot } from 'react-dom/client';

function HelloMessage({ name }) {
  return <div>Hello {name}</div>;
}

const root = createRoot(document.getElementById('container'));
root.render(<HelloMessage name="Taylor" />); 
```

## Docs

See the website.

## Contributing

Open PRs are welcome.

## License

MIT
