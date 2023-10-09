
# Docker Project 2 - DIO

   This repository contains the Docker Swarm project for [Digital Innovation One](https://web.dio.me). This project consists of creating a local Swarm Cluster, where we will use the Vagrant software to automate the process of creating and configuring both the virtual machines and the Cluster Swarm.

   As a proposed challenge, a container with a MySQL database application was added to the Cluster Manager, with data persistence in the created volume (data), from where another application can interact with this database through any MySQL client system.


## Requirements

- [Vagrant](https://www.vagrantup.com/)
- [Virtual Box](https://www.virtualbox.org/) (or other virtualization software)

## Usage


- Clone this repository to your local machine.
- Navigate to the project directory.
- Run the command below to start the container:
   
```bash 
    vagrant up 
```


## Author

[Miguel Mendes Serrano](https://github.com/miguelmendesSerrano)


## License

This project is licensed under the [MIT License.](https://choosealicense.com/licenses/mit)