# atmosalex.github.io

***

## Creating a Website to show your Final Project

### Copy this site as a template
1.  Create [a GitHub account](https://github.com/)
2.	Create a new GitHub repository with the name **user.github.io**, where **user** is your GitHub username as shown below. Select *public* and do not tick *Add a README file*. [![screenshot][1]][1]
3.	From your new repository, you should see a *Quick setup* guide. Scroll down to the bottom of the page and click *Import code*, as shown: [![screenshot][2]][2]
4.	In the box that says *Your old repository’s clone URL*, copy and paste this URL: `https://github.com/atmosalex/atmosalex.github.io/`, then hit enter.
5.	Go to the *Settings* tab, then click *Pages* (under *Code and automation*), and check that the *Build and deployment* section looks like this: [![screenshot][3]][3]
6.	Go to the *Actions* tab and check that the build and deployment action has finished. Once it has, navigate to user.github.io to see your site, which should be a copy of this one!

[1]: /assets/IMG/instr_create.png
[2]: /assets/IMG/instr_import.png
[3]: /assets/IMG/instr_bd.png

### Change the theme (optional)
1.	Choose your favourite theme [from this page](https://pages.github.com/themes/)
2.	Open `_config.yml` and replace `theme: jekyll-theme-minimal` with `theme: jekyll-theme-name` where `name` is the name of the theme from the above list

### Change your site logo (optional)
1. In your repository, upload a logo or profile picture to the `assets/IMG/` directory
2. Open `_config.yml` and modify the line `logo: /assets/IMG/template_IMG.png` to point to your new image

### Adding content
* The `README.md` file acts like your home page. Replace its contents with whatever you want the world to see.
* You can create other markdown files (.md) in your repository and navigate to them from this page using links, i.e.: [here is a link to `project.md`](project.md)
* Check a [guide to writing Markdown](https://www.markdownguide.org/basic-syntax/), or ask [ChatGPT](https://chat.openai.com/) for help.
* When writing in a markdown file, it is useful to wrap text by selecting the *Soft wrap* option as shown: [![screenshot][4]][4]
  
[4]: /assets/IMG/instr_wrap.png

***

## Including a link to your project from this page

Your final report will be hosted on your own website. You have various options to do this:
* One option is to write the whole report in markdown, then include it as a page on the site. To get you started with this, here is a template file to modify: [`project.md`](project.md).
* Another option is to write the report using a word processor or Latex, then export it as a .pdf file. Upload the .pdf file to the `assets` directory, and link to it [like so](/assets/project_demo.pdf).
