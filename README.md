# Application-Deployment-1
The goal is to automate the deployment of a React application.  
1.Cloning code 
2.Building the application 
3.Creating Docker image 
4.Uploading Docker image
5.Deploying Kubernetes  
6.Everything should happen automatically whenever you push code to GitHub.

Launch Ubuntu EC2
Ubuntu 24.04
t3.medium 
30 GB storage

<img width="1911" height="735" alt="image" src="https://github.com/user-attachments/assets/bdd1fbb9-cc93-4047-a226-0b8448cfffd3" />
<img width="1761" height="732" alt="image" src="https://github.com/user-attachments/assets/44dfc816-ab5e-4ae4-8a2d-a9614aa6b7da" />
<img width="1643" height="687" alt="image" src="https://github.com/user-attachments/assets/a2766fad-a3ac-4a22-ab1e-f031535a793d" />
<img width="1615" height="403" alt="image" src="https://github.com/user-attachments/assets/8853c4bf-4422-4c1b-867c-7338b405d725" />

Install Docker and allow ubuntu user 

<img width="1903" height="552" alt="image" src="https://github.com/user-attachments/assets/5c8f2774-1de7-47f3-9ef2-70962a98dd98" />

Clone Repository

<img width="1907" height="826" alt="image" src="https://github.com/user-attachments/assets/5eef0883-3df6-4543-b1a7-0f3163801f23" />

Install NodeJS and check verion and install npm node package manager

<img width="1917" height="153" alt="image" src="https://github.com/user-attachments/assets/5b8c2eb0-a95e-45b9-9312-a6644015484c" />

Repository already contains the built application the dist folder is the output of: npm run build
<img width="1907" height="533" alt="image" src="https://github.com/user-attachments/assets/e49b6270-cd16-42d9-92da-cea841f708f4" />

Create a Docker Hub Repository
<img width="1892" height="863" alt="image" src="https://github.com/user-attachments/assets/f0af82c7-d733-4dde-9b3a-30d4685ba849" />

Create docker file and build the image and confirm
<img width="1895" height="772" alt="image" src="https://github.com/user-attachments/assets/acaf3282-88b5-4c63-8b75-2fe41f28df30" />

Test the Image Locally and check using public ip  http://<EC2-PUBLIC-IP>:3000
<img width="1902" height="166" alt="image" src="https://github.com/user-attachments/assets/b4344229-fbe1-4cad-892b-2889e72d2bf0" />
<img width="1912" height="945" alt="image" src="https://github.com/user-attachments/assets/33443041-3d32-4756-9646-1c3f2740aad3" />

Login to Docker Hub and push the images to docker repo
<img width="1913" height="286" alt="image" src="https://github.com/user-attachments/assets/a2165a4a-eee1-46bf-8def-d927571fe938" />
<img width="1908" height="393" alt="image" src="https://github.com/user-attachments/assets/dd4e2f7d-c78c-448e-9356-53a601da9b19" />
<img width="1222" height="603" alt="image" src="https://github.com/user-attachments/assets/a92a38db-9dc7-4a74-9502-5be0c89de035" />

Install AWS CLI 
<img width="1906" height="336" alt="image" src="https://github.com/user-attachments/assets/032a09d7-bfd1-4517-ba14-69f8c0b90d1a" />


