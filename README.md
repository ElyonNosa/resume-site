# Hosting a Resume Using Markdown, Git, and a Static Site Generator

## Purpose

This README explains how to create and host a resume as a static website
using Markdown, Git, a static site generator, and a code hosting
platform. The goal is to demonstrate how modern technical documentation
tools can be used to publish simple and maintainable content on the web.

This guide is written for anyone who has basic familiarity with
Markdown and simple command-line operations but has not previously
worked with Git, static site generators, or online code hosting
platforms (also known as forges). By following these instructions,
you should be able to create a repository, format a resume using
Markdown, generate a static website, and publish it online.

The approach used here reflects several principles described in *Modern
Technical Writing* by Andrew Etter. Etter emphasizes writing
documentation in lightweight formats, storing documentation in version
control systems, and publishing documentation using automated tools.
These practices improve maintainability, accessibility, and
collaboration.

------------------------------------------------------------------------

## Prerequisites

Before starting, make sure you have the following:

-   A computer with a command line interface
-   Basic knowledge of navigating directories in the terminal
-   Git installed on your computer
-   A GitHub account
-   A text editor capable of editing Markdown files
-   An internet connection

These prerequisites follow Etter's recommendation to use simple and
widely supported tools. Using plain text formats such as Markdown
ensures documentation can be edited easily and remain portable across
systems.

------------------------------------------------------------------------

## Instructions

### 1. Install Git

Download and install Git from the official Git website.

Git is a distributed version control system that tracks changes to files
and allows collaboration. Etter recommends storing documentation in
version control systems because it makes documentation easier to
maintain and update.

------------------------------------------------------------------------

### 2. Create a repository on GitHub

Log in to your GitHub account and create a new repository.

A repository stores your project files and their revision history.
Hosting documentation in a repository allows it to be shared and updated
efficiently.

------------------------------------------------------------------------

### 3. Clone the repository to your computer

Open your terminal and run:

    git clone https://github.com/yourusername/resume-site.git

Cloning downloads the repository from GitHub to your local machine so
you can edit the files locally.

------------------------------------------------------------------------

### 4. Create a Markdown resume

Create a file named `resume.md`.

Write your resume using Markdown formatting.

Example structure:

    # Your Name

    ## Education
    Bachelor of Computer Science  
    University of Manitoba

    ## Skills
    - Python
    - Java
    - Git
    - JavaScript

    ## Experience
    Research Assistant – University of Manitoba

Markdown is a lightweight markup language. Etter recommends using
lightweight markup languages because they allow writers to focus on
content rather than complex formatting.

------------------------------------------------------------------------

### 5. Install a static site generator

Install a static site generator such as Jekyll.

Static site generators convert Markdown files into HTML automatically.
This allows documentation to be written in simple text while still
producing a professional website.

------------------------------------------------------------------------

### 6. Add your resume to the website content

Place your `resume.md` file inside your project content directory.

Static site generators process Markdown files and convert them into
formatted web pages.

This reflects Etter's recommendation to separate content from
presentation.

------------------------------------------------------------------------

### 7. Build the website

Run the build command:

    jekyll build

This command converts Markdown files into HTML pages that can be viewed
in a web browser.

Automation reduces manual work and ensures consistency when publishing
documentation.

------------------------------------------------------------------------

### 8. Commit your changes

Run the following commands:

    git add .
    git commit -m "Add resume and site files"

Committing creates a snapshot of your project files. Version control
makes it possible to track changes and revert to earlier versions if
necessary.

------------------------------------------------------------------------

### 9. Push your changes to GitHub

Upload your changes:

    git push origin main

Pushing sends your local changes to the online repository so they are
stored remotely.

Hosting documentation online improves accessibility and collaboration.

------------------------------------------------------------------------

### 10. Enable static website hosting

Enable GitHub Pages in the repository settings.

GitHub Pages automatically publishes the static website and provides a
public URL where your resume can be viewed.

This automated publishing process follows Etter's recommendation to
simplify documentation workflows.

------------------------------------------------------------------------

## Further Resources

Markdown tutorial\
https://www.markdownguide.org

Git documentation\
https://git-scm.com/docs

GitHub documentation\
https://docs.github.com

Jekyll documentation\
https://jekyllrb.com/docs

------------------------------------------------------------------------

## FAQ

### Why use Markdown instead of HTML?

Markdown is simpler and easier to read than raw HTML. The syntax is
minimal and allows writers to focus on the content itself. According to
Etter, lightweight markup languages improve documentation
maintainability.

### I changed my resume but the website did not update. Why?

Static websites must be rebuilt after changes are made. After modifying
your Markdown file, you must commit the changes and push them to the
repository so the updated version can be published.

------------------------------------------------------------------------

## Credits

Author\
Elyon Nosa-Aifesehi

Peer Review Contributors\
Michael Yan
Liam McCausland

Static Site Generator\
Jekyll

Hosting Platform\
GitHub Pages
