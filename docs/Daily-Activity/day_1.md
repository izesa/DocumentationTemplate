# 1. Activity of Day 1

## Summary

for the first Day, 
## 1. introduction to modeling and Fabrication.
 Foundation of modeling and Fabrication, why modeling and fabrication Matters, design-to-fabrication steps or cintinuum which are Design, Model, Prototype, Fabricate and Evaluate. Digital Fabrication Paradigms like Hybrid Fabrication Paradigm where it combines Subtractive and Addictive Fabrication paradigms. 

 ## 2. Activity 1: Building Documentation website using MkDocs Materials.
## 1. Install Prerequisites
• Install Python version 3.8 or later.
• Install MkDocs and the Material theme using pip.
"pip install mkdocs mkdocs-material"

## 2. Create a New MkDocs Project
Create a new documentation project and move into the project directory.
mkdocs new my-docs
"cd my-docs"

## 3. Enable the Material Theme
Edit the mkdocs.yml configuration file to enable the Material theme.
"site_name: Project Documentation
theme:
 name: material"

## 4. Write Documentation Content
• All documentation pages are written in Markdown.
• Place Markdown files inside the docs/ directory.
docs/
 index.md
 introduction.md
 hardware.md
 software.md

## 5. Configure Navigation
Define site navigation in mkdocs.yml to organize pages.
nav:
 - Home: index.md
 - Introduction: introduction.md
 - Hardware Design: hardware.md
 - Software Design: software.md

## 6. Preview the Website Locally
Run the development server to preview changes in real time.
"mkdocs serve"

## 7. Enable Material Features (Optional)
features:

 - navigation.tabs
 - navigation.top
 - search.suggest
 - content.code.copy
## 8. Add Recommended Markdown Extensions
markdown_extensions:

 - admonition
 - toc:
 permalink: true
 - pymdownx.superfences
 - pymdownx.highlight

## 9. Build the Static Website
Generate the static site files.
"mkdocs build"

## 10. Deploy the Documentation Website
• Deploy to GitHub Pages using MkDocs built-in support.
• Alternatively deploy to Netlify, Vercel, or a local server.
"mkdocs gh-deploy"




## Takehome 

to be Able to create a website page via Github Page that documents every activity done in every work performed during this Lessons.




