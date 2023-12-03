# Developer Facebook

Application strives to achieve a basic developer's facebook meaning the following are used: comments, likes/dislikes, registration, profiles, and posts to discuss topics with like minded individuals. This is accomplished through using mongodb, react, nodejs, and express.

## Getting Started

If interested in testing the website, follow the instructions below.

### Prerequisites

Once the repository is cloned and up in running in your personalized IDE, you will need to do the following command in both the root directory and under client

```
npm install
```

Due to the nature of this being a no longer maintained project, if you wish to run this you'll need to install nvm (instruction for Windows and Linux are provided below). You will need to roll the version of node back to 16.20.2. Assuming you're on a Windows device you can follow along with the instructions below to get it working. 

Download and install NVM ( https://github.com/coreybutler/nvm-windows/releases)
Reboot your IDE so it can register the changes. Assuming the install was successful run:

```
nvm install 16.20.2
nvm use 16.20.2
```


### Running

Once you've installed the prerequisites, cd back into the root directory and run the command below. Note, you will not be able to utilizing the website properly without a backend (MongoDb).

```
npm run dev
```


## Built With

* [MongoDb](https://www.mongodb.com/) - Database used
* [React](https://reactjs.org/) - Front end UI
* [Nodejs](https://nodejs.org/en/) - Language used for backend
* [Express](https://expressjs.com/) - Minimalist web framework

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Special thanks to Brad Traversy for the help and development of this project.
