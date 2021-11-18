# Deploy your Github Page Website
(This repo is part of lecture "CS50's Web Programming with Python and JavaScript 2020": <a href="https://www.youtube.com/watch?v=NcoBAfJ6l2Q">Git - Lecture 1<a>)

Let's learn to deploy static website on your github repo

## 1. Create repo for hosting your files. Name it {username}.github.io. Convention name like this will automatically support Github Pages. 
Note that you if you want to name your repo differently, you might need to setup some more, reference for <a href="https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site">this resources<a>.
My repo is "Elstargo00.github.io"

## 2. Then git clone that repo into your working directory. I'll clone it via ssh protocal:

``` 
cd project_dir
git clone git@github.com:Elstargo00/Elstargo00.github.io.git
cd Elstargo00.github.io.git
```

for your case:

```
git clone git@github.com:{username}/{username}.github.io.git
cd {username}.github.io.git
```

## 3. Now start working on your local. Create your customize "index.html", for example:

```HTML
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title>My Github Pages</title>
  </head>
  <body>
    <h1 style="color: green;"">Welcome to my Github page :)</h1>
  </body>
</html>
```

Note that it need to be named as index.html

## 4. Add and commit changes and push the code back to the repo

```
git add index.html
git commit -m "first commit" -m "first commit for github page website"
git push
```

## 5. Now go to Setting > Pages.

<img width="700px" src="https://raw.githubusercontent.com/Elstargo00/Elstargo00.github.io/master/setting_pages.png">
                                                                                                    
And your site is ready to go:
                                                                                                    
                                                                                                    
<img width="700px" src="https://raw.githubusercontent.com/Elstargo00/Elstargo00.github.io/master/page_example.png">
