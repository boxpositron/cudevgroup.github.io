# Covenant University Developers' Community (CDC) website
Hi guys! This is the repository for CDC's website at https://cudevgroup.github.io. The site contains information about CDC (who we are, what we do and hope to accomplish, how to be part of us etc) as well as links to important places like our Medium publication and GitHub organization. It also houses the profiles of our members i.e every CDC member should have a profile page at `/members/YOUR-FULL-NAME/index.html`.

## Pages
- [ ] Home page (index.html)
- [ ] About page (about.html)
- [ ] Contact page (contact.html)
- [ ] Join CDC page (join.html)
- [ ] Members page (members.html)

## Color Pallete
*Coming thru' in a bit...*

## How to contribute
Follow our [Git workflow](https://github.com/cudevgroup/git-workflow-tutorial) to contribute to this repository. Check for issues on the issues tab and register your interest with a comment if you want to work on any of them. If no one is currently working on the issue, you'll be assigned to it. When you're done, open a Pull Request (PR). It would be reviewed then merged.

If you find a bug on the site, you can go to the issues tab to start a new issue. Describe the current behaviour, expected behaviour and the steps to reproduce the problem. If you want a feature to be added to the site, move over to our `#open_source_ideas` channel on Slack and share your thoughts. We'll all discuss and decide whether to add the feature or not.

## Setup
To setup this project on your PC, clone your fork of the repository with `git clone https://github.com/YOUR-USERNAME/cudevgroup.github.io.git`. Once the project is downloaded, you can open the HTML files in a browser and view the content of the files in your favourite text editor.

## Member profiles
All CDC members are expected to create profile pages for themselves at `/members/YOUR-FULL-NAME/index.html`. Here are a few guidelines to help:
- Take a look at Jon Skeet's profile (`/members/Jon-Skeet/index.html`) to get an idea of how your profile should be like. You can also take a look at the profiles of other members to get some inspiration.
- Create a folder in the `members/` folder called `YOUR-FULL-NAME/` e.g `Jon-Skeet/`. Add the following files to the folder: `index.html`, `script.js`, `style.css` and a profile photo e.g *jon-skeet.jpg*. The photo should not be too large in size (<=1mb). Additional photos should be uploaded elsewhere and included on your page via external links.
- You must use our colour pallete for your page (so that the whole site looks and feels cohesive).
- All CSS and JavaScript libraries, and fonts should be accessed by your page using external links. For instance, if you wish to use Bootstrap in your page, use the CDN link to include it. Don't download it and add the files to the project.
- Your profile must have the CDC logo and a "back to members page" link at the top of the page.
- You don't need to be assigned to your profile page. Everyone is responsible for their page. Whenever you create/update your page, create a PR, indicating in the title that you worked on your page e.g "Created my profile page" or "Fixed broken links on my profile page".