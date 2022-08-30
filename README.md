<a name="readme-top"></a>


<h1 align="center">Flutterando Analysis</h1>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://pub.dev/packages/asuka">
    <img src="readme_assets/logo.png" alt="Logo" width="180">
  </a>

  <p align="center">
   <b>
   FLUTTERANDO Analysis
   </b>
   <br />
    A Simple and Clean approach to Snackbars, Dialogs and ModalSheets in a single provider.
    <br />
    <!-- <a href="https://link da documentação"><strong>Explore the docs »</strong></a>
    <br /> -->
    <br />
    <!-- <a href="https://link para o demo">View Demo</a> -->
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Report Bug</a>
    ·
    <a href="https://github.com/othneildrew/Best-README-Template/issues">Request Feature</a>
  </p>

<br>

<!--  SHIELDS  ---->

[![Version](https://img.shields.io/github/v/release/flutterando/asuka?style=plastic)](https://pub.dev/packages/asuka)
[![License](https://img.shields.io/github/license/flutterando/asuka?style=plastic)](https://github.com/Flutterando/asuka/blob/master/LICENSE)
[![Pub Points](https://img.shields.io/pub/points/asuka?label=pub%20points&style=plastic)](https://pub.dev/packages/asuka/score)
[![Contributors](https://img.shields.io/github/contributors/flutterando/asuka?style=plastic)](https://github.com/Flutterando/asuka/graphs/contributors)
[![Forks](https://img.shields.io/github/forks/flutterando/asuka?color=yellowgreen&logo=github&style=plastic)](https://github.com/Flutterando/asuka/graphs/contributors)


[![Pub Publisher](https://img.shields.io/pub/publisher/asuka?style=plastic)](https://pub.dev/publishers/flutterando.com.br/packages)
[![Flutterando Youtube](https://img.shields.io/youtube/channel/subscribers/UCplT2lzN6MHlVHHLt6so39A?color=blue&label=Flutterando&logo=YouTube&logoColor=red&style=plastic)](https://www.youtube.com/flutterando)
</div>

<!----
About Shields, some recommendations:
+-+
Build - GithubWorkflow ou Github Commit checks state
CodeCoverage - Codecov
Chat - Discord 
License - Github
Rating - Pub Likes, Pub Points and Pub Popularity (if still in early stages, we 		    recommend only Pub Points since it's controllable)
Social - GitHub Forks, Github Org's Stars (if using Flutterando as the main org),  	    YouTube Channel Subscribers (Again, using Flutterando, as set in the   		    example)
--->

<br>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#sponsors">Sponsors</a></li>
    <li><a href="#getting-started">Getting Started</a></li>
    <li><a href="#how-to-use">How to Use</a></li>
    <li><a href="#features">Features</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>

<br>

<!-- ABOUT THE PROJECT -->
## About The Project


<!-- PROJECT EXAMPLE (IMAGE) -->

<br>
<Center>
<img src="example/Asuka.gif" alt="Asuka package working gif" width="400">
</Center>

<br>

<!-- PROJECT DESCRIPTION -->

Asuka is a Dart package that aims to simplify and keep a clean approach when implementing some visual elements from Flutter like Snackbars, Dialogs and ModalSheets. 
With few and intuitive lines of code you can have those in your project in a lot less time than  


<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- SPONSORS -->
## Sponsors

<a href="https://fteam.dev">
    <img src="images/sponsor-logo.png" alt="Logo" width="120" style="aspect-ratio: 1/1; border-radius: 50%">
  </a>

<p align="right">(<a href="#readme-top">back to top</a>)</p>
<br>


<!-- GETTING STARTED -->
## Getting Started

To get Asuka in your project follow either of the instructions below:

a) Add Asuka as a dependency in your Pubspec.yaml:
 ```yaml
   dependencies:
     asuka: any
``` 

b) Use Dart Pub:
```sh
  dart pub add asuka
```

<br>


## How to Use

Add the following code where you call your Material App:

```dart
import 'package:asuka/asuka.dart';

MaterialApp(
    builder: Asuka.builder,
    navigatorObservers: [
       Asuka.asukaHeroController //This line is needed for the Hero widget to work
    ],
);
``` 
Now you just have to call the named constructors for each widget that you want to use: 

```dart
import 'package:asuka/asuka.dart';

Asuka.showSnackBar(SnackBar(
    content: Text("Hello World"),
));

AsukaSnackbar.success("success").show();
```

<br>

_For more examples, please refer to the_ 🚧 [Documentation]() _-Currently being updated-_ 🚧

<p align="right">(<a href="#readme-top">back to top</a>)</p>




<!-- FEATURES -->
## Features

- ✅ Snackbars
- ✅ Dialog
- ✅ BottomSheet
- ✅ ModalBottomSheet
- ✅ Overlay 

Right now this package has concluded all his intended features. If you have any suggestions or find something to report, see below how to contribute to it. 

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing
 
🚧 [Contributing Guidelines]() - _Currently being updated_ 🚧

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the appropriate tag. 
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

Remember to include a tag, and to follow [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) and [Semantic Versioning](https://semver.org/) when uploading your commit and/or creating the issue. 

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Flutterando Community
- [Discord](https://discord.gg/qNBDHNARja)
- [Telegram](https://t.me/flutterando)
- [Website](https://www.flutterando.com.br)
- [Youtube Channel](https://www.youtube.com.br/flutterando)
- [Other useful links](https://linktr.ee/flutterando)


<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!----
  TODO: Escrever as Contributing Guidelines
->

<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements 


Thank you to all the people who contributed to this project, whitout you this project would not be here today.

<br>

<a href="https://github.com/flutterando/asuka/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=flutterando/asuka" />
</a>
<!-- Bot para Lista de contribuidores - https://allcontributors.org/  -->
<!-- Opção (utilizada no momento): https://contrib.rocks/preview?repo=flutterando%2Fasuka -->


<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MANTAINED BY -->
## Maintaned by

---

<br>
<p align="center">
  <a href="https://www.flutterando.com.br">
    <img width="110px" src="images/logo-flutterando.png" style="border-radius: 50%;">
  </a>
  <p align="center">
    Built and maintained by <a href="https://www.flutterando.com.br">Flutterando</a>.
  </p>
</p>