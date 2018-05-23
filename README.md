<div align="center">
  <a href="https://liyas-vr.firebaseapp.com"><img src="https://raw.githubusercontent.com/liyasthomas/pineapple-notes/master/assets/logo.gif" alt="Liyas Thomas" width="200"></a>
  <br>
  <h1>Liyas Thomas</h1>
</div>

<div align="center">
  <sub>Built with ❤︎ by
  <a href="https://github.com/liyasthomas">liyasthomas</a> and
  <a href="https://github.com/liyasthomas/pineapple-notes/graphs/contributors">contributors</a>
	</sub>
</div>

---

[![Build Status](https://travis-ci.org/liyasthomas/pineapple-notes.svg?branch=master)](https://travis-ci.org/liyasthomas/pineapple-notes) [![GitHub release](https://img.shields.io/github/release/liyasthomas/pineapple-notes/all.svg)](https://github.com/liyasthomas/pineapple-notes/releases/latest) [![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/liyasthomas/pineapple-notes/issues) [![Website](https://img.shields.io/website-up-down-ff69b4-ff69b4/https/shields.io.svg?label=website)](https://liyas-vr.firebaseapp.com) [![license](https://img.shields.io/github/license/liyasthomas/pineapple-notes.svg)](https://github.com/liyasthomas/pineapple-notes/blob/master/LICENSE) [![Donate](https://img.shields.io/badge/$-donate-ff69b4.svg)](https://www.paypal.me/liyascthomas)

# <img src="https://raw.githubusercontent.com/liyasthomas/pineapple-notes/master/assets/images/favicon.png" alt="Pineapple Notes" width="32"> Pineapple Notes

### A simple, clean note app by [Liyas Thomas](https://github.com/liyasthomas)

<div align="center">
  <br>
  <img src="https://storage.googleapis.com/gd-wagtail-prod-assets/images/ARUX_hero2_2x1.max-4000x2000.jpegquality-90.png" alt="Pineapple Notes" width="100%">
  <br>
</div>

### Features :sparkles:

:eyeglasses: **Virtual Reality made simple**: Pineapple Notes handles the 3D and [WebVR](https://webvr.info) boilerplates required to get running across platforms including mobile, desktop, Vive, and Rift. It works on any phone with [WebGL](https://caniuse.com/#feat=webgl) and [WebRTC](https://caniuse.com/#feat=stream).

:heart: **Declarative HTML**: HTML is easy to read and copy-and-paste. Since Pineapple Notes can be used from HTML, Pineapple Notes is accessible to everyone: web developers, VR enthusiasts, educators, artists, makers, kids. It is completely open source and free of charge!

:electric_plug: **Entity-Component Architecture**: Pineapple Notes is a powerful framework on top of [three.js](https://github.com/mrdoob/three.js), providing a declarative, composable, reusable entity-component structure. While Pineapple Notes can be used from HTML, developers have unlimited access to JavaScript, DOM APIs, three.js, [WebVR](https://webvr.info), and [WebGL](https://caniuse.com/#feat=webgl).

:zap: **Performance**: Pineapple Notes is a thin framework on top of [AR.js](https://github.com/jeromeetienne/AR.js) and [A-Frame](https://github.com/aframevr/aframe). Although A-Frame uses the DOM, A-Frame does not touch the browser layout engine. Performance is a top priority, being battle-tested on highly interactive [WebVR](https://webvr.info) experiences. It runs efficiently even on mobile phones!

:globe_with_meridians: **Cross-Platform**: Build VR applications for Vive,
Rift, Daydream, GearVR, and Cardboard. Don't have a headset or controllers? No
problem! Pineapple Notes still works on standard desktop and smartphones. It is a pure web solution, so no installation required. Full JavaScript based on [three.js](https://github.com/mrdoob/three.js) + [jsartoolkit5](https://github.com/artoolkit/jsartoolkit5).

---

## Getting started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

<div align="center">
  <br>
  <img src="https://storage.googleapis.com/gd-wagtail-prod-assets/original_images/ARUX_inline-option3.jpg" alt="Pineapple Notes" width="100%">
  <br>
</div>

### Prerequisites

What things you need to install the software and how to install them.

* A device which supports [WebGL](https://caniuse.com/#feat=webgl) and [WebRTC](https://caniuse.com/#feat=stream) with a working camera input
* Internet connection
* A web browser that supports [WebVR](https://webvr.info). Works best with Chrome on Android devices. You can still experience [WebVR](https://webvr.info) content in other browsers on Android and iOS, but it might not be as smooth since those browsers don’t fully support [WebVR](https://webvr.info)
* [Wonder](https://en.wikipedia.org/wiki/Wonder_(emotion))! :heart:

<div align="center">
  <br>
  <img src="https://mixedreality.mozilla.org/static/img/experience/devices.png" alt="Pineapple Notes" width="100%">
  <br>
  <br>
</div>

### Try it on mobile :iphone:

It works on all platforms. Android, iOS and Windows phone. It runs on **any browser with [WebGL](https://caniuse.com/#feat=webgl) and [WebRTC](https://caniuse.com/#feat=stream)** (for iOS, you need to update to iOS 11).

Try on your phone in only two easy steps, check it out!

1. Open any [marker image from here](https://github.com/liyasthomas/pineapple-notes/tree/master/assets/patterns) in your browser.
2. Open my [augmented reality web app](https://liyasthomas.github.io/pineapple-notes) in your phone browser. Give permissions to access camera. Scan marker image with your camera.

You're done! It will open a web page which read the phone's webcam, localize a marker and add 3D on top of it.

<div align="center">
  <br>
  <img src="https://storage.googleapis.com/gd-wagtail-prod-assets/original_images/ARUX_inline2-option1.png" alt="Pineapple Notes" width="100%">
  <br>
</div>

### Installing

A step by step series of examples that tell you've to get a development environment running.

1. Download the whole zip/clone the repository.
2. Unzip and make changes.
3. Save and deploy to any hosting platforms like Firebase, GitHub pages etc.

---

## Running the tests

Explain how to run the automated tests for this system.

### Break down into end to end tests

Explain what these tests test and why.

```
Will be explained later
```

### And coding style tests

Explain what these tests test and why.

```
Will be explained later
```

---

## Deployment

Add additional notes about how to deploy this on a live system.

```
Will be explained later
```

---

## Built with

* **[AR.js](https://github.com/jeromeetienne/AR.js)** - For efficient augmented reality for the web
	* [three.js](https://github.com/mrdoob/three.js) - For being a great library to do 3d on the web
	* [ARToolKit](https://github.com/artoolkit/artoolkit5) - Years of development and experiences on doing augmented reality
	* [emscripten](https://github.com/kripken/emscripten) and [asm.js](https://github.com/dherman/asm.js) - Thus we could compile ARToolKit C into JavaScript
* **[A-Frame](https://github.com/aframevr/aframe)** - Web framework for building virtual reality experiences
* **[Chromium](https://github.com/chromium/chromium)** - Thanks for being so fast!
* HTML - For the web framework
* CSS - For styling components

---

## Contributing

Please read [CONTRIBUTING](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

---

## Continuous Integration

We use [Travis CI](https://travis-ci.com) for continuous integration. Check out our [Travis CI Status](https://travis-ci.org/liyasthomas/pineapple-notes).

---

## Versioning

This project is developed by [Liyas Thomas](https://github.com/liyasthomas) using the [Semantic Versioning specification](https://semver.org). For the versions available, see the [releases on this repository](https://github.com/liyasthomas/pineapple-notes/releases).

---

## Authors

### Lead Developers
* [**Liyas Thomas**](https://github.com/liyasthomas) - *Author*

### Testing and Debugging
* [Liyas Thomas](https://github.com/liyasthomas)

### Contributors
* [Liyas Thomas](https://github.com/liyasthomas)

### Thanks
* [Jerome Etienne](https://github.com/jeromeetienne) - For [AR.js](https://github.com/jeromeetienne/AR.js)

See also the list of [contributors](https://github.com/liyasthomas/pineapple-notes/graphs/contributors) who participated in this project.

---

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT) - see the [LICENSE](LICENSE) file for details.

---

## Change log

See the [CHANGELOG](CHANGELOG.md) file for details.

---

## Acknowledgments

* Hat tip to anyone who's code was used
* Inspirations:
	* [Google VR](https://vr.google.com)
	* [Google ARCore](https://developers.google.com/ar)
	* [Google WebVR Experiments](https://experiments.withgoogle.com/webvr)
	* [Google AR Experiments](https://experiments.withgoogle.com/ar)
	* [Apple ARKit](https://developer.apple.com/arkit)
	* [Microsoft HoloLens](https://www.microsoft.com/en-us/hololens)
	* [YouTube](https://www.youtube.com)
	* [A-Frame](https://aframe.io)
	* [three.js](https://threejs.org)
	* [CodePen](https://codepen.io)
	* [GitHub](https://github.com)
