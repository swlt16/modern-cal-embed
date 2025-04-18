# Modern iCal Calendar Embed

<img src="https://github.com/GRA0007/modern-cal-embed/raw/master/example.png?raw=true" alt="Example">

This is a fully browser-side iCal (ics) calendar embed. It takes a link to an iCal file, and parses it and turns it into an embed. To use it, simply visit the link below and fill out the fields.

https://gra0007.github.io/modern-cal-embed/

**Note:** To use iCal urls that don't specify an `Access-Control-Allow-Origin` header, like from Google calendar, you'll need to use a cors proxy like https://cors-anywhere.herokuapp.com/.

You can test the embed's functionality using the following ics file url:
`https://gra0007.github.io/modern-cal-embed/example.ics`

# IMPORTANT
Use `header('Access-Control-Allow-Origin: *');` on the PHP side, if the data source is on another host!

# MULTIPLE CALENDARS
You can use multiple calendar links as data source, just separate the links with a pipe (`|`).
They will be displayed as a combined calendar in the plugin.
The meta data is used from the first calendar in the list.