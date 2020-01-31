# roblox-ts Demo Template

Looking to get started with [**roblox-ts**](https://roblox-ts.github.io)?
Just download this repository to get started!

## Prerequisites
You'll need:
- NodeJS and NPM
- roblox-ts 0.2.14+ ( `npm i -g roblox-ts` )
- Rojo 0.5.x

If you're unsure on how to install these things, please refer to our ["Quick Start" guide](https://roblox-ts.github.io/docs/quick-start).

## Setup
`npm install`

## Usage
`rbxtsc && rojo build -o model.rbxmx`

This will compile your files into the `out` folder and then create a `model.rbxmx` to open in Roblox Studio.

## Releases

This template allows you to release compiled .rbxmx files automatically using GitHub Actions!\
This is useful for manually distributing model or plugin files.

1. Run one of the following commands locally on your project and push:\
`npm run release-major` (bumps version by 1.0.0)\
`npm run release-minor` (bumps version by 0.1.0)\
`npm run release-patch` (bumps version by 0.0.1)

2. GitHub Actions will now generate a release called `bundle.rbxmx` in your "releases" section on GitHub