Step 1: Connect to Your VPS
Log in to your VPS using SSH:

sh
Copy
Edit
ssh root@your-vps-ip
Step 2: Clone the Repository
Download the script from GitHub:

sh
Copy
Edit
git clone https://github.com/NFTsaz-scripts/klok.git
Navigate to the project folder:

sh
Copy
Edit
cd klok
Step 3: Install Dependencies
Run the following command to install required Node.js packages:

sh
Copy
Edit
npm install axios uuid fs
Step 4: Create a Token File
Open a new file to store your token:

sh
Copy
Edit
nano token.txt
Paste your token inside the file, then save and exit (CTRL + X, then Y and ENTER).

Step 5: Run the Script
Execute the script with Node.js:

sh
Copy
Edit
node klok.js
