=== Plugin Name ===
Contributors: apixu
Tags: widgets, sidebar, shortcode, apixu, weather, weather widget, forecast, global, temp, local weather,local forecast
Requires at least: 3.5
Tested up to: 4.5.2
Stable tag: trunk
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Beautiful weather widgets for your beautiful site.

== Description ==
This plugin allows you to easily add Apixu weather widgets to your site.

The weather data is provided for free by http://apixu.com, they require an [API Key](http://www.apixu.com/signup.aspx) to access their weather.
Once you have the API Key you can simply add it in 'Settings' -> 'Apixu Weather' and you're ready to go.

Use the built in widget with all of its marvelous settings or add it to a page or theme with the shortcode: (all settings shown)

`[apixu-weather location="Minsk" units="C" size="tall" forecast_days="3" hide_stats="1" show_link="1" inline_style='max-width: 300px']`

= Settings =

*   Location: Enter a string like "Minsk, Belarus" or just "London".
*   Units: C (default) or F
*   Size: tall (default) or wide
*   Forecast Days: How many days to show in the forecast bar (3 or 5)
*   Hide stats: Hide the text stats like humidity, wind, high and lows, etc
*	Show link: Show link to Apixu site.
*   Inline style: styles for widget

== Installation ==

1. Add plugin to the `/wp-content/plugins/` directory
1. Activate the plugin through the 'Plugins' menu in WordPress
1. Register for an Apixu [API Key](http://www.apixu.com/signup.aspx)
1. Add your API Key to the settings field in 'Settings' -> 'Apixu Weather' (added in version 1.0)
1. Use shortcode or widget to display apixu weather on your apixu site

== Screenshots ==
1. Basic tall layout (all stats)
2. Basic tall layout
3. Basic tall layout
4. Basic tall layout
5. Basic tall layout
6. Basic tall layout
7. Basic tall layout
8. Basic tall layout

== Upgrade Notice ==
no yet

== Frequently Asked Questions ==
no yet

== Changelog ==
= 1.0 =
* Initial load of the plugin.
= 1.1.0 =
* Change api logic.
= 1.2.0 =
* Add selection how to render location.