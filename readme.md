# Original code and how it works
## Server 
![alt text](image.png)

## Client 1 
![alt text](image-2.png)

## Client 2 
![alt text](image-1.png)

## Client 3 
![alt text](image-3.png)

# Modifying Ports
The parts that needed to be change is the listener part of the `server.rs` aside from the websocket protocol. 

# Small Changes 
![alt text](image-4.png)

![alt text](image-5.png)

This step we add information of the sender for every client in IP and Port. The small changes are made in the `bcast_tx.send` format in `server.rs`