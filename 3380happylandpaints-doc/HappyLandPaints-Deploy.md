
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
```
> Additional nodemdules used for Frontend:

```bash
$ npm install xlsx
$ npm install nodemailer
```
### Backend
>Run following commands in command prompt :

```bash
$ mkdir 3380happylandpaints-ws
$ cd 3380happylandpaints-ws
$ npm install 
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
### Deploy Backend on AWS:
```bash
$ mkdir 3380happylandpaints-ws
$ cd 3380happylandpaints-ws
$ git init
$ git remote add origin git@github.com:Singh-g1235/3380happylandpaints-ws.git
$ git pull --all
$ nodemon index.js
```

## Deploy on Heroku
* Heroku Set Up: 
    - Github > Import Repository 
      >Your old repository’s clone URL : (https://github.com/Singh-g1235/3380happylandpaints-app.git) 
      >Repository Name : 3380happylandpaints-heroku
      >Begin Import
    - Create a new app in heroku
    - Choose Deployment method as Github in Deploy tab of apps
    - Search for a repository to connect to and press connect : 3380happylandpaints-heroku
    - Choose a branch to deploy : main
    - Enable Automatic Deploys
    - Choose a branch to deploy : main
    - Deploy Branch
    - After deployment, heroku display 'Your app was successfully deployed.'. Click View
    - View logs
```bash
$ heroku logs --app 3380happylandpaints-heroku --tail
```
