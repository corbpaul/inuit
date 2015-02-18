# Inuit

Base setup for using inuit.css https://github.com/inuitcss

* bower.json with all components required
* main.scss with contents and includes for all bower components

To get started use `bower install` to download the inuit.css components.

Each section has it's own folder i.e. `settings` that contains a index file. Import any files from that folder into this file which in turn is imported in the top level main.scss file.

This ensures the top level file doesn't get overcrowded. Each section file will also have a contents list.
