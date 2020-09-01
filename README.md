This is a starter template for [Learn Next.js](https://nextjs.org/learn).


# Notes about my experience

## This is my first experience running a dev server on my computer to execute a .js based webapp.

It is now being hosted [here](http://localhost:3000)

What are the implications?

I guess if I did this and executed bad code i could potentially fuck up my system.  That's not the case if you ran it in a container, like on a **remote dev server!!**

**So the development server continues to run at http://localhost:3000 until I go back to the terminal and press ```ctrl + c```.  It will ask 
whether or not I want to terminate batch job, and I type "y" and enter.  At that point it goes back go command line mode and http://localhost:3000 disconnects and stops loading anything**

So...

**Go to terminal and type ``` ctrl + c ``` to terminate the server.

Also, every time it compiles again, the server also checks the code and makes sure the syntax is correct.
I typed in a standard "&lt;br&gt;" for a line break, and it doesn't work because I didn't have an end tag.  So I had to write in the ```<br />```

#### Since this directory is backed up automatically by OneDrive, I don't have to worry.  I could potentially use local Git to do the same job as GitHub, just without the collaboration features.
Right now as we speak, there is another starter Next.js template already ***deployed*** over at Vercel.  The only problem is, I cloned the repository from GitHub, and by default they don't have the other stuff that npm installs, or the run or dev function, so I tried to run it and it didn't work.
I then found this suggestion right off the Next.js website, and they had a template that was available directly from npm.  So now I have a working development environment here on my local pc, and then we have a remote deployed dev site that I had no clue how to run the development server remotely.  Like, they make it so easy to deploy a site straight from the Vercel website, but then what do you do after that if you want to edit locally?  Because all the npm stuff was not included in the new GitHub repository created by Vercel.

## This Git repo was created by npm.

