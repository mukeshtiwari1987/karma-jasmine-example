# rollup-karma-jasmine-example
>An example calculator project that bundles es6-modules with Rollup. Tests use Jasmine and are run in the browser with Karma.

## Setup

- This example requires node/npm to run, set these up first if not already done.

- Clone the repository
  ```
  $ git clone https://github.com/mukeshtiwari1987/karma-jasmine-example.git
  $ cd karma-jasmine-example
  ```

- Fetch all the node dependencies
  ```
  $ npm install
  ```

## BrowserStack Configuration

Export the environment variables for the username and access key of your BrowserStack account.
These can be found on the automate accounts page on [BrowserStack](https://www.browserstack.com/accounts/automate).

`export BROWSERSTACK_USERNAME=<browserstack-username>`

`export BROWSERSTACK_KEY=<browserstack-access-key>`

You can further customize configuration in karma.conf.js. For detailed reference, visit karma-browserstack-launcher github repository [here](https://github.com/browserstack/karma-browserstack-launcher).

## Usage

- Tests can be run using the npm test script
  ```
  $ npm -s test
  ```

- The calculator can be bundled using the npm build script.
  ```
  $ npm run build
  ```
