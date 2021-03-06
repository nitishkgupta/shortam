## Shortam

Shortam is a simple and light front-end shortcode framework built on vanilla JavaScript and CSS. 

This project uses shortcode.js (https://github.com/nicinabox/shortcode.js) for building shortcodes.

<b>Note - Shortam is currently under developement (don't use it now in production)</b>

<b>Note - Shortam uses ```Roboto``` Google font for it's components. Be sure to include it in your project.</b>

## Features

1. Very Light
2. Currently in developement
3. More components coming soon
4. Custom shortcodes support
5. And much more

## Documentation

### Alerts

Use this code to add alerts -

```
[alert id="test" width="70" type="green" text="test"]
```

<B>Customisations -</b>

1. width="70" // Width of alert in percentage (in this case 70%)
2. type="green" // Theme of alert (Supported - green/blue/red/orange)
3. text="test" // Text to be shown inside alert box (can be html)
4. id="test" // Adds id to the object for extra usage (optional, leave blank for null)

### Buttons

Use this code to add buttons

```
[bt id="test" type="green" href="http://abc.com" text="Download" target="_blank"]
```
<B>Customisations -</b>

1. type="green" // Theme of button (Supported - green/blue/red/orange)
2. href="http://abc.com" // Target of link (Use #! for null)
3. text="test" // Text to be shown inside button (can be html)
4. target="_blank" // Target of link (Supported - all html target values)
5. id="test" // Adds id to the object for extra usage (optional, leave blank for null)

## Upcoming Features

1. Bootstrap 4 support
2. More custom elements
3. Much more

## License

MIT License
