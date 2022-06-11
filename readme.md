# Scratch project

### Objective

- To create custom operator blocks to compute Square and square root of a number.

### Demo

![image](https://user-images.githubusercontent.com/59413872/173130760-e563f93e-f831-48c3-afdd-656f5247141c.png)

- Video <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-volume-up-fill" viewBox="0 0 16 16">
  <path d="M11.536 14.01A8.473 8.473 0 0 0 14.026 8a8.473 8.473 0 0 0-2.49-6.01l-.708.707A7.476 7.476 0 0 1 13.025 8c0 2.071-.84 3.946-2.197 5.303l.708.707z"/>
  <path d="M10.121 12.596A6.48 6.48 0 0 0 12.025 8a6.48 6.48 0 0 0-1.904-4.596l-.707.707A5.483 5.483 0 0 1 11.025 8a5.483 5.483 0 0 1-1.61 3.89l.706.706z"/>
  <path d="M8.707 11.182A4.486 4.486 0 0 0 10.025 8a4.486 4.486 0 0 0-1.318-3.182L8 5.525A3.489 3.489 0 0 1 9.025 8 3.49 3.49 0 0 1 8 10.475l.707.707zM6.717 3.55A.5.5 0 0 1 7 4v8a.5.5 0 0 1-.812.39L3.825 10.5H1.5A.5.5 0 0 1 1 10V6a.5.5 0 0 1 .5-.5h2.325l2.363-1.89a.5.5 0 0 1 .529-.06z"/>
</svg> : https://drive.google.com/file/d/1_xTl2-7bZPWYvXfi34r4yUbewRYbvP5N/view?usp=sharing

- File  : https://drive.google.com/file/d/1tGDSo4xE8godlOS7I-JvpFAUNw7BOAtw/view?usp=sharing

### Getting Started

#### Requirements

- Python 2.X
- Java
- Node JS
- npm / yarn
(Set environment variables for python 2.X if running multiple versions)
    
#### Steps to follow

- Clone the repo
- On Windows platform patch the build.py file in scratch-blocks from [here](https://github.com/LLK/scratch-blocks/pull/2138/commits/9007da52532cd380df5d0ac1a560788ed4f962cd#)
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
- Add AWS text to speech extension 

After every change to scratch-blocks run `npm run prepublish` in `../scratch-blocks`



