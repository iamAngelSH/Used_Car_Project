# Used Car Project


<hr>

## How to use:

1. Clone this [repository](https://github.com/iamAngelSH/Used_Car_Project.git) to a directory of your choice on your terminal.
  - Command to clone:
  ```git
  git clone https://github.com/iamAngelSH/Used_Car_Project.git
  ```
2. Step in the repository directory
  - Change Direcotry
  ```terminal
  cd Used_Car_Project
  ```
3. Here you should have all the contents you need.
4. Having Docker running already on your computer, we can get started with the FLask App.
5. Let's build the image
  - Run docker-compose up in the same directory you are in
  ```docker
  docker-compose up
  ```
6. On your terminal you should see a build with links to access the server.
  - Once the image is the done building you should get a similar link as shown below:
    -  http://8fb526fba343:8888/lab?token=0e90fd3d58c88017f252e01d2c10e74d3ffdafcbfbcf8911
    -  Click one of the links and it will take you to a web page that won't load.
  - WE NEED TO CHANGE THE PORT!
    - Since port 8888 is for the server running on the docker container, we need to use the port running on our local machine that I set in our docker-compose file.
    - Use the following port:
      - 9090
      - New link should look something as follows:
        - http://8fb526fba343:9090/lab?token=0e90fd3d58c88017f252e01d2c10e74d3ffdafcbfbcf8911 
7. Congrats 🥳 PySpark Jupyter-notebook is up and running

<hr>

