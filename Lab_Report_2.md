# Part1:

### Code for my StringServer:
![image](https://github.com/Sam110120/cse15l-lab-report2/assets/71369089/2b323486-71d9-406b-a972-414c89bff07f)

### /add-message for "Hi":
![image](https://github.com/Sam110120/cse15l-lab-report2/assets/71369089/1e0ff4a5-b11c-49b5-b5f8-305add3d399e)
* I called the handleRequest method which contains all my implementations for URL querying features.
* The relevant arguments are the website URL as the method parameter, and the values are the website path, querying key, and querying messages.
* If I want to add and show messages on the website, I will have to change the URL information by adding "/add-message?s=<string>" at the end. In the code itself, I pre-defined an ArrayList which will contain all the messages. So whenever certain messages are added by querying request "/add-message?s=<string>", the ArrayList will store the information.

### /add-message for "How are you":
![image](https://github.com/Sam110120/cse15l-lab-report2/assets/71369089/94ecc603-29d6-4f80-8970-e9889c4edc82)
* Everything is pretty much the same as the part above except I added another message by putting "/add-message?s=How are you" at the end, which replaced the "/add-message?s=Hi". So the message "How are you" will be stored in the ArraryList as the second element with corresponding sequence value 2, and all the messages stored in ArraryList will be displayed on the website with the corresponding sequence (The order when the message is added to the ArrayList).

# Part2:
### Private key in my computer:
![image](https://github.com/Sam110120/cse15l-lab-report2/assets/71369089/cf76295b-5736-4108-9547-04c15677793f)

### Public key within my account on ieng6:
![image](https://github.com/Sam110120/cse15l-lab-report2/assets/71369089/c246a00b-2c2d-4097-afd0-d72c6f6a9a22)

### log into ieng6 without password:
![image](https://github.com/Sam110120/cse15l-lab-report2/assets/71369089/8b6ecb69-b826-4190-97bd-3ddd90cc03b3)


# Part3: 

* In weeks 2 and 3 I learned different things such as how to ssh into the remote server and start my own local host server using different ports. It was also quite interesting that I could generate my own password token so that I could log in to the remote server directly without entering my password because I always forget what my password is.
