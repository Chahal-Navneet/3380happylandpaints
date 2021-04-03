
## Table of Contents

<details>
  <summary><b>Expand to show Table of Contents</b></summary>

<!-- toc -->

- [Installation](#installation)
- [Deploy on Localhost](#deploy-on-localhost)
- [Deploy on AWS](#deploy-on-aws)
- [Deploy on Heroku](#deploy-on-heroku)


<!-- tocstop -->

</details>

## Installation

### Frontend
>Run following commands inside 3380happylandpaints-app:

```bash
$ npm install
$ npm install xlsx
$ npm install nodemailer
```
### Backend
>Run following commands in command prompt:

```bash
$ mkdir 3380happylandpaints-ws
$ npm init
$ npm install 
$ npm install nodemon
$ npm install express
$ npm install body-parser
$ npm install cors
$ npm install mongoose
```
## Deploy on localhost

### Frontend
>Run following commands inside 3380happylandpaints-app to run application on [localhost](http://localhost:3000/)

```bash
$ npm start
```
### Backend
>Run following commands in command prompt:

```bash
$ nodemon index.js
```
## Deploy on AWS
* Requirements: 
    - EC2 Ubuntu Instance
    - Firewall rule setting to allow all inbound traffic
    - Created ssh keys for EC2 instance
    - Added ssh public key of EC2 instance to github
    - npm dependencies install on EC2 instance
    ```bash
        $ sudo apt install npm
        $ sudo apt install nodejs
        $ sudo npm install -g nodemon
    ```

### Deploy Backend to AWS
>Run following commands in command prompt:
```bash
$ mkdir 3380happylandpaints-ws
$ git init
$ git remote add origin git@github
```

## Deploy on Heroku

