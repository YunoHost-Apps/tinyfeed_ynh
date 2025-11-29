tinyfeed is a CLI tool that generate a static HTML page from a collection of feeds.
It's dead simple, no database, no config file, just a CLI and some HTML
Give it a list of RSS, Atom or JSON feeds urls and it will generate a single HTML page for it. Then you can effortlessly set it up in crond, systemd or openrc and voilà, you’ve got yourself a webpage that aggregates your favorite feeds.

### Feature

    RSS, Atom and JSON feeds are all supported thanks to the awesome gofeed library
    Highly customizable, especially with the ability to use external stylesheets and templates.
    Dark / Light theme based on system preference
    The generated page is lightweight and fully accessible.
    Supports a daemon mode to re-generate the output periodically.
