# Recruitment meeting presentation

## Contents

1. `slides.md` contains content for the presentation
2. `custom.css` allows you to customize CSS for the layout
3. `move_images_outside_p.rb` this basically removes <p> tags around <img> tags

## Usage

1. Install pandoc and Ruby
2. Clone this repository
3. Download the latest version of [reveal.js](https://github.com/hakimel/reveal.js) and extract it into `reveal.js` directory in repository's root.
4. Edit `slides.md` to suit your need, put images in the `images` directory
5. `make` will give you an index.html that you can open in your browser to see if it looks like you want

If you want a zip file that you can send to someone then `make release` is going to create a `presentation.zip` in your home directory
