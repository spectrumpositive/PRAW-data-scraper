<div align="center">
  <a href="https://github.com/spectrumpositive/PRAW-data-scraper"><img src="https://elijahpepe.com/i/CUMq1Jvg7b.png" height="160"></a>
  <br>
  <br>
  <p>
    <b>A free, fast and beautiful PRAW data scraper</b>
  </p>
  <p>
     <i>A Python tool to scrape Reddit results.</i>
  </p>
  <p>

[![Travis Build Status](https://img.shields.io/travis/com/spectrumpositive/PRAW-data-scraper?logo=Travis)](https://travis-ci.com/spectrumpositive/PRAW-data-scraper) [![GitHub release](https://img.shields.io/github/release/spectrumpositive/PRAW-data-scraper/all?logo=GitHub)](https://github.com/spectrumpositive/PRAW-data-scraper/releases/latest) [![Website](https://img.shields.io/website?url=https%3A%2F%2Felijahpepe.com/prawdatascraper&logo=PRAWDataScraper)](https://elijahpepe.com/prawdatascraper) [![Contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen)](CONTRIBUTING.md) [![Financial Contributors on Open Collective](https://img.shields.io/opencollective/all/prawdatascraper?logo=Open-Collective&label=financial+contributors)](https://opencollective.com/prawdatascraper) [![Chat on Discord](https://img.shields.io/badge/chat-Discord-violet?logo=discord)](https://discord.gg/n2VuTrS)

  </p>
  <p>
    <sub>Built with ❤︎ by
      <a href="https://github.com/spectrumpositive">spectrumpositive</a> and
      <a href="https://github.com/spectrumpositive/PRAW-data-scraper/graphs/contributors">contributors</a>
    </sub>
  </p>
</div>

---

<details>
  <summary>Table of contents</summary>

---

- [Features](#features-)
- [Demo](#demo--)
- [Usage](#usage-)
- [Built with](#built-with-)
- [Developing](#developing-)
  - [Browser based development environment](#browser-based-development-environment)
  - [Local development environment](#local-development-environment)
  - [Docker compose](#docker-compose)
- [Docker](#docker--)
- [Releasing](#releasing-)
- [Contributing](#contributing-)
- [Continuous Integration](#continuous-integration--)
- [Versioning](#versioning--)
- [Change log](#change-log-)
- [Authors](#authors-)
  - [Lead Developers](#lead-developers)
  - [Testing and Debugging](#testing-and-debugging)
  - [Collaborators](#collaborators-)
  - [Thanks](#thanks)
  - [Financial Contributors](#financial-contributors)
    - [Organizations](#organizations)
    - [Individuals](#individuals)
  - [Code Contributors](#code-contributors)
- [License](#license-)
- [Acknowledgements](#acknowledgements-)
- [Badges](#badges-)

---

</details>

### Features ✨

❤️ **Lightweight**: Crafted with minimalistic code.

⚡️ **Fast**: The Python code only takes anywhere from a few seconds to a few minutes.

**Settings:**

- `client_id` - Reddit app client ID.
- `client_secret` - Reddit app client secret.
- `agent_name` - Reddit app agent name.
- `lim` - Amount of posts (sorted by new) that will be counted in the dataset.
- `sub` - Name of subreddit you wish to scrape. 'all' will extract all subreddits.
- `flair item` - Name of flairs you want to sort by. If you change this property, you must change it in the topics data. *This is optional.*

**Features:**

- Flair sorting

## Demo 🚀 [![Website](https://img.shields.io/website?url=https%3A%2F%2Felijahpepe.com/prawdatascraper&logo=prawdatascraper)](https:/elijahpepe.com/prawdatascraper)

The website is currently a work in progress.

### Usage 💡

1. Input the subreddit you want to scrape.
2. Input the client ID, secret, and agent name. This information is not saved or stored on any server.
3. Input the amount of posts that will be counted in the dataset.
4. Input the flairs you'd like to sort by.

## Built with 🔧

- PRAW - For the scraping element.
- Python - For the entire script.
- HTML - For the website.

## Running 👷

Running the script is as easy as downloading it with Git or through GitHub itself, and running it in Python with the only dependencies as PRAW.

## Contributing 🍰

Please read [`CONTRIBUTING`](CONTRIBUTING.md) for details on our [`CODE OF CONDUCT`](CODE_OF_CONDUCT.md), and the process for submitting pull requests to us.

We use [Travis CI](https://travis-ci.com) for continuous integration. Check out our [Travis CI Status](https://travis-ci.com/spectrumpositive/PRAW-data-scraper).

## Versioning 🔖 [![GitHub release](https://img.shields.io/github/release/liyasthomas/postwoman/all?logo=GitHub)](https://github.com/liyasthomas/postwoman/releases/latest)

This project is developed by [Spectrum Positive](https://github.com/spectrumpositive). For the versions available, see the [releases on this repository](https://github.com/spectrumpositive/PRAW-data-scraper/releases).

## Change log 📝

See the [`CHANGELOG`](CHANGELOG.md) file for details.

## Authors 🧙

### Lead Developers

- **[SpectrumPositive](https://github.com/spectrumpositive)** - _Author_
- **[ElijahPepe](https://github.com/ElijahPepe)** - _Community Lead_

### Collaborators <!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->

[![All Contributors](https://img.shields.io/badge/all_contributors-14-orange.svg?style=flat-square)](#contributors-)

<!-- ALL-CONTRIBUTORS-BADGE:END -->

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://github.com/spectrumpositive"><img src="https://avatars1.githubusercontent.com/u/68460525?v=4" width="100px;" alt=""/><br /><sub><b>SpectrumPositive</b></sub></a><br /><a href="https://github.com/spectrumpositive/PRAW-data-scraper/commits?author=spectrumpositive" title="Code">💻</a> <a href="#design-spectrumpositive" title="Design">🎨</a></td>
    <td align="center"><a href="https://elijahpepe.com"><img src="https://avatars3.githubusercontent.com/u/29153977?v=4" width="100px;" alt=""/><br /><sub><b>ElijahPepe</b></sub></a><br /><a href="https://github.com/spectrumpositive/PRAW-data-scraper/commits?author=ElijahPepe" title="Code">💻</a> <a href="#design-ElijahPepe" title="Design">🎨</a></td>
  </tr>
</table>

<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

See the list of [contributors](https://github.com/spectrumpositive/PRAW-data-scraper/graphs/contributors) who participated in this project.

### Code Contributors

This project exists thanks to all the people who contribute [[Contribute](CONTRIBUTING.md)].

<a href="https://github.com/spectrumpositive/PRAW-data-scraper/graphs/contributors"><img src="https://opencollective.com/prawdatascraper/contributors.svg?width=890&button=false" /></a>

## License 📄

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT) - see the [`LICENSE`](LICENSE) file for details.

## Acknowledgements 🙏

- Hat tip to anyone whose code was used

---

<div align="center">
  <br>
  <a href="https://github.com/spectrumpositive/PRAW-data-scraper"><img src="https://avatars3.githubusercontent.com/u/68460525?s=460&v=4f" alt="SpectrumPositive" width="200"></a>
  <br>
  <h3>Happy Coding ❤︎</h3>
</div>
