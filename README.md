# DDK_file_sender
Use the socket to send a file.
* I will implement it someday.

# Features
* light

# Behaviors
* Put it in the same folder.
* Input remote ip.
* Input the file name.
* Waiting until finish or timeout.

# Step by Step
1. Starup socket.
2. Initial the server description.
3. Connect to this server.
4. Open the file.
5. Read it to buffer.
6. Send data when buffer is fulled.
7. Clean this buffer.
8. Do step5 to step7 recurssively until all the file sent.
10. Close the socket.

# Refrences
