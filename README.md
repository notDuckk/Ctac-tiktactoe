# Ctac-tiktactoe

### This a my React tik tac toe app!

#### There are only a few simple directions to follow in order to get this app runing and conterized onto your machine.

- Once you have cloned the repo onto your machine you need to run the command ``` docker build -t ctac-tiktactoe . ``` in the projects directory. ( this will build the react app and build the docker image. )
####
- Next you need to run the command ``` docker run -p 4000:3000 ctac-tiktactoe ``` (this will run the the dockerr container)

- From there visit http://localhost:4000/ and now you have an awesome react tiktactoe app in a docker container running on your machine.
