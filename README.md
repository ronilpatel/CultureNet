# CultureNet

_CultureNet_ is a web application designed to provide users with a platform to review, log, and network around movies, TV shows, music, and books. The main purpose of the project is to enable users to discover new entertainment content, share their opinions and insights, and connect with like-minded individuals.

- _Date Created_: 27 Feb 2023
- _Last Modification Date_: 13 Apr 2023
- _Git URL (Frontend)_: https://git.cs.dal.ca/andharia/csci5709-group11/-/tree/main
- _Git URL (Backend)_: https://git.cs.dal.ca/andharia/csci5709-group11-backend/-/tree/main
- _Deployed App URL_: https://csci5709-group11.netlify.app/

## Authors

- [Monil Andharia](andhariamonil@dal.ca) - _Full Stack Developer_
- [Nikhil Panikkassery](nk561034@dal.ca) - _Full Stack Developer_
- [Pranay Raycha](pr746594@dal.ca) - _Full Stack Developer_
- [Rishi Vasa](rishi.vasa@dal.ca) - _Full Stack Developer_
- [Ronil Patel](ronil.patel@dal.ca) - _Full Stack Developer_

## Getting Started

### Prerequisites

To have a local copy of this lab / assignment / project up and running on your local machine, you will first need to install the following software/libraries / plug-ins

```
Node.js
```

See the following section for detailed step-by-step instructions on how to install this software / libraries / plug-ins

### Installing

1. Install [Node.js](https://nodejs.org/en/download/) from the following link:

2. Clone the git repository.

3. Checkout to the `main` branch.

4. Open the terminal and run the following commands:

#### Frontend

```bash
> npm install
> npm start
```

#### Backend

```bash
> npm install --legacy-peer-deps
> npm server-local.js
```

## Deployment

### Auto deployment (CI/CD)

1. Login to [Netlify](https://app.netlify.com/)

2. Create a new site.

3. Upon pushing a new commit on `main` branch, the application will be automatically published to https://csci5709-group11.netlify.app/

### Manual deployment (Frontend)

1. Login to [Netlify](https://app.netlify.com/).

2. Click "Add a new site" on Netlify

3. Click "Drop manually"

4. Run "npm install" command in terminal in Visual Studio Code in local.

5. Run "npm run build" command in terminal in Visual Studio Code in local.

6. Drag folder "build" from local project folder and drop it in Netlify.

7. Click Deploy Site.

8. Netlify should provide url for the application.

### Manual deployment (Backend)

1. Login to [Netlify](https://app.netlify.com/).

2. Run following commands through project terminal
   - npm install --legacy-peer-deps
   - npm install netlify-cli -g
   - npm run build

3.Run following command with environment variables id and token received from netlify.
-netlify deploy --dir "build" --auth $token --site $id --prod 4. Netlify should provide url for the application.

## Built With

- [Node.js](https://nodejs.org/en/) - JavaScript runtime environment

- [Express.js](https://expressjs.com/) - Web framework for NodeJS

- [MUI](https://mui.com/) - Web component library

- [Mongoose](https://mongoosejs.com/docs/) - MongoDB library

- [Nodemailer](https://nodemailer.com/usage/using-gmail/) - Node library for email sending via OAuth2

- [MongoDB] (https://www.mongodb.com/)- Used for data storage

## Sources Used

### For Deployment on Netlify

Backend code needed to be deployed as serverless-http functions on Netlify. I referred to the following video to learn and implement the deployment.

- [Owen Conti](https://www.youtube.com/watch?v=hQAu0YEIF0g)

## Acknowledgments

- [Gitlab docs](https://docs.gitlab.com/ee/ci/examples/deployment/index.html#storing-api-keys) for providing _yml_ to deploy code to Heroku

- [React documentation](https://reactjs.org/docs/create-a-new-react-app.html) for guiding how to create first react application

- [MUI](https://mui.com/) for providing better UI components

- [Mongoose](https://mongoosejs.com/docs/) for connecting to MongoDB

- [Nodemailer](https://nodemailer.com/usage/using-gmail/) for sending password reset code to email

- [“mongoose "Find" with multiple conditions” Stack Overflow](https://stackoverflow.com/questions/33627238/mongoose-find-with-multiple-conditions) for finding aggregates

- [“How I can use "LIKE" operator on mongoose?” Stack Overflow](https://stackoverflow.com/questions/43729199/how-i-can-use-like-operator-on-mongoose) for using `LIKE` operator on mongoose

- [“Stunning royalty-free images & royalty-free stock” pixabay](https://pixabay.com/) for free licensed images

- The Professor

- All the TAs of this course
