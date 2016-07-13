# web\_pilates
Template web site in xhtml5 for Marta

## Configuration

### So pages work well on hard disk, CD ROM and USB memory or other

To make it work without the web server you have to accept that the paths end up with `index.html`, otherwise comment in the `_config.yml` file line

    # index: "index.html"

###  Disable events

Comment out all rige

    # events
    collections:
      events:
        output: true

delete the item ["events", "/ events /"] from the row below
    
    # site Menu [ [ neme_link, absolute_path ], ... ]

### Remove the blog

delete the item ["blog", "/blog/"] from the row below

     # Site Menu [[neme_link, absolute_path], ...]

And delete the directory `/blog` and /_post`

### Remove the log

The print logs, in chronological order, everything printed elsewhere, are
post, etc. events.

delete the item ["log", "/log/"] from the row below

     # Site Menu [[neme_link, absolute_path], ...]

And delete the `/log` directory

