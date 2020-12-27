# nmea0183-to-nmea0183

Signal K Node server plugin to filter and forward NMEA0183 sentences.

## Usage


1. Add NMEA0183 input and optionally customize the sentence event

![image](https://user-images.githubusercontent.com/1049678/103177484-9143fe00-4883-11eb-8480-4a285aaa02ed.png)


2. Activate the plugin and add a new configuration block that lists all NMEA0183
sentences and describes the internal SignalK server `input` and `output` events. The input event can be the standard `nmea0183` event or a custom event you configured in step 1.

<a href='https://user-images.githubusercontent.com/1435910/27770068-10ba1596-5f41-11e7-8b60-a5c1226208d1.png'><img src='https://user-images.githubusercontent.com/1435910/27770068-10ba1596-5f41-11e7-8b60-a5c1226208d1.png' width='600px'/></a>

3. Add the custom event in a connection's `Output events` configuration.

[The event mechanism explained in more detail](https://github.com/SignalK/signalk-server/wiki/Events-and-Outputting-Data).

## Contribute

Use [GitHub issues](https://github.com/vokkim/nmea0183-to-nmea0183/issues) and [Pull Requests](https://github.com/vokkim/nmea0183-to-nmea0183/pulls).

## License

MIT
