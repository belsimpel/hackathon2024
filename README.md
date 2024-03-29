# Gomibo Hackathon 2024 :office: :computer: :crown:
<img src="https://werkenbijbelsimpel.nl/wp-content/uploads/2023/01/Belsimpel-A-Gomibo-company_RGB_op-wit.svg" width="300" height="150">

## Installation guide
This section contains all relevant information to setup the necessary things to participate in the hackathon. You will be setting up a Docker environment running two services: MySQL and PHPMyAdmin. We've created a docker-compose.yml file which should do most of the work for you. 
#### Important to note: 
You're free to use whatever database management system and programming language. This is just to give you something to work with, but we're giving you a lot of freedom. As long as your able to store/retrieve data from a database, you should be okay!

### Clone Github repository
Start by cloning the Github repository on your device. Most of you will probably have done this before, but if not we highly recommend the following **before** cloning the repository.
1. Create a Github account --> [Sign up here!](https://github.com/signup?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home)
2. Add SSH token to your account --> [How do I do that??](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account)
3. Install Git on your device --> [More instructions!](https://github.com/git-guides/install-git)

Now you should be ready to clone the repository:
1. Navigate to a folder on your device where you would like to clone the repository into.
2. Clone the repository.
```
git clone git@github.com:belsimpel/hackathon2024.git
```
3. Navigate into the repository.
```
cd hackathon2024
```
4. You should now see the project files!

### Setup credentials
1. Open the hackathon2024 directory on your favorite IDE.
2. Edit the `.env` environmental file. You should add some credentials.

### Start Docker container
1. Now it's time to start spinning up the Docker environment.
2. First up, install Docker using [this guide](https://docs.docker.com/get-docker/).
3. Next, install Docker Compose by using [this guide](https://docs.docker.com/compose/install/).
2. First up, read through this installation guide for installing Docker and Docker Compose.
3. In a terminal, move to the projectfolder again (hackathon2024).
4. Pull the latest images.
```
docker-compose pull
```
5. Start the docker environment.
```
docker-compose up
```
*Tip, add the `-d` flag to run the container in the background.*

6. Go to http://localhost:8081/ and you should see PhpMyAdmin! You're now good to go.

### Shutting down
1. To shut everything down, just enter the following in your terminal.
```
docker-compose down
```

### Assignment
We're not spoiling the full assignment just yet, but it will be focused on our warehouse. Together with your team you will be designing a new warehouse system. Before coding, you will think of ways to implement the requirements in a nice way. On the day of the hackathon, we'll push the assignment to [this folder](/assignment/). Make sure to read through the assignment carefully! 

### Working together
How you work together is up for you to decide, but we recommend setting up a Github repository. You should already be assigned to a team, please contact each other and discuss how you want to work together. It might save time to set up a Github repository already so you can start working on the assigenment as soon as possible. Your group should consist of a mix of developers. Try to let everyone perform a task he/she likes and can handle with their skill level and knowledge. Also, think of a cool team name!
