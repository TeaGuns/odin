---
layout: post
title: "Changing Odin's Base Content"
date: 2019-11-05 08:44:38 -0400
category: customizing-odin
author: mac
short-description: Adding your brand name, links, etc
---

-----

*This article is a stub, more info coming soon. Some sections should be cleaned up.*

You can change virtually all of Odin's content from the `_config.yml` file. There are three things you cannot change from here, which need to be changed elsewhere - [colors](), [fonts](), and [categories](). Everything else is edited from this file.



##### Base Content

At the top of `_config.yml` you'll find a number of base settings you should change. These include your site title and description, as well as your brand logo and name. It also includes options to change the home page header and subheader.


##### Navigation Links
Out of the box, Odin supports 3 custom navigation links + a 'return home' button. Each link supports a name and a link. If you want to disable a link, just add `#` to both options for that link. 

The navigation button can be edited by changing the `nav_button` and `nav_button_link` options.

##### More Help Section

The more help section shows up under your list of categories on your homepage, as well as under each article. This section supports 0, 1 or 2 content blocks, which can be edited from the # More Help section of the `_config.yml` file. These sections are a great way to add links to your email, twitter, or other methods for users to reach you for support.

**help_one_title** - the header title for this section

**help_one_content** - the extended text for this help section. Works best if under 200 characters.

**help_one_button** - the text to show for the link in this help section

**help_one_link** - where the help section button should take users

##### Social Links

The social links section defines which social links show in the footer. By default Odin supports Instagram, Twitter, Facebook, LinkedIn, Email, and Github. Simply add the relevant social item to the right section, or add `#` if you don't want that social item to show in the footer.

----

After making any changes to the above, run `jekyll serve` to see the changes locally. If you're satisfied with your changes, run `jekyll build` and then push your changes to your repo.



