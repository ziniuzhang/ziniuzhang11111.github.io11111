# Take notes about how to set up my personal website

Actually, I use the template on the github. It seems that you can folk others repository. But this method doesn't work in my case. So I download other's template and then add name to my repository.

---

**Remember that the repository must be named as 'yourusername.github.io'**

When you have prepared your repository, just wait for a few minutes. Github needs time to parse your project.

If you want to change the picture on the head of the website(mine is a cat), you need first transfer your ```.jpg``` picture to ```.ico``` type.

Then open ```_includes/head.html``` and add following commands. Here the ```favicon.ico``` is your picture.
```
<link rel="shortcut icon" href="/favicon.ico" type="image/x-icon">
<link rel="icon" href="/favicon.ico"type="image/x-icon">
```
