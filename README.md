# JobHub

<img height="35" alt="React" src="https://img.shields.io/badge/-React-45b8d8?style=flat-square&logo=react&logoColor=white" /> <img height="35" alt="Nodejs" src="https://img.shields.io/badge/-Nodejs-3c873a?style=flat-square&logo=Node.js&logoColor=white" /> <img height="35" alt="GraphQL" src="https://img.shields.io/badge/-GraphQL-e535ab?style=flat-square&logo=graphql&logoColor=white" /> <img height="35" alt="MongoDB" src="https://img.shields.io/badge/-MongoDB-13aa52?style=flat-square&logo=mongodb&logoColor=white" /> <img height="35" alt="MongoDB" src="https://img.shields.io/badge/-Docker-45b8f8?style=flat-square&logo=docker&logoColor=white" />

A platform to connect job seekers and job providers

### Technologies Used

-   Back-end : Node js, Express JS, Graphql, JWT, Docker(containerization)

-   Database : Mongo DB

-   Front-end : ReactJS, Bootstrap, SCSS

### Installation

#### Install mongoDB and NodeJS

#### Clone the repository

```bash
git clone https://github.com/SparshJain2000/Jobhub.git
```

#### Declare environment variables

##### Create a file .env

```txt
DB_URI = 'Your mongo url'
secret = 'secret for jwt(tokens)'
```

### Docker 🐳

Build the client docker image

```bash
docker build -t "client" ./client
```

Build the client docker image

```bash
docker build -t "server" .
```

#### Dev container

Build the container using docker compose

```bash
cat docker-compose.dev.yml > docker-compose.yml
docker-compose up --build
```

#### Production Contaienr

```bash
cat docker-compose.prd.yml > docker-compose.yml
docker-compose up --build
```

### Running locally(without docker)

#### Install dependencies

```bash
npm install
npm install --dev
```

#### Start the application (both server (server.js) and client simultaneously using concurrently)

```bash
npm run dev
```

#### Server is on [http://localhost:3000](http://localhost:3000) and frontend is on [http://localhost:8080](http://localhost:8080)

#### For Front end

Runs the app in the development mode.<br />
Open [http://localhost:8080](http://localhost:8080) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

```bash
npm test
```

Launches the test runner in the interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

```bash
npm run build
```

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
Your app is ready to be deployed!

## Contributing

🍴 Fork the repository

👯 Clone the forked repo

📝 Change it / add your code ,

✔️ Do a "pull request"

## Support

Give a 🌟 to this repo if it helped you a bit .

