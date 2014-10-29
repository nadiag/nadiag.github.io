# ePortolio template (GitHub option)

This ePortfolio template is for students looking for a quick, responsive layout. Students should just focus on developing content. This layout does not 

## Pre-requisites

- A GitHub account
- The GitHub client for your computer's operating system: [Windows](https://windows.github.com/) or [Macintosh](https://mac.github.com/)
- Working knowledge of markdown. You can start with this [tutorial](http://markdowntutorial.com/)


## Steps

1. Download and install your GitHub client
2. Log in to your GitHub account in your computer's client
2. Download this repository as .zip file to your computer (link on the right side of this text)
3. Locate the files in your computer
4. Rename the repository to `username.github.io,` where "username" is your GitHub user name.
4. Open the file `_config.yml` in your text editor: [Atom](https://atom.io/) or [Sublime Text](http://www.sublimetext.com/). 
5. Edit the values for `name:` and `author:`
 - `name:` should be the title of your ePortfolio. Keep it short to accommodate small screens 
 - `author:` should be your name ;-)
6. Save and close the file
    - Do not edit other fields unless you know what you're doing
7. Open and edit the project files! I have 4 sample `projectX.md` files. Open them and update as needed.
8. Respect the metadata for layout and title. Do not change the value for layout (it should always be "base"). Updated title to reflect your project's specific title.
9. Write your content in markdown with links to PDFs and images as needed (see "Linking to PDFs" section below).
10. Open the file `topics.yml` inside the `_data` folder.
11. For each project page you create, you will need a topic entry in `topics.yml`. The topic value should be a brief title for your page, and the filename is your project's file name with the extension ".md" (markdown) updated to ".html"
12. Open and edit the file `index.md` to create your ePortfolio's home page.
13. Go back to your GitHub client and open the `changes` tab
14. Drag and drop your repository's folder from your computer to your Github client.
12. Commit your changes. Commit whenever you make any changes! 
13. Enter a brief summary to each commit and an optional description
13. Wait some good 10 minutes and then go to `http://username.github.io`. Your fancy ePortfolio should be there (only this initial commit takes about 10 minutes. All additional updates should be pretty fast).

## Linking to PDFs

You can include PDF samples in the `samples` folder... duh! Look at my example in the `project1.md` file. The syntax for a PDF link should look like this:

>This is [my PDF](samples/file.pdf)

Don't forget to copy your actual PDFs to the `samples` folder. Use only lowercase in your file names and avoid blank spaces. `ditaproject.pdf` is good. `DITA project.pdf` is not.

## Customizing the template's look

Inside the `_layouts` folder there's a file named `base.html`. That's the heart of this template. **Touch it only if you know what you're doing!** 

The easiest way to customize the colors is to replace the external CSS link on line 11. Feel free to replace it with one of the color palettes from [Bootswatch](http://www.bootstrapcdn.com/#bootswatch_tab).

Need more customization? Then you probably shouldn't use a template ;-)
