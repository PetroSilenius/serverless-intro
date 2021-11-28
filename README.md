# Introduction to Serverless Functions course

My repository for the course Introduction to Serverless Functions by Jason Lengstorf on Frontend Masters.
The course can be found [here](https://frontendmasters.com/workshops/serverless-functions/) and the content is briefly described below

> Serverless functions enable you to build dynamic web experiences without the hassle of setting up or maintaining servers! In this course, you'll learn how to create serverless functions to accomplish a variety of tasks that typically require a back-end. Whether that's securely loading data, processing form entries, handling user access, or doing something totally off the wall, serverless functions let you skip the boilerplate and get straight to building your app's logic!

## Final product

Available on [serverless-intro.netlify.app](https://serverless-intro.netlify.app/)

A movie resource website with a specific theme around the Shiba Inu dog breed. Users can log into the website on ```/login``` and they're then redirected to the admin panel. All functionalities are built with serverless functions and the web page content is built using [11ty](https://www.11ty.dev/).

## Installation

1. Clone the repo
   ```sh
   git clone git@github.com:PetroSilenius/serverless-intro.git
   ```
2. Install dependencies based on the lock file
  ```sh
  npm ci
  ```

3. Install netlify-cli tools globally
  ```sh
  npm install netlify-cli -g
  ```

4. Initialize the Netlify project
  ```sh
  netlify init
  ```
  
5. Start up the environment
  ```sh
  netlify dev
  ```

6. Open [http://localhost:3000/](http://localhost:8000/) to view the index page

In order to configure Netlify Identity, Hasura API and Heroku Database, I recommend you to check out the Frontend Masters course.

## Resources

- [Netlify Functions](https://www.netlify.com/products/functions/?utm_source=fem-sls&utm_medium=functions-jl&utm_campaign=devex)
- [Netlify Identity](https://docs.netlify.com/visitor-access/identity/?utm_source=fem-sls&utm_medium=functions-jl&utm_campaign=devex)
- [Hasura](https://cloud.hasura.io/)
- [Heroku](https://www.heroku.com/)

## Acknowledgements

* [Jason Lengstorf](https://frontendmasters.com/teachers/jason-lengstorf/)

## License

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License</a>.
