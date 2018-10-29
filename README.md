# simple-presentation-slides
Simple html slides for presentations

# Usage
## Add slide
Files in `/src` are added as slides with urls being the name of the file.
Simply add a file to the `/src` directory to add a new slide.

## Data for the slides
You can customize the slides and layouts by editing the templates in `/layouts`
and by customizing data in each slide using YAML.

Default data:
- `title`: title of the document (shown as meta title)
- `header`: header of slide (defaults to title if none)
- `subheader`: subheader of slide
- `next`: next slide
- `previous`: previous slide
