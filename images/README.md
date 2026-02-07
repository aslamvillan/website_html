# Image Organization Guide

Place your images in the following folders:

## Folder Structure

```
public/
  images/
    hero/          # Hero section background images
    profile/       # Profile pictures
    research/      # Research-related images
    gallery/       # Gallery images
```

## Required Images

### Hero Images (`/images/hero/`)
- `aslam-hero.jpg` - Home page hero background
- `hero-research.jpg` - Research page hero background
- `hero-contact.jpg` - Contact page hero background
- `hero-home.jpg` - Alternative home hero (used in gallery)
- `hero-about.jpg` - About/profile hero background

### Profile Images (`/images/profile/`)
- `aslam.jpg` - Main profile picture (circular, used on home page)

### Research Images (`/images/research/`)
- `research-1.jpg` - Research image 1
- `research-2.jpg` - Research image 2
- `research-3.jpg` - Research image 3
- `research-4.jpg` - Research image 4

### Gallery Images (`/images/gallery/`)
- You can reuse images from other folders or add specific gallery images here

## How to Add Images

1. Copy your image files to the appropriate folder above
2. Make sure filenames match exactly (case-sensitive)
3. Supported formats: `.jpg`, `.jpeg`, `.png`, `.webp`

## Current Image References

- Home page: `/images/hero/aslam-hero.jpg` and `/images/profile/aslam.jpg`
- Research page: `/images/hero/hero-research.jpg` and `/images/research/research-*.jpg`
- Contact page: `/images/hero/hero-contact.jpg`
- Gallery page: Uses images from research and hero folders
