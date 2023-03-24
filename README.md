# Assignment1_Part3

## Part 3: Docker Volumes

### Step1: (Create a new Docker volume named "my_volume")

![image](https://user-images.githubusercontent.com/126570628/227563625-0046cd73-7abb-444c-adb8-90e90d940053.png)

### Step2: (Create a new Docker container using the "nginx" image and mount the "my_volume" volume to the container's "/usr/share/nginx/html" directory)

![image](https://user-images.githubusercontent.com/126570628/227563698-d4bbd629-17bc-4ed7-b4fc-94de4ee90337.png)

### Step3: (Verify that the "nginx" default page is accessible on your host machine at "http://localhost:8080")

![image](https://user-images.githubusercontent.com/126570628/227563772-7adf54d7-0636-434c-a1aa-afa5e88ba0e0.png)

### Step4: (Create a new file named "index.html" on your host machine and add some text to it)

![image](https://user-images.githubusercontent.com/126570628/227563951-44ab7ddb-7ddd-495c-a0dc-d931da7c7a1b.png)

### Step5: (Copy the "index.html" file from your host machine to the "my_volume" volume using the "docker cp" command)

![image](https://user-images.githubusercontent.com/126570628/227564186-7048c411-a771-4fcc-bdf7-a5280bc7789d.png)

### Step6: (Verify that the "index.html" file is accessible on your host machine at "http://localhost:8080")

![image](https://user-images.githubusercontent.com/126570628/227564381-397d18bd-5eb9-4f8d-b665-121c5c47e0d3.png)

### Step7: (Stop and remove the container)

![image](https://user-images.githubusercontent.com/126570628/227564507-11f04486-cf29-4ce0-8687-95bd3a2b1cd7.png)

### Step8: (Create a new Docker container using the "httpd" image and mount the "my_volume" volume to the container's "/usr/local/apache2/htdocs" directory)

![image](https://user-images.githubusercontent.com/126570628/227564826-35e6cf36-d5e7-4a20-a90e-23fba3b06fd0.png)

### Step9: (Verify that the "httpd" default page is accessible on your host machine at "http://localhost:8081")

![image](https://user-images.githubusercontent.com/126570628/227565223-95a826a3-2ef8-47d6-8b8c-27b95ab36811.png)

### Step10: (Create a new file named "about.html" on your host machine and add some text to it)

![image](https://user-images.githubusercontent.com/126570628/227565421-06245437-c87a-4d67-92c6-78771e82e115.png)

### Step11: (Copy the "about.html" file from your host machine to the "my_volume" volume using the "docker cp" command)

![image](https://user-images.githubusercontent.com/126570628/227565509-5f2b6971-e1e1-4594-812b-26cd8dae1992.png)

### Step12: (Verify that the "about.html" file is accessible on your host machine at "http://localhost:8081/about.html")

![image](https://user-images.githubusercontent.com/126570628/227565643-b9ce2eb4-4ef5-4b05-b1ef-e3f5a236960e.png)

### Step13: (Stop and remove the container)

![image](https://user-images.githubusercontent.com/126570628/227565743-29a96c9f-ed3d-43a0-bf76-9f48dd74534d.png)

### Step14: (Verify that the "index.html" and "about.html" files are still available in the "my_volume" volume)

![image](https://user-images.githubusercontent.com/126570628/227565835-3f76d2c4-1c3f-4937-aed7-611d227b946c.png)

### Step15: (Cleanup: Remove the "my_volume" volume)

![image](https://user-images.githubusercontent.com/126570628/227565974-96548010-7b1d-419f-82af-b1d79b2c2683.png)

### Step16: (Create a README.md file)

Created a README.md file in “Assignment1_Part3” GitHub repository under the main branch. This file contains the findings for each command used in Part 3 of the assignment. 

### Step17: (Push the codebase for the sample application to your GitHub repository)

Initializing git in “assignment1_part3” directory, and then committing the sample application files to local repository. 

![image](https://user-images.githubusercontent.com/126570628/227566186-365189fd-c1c0-4686-95ef-9191c19986b2.png)

Then we pushed the codebase for the sample flask application to the GitHub repository under master branch by first setting the remote repository configuration: “git remote add origin https://github.com/nab1999/Assignment1_Part3.git” and then pushing the local git repository to remote/central/GitHub repository by using the command: “git push -u origin master”. To verify that is has been pushed successfully we can check the files in the GitHub repository in the browser. And to pull the files/repository to our local machine/repository, we used the command “git pull -u origin master”.


OUTPUT:

![image](https://user-images.githubusercontent.com/126570628/227566347-9dc87e2f-4e1f-46a8-86fb-2d8a1ab513b1.png)

![image](https://user-images.githubusercontent.com/126570628/227566373-f311d821-ff09-4e5b-9476-0847c31982c2.png)



