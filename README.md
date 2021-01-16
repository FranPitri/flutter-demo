# Hola 👋 Vamos a aprender algunas cosas de Flutter 🎉

## 🚀 Primeros pasos

* Para instalar Flutter, seguimos la [guía de instalación](https://flutter.dev/docs/get-started/install)
* Activamos el channel _beta_ con `flutter channel beta`. [¿Qué canal elijo para mi app?](https://github.com/flutter/flutter/wiki/Flutter-build-release-channels)
* Creamos un nuevo proyecto con `flutter create demo`

## 🔧 Algunas herramientas

* Vamos a usar [VSCode](https://code.visualstudio.com/download), pero también se puede usar Android Studio
* [scrcpy](https://github.com/Genymobile/scrcpy) está bueno
* [codepen](https://codepen.io/pen/editor/flutter) está bueno
* [dartpad](https://dartpad.dev/) está bueno
* [fvm](https://github.com/leoafarias/fvm) está bueno

## 🤓 Conceptos básicos

* 🧱 Widgets
* ⚡ Hot reload / ♻️ Hot restart
* 🔬 Devtools

## 🖼️ Layout básico

* `Row`s
* `Column`s
* `Expanded`
* `Center`
* [Constraints](https://flutter.dev/docs/development/ui/layout/box-constraints) ([examples](https://flutter.dev/docs/development/ui/layout/constraints))

## 📦 Assets

* Fonts ([Poppins](https://fonts.google.com/specimen/Poppins))
* Images

## 📝 State

* `setState`
* Cuando la app crece en complejidad, consideramos soluciones como: [bloc](https://github.com/felangel/bloc), [Redux](https://github.com/fluttercommunity/redux.dart), [Mobx](https://github.com/mobxjs/mobx.dart), [riverpod](https://github.com/rrousselGit/river_pod), etc.

## 🛸 Navigation

* `Navigator`
* Push, pop!

<br />

# Hola de nuevo 👋
## 🚀 Para esta encuentro, añadimos las siguientes mejoras a la base de la app:

* 🖼️ Llevamos el layout básico de las pantallas a su propio widget
* ⌨️ Agregamos la fuente Poppins
* 🎨 Implementamos colores y texto a través de un tema
* 📱 Cambiamos el color de Status/Navigation bar

<br />

🤓 **Hoy nos vamos a concentrar en:**

## 🎁 Packages

* Cómo introducirlos en nuestra aplicación
* Podemos usar algunas tools como [pubspec assist](https://marketplace.visualstudio.com/items?itemName=jeroen-meijer.pubspec-assist)
* [dio](https://pub.dev/packages/dio), [http](https://pub.dev/packages/http)

## 💉 Manejar state con ChangeNotifier e inyectarlo con provider
* [ChangeNotifier](https://flutter.dev/docs/development/data-and-backend/state-mgmt/simple#changenotifier)
* [provider](https://pub.dev/packages/provider)

## 🌐 Acceder a APIs
* Cómo hacer http requests
* Cómo hacer un provider que consuma un API
* Vamos a usar [JSONPlaceholder](https://jsonplaceholder.typicode.com/)