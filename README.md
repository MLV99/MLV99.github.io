# Hi, my name is Mileisha L. Velázquez - Welcome to my website! 

I've developed a website for creating and sharing both personal and research data, all of which is possible through coding within the R programming language.  

Feel free to explore the page and learn more about me and my work as a master's graduate student in the Marine Sciences department at the University of Puerto Rico - Mayagüez Campus. 

## What you may find: 

Sections include: 

- About me
- View and download my  Curriculum Vitae
- View most recent data using R
- Direct access to my Linkedin  and Github profile 
- Email for contact 

<<<<<<< HEAD
Access my page [here](https://mlv99.github.io/index.html)
=======
- Make sure that you have enabled Git in RStudio. More information can be found [there](https://privefl.github.io/advr38book/good-practices.html#git).

- You need a GitHub account.

### Make the first version of your website

- Fork this repo (top-right) and **rename it to be 'YOURGITHUB.github.io'** (in Settings of your brand new repo). Replace 'YOURGITHUB' by your GitHub username (case sensitive).

- Get the link from cloning the repo. Use the green button "Clone" and make sure you use SSH, not HTTPS. Then, go to RStudio, create a New Project > Version Control > Git and copy this link. You have cloned your new repo as an R project.

- Build the website by running `rmarkdown::render_site(encoding = "UTF-8")` or just `Ctrl/Cmd + Shift + B`.

- Commit and push all new files from RStudio. The first time you build the website, there is a full directory, `site_libs/`, that is created. Trying to add all the files from this directory to a commit can make RStudio freeze. If it happens, restart RStudio, and run `rm .git/index.lock` in the linux terminal of RStudio. Then run `git add .` in the terminal as well; this will add all the new files for you to commit (you can see all the added files in the Git panel after refreshing it).

- Go see your new website at https://YOURGITHUB.github.io/index.html.

### Change the content of your website

- Modify `_site.yml`, `index.Rmd`, `about.Rmd`, `cv.Rmd` and `CV.pdf` with your own content.

- Build your website again. At any moment, you can preview your website locally, by rendering your site and viewing any of your local html file in your Web Browser. 

- Commit and push everything from RStudio.

- Go see your new website with your own content at https://YOURGITHUB.github.io/.

### The blog part

For now, the 'Blog' link is giving a 404 page. 

If you want to add a static blog to your webpage, go [there](https://github.com/privefl/jekyll-now-r-template).
If you don't, just remove the corresponding 3 lines from `_site.yml`.

## Two examples

You can see for example 
- [my own website](https://privefl.github.io/),

- [the website of the R user group in Grenoble](https://r-in-grenoble.github.io/).

## Conclusion

As a reminder, most credit goes to RStudio/Posit (thanks also to [GitHub pages](https://pages.github.com/)). I just made some minor modifications and made a tuto about how to use all this together.

If anything is not clear enough, feel free to open an issue in this repo.
If it is an issue only related with R Markdown, you'll find a better answer posting your issue [there](https://github.com/rstudio/rmarkdown).
>>>>>>> 9a69b8df2ae49b3b33d6f2e12e43de814a7e8a5c
