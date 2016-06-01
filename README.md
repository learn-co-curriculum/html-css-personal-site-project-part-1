# Personal Site Project - Part 1

## Objectives

1. Create a hello world page.
2. Publish to Github Pages.

## Instructions

Throughout this course you will build a personal website project adding to it each week. As you learn new skills you will implement them into your personal project to help memory retention and gain confidence that you can perform what you have learned. This process also allows you personal creative freedom to make whatever you want. In the past students have build portoflio sites, resume pages, sites celebrating a new baby or family pet. Wedding announcement sites, Sites for a friend, family, or your own business. Some have built sites for hobbies from fitness, gaming, to synth collections. Others have re-built non-profit sites or donation pages for charities. Whatever you choose to build it is entirely up to you. Most sites are under 5 pages and are fully responsive and viewable on any device.

1. In terminal create a new directory somewhere on your computer naming it with an easy to undertand title for your project `mkdir <your-project-name>` like mkdir jakes-portfolio-site or mkdir annes-jelly-bean-farm-site.

2. `cd <your-project-name>` into the directory for your site project, and `git init` to initialize and empty git repo.

3. Then `touch index.html` to create an index page and `touch README.md` to create a readme file.

4. Then `subl .` to open the folder in Sublime Text.

5. Double click README.md and type a quick description covering what your site will be about.

6. Double click on index.html to open it and then type `Hello World` into the page and save.

7. Next in Terminal `git add index.html README.md`, and `git commit -m "part 1"`.

8. In your browser go to Github and click the plus symbol in the top navigation and select New Repository. Name the Repository the same name as your folder name for the site like jakes-portfolio-site or whatever yours is called. then click create repository.

9. Copy either the ssh or https link of the repository on the next screen.

10. Back in Terminal inside the folder for your site project type `git remote add origin <paste in the link to your github remote repository you copied earlier here>`.

11. Then push your work up to Github using `git push -u origin master`.

12. Next, make a gh-pages branch `git co -b gh-pages` and press return, then `git push origin gh-pages` and press return.

13. Now head back to Github.com and click the gear icon under the page for this repository. Scroll down to Github pages and click the url, your live site should come up in the browser hosted on Github pages. 

<p class='util--hide'>View <a href='https://learn.co/lessons/html-css-personal-site-project-part-1'>HTML CSS Personal Site Project Part 1</a> on Learn.co and start learning to code for free.</p>
