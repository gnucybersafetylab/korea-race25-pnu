# Project Structure

## Directory Organization

### HTML Pages
- `index.html` - Home page
- `about.html` - About page
- `timeline.html` - Event timeline
- `race-resources.html` - Race rules and resources (with English/Korean tabs)
- `getting-started.html` - Getting started guide (with English/Korean tabs)
- `registration.html` - Registration information (with English/Korean tabs)
- `contact.html` - Contact page
- `post.html` - Sample post page

### Results & Stream
- `results-stream/` - Results and streaming page
  - `index.html` - Main results/stream page
  - `images/` - Event images and graphics
  - `photos/` - Competition photos (to be added)

### Images Organization
- `img/backgrounds/` - Background images for page headers
  - `bg_header.jpg` - Main homepage background
  - `f1_race.jpg`, `f1_race_2.jpg` - Race backgrounds
  - `indy_game_01.jpg` - Game/event backgrounds
  - `about-bg.jpg`, `contact-bg.jpg`, `post-bg.jpg`, `home-bg.jpg` - Page-specific backgrounds

- `img/rules/` - Rule documentation images
  - `rule_fig1.png` - Pit stop zone diagram
  - `rule_fig2.png` - Qualification time trial diagram
  - `rule_fig3.png` - Head-to-head race diagram
  - `rule_fig4.png`, `rule_fig5.png` - Collision examples

- `img/logos/` - Logo and branding images
  - `roboracer_korea_banner_*.jpeg/png` - Banner images
  - `logo*.png` - Logo files
  - `favicon.png` - Site favicon

- `img/general/` - General purpose images
  - `person_*.jpg/png` - Team member photos
  - `about.jpg`, `post-sample-image.jpg` - Content images
  - `learn_overview.png` - Learning resources images
  - `arrows.png` - UI elements
  - `1.jpg`, `2.jpg` - Miscellaneous images

- `img/results/` - Competition results images (to be added)

### Other Directories
- `css/` - Stylesheets
- `js/` - JavaScript files
- `fonts/` - Web fonts
- `_site/` - Jekyll build output (generated)

## Notes

- All image paths in HTML files have been updated to reflect the new folder structure
- Results and event photos should be added to `results-stream/images/` and `results-stream/photos/`
- The `results-stream/` folder is organized as a separate section for better content management

