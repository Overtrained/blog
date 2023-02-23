# On-Site Presentation 2023-02-23

# Machine Mindset: A communication platform for Data Practitioners

## Authors:

- Ajayi, Moyo
- McNew, Coy

# 🎆How a Reflections Page will be Useful

- To assist in creating the visibility of the Data Science team, Coy and I thought we would start a team blog, or as we call it, a reflections page
- Other data science teams have used blogs and reflections pages to communicate their completed projects and highlight
    - Example blog: Uber
        
        [Data / ML | Uber Blog](https://www.uber.com/blog/engineering/data/)
        

# ✅ What type of content?

- Technical explanations
    - Rome was not built in a day, lay the groundwork here for building bridges to success 🛠️
    - These types of posts will require the writer to:
        1. Establish a data-related topic (e.g., “Evaluating a binary classification model”)
        2. Demonstrate what you will teach regarding the topic (e.g., “Use benchmark data to build a model prototype and then execute various strategies to evaluate its fit”)
        3. Provide code and graphic examples where appropriate to help the reader understand 1. and 2.
        4. Summarize demonstration
- Documentation or Reference
    - Just finished a difficult task and want to leave breadcrumbs for the next person? Write a helpful post 🖥️
    - These types of posts will require the writer to:
        1. Identify general topic or piece of established code
        2. Illustrate the key principles behind the use case for the topic or codei
        3. Provide either further context behind the use case or a step-by-step description on how to use the reference or code
- Extracurricular Activities
    - Data practitioners like to have fun too. This is a good way to share the joy ☀️
    - These types of posts will require the writer to:
        - Highlight the people and place(s) where the fun took place
        - Provide a brief motivation and narrative of the event
        - Supply context on how this experience was related to growth or how the time away from the computer was refreshing
        - Team outings, conferences, and fun trips would all be applicable here
- Job Posting
    - Instead of the wrote and plain Workday job post, we can make something flashier and more attractive on our site 🧑‍💻
    - These types of posts will require to:
        - Identify a current open role for the team
        - Draft a relevant job but creative job description
        - Embed related projects and/or other posts that would entice an enthusiastic candidate to apply

# 🌐 Blog Version 1.0

- Open source
- Publicly hosted
- Not officially affiliated with Bridgestone

[Home](https://machinemindset.netlify.app)

# 🤔 How to contribute

- Join the [organization on GitHub](https://github.com/Overtrained)
    
    [Overtrained](https://github.com/Overtrained)
    
- Clone or add remote to blog repo
- 

[GitHub - Overtrained/blog: This is the repo for the blog Machine Mindset](https://github.com/Overtrained/blog)

- Create a branch for your new post
- Add a post in .md under the _posts directory.  There are many example posts under the _examples directory
- Once your post is finished, submit a pull request into main
- A preview page will automatically be deployed
- Automatic build checks
- Review required before merging into main

# 👨🏽‍💻 Static Site Development Resources

- Static website developed in Jekyll
    - [Jekyll](https://github.com/jekyll/jekyll) is a static site generator written in Ruby
    - Local dev includes making changes and/or adding content and serving site locally
- [Quickstart](https://jekyllrb.com/docs/)
    - [Install prerequisites](https://jekyllrb.com/docs/installation/)
        - Ruby ≥ 2.5.0
        - [RubyGems](https://rubygems.org/pages/download)
        - [GCC](https://gcc.gnu.org/install/) and [Make](https://www.gnu.org/software/make/)
    - Bundle gems:
    
    ```bash
    gem install jekyll bundler
    ```
    
    - Create a new site
    
    ```bash
    jekyll new my-site
    ```
    
    - Navigate into site directory
    - Serve site locally
    
    ```bash
    bundle exec jekyll serve
    ```