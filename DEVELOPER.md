Submitting Changes
------------------

Do NOT submit changes to the built files in the `dist` folder. These are generated before
releases.


To run tests
------------

Make sure your environment is set up with:

`npm install`

In a separate process, run the WebSockets server:

`node ./test/ws-server.ts`

Run the tests using Karma:

`npm test`
