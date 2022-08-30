<a name="readme-top"></a>


<h1 align="center">Flutterando Analysis</h1>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://pub.dev/packages/asuka">
    <img src="readme_assets/logo.png" alt="Logo" width="180">
  </a>

  <p align="center">
    This package provides lint rules for Dart and Flutter which are used in 
    <a href="https://pub.dev/publishers/flutterando.com.br/packages">Flutterando's</a> and <a href="https://fteam.dev">FTeam's</a> packages and projects. For more information, see the <a href="https://github.com/Flutterando/flutterando_analysis/blob/main/lib/analysis_options.0.0.1.yaml">complete list of options</a>.
    <br />
    <br />
    <a href="https://github.com/Flutterando/flutterando_analysis/issues/">Report Bug</a>
    ·
    <a href="https://github.com/Flutterando/flutterando_analysis/issues">Request Feature</a>
  </p>

<br>

<!--  SHIELDS  ---->

[![Version](https://img.shields.io/github/v/release/flutterando/flutterando_analysis?style=plastic)](https://pub.dev/packages/flutterando_analysis)
[![License](https://img.shields.io/github/license/flutterando/flutterando_analysis?style=plastic)](https://github.com/Flutterando/flutterando_analysis/blob/main/LICENSE)
[![Pub Points](https://img.shields.io/pub/points/flutterando_analysis?label=pub%20points&style=plastic)](https://pub.dev/packages/flutterando_analysis/score)
[![Contributors](https://img.shields.io/github/contributors/flutterando/flutterando_analysis?style=plastic)](https://github.com/Flutterando/flutterando_analysis/graphs/contributors)
[![Forks](https://img.shields.io/github/forks/flutterando/flutterando_analysis?color=yellowgreen&logo=github&style=plastic)](https://github.com/Flutterando/flutterando_analysis/graphs/contributors)


[![Pub Publisher](https://img.shields.io/pub/publisher/asuka?style=plastic)](https://pub.dev/publishers/flutterando.com.br/packages)
[![Flutterando Youtube](https://img.shields.io/youtube/channel/subscribers/UCplT2lzN6MHlVHHLt6so39A?color=blue&label=Flutterando&logo=YouTube&logoColor=red&style=plastic)](https://www.youtube.com/flutterando)
</div>

<br>

---
<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#sponsors">Sponsors</a></li>
    <li><a href="#how-to-use">How to Use</a></li>
    <li><a href="#how-to-suppress-lints">How to Supress Lints</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>

---


<br>

<!-- ABOUT THE PROJECT -->
## About The Project


<!-- PROJECT EXAMPLE (IMAGE) -->



<br>

<!-- PROJECT DESCRIPTION -->

Asuka is a Dart package that aims to simplify and keep a clean approach when implementing some visual elements from Flutter like Snackbars, Dialogs and ModalSheets. 
With few and intuitive lines of code you can have those in your project in a lot less time than  


<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- SPONSORS -->
## Sponsors

<a href="https://fteam.dev">
    <img src="readme_assets/sponsor-logo.png" alt="Logo" width="120">
  </a>

<p align="right">(<a href="#readme-top">back to top</a>)</p>
<br>


<!-- GETTING STARTED -->
## How To Use

To use our linter rules import it to your project like this:

a) Adding the package as a dependency in your Pubspec.yaml:
```yaml
# Add it as a dev dependency
dev_dependencies:
  flutterando_analysis: ^0.0.1

# Or as a normal dependency if you need to
dependencies: 
  flutterando_analysis: ^0.0.1
```

b) Alternatively, use Dart Pub. You can take out the tag `--dev` if you want to install as a normal dependency:
```sh
  dart pub add --dev flutterando_analysis
```

After importing it, add an include in your project's `analysis_options.yaml`:

```yaml
include: package:flutterando_analysis/dart/dart.yaml
```
<br>


## How To Suppress Lints


There may be cases where specific lint rules are undesirable. Lint rules can be suppressed at the line, file, or project level.

An example use case for suppressing lint rules at the file level is suppressing the `prefer_const_constructors` in order to achieve 100% code coverage. This is due to the fact that const constructors are executed before the tests are run, resulting in no coverage collection.

### Line Level

To suppress a specific lint rule for a specific line of code, use an `ignore` comment directly above the line:

```dart
// ignore: public_member_api_docs
class A {}
```

### File Level

To suppress a specific lint rule of a specific file, use an `ignore_for_file` comment at the top of the file:

```dart
// ignore_for_file: public_member_api_docs

class A {}

class B {}
```

### Project Level

To suppress a specific lint rule for an entire project, modify `analysis_options.yaml`:

```yaml
include: package:flutterando_analysis/analysis_options.yaml
linter:
  rules:
    public_member_api_docs: false
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>





<!-- CONTRIBUTING -->
## Contributing
 
🚧 [Contributing Guidelines]() - _Currently being updated_ 🚧

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better or questions, please open an issue here, with the appropriate tag. 
Don't forget to give the project a star! Thanks!

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


<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements 


Thanks to the people who contributed to this project
<br>

<a href="https://github.com/flutterando/asuka/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=flutterando/asuka" />
</a>


<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MANTAINED BY -->
## Maintaned by

---

<br>
<p align="center">
  <a href="https://www.flutterando.com.br">
    <img width="110px" src="readme_assets/logo-flutterando.png">
  </a>
  <p align="center">
    Built and maintained by <a href="https://www.flutterando.com.br">Flutterando</a>.
  </p>
</p>














## Badge

To indicate that your project is using `flutterando_analysis` you can use this badge: 

<img src="https://img.shields.io/badge/style-flutterando__analysis-blueviolet">

<br>

Just copy and paste in your readme.md the code below: 
```md
[![style: Flutterando analysis](https://img.shields.io/badge/style-flutterando__analysis-blueviolet)](https://pub.dev/packages/flutterando_analysis)
```