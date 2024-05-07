# BYUI DS Portfolio Template
## Building a Quarto Portfolo

A template for a portfolio developed with Quarto and hosted on GitHub.

This is all configured so you only need to edit the source files in Quarto (.qmd). The website is generated and hosted automatically by GitHub.

## Using this template

1. Click on green button `Use this Tempalte` -> `Create a new Repo`  
![](/Images/use_this_template.png){width=150}

1. Select `Owner` as `byui-math-dept`  
![](/Images/owner.png){width=500}

1. Name for your repository as your GitHub profile name + '_' +  1st semester  and year  
(example `chaz-clark_fa23`)  

1. Select `Private` as the type of Repo, then click `Create Repository`  
![](/Images/private.png){width=500}

1. Once your repo is created, go into the `settings` and click on the `pages`  
![](/Images/settings.png){width=500}

    ![](/Images/pages.png){width=500}

1. Set the `Branch` section of `Build and Deployment` to `main` and `/docs` then click `save`  
![](/Images/main_docs.png){width=500}

1. Navigate back to `<> Code` and click the green button `<> Code` and select `Open with GitHub Desktop`  
![](/Images/open_in_desktop.png){width=400}

1. Remember to update the names and links in the `_quarto.yml`, replacing every instance 'your_name'

1. The first time you publish to your repo, open a terminal in VS Code and use this command `quarto render`

1. Once `quarto render` has completed you can use GitHub Desktop to `commit` and `push` changes back to GitHub

1. To find your site URL, click the `View on GitHub` button on GitHub Desktop
    a. Navigate back to `Settings` and `Pages`
    a. Your URL will be in the `GitHub Pages` Section
    a. Note: each time you `render` and `push` your changes to GitHub this URL will change  
    ![](/Images/url.png){width=500}
