# Project Title: Deploy Angular Application in Docker Container

1.	First I developed an angular application along with dockerfile,nginx to my git repository as below.
a.https://github.com/SUBHA1997-SELVI/new-1.git
2.	Then installed node/NPM on Ubuntu
3.	Install angular on Ubuntu.
4.	Cloned my angular git repository.
5.	Point to your git hub repository at local machine
6.	Run npm update
7.	Run npm install –save-dev @angular-devkit/build-angular
8.	Run npm audit fix
9.	Build angular project with environment configure(prod)
10.	Create docker image
11.	Run docker image in docker container
12.	Commands:
a.	Curl –sL https://deb.nodesource.com/setup_16.x | sudo -E bash –
b.	Sudo apt install nodejs
c.	npm install –g @angular/cli
d.	git clone https://github.com/SUBHA1997-SELVI/new-1.git
e.	npm update
f.	npm install --save-dev@angular-devkit/build-angular
g.	npm audit fix
h.	ng build –prod
i.	docker build –t  MyAngularApp-image .
j.	docker run –name MyAngularApp-container –d –p localhost:4200 MyAngularApp-image
    
           a. install Node
i.	Curl –sL https://deb.nodesource.com/setup_16.x | sudo -E bash –
ii.	Sudo apt install nodejs
b.	Install Angular on Ununtu
i.	npm install –g @angular/cli  
ii.	npm  update –g
c.	Git one Angular Project
i. git clonehttps://github.com/SUBHA1997-SELVI/new-1.git

