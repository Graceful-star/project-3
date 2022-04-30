# Documentation of project3
## Step  1
1. I updated ubuntu

   `sudo apt update`
   ![ubuntu](images/capture.PNG)

2. I upgraded ubuntu

   `sudo apt upgrade`

   ![ubuntu](images/image2.PNG)

3. I got the location of node-js software
   `curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -`

    ![ubuntu](images/image3.PNG)

4. I installed node.js
   `sudo apt-get install -y nodejs`

   ![ubuntu](images/image4.PNG)

5.  I verified the node installation
   `node -v`

   ![ubuntu](images/image5.PNG)
   
   `npm -v`
   ![ubuntu](images/image6.PNG)

6. I created a Todo directory
   `mkdir Todo`

   ![ubuntu](images/image7.PNG)

7. I verified if it  was created
   `ls`

   ![ubuntu](images/image8.PNG)

8. I changed my current directory to Todo directory
   
   `cd Todo`

   ![ubuntu](images/image9.PNG)

9. I initialised my project

   `npm init`
   ![ubuntu](images/image10.PNG)

10. I confirmed if package.json file was created during the process
    
    `ls`
    ![ubuntu](images/image11.PNG)

## Step 2
1. I installed express using npm
   `npm install express`

   ![ubuntu](images/image12.PNG)

2. I created a file named 'index.js'

   `touch index.js`
   ![ubuntu](images/image13.PNG)
    ![ubuntu](images/image14.PNG)

3. I installed dotenv module
   `npm install dotenv`

   ![ubuntu](images/image15.PNG)

4. I opened the file and inputed the required codes
   `sudo vim index.js`

   ![ubuntu](images/image16.PNG)

5. I started my server to see if it works
   `node index.js`

   ![ubuntu](images/image17.PNG)

6. I accessed my public ip address on my browser
  
  `http://<PublicIP-or-PublicDNS>:5000`
   
   ![ubuntu](images/browser1.PNG)

7. I created a routes directory
   
   `mkdir routes`
   ![ubuntu](images/image18.PNG)

8. I changed the current directory to the one I just created
     `cd routes`
     ![ubuntu](images/image19.PNG)

9.  I created a new file 
    
    `touch api.js`
    ![ubuntu](images/image20.PNG)

10.  I opened the file and inserted the required codes, then I saved it
     
     `sudo vim api.js`

     ![ubuntu](images/image21.PNG)

## Step 3
1. I changed the directory back to 'Todo' and installed mongoose

   `npm install mongoose`
   ![ubuntu](images/image22.PNG)

2. I created 'models' directory
    `mkdir models`
    ![ubuntu](images/image23.PNG)

3. I changed directory into the newly created folder
    `cd models`
    ![ubuntu](images/image24.PNG)

4. I created a file and named it todo.js
   `touch todo.js`
   ![ubuntu](images/image25.PNG)

5. I opened the file created and pasted the required codes
   `sudo vim todo.js`
   ![ubuntu](images/image27.PNG)

6. Then, I updated the file in the routes directory
   `sudo vim api.js`

   ![ubuntu](images/image28.PNG)

7. I opened a Mongodb database and got my connection string. Then I copied the connection string in a new file that I created.
    ![ubuntu](images/image29.PNG)

8. I updated the 'index.js' file to reflect the use of '.env'
   
   ![ubuntu](images/image30.PNG)

9.  I started my server again
    
    `node index.js`
    ![ubuntu](images/image31.PNG)

10. I installed Postman and created a POST and GET request for my API
   
   ![ubuntu](images/image32.PNG)
   ![ubuntu](images/image33.PNG)


## Step 3
1. I created a new folder in my Todo directory
   ` npx create-react-app client`

   ![ubuntu](images/image34.PNG)

2. I installed concurrently
    `npm install concurrently --save-dev`

    ![ubuntu](images/image35.PNG)

3.  I installed nodemon
     
     `npm install nodemon --save-dev`

     ![ubuntu](images/image36.PNG)

4.  I updated the package.json file
    `sudo vim package.json`

    ![ubuntu](images/image37.PNG)

5.  I veriified my local host server
    `npm run dev`

    ![ubuntu](images/image38.PNG)

6.  I installed Axios after doing the necessary steps
    
    ![ubuntu](images/image39.PNG)

7. I went to my componentas directory, opened Listtodo.js and pasted the required codes
    ![ubuntu](images/image40.PNG)

8. I opened the necessary files and pasted the required codes
   
   ![ubuntu](images/image41.PNG)
   ![ubuntu](images/image42.PNG)

  
   