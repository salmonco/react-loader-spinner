# react-loader-spinner

You can display the loading status visually through the loader.

## Screenshot

![fade0](https://github.com/salmonco/react-loader-spinner/assets/86469788/2d6a78ff-c3d8-4b72-b650-03ff973a9d6b)
![fade1](https://github.com/salmonco/react-loader-spinner/assets/86469788/db600b8e-47de-46b0-8c98-458c83bb286b)
![fade2](https://github.com/salmonco/react-loader-spinner/assets/86469788/71e12111-3909-483c-bb64-87a07581cac4)

You can resize the loader using margin.

## Installation

```
npm install @salmonco/react-loader-spinner
```

## Usage

```typescript
import { FadeLoader } from '@salmonco/react-loader-spinner';

<FadeLoader color="green" width={3} height={10} margin={8} />;
```

## Props

|Prop|Description|Type|Default|
|---|---|---|---|
|color|Color of the loader|string|salmon|
|width|Width of elements that make up the loader|number|5|
|height|Height of elements that make up the loader|number|15|
|radius|Border radius of elements that make up the loader|number|2|
|margin|Distance of elements from the center of the loader|number|10|

If you write it as a number, it will automatically be treated as px.

## Contributing

Contributions are always welcome!

## License

MIT
