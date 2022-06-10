## Scratch project

### Objective

- To create custom operator blocks to compute Square and square root of a number.

### Demo

![image](https://user-images.githubusercontent.com/59413872/173130760-e563f93e-f831-48c3-afdd-656f5247141c.png)

- video : https://drive.google.com/file/d/1_xTl2-7bZPWYvXfi34r4yUbewRYbvP5N/view?usp=sharing

- File  : https://drive.google.com/file/d/1tGDSo4xE8godlOS7I-JvpFAUNw7BOAtw/view?usp=sharing

### Getting Started

#### Requirements

- Python 2.X
- Java
- Node JS
- npm / yarn
    
#### Steps

- Clone the repo
- If working Windows platform patch the build.py file in scratch-blocks from [here](https://github.com/LLK/scratch-blocks/pull/2138/commits/9007da52532cd380df5d0ac1a560788ed4f962cd#)
- `cd scratch-vm`
- `npm install`
- `npm link`
- `npm run watch`
- `cd ../scratch-blocks`
- `npm install`
- `npm link`
- `cd ../scratch-gui`
- `npm install`
- `npm link scratch-vm scratch-blocks`
Incase of any upstream dependency conflict use `--legacy-peer-deps` in previous two steps.
- `npm start`
App local address : http://localhost:8601

After every change to scratch-blocks run `npm run prepublish` in `../scratch-blocks`

##### Add AWS text to speech extension 

