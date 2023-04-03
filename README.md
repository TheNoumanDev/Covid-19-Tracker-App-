### COVID-19 Tracker App

I learnt how to build a COVID-19 Tracker App using a REST API and flutter, with different features. I used `disease.sh` API with the following endpoints:

- [World Stats](https://disease.sh/v3/covid-19/all)
- [Countries List](https://disease.sh/v3/covid-19/countries)

I used different packages to display the data in the app, like:

- [http](https://pub.dev/packages/http)
- [animated_text_kit](https://pub.dev/packages/animated_text_kit)
- [pie_chart](https://pub.dev/packages/pie_chart)
- [flutter_spinkit](https://pub.dev/packages/flutter_spinkit)
- [shimmer](https://pub.dev/packages/shimmer)

I designed 4 different screens for the app, as follows:

- `Splash Screen`: The app starts with a splash screen, where the app logo is displayed with a rotating animation.
- `World Stats Screen`: The app displays the world stats in a card, where the user can see the total cases, recovered cases, and deaths around the world.
- `Countries List Screen`: The app displays a list of all the countries, where the user can see the total cases, recovered cases, and deaths in each country. The user can also search for a specific country. The user can tap on a country to see the country details This screen shows a shimmer effect while the country data is loading.
- `Country Details Screen`: The app displays the country details in a card, where the user can see the total cases, recovered cases, and deaths in the country. The user can also see the country flag and country name.

---

### Video Preview
https://user-images.githubusercontent.com/76642732/229552921-3ff3b954-d9d7-4891-a09d-984bd9ddfa3d.mp4

