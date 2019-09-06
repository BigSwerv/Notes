#Scotch Angular Notes
---

###Step 1 : Installing the Angular CLI
 - Start by installing the command line 
 
		npm install -g @angular/cli

 > we use the ``` -g``` to flag to install this gloabally on our system.
 
 > Next we should be able to run ```ng -v``` to see what version we are running

---
###Step 2 : Starting up project

 We can start by using this 

	ng new my-angular-site
 Now we have a full Angular applications ready to build with.You can see the folder structure and the files that get generated for us:


 >We will mainly be working inside the ```  src ``` folder. The ``` .angular-cli.json```
 >is the file that tells our CLI how to run.
 
---

###Step 3 : Serving Our Project

 We can start this Angular app by using the ``` ng serve ``` command:
 > We can see this app in ouor browser now at  http://localhost:4200

---

###Step 4 : Starting a Minimal Angular CLI Project

  > While that first setup is great for large production ready applications, it can be a little daunting when we only want to make a test site to get some experience with Angular.
  > 
Let's use the [Link](https://scotch.io/tutorials/create-a-barebones-angular-app-with-the-minimal-flag)
. This will remove the tests ``` spec.ts ``` files) and make our folder structure simpler by inlining the template and styles instead of creating separate files for them.

	ng new --minimal my-angular-site

---

###Step 5: Adding Routing and Using Sass for styles
> Let's use the CLI to handle more for us. We want to eventually route our application so that our single page app can navigate between pages. We also want to use Sass because it will make writing our CSS easier.

 - Delete that project one last time and create a new one with the ``` --routing``` flag and also the ``` --style=scss ``` flag:
 	
	``` ng new --minimal --routing --style=scss my-angular-site
 ```

Now we are given a routing file at ``` src/app/app-routing.module.ts ``` and also our ``` .css ``` files are now ``` .scss  ``` files.

---







  

	


		