# annotate-fonts

A Photoshop script that automatically annotates your PSDs with font information.

- Lists font names, sizes (in pts) and hex color codes
- Ignores invisible or zero-opacity layers
- Supports @2x designs
- Run on the current document or an entire directory

All annotations are kept in a seperate top-level Font Annotations layer group and no other changes are made to the existing document.


## Before

![](before.png)

## After

![](after.png)

Example created with [Flat UI Kit](http://designmodo.com/flat/) by @designmodo.

## Installation

- Download the .zip near the top of the page
- Move annotate-fonts.jsx into /Applications/Adobe Photoshop CS6/Presets/Scripts/
- Restart Photoshop

The next time you need to annotate a PSD, go to File > Scripts > Annotate Fonts to run it.

## Contributing

I'm open to optimizations, fixes and improvements and would encourage opening an issue before adding new features. annotate-fonts is a small and simple script that attempts to do just one thing well.

- Fork it
- Create your feature branch (git checkout -b my-new-feature)
- Commit your changes (git commit -am 'Add some feature')
- Push to the branch (git push origin my-new-feature)
- Create new Pull Request