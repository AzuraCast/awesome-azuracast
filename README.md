# Awesome AzuraCast
A curated list of tools, scripts and supporting software to help improve your AzuraCast broadcasting experience.

- [First-Party Tools](#first-party-tools)
- [AzuraCast Add-Ons](#azuracast-add-ons)
- [Broadcasting Tools](#broadcasting-tools)
- [Communications Tools](#communications-tools)
- [Station Discovery](#station-discovery)
- [Audio Post-Processing Tools](#audio-post-processing-tools)
- [Commercial Operations](#commercial-operations)
- [Miscellaneous Utilities](#miscellaneous-utilities)

## First-Party Tools
Tools maintained by the AzuraCast team directly.

- **[AzuraCast](https://github.com/AzuraCast/AzuraCast)** (FOSS, AGPL 3): A self-hosted web radio broadcasting suite. Includes an AutoDJ based on Liquidsoap, a broadcasting frontend based on Icecast, and a web UI to manage media, streaming, metrics and more.

- **[AzuraRelay](https://github.com/AzuraCast/AzuraRelay)** (FOSS, Apache 2): A drop-in tool to relay streams from a "parent" AzuraCast installation. Use it to add additional listener capacity to stations or offer streams that are geographically closer to listeners.

## AzuraCast Add-Ons
Proprietary software that you can download and incorporate into AzuraCast.

- **[Shoutcast](https://radiomanager.shoutcast.com/RMO/user/your-plan/your-plan)** (Proprietary): An alternative broadcasting frontend for listeners to connect to. Popular, but limited in its free offering.

- **[Stereo Tool](https://www.thimeo.com/stereo-tool/download/)** (Proprietary): A popular audio mastering tool that gives your station the compressed, equalized feel of FM radio stations. A proprietary alternative to the `master_me` tool we ship in newer versions of AzuraCast.

- **[Maxmind GeoIP](https://www.maxmind.com/en/geoip2-country-database)** (Proprietary): An alternative to our built-in IP geolocation database that is considered more accurate in some situations. Allows you to approximate the location of your listeners and visualize them on a map.

## Broadcasting Tools
Recommended tools to use when broadcasting to AzuraCast. See our [Guide to Streaming Software](https://docs.azuracast.com/en/user-guide/streaming-software) for additional information about streaming tools.

- **[Mixxx](https://www.mixxx.org/)** (FOSS): A powerful cross-platform tool for DJs with built-in Icecast broadcasting support.

- **[Broadcast Using This Tool (BUTT)](https://danielnoethen.de/butt/)** (FOSS): A lightweight, multi-OS streaming tool with support for Icecast or Shoutcast.

- **[iziCast for iOS](https://apps.apple.com/us/app/izicast/id1462571191)** (Proprietary): An AzuraCast-compatible broadcasting tool specifically for iPads and iPhones.

## Communications Tools
Tools to help you communicate and engage with your audience.

- **[Azuri](https://github.com/TwixGamer00/azuri)** (FOSS, Apache 2): A community-supported Discord bot that lets you control your station from inside your Discord community and listen to broadcasts inside Discord chat channels.

- **[Pro.radio](https://pro.radio/)** (Proprietary): A set of paid Wordpress-based tools to help power your radio station's public presence. Supports AzuraCast directly.

- **[Now Playing for AzuraCast Wordpress Plugin](https://wordpress.org/plugins/now-playing-widget-fuer-azuracast-stationen/)** (FOSS): A Wordpress plugin that adds Now Playing data to your Wordpress site. (May no longer be maintained)

- **[AzuraCast Player](https://github.com/PeWe79/AzuraCast-Player)** (FOSS): A full-featured interactive web player that uses AzuraCast's API to display rich metadata for multiple stations in a single interface.

## Station Discovery
Web sites and tools to promote your own station or to find others you may enjoy.

- **[RadioBrowser](https://www.radio-browser.info/owners)**: An open-source community-driven database of Internet radio stations around the world.

- **[Xiph's Icecast Directory](http://dir.xiph.org/)**: The default "Yellow Pages" (YP) directory that Icecast stations report to.

## Audio Post-Processing Tools
Tools to help you add compression, equalization and other refinements to your broadcasted signal.

- **[master_me](https://github.com/trummerschlunk/master_me)** (FOSS): An automatic mastering plugin with built-in presets for common broadcast destinations. Supported directly inside AzuraCast since April 2023.

- **[mkpascal's Liquidsoap Scripts](https://github.com/mkpascal/mk_liquidsoap_processing)** (FOSS): A comprehensive set of processing steps that can be added into Liquidsoap advanced code.

- **[StereoTool](https://www.thimeo.com/stereo-tool/)** (Proprietary): A licensed software audio processor with widespread use in both the terrestrial and Internet radio spaces. Numerous presets are available to fine-tune broadcast signals. Support for Stereo Tool is included in AzuraCast, but the software is proprietary and must be installed by the system administrator.

## Commercial Operations
Resources specifically for commercial operators or resellers.

- **[AzuraCast WHMCS Module](https://git.tidynode.co.uk/AndyRixon/azuracast-whmcs-module)** (FOSS): A community-maintained WHMCS module for AzuraCast provisioning.

## Miscellaneous Utilities
Other tools or add-on scripts to enhance your AzuraCast experience.

- **[Video Stream](https://gist.github.com/BusterNeece/5dbfb4dbc1846055c9ab07a7c685899c)** (FOSS): An example snippet of advanced Liquidsoap code that allows you to convert your audio-only radio station into one with a looping video and live "Now Playing" metadata embedded into the video stream. A great starting point for running a YouTube 24/7 radio station, for example.

- **[XMLTV/EPG Guide](https://github.com/Moonbase59/azuracast_xmltv)** (FOSS): A tool to create electronic program guides to allow software to browse your AzuraCast program schedule using a standardized TV guide format.
