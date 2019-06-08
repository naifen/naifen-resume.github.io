---
toc: true
toc_label: "Table of Contents"
toc_icon: "file-alt"
layout: single
title:  "Interact With Google Tasks With a Rails Stimulusjs Web App"
date:   2019-01-18 20:18:33 -0700
categories: ruby rails stimulus google-apo service-object
---
# Intro
A Rails 5 App to connect to Google Tasks with google-api ruby gem.
Frontend build with Stimulus.js and bulma.io, completely replace
sprockets with webpack for assets management. Utilizing Redis to store
user credentials returned from Google Api requests for later use.

## Demo

### Live Demo

### Screenshots

![get-cred](/assets/images/google-api-get-cred.gif){:height="576px" width="288px"}
![auth](/assets/images/google-api-auth.gif){:height="576px" width="288px"}
![list Google Tasks](/assets/images/google-taskslist.png){:height="296px" width="214px"}

## What I've learned

### * How to get rid of sprockets and replace it with webpack.

Webpack is going to be the new default assets manangment tool in up
coming rails 6. We can use Webpack to manage both your javascript,
css and images. Use foreman to fire up server and compile assets with a
Procfile works like a charm.

### * How to combine authlogic with pundit.

User sessions management with authlogic gem, user authorization using pundit.
Devise is more popular user authentication solution in Rails community,
it's easy to setup and running but always take a lot more efforts when
it comes to customization(which I've had a bad time with)

### * How to use Google API gem in a rails app to access Google Tasks.

### * How to create frontend using Stimulus.js with Typescript.
