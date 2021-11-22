# HTML & CSS workshop 2: My Own Live Webpage project

You will build your webpage and get it live on github

## Create a Github account (skip if you already have one)

Follow the instructions from `Part 1: Configuring your GitHub account` [here](https://docs.github.com/en/get-started/onboarding/getting-started-with-your-github-account)

## Create your live webpage

### Create a repository

Head over to GitHub and create a new public repository named username.github.io, where username is your username (or organization name) on GitHub.

If the first part of the repository doesn’t exactly match your username, it won’t work, so make sure to get it right.

### Clone the repository

Go to the folder where you want to store your project, and clone the new repository. Run this command in your terminal:

```
git clone https://github.com/username/username.github.io
```

### Add index.html

Enter the project folder and add an index.html file:

```
cd username.github.io
echo "Hello World" > index.html
```

### Push your changes

Add, commit, and push your changes by running the below commands in your terminal:

```
git add --all
git commit -m "Initial commit"
git push -u origin main
```

### Check your webpage is live

Open a browser and go to https://username.github.io.

### Add information about yourself to the page

Add the below content to your index.html file changing `Tania` with your name:

````
<!DOCTYPE html>
<html lang="en">
    <head></head>
    <body>
        <p>Hello World! It's me, Tania</p>
    </body>
</html>
````
Save the file.

Add, commit, and push your changes:

```
git add --all
git commit -m "Initial commit"
git push -u origin main
```

When you go to go to https://username.github.io and refresh the page, you will see the `Hello World` message you added before.

### Add more details!

Use the content of index.html file from the [previous workshop](https://github.com/coding-sisterhood/html-css-workshop/blob/main/README.md) as an inspiration for building you webpage.

Below are some html templates you can use as an example for your web page:

- [Resume template](https://www.w3schools.com/w3css/tryit.asp?filename=tryw3css_templates_cv&stacked=h)
- [Blog template](https://www.w3schools.com/w3css/tryit.asp?filename=tryw3css_templates_blog&stacked=h)
