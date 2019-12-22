# Odin Knowledge Base

This is the Odin Jekyll template for the Commsor knowledge base. Please see the [official Jekyll docs](https://jekyllrb.com/docs/) for more info on running, building and editing a Jekyll site.

## Adding a new article

To add a new article, first duplicate the draft post file in the _drafts folder and place it in the _posts folder.

#### Front Matter

Next you'll want to update the front matter (the stuff at the top of the file) to match your article. 

**layout** - leave this as `post`

**title** - the title of your post, enclosed in ""

**date** - the date your're writing (or updating) the article, in YYYY-MM-DD HH-MM-SS format

**category** - options for category are `getting-started` `your-account` `memberships` `partner-club` `job-network` or `relay`. Must match an existing category exactly.

**category-name** - the plain English, with capitalization, name of the category. `"Partner Club"` for example

**author** - lowercase first name of the author of the post. Probably you

**short description** - 80 character or less short description of the article.

#### Content

Once you've properly filled out the front matter for your article, its time to write the article itself. Start writing below the ---- line, using markdown formatting. [See here](https://www.markdownguide.org/tools/jekyll/) for more info on markdown.

#### Deploying

After you're satisfied with your article and ready to put it live, run `jekyll build`, let the site compile, and then push it to this repo. It will automatically be deployed on GH Pages.



*If you have any questions, contact Mac on Slack*

*Feel free to make a pull request if you have thoughts on improving the overall theme itself!*


