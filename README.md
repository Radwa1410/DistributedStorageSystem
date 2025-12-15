# DistributedStorageSystem

## Description
Distributed File Storage System is a TCP-based network programming project. A client sends a file to a central server, which splits the file into chunks and distributes them across multiple storage servers. The server later retrieves and merges the chunks to reconstruct the original file.

## Architecture
- Client: Sends a file and requests it back.
- Main Server: Splits, distributes, and merges file chunks.
- Storage Servers: Store and return individual file chunks.

## Technologies Used
- Python
- TCP Sockets
- Client-Server Architecture

## How to Run
1. Run all storage servers (ports 6001–6004).
2. Run the main server on port 5000.
3. Run the client and send any file (text, image, or video).

## Notes
- The system transfers raw binary data and supports all file types.
- Storage servers keep data in memory for
