# Update System
<img width="496" alt="update" src="https://user-images.githubusercontent.com/114501322/200607127-bf2e276e-8dc8-44bb-ad91-c5b8e2e4b897.png">

# Install Docker and Test with 'hello-world'
The commands traight from class document:
- sudo apt update
- sudo apt install ca-certificates curl gnupg lsb-releasecurl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo gpg --dearmor -o /usr/share/keyrings/docker-archive-keyring.gpg
- echo "deb [arch=$(dpkg --print-architecture)signed-by=/usr/share/keyrings/docker-archive-keyring.gpg]https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable" | sudo tee/etc/apt/sources.list.d/docker.list > /dev/null
- sudo apt update
- sudo apt install docker-ce docker-ce-cli containerd.io
- sudo usermod -aG docker sysadmin
- sudo docker run hello-world

<img width="497" alt="test docker" src="https://user-images.githubusercontent.com/114501322/200607319-9318bfd7-e132-4744-ba23-ea23320d63e7.png">

# Check Docker Compose Version
<img width="497" alt="check version" src="https://user-images.githubusercontent.com/114501322/200612855-eaa75616-85b7-467d-9ff3-9278b3613eb9.png">

# Create a new project directory for WordPress application with the following command:
- mkdir wordpress

# Navigate to the new directory:
- cd wordpress

# Using Preferred Text Editor, Create a New docker-compose.yml File, and Paste the Contents Below:
- For more information please visit: https://www.hostinger.com/tutorials/run-docker-wordpress
<img width="960" alt="create new file" src="https://user-images.githubusercontent.com/114501322/200646954-f7a1f5a6-1219-454e-9881-66a6fdd39c5f.png">

# With the Docker Compose File Created, Run the Following Command in the Same wordpress Directory to Create and Start the Containers:
<img width="675" alt="docker up" src="https://user-images.githubusercontent.com/114501322/200651515-31c4293d-81ba-4778-b2d2-8c07dae44e8e.png">

# Open browser and enter http://localhost:8000/. WordPress setup screen will appear. Select the preferred language and continue.
<img width="960" alt="wordpress" src="https://user-images.githubusercontent.com/114501322/200713749-c67b5abf-a5aa-4135-939d-32c86a40818c.png">

# Fill in site name, username, password, and email.
<img width="960" alt="open account" src="https://user-images.githubusercontent.com/114501322/200715416-04fe30ec-af7b-4284-95a0-82aa534c9ea4.png">

# WordPress dashboard screen
<img width="960" alt="inside wordpress" src="https://user-images.githubusercontent.com/114501322/200716516-716f9ea7-e285-4184-9560-efc7b71dbec9.png">

# WordPress Admin interface with my username
<img width="960" alt="admin" src="https://user-images.githubusercontent.com/114501322/200719931-1e2c4459-b35a-405f-bb16-ebcf6c79ed53.png">




