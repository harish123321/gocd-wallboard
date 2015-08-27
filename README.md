# GoCD Wallboard

This is a very minimal visualizer for [GoCD](http://go.cd) pipeline status. It can display the status of all available pipelines or pipelines from a single pipeline group.

### Usage

1. Modify `js/config.js` as necessary.
2. Serve this directory with the webserver of your choice.

### Configuration

Default configuration values are sourced from `js/config.js`.

- `server`: URL to your GoCD server
- `group`: optional pipeline group name to display. Empty string will cause all available pipelines to be displayed.

Configuration values can be overriden at run time via URL query parameters, e.g. `http://gocd-wallboard/?server=http://my.gocdserver.com&group=somegroup`

### Copyright

Copyright (c) 2015 Matt Greensmith