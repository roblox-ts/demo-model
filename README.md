# roblox-ts Demo Template

Looking to get started with [**roblox-ts**](https://roblox-ts.github.io)?
Just download this repository to get started!

## Prerequisites
You'll need:
- NodeJS and NPM
- roblox-ts 0.0.36+ ( `npm i -g roblox-ts` )
- Rojo 0.5.x

If you're unsure on how to install these things, please refer to our ["Quick Start" guide](https://roblox-ts.github.io/docs/quick-start).

## Setup
`npm install`

## Usage
`rbxtsc && rojo build --output build.rbxlx`

This will compile your files into the `out` folder and then create a `build.rbxlx` to open in Roblox Studio.

## Publishing
You will need to first register your repository with [Travis CI](https://travis-ci.com/)

To publish a new release, run one of the following commands:
`npm run release-major` (+1.0.0)
`npm run release-minor` (+0.1.0)
`npm run release-patch` (+0.0.1)
