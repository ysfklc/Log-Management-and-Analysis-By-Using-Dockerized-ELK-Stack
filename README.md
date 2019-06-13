Log Management and Analysis By Using Dockerized ELK Stack
=========================================================

### Installation

`git clone https://github.com/ysfklc/Log-Management-and-Analysis-By-Using-Dockerized-ELK-Stack.git`

`cd Log-Management-and-Analysis-By-Using-Dockerized-ELK-Stack/`

### Running

`docker-compose up`

### Configuration

* Change path of log directory

    /filebeat/config/filebeat.yml line:28
    
    `- /your/path/to/log/file`

* You can add whole log in the specific directory 

    `- /your/path/*/*.log`

* You can add more than one directory for log source
    
    /filebeat/config/filebeat.yml after line:28
    
    `- /your/path/to/another/log/file`