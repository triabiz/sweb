# Sweb
Minimal Base Code for Socketed Webapps, Websites

## Front-end
jQuery ($.load, $.getScript)

Load screen example:
`load_screen("/home");`

Load component example:
`load_component("/header");`
`load_component("/footer");`

## Back-end
Express.js serves static files: .js,.css,.html,.png,etc.

No HTTP GET/POST for data, Socket.io serves all data.
