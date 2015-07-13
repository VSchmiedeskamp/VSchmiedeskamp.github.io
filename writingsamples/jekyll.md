---
layout: post
title: Blogging with Jekyll and Github
---

# Narrative Statement

The following document is an introduction to Jekyll, a static-site generator. It is the first in a series about how to build and maintain a Jekyll site.

Much of the existing introductory documentation moves straight into the “how” of using Jekyll, often in technical terms. This article aims to help novice website builders conceptualize the “what” and “why” of Jekyll without getting bogged down in the “how.” It introduces and explains the relationship between Jekyll, Git, and GitHub in general terms, providing the context for how these can be used to publish content to the web.

# Introduction: or, “I have a project and some code. Now I want to write about it.” 

Professionals of all stripes increasingly share projects on public-facing blogs. Most developers, data analysts, and scientists want a way to share their projects using a familiar set of tools and services.

If you use, write, or edit code as a part of your project work, you probably use GitHub. You may also be looking for a blogging tool that helps you with the following tasks:

* write posts in your favorite text editor
* blog collaboratively with teammates
* track changes to files on your blog, especially for blogs with frequent updates or multiple contributors
* customize the layout of the site to match your team, company, or group’s look

This article introduces Jekyll, a static site generator, and explains why it is a good fit for writers who already use GitHub and want to share the results of their project work.


# Jekyll, Git, and GitHub: or, “What’s on the menu?”

**Jekyll** is a piece of software that converts text files into a website. This helps writers take the text they’ve already written and convert it into a webpage for public display. 

Jekyll is a bit different from other site or blog generators such as Wordpress or Tumblr in that it will convert text into a **static set of pages**. These static pages don’t have a lot of extras such as editable text boxes or interactive elements; the text is simply displayed for reading, no bells and whistles. This makes hosting the site a little simpler as well as more maintainable, secure, and scaleable.

Jekyll pages are easily hosted on a site called **GitHub**. This website is frequently used by developers, data analysts, and scientists to post, share, and collaborate on projects. It uses a version control system called Git to track changes to files stored on GitHub. Have you ever collaborated on a document with someone, only to pass it back and forth, wondering all the while if you were looking at the most up-to-date version of that document? Git tracks changes made to any document and records who made the changes to that version of the file. When writing with a team, changes made by multiple authors working at the same time can be merged. Since Git tracks changes made to a given file, users can access or restore all previous versions of that document. Nothing can get lost in the shuffle.

Let’s see what this looks like in action. 


# Version control in action: or, “Wait, did I already send this to you?”
 
Jeffrey is working on a project with a small team. The project has a lot of pieces to it and he’s proud of the work his group has produced. Jeffrey wants to publish the results of the project online in a format that other departments in his organization can easily understand. A team blog is the perfect format for writing up the results of his team’s work as it progresses.

Jeffrey’s team uses GitHub to organize data files, store code to analyze results, and write up their observations. Anyone on Jeffrey's team can edit files in the shared repository. 


Figure 1 shows how Git interacts with files within a repository. When a user clones a repository, Git creates a copy in a directory on the user’s computer. The user can work with any file in this directory and make edits. Changes can committed and then pushed back to the cloud for everyone else to see. With every committed set of changes, Git records the person responsible for the change as well as other information about the edits. Git can even show just the portion of text that changed between committed revisions.

![Revision control overview](/assets/img/git-committing.svg "Figure 1--How Git controls updates
(Source: software-carpentry.org)")

In this way, GitHub helps Jeffrey and his team keep track of who is making changes to the team’s files and allows everyone to easily find the most recent version of any given file. Team members can safely work on any file at the same time as changes can typically be automatically merged.

# How Git and Jekyll work together with GitHub Pages

A Jekyll-generated site can be hosted using GitHub, and updates can be managed using Git. Storing a website in Git and hosting the rendered site on GitHub is simple. The source code of a Jekyll site is a collection of various scripts and other text files.

GitHub looks for repositories containing Jekyll websites that are named like [yourusername].github.io, and will automatically convert the content into a finished website. For example, Jeffrey’s organizational github account “ultrabean” would have a repository containing his Jekyll site called “ultrabean.github.io,” and the site would be viewable on the web at http://ultrabean.github.io.

Changes to the Jekyll source files can be made by any team member with access to the ultrabean.github.io repository. Once changes are committed and then pushed to GitHub, the website will be automatically regenerated and republished.


# The takeaway

Jekyll allows authors to create and quickly update websites using source files stored on GitHub. Those files contain content and information that control the layout and design of the Jekyll page. Anyone with access to a GitHub repository a Jekyll site can make changes to the content. These sites are simple, maintainable, secure, and scaleable. 

# Next Steps: getting started with GitHub and Jekyll

Creating a blog with Jekyll requires a few specialized tools:

**Operating systems:** Windows, Mac, or Linux operating systems 
**Text editor:** Notepad, TextEdit, Vim, or similar text editor
**Applications:** Ruby and Ruby Gems (both free to download)

Ready to give it a try? Set up your [GitHub profile](https://github.com/) and [download Jekyll](http://jekyllrb.com/docs/quickstart/).
