---
title: How to create react app
subtitle: >-
  React uses javascript library to create efficient user interfaces of web
  application in effective way. It helps us to compose small pieces of code from
  complex UIs. It’ll update the...
excerpt: >-
  React uses javascript library to create efficient user interfaces of web
  application in effective way. It helps us to compose small pieces of code from
  complex UIs. It’ll update the right component when data changes and allow us
  to create fast and simple web application. First of all you’ve to install...
date: '2020-04-28'
thumb_img_path: /images/1_APxIYY2fRfOSXoOLWsNvPw.png
thumb_img_alt: create react app
content_img_path: /images/Polygon Luminary.svg
seo:
  title: Fox Village In Japan
  description: >-
    Apparently, Japan is covered in magical and irresistibly cute animal
    sanctuaries.
  extra:
    - name: 'og:type'
      value: article
      keyName: property
    - name: 'og:title'
      value: Fox Village In Japan
      keyName: property
    - name: 'og:description'
      value: >-
        Apparently, Japan is covered in magical and irresistibly cute animal
        sanctuaries.
      keyName: property
    - name: 'og:image'
      value: images/10.jpg
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Fox Village In Japan
    - name: 'twitter:description'
      value: >-
        Apparently, Japan is covered in magical and irresistibly cute animal
        sanctuaries.
    - name: 'twitter:image'
      value: images/10.jpg
      relativeUrl: true
layout: post
hide_header: false
---
React uses the javascript library to create efficient user interfaces of web applications in an effective way. It helps us to compose small pieces of code from complex UIs. It’ll update the right component when data changes and allow us to create fast and simple web applications.

First of all, you’ve to install “NodeJs”. If you don’t have “NodeJs” in your local machine then you should install it from [here](https://nodejs.org/en/download). You’ve to install the LTS Version of NodeJs according to the bit of your computer.

Now we are going to create react app…

> F
>
> *irst command: “**npx create-react-app first***
>
> \**-app***”*

                                 ![First command in vs code](https://preview--nazmus-simple-blog-14b6f.stackbit.dev/\_static/app-assets/images/1\_cJrTgmUdEdJAlvaESYnFuA.png)

It will take some time to install.

If you’ve previously installed “***create-react-app***” globally via “***npm install -g create-react-app***”, we recommend you uninstall the package using “***npm uninstall -g create-react-app***” to ensure that npx always uses the latest version.

[*“**npx***](https://medium.com/@maybekatz/introducing-npx-an-npm-package-runner-55f7d4bd282b)*” is a package runner tool that comes with np*m 5.2+ and higher. It is easier to work with updated versions for being \*competitive with browser and vs code.

“***create-react-app***” is the command to build the react app.

“***first-app***” is the command we where we’ve to be careful. This will be our app name so we’ve to choose a meaningful name here. Here we’ve used the “***first-app***” name to create our react app. Every time we want to create a react app we’ve to choose a name that is something related to our work that can express our goal.

                                      ![Vs code output in a terminal window](/images/2-da3c4231.png)

Here we can see in the terminal window that npx is downloading the necessary data to run react app.

                                      ![Vs code output in a terminal window](/images/3.png)

Here we can see react app installation complete message in the terminal window.

After installation, it will create a directory called “***first-app***” inside the current folder of your desired location.
Inside that directory, it will generate the initial project structure and install all the transitive dependencies.

Here we can see no configuration or complicated folder structures is there, just only the files you will need to build your app.
Now, you can open your directory as the installation is done.

```
                               ![File in react app directory](/images/4.png)

```

Here *node_modules* is full with many folders made by react developers. There are many webpack and babel preconfigured and hidden here. So you don't have to focus on this folder. As a beginner, you just ignore the folder and don't touch it.

                               !\[File in public folder]\(stackbit_asset_id:static:public/images/5.png)

The public folder contains the *index.html* file and fav icon for the website and other logos. If you want to change the fav icon you’ve to replace the fav icon here or

                               !\[index.html file]\(stackbit_asset_id:static:public/images/6.png)


you can change the code in vs code to get a new favicon.

As a developer, all your focus will be in* the src* folder. In this folder, you will put

                             !\[Src folder]\(stackbit_asset_id:static:public/images/7.png)

your app file is here. Here you can create a folder as your requirement, you can create a folder later you can import a file of the folder in the vs code.
                             

                             !\[Gitignor file]\(stackbit_asset_id:static:public/images/8.png)

Here we are going to discuss *the **.gitignor*** file. The file that we don’t wanna share in public or push in Github, will store here.

                            !\[Package.json file]\(stackbit_asset_id:static:public/images/9.png)

In the package.json file, we can see that the dependencies file will store in here. Web apps may require other dependencies than we have to install them, other dependencies files will also store in here.

After the first command, we’ve familiar with react app directory. Now we are going to command our code to launch the app.

> S
>
> *econd Command: “**cd first-app**”*

Here cd means change directory. We are going to change our directory to connect vs code to app file stored in the directory.



> *Third Command: “**npm start**”*

In this command, npm will launch the app. A new window will open in the browser. In vs code, we can see the successful compilation message.

                                           !\[Compiled successfully Message in vs code]\(stackbit_asset_id:static:public/images/10.png)


In the browser, we can see port: <http://localhost:3000/> which is launching our app.

                                            !\[React app in the browser]\(stackbit_asset_id:static:public/images/10.png)

Congratulation you’ve created your first react app.




