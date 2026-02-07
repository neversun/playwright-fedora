# playwright on Fedora

## Prepare

1. install docker on your system
2. install nodejs: https://nodejs.org/en/download
3. install dependencies
  `npm run install`

## Running tests

1. `npm run server` Run the server and keep it running
2. `npm run test` Run the tests


## Useful commands

`npm run report:show` Show playwright results/report
`npm run test:update-snapshots` Update the screenshots created with the first run of `npm run test` (if any)
`npm run test:codegen` Start a recording session with playwright's Test Generator

