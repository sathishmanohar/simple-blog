Simple blog
===========

A simple rails blog engine

## Why?
I'm not happy with the blogging solutions I've found online. So, I'm building my own.

---

# Desired Features

## Content Creation Flow

### Post types

#### Hybrid Post
Hybrid post is a type of post that can encompass any kind of data within it like text, images, image gallery, video or video playlist.

#### Image Post
A single image takes the center stage, with commentary and meta data that can be viewed if needed.

#### Image Gallery
A set of images with cover photo and gallery description, individual images have all the attributes available for the single image post

#### Video Post
A single video takes the center stage, with commentary and meta data that can be viewed if needed.

#### Video Playlist
A set of videos with cover photo and playlist description, individual videos have all the attributes available for the single video post

#### Audio Post
A single audio takes the center stage, with commentary and meta data that can be viewed if needed.

#### Audio Playlist
A set of audios with cover photo and playlist description, individual audios have all the attributes available for the single audio post

#### Link Post
A single link takes the center stage, with optional commentary.

#### Link List Post (if it makes sense)
A set of links with cover photo and list description, individual links have all the attributes available for the single link post

##### Each post type:
* can be Created Edited Published or Destroyed
* can belong to many categories
* can be a draft (private work in progress) or public(published)
* should have a published date

##### Good to have
* Revision History
* Multi Author Login
* Static Site Generation

# User Flow

### Navigation
* Article list
* Category list
* Article list by type
* Article list by category
* Article list by type and category
* Article Page
* Archives by date

#### Good to have
* Published revision history
* Author articles List if multiple authors
