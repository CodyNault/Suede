# Suede
Suede Universal Execution and Distribution Environment (Browser-Based Grid Computing).

### This project is not active!
Suede is not currently under development due to lack of interest. Sorry but I wont be developing this one on my own if I don't have contributers. If someone wants to bring this project back from the dead then please send me a message, I'd be happy to contibute to a new version. Also note that this version was started back when there wasnt many great options for websocket servers yet.

### Running the Server
Simply upload the source code to your server and run the commands
```
sudo make
sudo ./bin/suede
```
This should start the websocket server and put it into a listening state.

### Configuring the client
client\src\test_config.js contains the ip and port settings for connecting to the server. These settings must be set according to the IP address of your server.

### Running the client
Simply open the file client\src\tester.html this will perform a websocket echo test to he server. This page will be updated with new instructions when a functional client process handler is completed.

### Unit testing
Suede source code is packaged with google test for c++ unit testing and qUnit for javascript unit testing
to run google test run the following commands from the root of the server directory
```
sudo make test
sudo ./bin/suede_test
```
To run the qUnit tests simply open the file client\test\tester.html
