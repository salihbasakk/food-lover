# Food Lover

Food lover is a my first nodejs project a platform where food lovers come together

## Installation

If you need to install Node.js and npm, use any of the official [Node.js](https://nodejs.org/en/download/) installers provided for your operating system.

Clone the project repository:

```bash
git clone git@github.com:salihbasakk/food-lover.git
```

Make food-lover the current working directory:

```bash
cd food-lover
```

Install the project dependencies:

```node
npm i
```

Run the server using nodemon under the hood:

```node
npm run dev
```

In a separate terminal window, serve the client from a static server using Browsersync under the hood:

```node
npm run ui
```

## Usage

Browsersync proxies the server running on port 8000 with nodemon. Check out the npm script commands present in package.json for more details.

To see the app in action, visit http://localhost:8000 on your browser.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.