
|||||
|:-:|:-:|:-:|:-:|
|![First Image](https://res.cloudinary.com/dyamr9ym3/image/upload/v1662482775/github_readme_images/react_dzmcqt.png)|![Second Image](https://res.cloudinary.com/dyamr9ym3/image/upload/v1662483177/github_readme_images/axios_jlnlcn.png)|![Third Image](https://res.cloudinary.com/dyamr9ym3/image/upload/v1662483316/github_readme_images/sass_yxqpyf.png)|![Fourth Image](https://res.cloudinary.com/dyamr9ym3/image/upload/v1662483366/github_readme_images/date-fns_dukuao.png)

|||||
|:-:|:-:|:-:|:-:|
|![First Image](https://res.cloudinary.com/dyamr9ym3/image/upload/v1662483522/github_readme_images/react-skeleton-loader_vxafmb.png)|![Second Image](https://res.cloudinary.com/dyamr9ym3/image/upload/v1662483825/github_readme_images/msw-logo_gzlqe3.svg)|![Third Image](https://res.cloudinary.com/dyamr9ym3/image/upload/v1662483732/github_readme_images/redux-toolkit_nxvzow.png)|![Fourth Image](https://res.cloudinary.com/dyamr9ym3/image/upload/v1662482745/github_readme_images/socketio_lcyu8y.jpg)

||
|:-:|
![First Image](https://res.cloudinary.com/dyamr9ym3/image/upload/v1662565384/github_readme_images/react-app-rewired_iw8y1f.png)

Chatty App is a real-time socialnetwork application built with `react`. 

You can find the repo for the backend [here](https://github.com/uzochukwueddie/chatty-backend).

## Screenshots

![first image](https://res.cloudinary.com/dyamr9ym3/image/upload/v1662569599/github_readme_images/Screenshot_2022-09-07_at_6.39.16_PM_oj1ijk.png)
![second image](https://res.cloudinary.com/dyamr9ym3/image/upload/v1662569598/github_readme_images/Screenshot_2022-09-07_at_6.47.19_PM_cvxvcm.png)
![third image](https://res.cloudinary.com/dyamr9ym3/image/upload/v1662569597/github_readme_images/Screenshot_2022-09-07_at_6.49.40_PM_jlgccj.png)
![fourth image](https://res.cloudinary.com/dyamr9ym3/image/upload/v1662569598/github_readme_images/Screenshot_2022-09-07_at_6.49.54_PM_hi1vi7.png)
![fifth image](https://res.cloudinary.com/dyamr9ym3/image/upload/v1662569600/github_readme_images/Screenshot_2022-09-07_at_6.52.36_PM_v9wlpo.png)
![sizth image](https://res.cloudinary.com/dyamr9ym3/image/upload/v1662569597/github_readme_images/Screenshot_2022-09-07_at_6.52.58_PM_yvlmic.png)

## Features
1. Signup and signin authentication
2. Forgot password and reset password
3. Change password when logged in
4. Create, read, update and delete posts with images and gifs
5. Post reactions
6. Comments
7. Followers, following, block and unblock
8. Private chat messaging with text, images, gifs, and reactions
9. Image upload
10. In-app notification and email notification
11. Custom components
12. Custom React hooks
13. Unit tests
14. Redux implementation using redux-toolkit

## Main Tools
- Create react app
- React
- Redux-toolkit
- Axios
- Date-fns
- React redux
- React router DOM
- SocketIO
- React icons
- SASS
- Lodash
- Jest
- React testing library
- ESLint and Prettier
- React app rewired
- React loading skeleton
- Mock service worker

## Requirements

- Node 16.x or higher
- Giphy API key. You can create an account and obtain a key [here](https://developers.giphy.com/)

- You'll need to copy the contents of `.env.develop`, add to `.env` file and update with the necessary information.

## Local Installation

- There are three different branches develop, staging and main. The develop branch is the default branch.

```bash
git clone https://github.com/punithnayak/coonectwithfrontend.git
npm install
```
- To start the server after installation, run
```bash
npm start
```

## Unit tests

- You can run the command `npm run test` to execute the unit tests added to the components.

## Update APP_ENVIRONMENT

- Inside the `axios.js` file found via this path `src/services`, there is a variable called `APP_ENVIRONMENT`.
- If you are setting up the application locally, the variable name needs to be `local`.
- If you are deploying based on the branch, for example develop branch, the variable value needs to be `development`.
