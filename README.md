<p align="center">
  <a href="https://github.com/empress-eco/react-sdk">
    <img src="https://img.shields.io/maintenance/yes/2024?style=flat-square" />
  </a>
  <a href="https://github.com/empress-eco/react-sdk">
    <img src="https://img.shields.io/github/license/empress-eco/react-sdk?style=flat-square" />
  </a>
  <a href="https://www.npmjs.com/package/react-sdk">
    <img src="https://img.shields.io/npm/v/react-sdk?style=flat-square" />
  </a>
  <a href="https://www.npmjs.com/package/react-sdk">
    <img src="https://img.shields.io/npm/dw/react-sdk?style=flat-square" />
  </a>
</p>

## Overview
Empress React-SDK is your go-to library for building robust, reactive React applications powered by the Framework backend. It is designed to simplify your development process by providing a set of intuitive hooks integrating seamlessly with your React code, allowing efficient and effective interaction with a Framework backend.

## Key Features
- **User Authentication**: Supports login with username and password, as well as token-based authentication.
- **Database Operations**: Provides a set of hooks for performing CRUD operations on your backend database.
- **File Uploads**: The library offers a hook for uploading files to the Empress filesystem.
- **API Calls**: Effortlessly make API calls to your whitelisted backend functions with Empress React-SDK.
- **Search Functionality**: Perform a search on your database documents using the provided hook.

## Technical Stack
Empress React-SDK uses the [Empress-js-sdk](https://github.com/The-Commit-Company/Empress-js-sdk) and [SWR](https://swr.vercel.app) for making API calls to your Empress backend. SWR uses a cache invalidation strategy and also updates the data constantly and automatically in the background, ensuring that your UI is always fast and reactive.

## Installation
You can install Empress React-SDK using npm or yarn:

```bash
npm install react-sdk
```
or
```bash
yarn add react-sdk
```

To begin using Empress React-SDK, initialize the library by wrapping your App with the `EmpressProvider`. You can also provide the URL of your Empress server if your web app is not hosted on the same URL.

```jsx
import { EmpressProvider } from "react-sdk";

function App() {
  return (
    <EmpressProvider url='https://my-Empress-server.Empress.cloud'>
    {/** Your other app components **/}
    </EmpressProvider>
  )
}
```

## Documentation
For more detailed setup instructions and usage guidelines, please refer to our [official documentation](https://grow.empress.eco/).

## Contribution
We welcome community contributions! If you'd like to contribute, please follow our [contribution guidelines](https://github.com/empress-eco/react-sdk/blob/main/CONTRIBUTING.md).

## Bug Reports and Feature Requests
Encountered a bug or have a feature in mind? Please report bugs and request features via our [GitHub issues](https://github.com/empress-eco/react-sdk/issues).

## License and Acknowledgements
Empress React-SDK is licensed under the MIT License. See [LICENSE](./LICENSE) for more information.

Special thanks to the Empress Community for their foundational contributions to the tools that power this project. Their innovation and dedication have been instrumental in building the functionalities we rely on. We are profoundly grateful for their pioneering work and ongoing support.