# Netlify
My Netlify sites

-----

## Why use GitHub/Netlify?

- GitHub, is used to store 'static' source codes    
  (you will see only just plain text files)  
   
- Netlify, is used to deploy web sites 'live'...;      
  so, that you can both 'view/interact' with that web site...;      
  simply, by typing in the site URL address into your web browser.  

Of course, you will need to sign up with both services in order to use them either alone/or else, in conjunction together.

-----

## 1> Netlify Deployment method: drag and drop - (uses only Netlify/and, no GitHub)   

After you've gone and signed up for a Netlify online a/c.; and, are already signed into the a/c. 

You simply 'drag and drop' a folder onto the Netlify user interface;   
and, your site/web page/s are, automatically, deployed (this process, usually, takes just merely seconds);    
you are, then, given a FREE URL address to go and view it.  

- https://paulramnora.netlify.com  

**NOTE:** It's possible to change the prefix name: 'paulramnora' part of the URL address by going into Netlify: [Settings] > Change name.  

-----

## 2> Netlify Deployment method: Netlify-cli - (uses only Netlify/and, no GitHub)     

First, create a folder by giving it a name:   

> NCTest  

Second, make sure to include an: [index.html] web page file inside of the named folder:   

> NCTest/index.html  

Now, run a DOS Command Prompt window inside of the named folder:  

> C:\NCTest>  

And, type in the following command...    

> C:\NCTest>npm i -g netlify-cli  

...this will set up Netlify-cli to run on your own computer operating system.  
You will be prompted to answer certain questions...;  
continue following each of the prompts through until the end.  

Eventually, you will be given a 'preview' web site to go and see;   
view this inside of your web browser if you wish.  
Finally, if you feel you are satisifed with what you see; then,...

> C:NCTest>npm deploy --prod

...will create the web site in full production.   
When done you will be given 2 Netlify web site URL's   
to both view/administer the site.  

- https://pr-netlify-cli-01.netlify.app/

-----

## 3> Netlify deployment method: Netlify/GitHub - (used in conjunction together)  

1. First, create inside of the GitHub folder directory you wish to link to an [index.html] file  
2. Next, sign in to Netlify/(you can use GitHub credentials to sign into the Netlify service)       
4. From inside of Netlify, select the GitHub folder (where you have your main web page [index.html] file)    
5. The Netlify service will next produce an internet URL 'link'...;               
   which displays your GitHub [index.html] file inside of your web browser.     

-----

## 4> Netlify CMS/Content Management System  

- https://www.netlifycms.org/  

-(This section is still to come...)- 

-----

**NOTE**: I only signed up for a FREE Netlify a/c.; with no special services added on.    
Netlify, also, has many other services including 'paid for'...such as, buying Domain Name/SSL/forms/-etc.;   
I still haven't actually checked out all that the Netlify service can do, yet...?  

-----

## Links...

GitHub, FREE personal web site hosting service/(can be used as an alternative to, Netlify)     
- http://www.github.io  

Netlify  
- http://www.netlify.com  

Netlify CMS/Content Management System    
- https://www.netlifycms.org/  

## YouTube Video Tutorials...

Launch Your FREE, Fast Website with Netlify - Step-by-Step Guide  
- https://www.youtube.com/watch?v=CSwoCvd4QIc&t=1806s  
(NOTE: The above video also teaches: Hugo/Markdown/Netlify/GitHub/GitBash/-etc.)  

Deploy Websites In Seconds With Netlify - (YouTube Channel: Brad Traversey)  
- https://www.youtube.com/watch?v=bjVUqvcCnxM  
(NOTE: The above video teaches: Netlify Forms/Netlify-CLI deployment/-etc.)  

