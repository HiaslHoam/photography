# Photography Portfolio

A clean and elegant photography portfolio website built with Jekyll. This site showcases my photography work with automatic EXIF data display and responsive design.

## Features
- Clean, minimalist design focused on showcasing photographs
- Automatic EXIF data display (aperture, shutter speed, ISO) when clicking on images
- Responsive layout that works on all devices
- Easy image management with automated thumbnail generation

## Development

### Running locally
1. `$ bundle install` - install gems
2. `$ bundle exec jekyll serve` - start the website locally

### Adding new photos
1. Copy your photos to the `images` directory
2. Run `$ npm install` to install dependencies
3. Run `$ npx gulp resize` to automatically resize images and generate thumbnails
4. The processed images will be placed in `images/fulls` and `images/thumbs`

## Credits

This photography portfolio is based on the excellent template by [Ram Patra](https://github.com/rampatra/photography). Thanks to [AJ](https://twitter.com/ajlkn) for the original website template and Ram for adapting it for Jekyll.

**Original repository:** [https://github.com/rampatra/photography](https://github.com/rampatra/photography)
