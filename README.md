<div align="center">
<br />
<img src="app/src/main/res/mipmap-xxxhdpi/ic_launcher_round.webp" />
</div>

<h1 align="center">Breezy Weather</h1>

<br />

<div align="center">
  <img alt="API 21+" src="https://img.shields.io/badge/Api%2021+-50f270?logo=android&logoColor=black&style=for-the-badge"/>
  <img alt="Kotlin" src="https://img.shields.io/badge/Kotlin-a503fc?logo=kotlin&logoColor=white&style=for-the-badge"/>
  <img alt="Jetpack Compose" src="https://img.shields.io/static/v1?style=for-the-badge&message=Jetpack+Compose&color=4285F4&logo=Jetpack+Compose&logoColor=FFFFFF&label="/>
  <img alt="Material You" src="https://custom-icon-badges.demolab.com/badge/material%20you-lightblue?style=for-the-badge&logoColor=333&logo=material-you"/>
  <br />
  <img src="https://img.shields.io/github/license/breezy-weather/breezy-weather?style=for-the-badge" alt="License LGPL-3.0" />
  <img src="https://img.shields.io/github/languages/code-size/breezy-weather/breezy-weather?style=for-the-badge" alt="GitHub code size in bytes" />
  <br /><br />
  <a href="https://github.com/breezy-weather/breezy-weather/releases/latest">
      <img src="https://img.shields.io/github/v/release/breezy-weather/breezy-weather?color=purple&include_prereleases&logo=github&style=for-the-badge" alt="Download from GitHub" />
  </a>
  <a href="https://apt.izzysoft.de/fdroid/index/apk/org.breezyweather/">
      <img src="https://img.shields.io/endpoint?url=https://apt.izzysoft.de/fdroid/api/v1/shield/org.breezyweather?color=purple&include_prereleases&logo=FDROID&style=for-the-badge" alt="Download from IzzyOnDroid repo" />
  </a>
</div>


<h4 align="center">Breezy Weather is a weather app with a strong focus on design, with a simple, clean UX, smooth animations, and Material Design all over, plus lots of customizability.</h4>

<hr />

<div align="center">
    <img src="fastlane/metadata/android/en-US/images/phoneScreenshots/01.png" alt="" style="width: 300px" />
</div>


<div align="center">

# Download

<a href="https://github.com/breezy-weather/fdroid-repo/blob/main/README.md">
<img src="https://f-droid.org/badge/get-it-on.png"
alt="Get it from Breezy Weather F-Droid repository" align="center" height="80" /></a>

<a href="https://apt.izzysoft.de/fdroid/index/apk/org.breezyweather/">
<img src="https://gitlab.com/IzzyOnDroid/repo/-/raw/master/assets/IzzyOnDroid.png"
alt="Get it on IzzyOnDroid" align="center" height="80" /></a>

<a href="https://github.com/breezy-weather/breezy-weather/releases">
<img src="https://user-images.githubusercontent.com/69304392/148696068-0cfea65d-b18f-4685-82b5-329a330b1c0d.png"
alt="Get it on GitHub" align="center" height="80" />
</a>
</div>

# Features

- Weather data
    - Daily and hourly forecasts up to 16 days
      - Temperature
      - Air quality
      - Wind
      - UV index
      - Precipitation
    - Precipitation in the next hour
    - Air quality
    - Pollen & Mold
    - Ephemeris (Sun & Moon)
    - Severe weather and precipitation alerts
    - Real-time weather conditions
      - Temperature
      - Feels like
      - Wind
      - UV index
      - Humidity
      - Dew point
      - Atmospheric pressure
      - Visibility
      - Cloud cover
      - Ceiling

- <details><summary>Multiple weather sources (<a href="docs/SOURCES.md">comparison</a>)</summary>

  - Open-Meteo
  - AccuWeather
  - MET Norway
  - OpenWeatherMap (often rate-limited)
  - Pirate Weather (no API key provided)
  - HERE (no API key provided)
  - Météo France
  - Mixed China sources
</details>

- Large selection of home screen widgets for at-a-glance information
- Live wallpaper
- Custom icon packs
  - [Geometric Weather icon packs](https://github.com/breezy-weather/breezy-weather-icon-packs/blob/main/README.md)
  - Chronus Weather icon packs
- Automatic dark mode

- <details><summary>Free and Open Source</summary>

  - No proprietary blobs/dependencies
  - Releases generated by GitHub actions, guaranteeing it matches the source code
  - Fully works with Open-Meteo (FOSS source)
</details>

- <details><summary>Privacy-friendly</summary>

  - No personal data collected by the app ([link to app privacy policy](https://github.com/breezy-weather/breezy-weather/blob/main/PRIVACY.md))
  - Multiple sources are available, with links to their privacy policies for transparency
  - Current location is optional and not added by default
  - If using current location, an IP location service can be used instead of GPS to send less accurate coordinates to weather source
  - No trackers/automatic crash reporters
</details>


# Help

* [Frequently Asked Questions / Help](HELP.md)
* [Homepage explanations](docs/HOMEPAGE.md)
* [Weather sources comparison](docs/SOURCES.md)


# Contribute

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

* [Contribution guide (includes a guide to create a new weather source)](CONTRIBUTE.md)


# Translations

Translation is done externally [on Weblate](https://hosted.weblate.org/projects/breezy-weather/breezy-weather-android/#information). Please read carefully project instructions if you want to help.

[![Translation progress report](https://camo.githubusercontent.com/c651422c22fc5743a6bf2003b86ed171e1852a8b90030c2e3bae322e32b9f778/68747470733a2f2f686f737465642e7765626c6174652e6f72672f776964676574732f627265657a792d776561746865722f2d2f627265657a792d776561746865722d616e64726f69642f686f72697a6f6e74616c2d6175746f2e737667)](https://hosted.weblate.org/projects/breezy-weather/breezy-weather-android/#information)

* English regional variants must be updated on GitHub if they differ from the original English file
* French translation is maintained by repo maintainers


# Contact us

* If you’d like to report a bug or suggest a new feature, GitHub discussions or issues are best for organization.
* We’ve also created a Matrix/Element space with a number of different channels for more general discussion: [`#breezy-weather-space:matrix.org`](https://matrix.to/#/#breezy-weather-space:matrix.org).
  * If you are not comfortable writing a GitHub discussion/issue in English, you can ask on the channel if someone can help you in your language.
    * We also have a dedicated help channel in French: [`#breezy-weather-francais:matrix.org`](https://matrix.to/#/#breezy-weather-francais:matrix.org)
  * If you’d prefer a direct channel link instead of a space link, here’s the main Breezy Weather Matrix channel: [`#breezy-weather:matrix.org`](https://matrix.to/#/#breezy-weather:matrix.org)
* Mastodon account: [`@breezyweather@fosstodon.org`](https://fosstodon.org/@breezyweather)


# Build variant

A variant called `gplay` is available and may be distributed on Google Play Store in the future.
It enables Instant App and bundles Google Network Location Provider (proprietary).


# License

* [GNU Lesser General Public License v3.0](/LICENSE)
* [Additional license terms](/LICENSE_ADDITIONAL)
* [Guidelines regarding Breezy Weather identity and forks](/IDENTITY.md)
* [Built on Geometric Weather Android app (GNU Lesser General Public License v3.0)](https://github.com/WangDaYeeeeee/GeometricWeather). Breezy Weather is not officially associated with Geometric Weather or its products.

