# roblox-ts Demo Template

Looking to get started with [**roblox-ts**](https://roblox-ts.github.io)?
Just download this repository to get started!

## Prerequisites
You'll need:
- NodeJS and NPM
- roblox-ts 0.1.7+ ( `npm i -g roblox-ts` )
- Rojo 0.5.x

If you're unsure on how to install these things, please refer to our ["Quick Start" guide](https://roblox-ts.github.io/docs/quick-start).

## Setup
`npm install`

## Usage
`rbxtsc && rojo build --output build.rbxmx`

This will compile your files into the `out` folder and then create a `build.rbxmx` to open in Roblox Studio.

## Releases

This template allows you to release compiled .rbxmx files automatically using Travis CI!\
This is useful for manually distributing model or plugin files.

1. Connect your repo to Travis CI\
You'll need to make an account, and enable CI for the repo you created.

2. Generate a new token from [here](https://github.com/settings/tokens) with "repo" permissions

3. Create a new environment variable in your Travis CI repo settings\
The name should be `GITHUB_API_KEY`\
The value shold be the token you generated in step #2\
**Make sure you have `DISPLAY VALUE IN BUILD LOG` disabled!**

4. Run one of the following commands locally on your project and push:\
`npm run release-major` (bumps version by 1.0.0)\
`npm run release-minor` (bumps version by 0.1.0)\
`npm run release-patch` (bumps version by 0.0.1)

5. Travis CI will now generate a release called `bundle.rbxmx` in your "releases" section on GitHub