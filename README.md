<h1 align="center">Twitter Helper Craft Extension</h1>

<p align="center">A <a href="https://craft.do/" target="_blank" noreferrer noopener>Craft Docs</a> extension to help you write tweets in limit</p>

<hr>

Say goodbye to checking the character count manually and then deleting and rewriting your tweet! This extension shows you a character counter and provides a visual indicator of how many characters you have left to write your tweet in.

## Table of Contents <!-- omit in toc -->

- [(DO THIS FIRST) Enable Craft eXtensions](#do-this-first-enable-craft-extensions)
- [Installation](#installation)
  - [Install from release](#install-from-release)
  - [Build from source and install](#build-from-source-and-install)
- [Usage](#usage)
- [Acknowledgements](#acknowledgements)
- [License](#license)

## (DO THIS FIRST) Enable Craft eXtensions

1. Open Craft
2. Enable eXtensions in the settings

    - Mac: At the top left of the app, click your avatar, select Preferences, click Advanced. Under Craft eXtensions, click the dropdown, and select Enabled.

        ![Mac](https://secure-res.craft.do/v2/5DbS6ppn13eXWaikiwEbXZeoSrYsQ4i2tif9qMkWiD3eSKbGhpvknfUvMkEvzFZEDXyEwDDJeWdBBEkLQLgHRGCwtKxs2UYvkooCSBzmekXswUsoLQ1nkPtCr9GL8mNwfQ2vSaYrgqYVipymp3vnBjcQBhSBRQd8Ytn1Ye5wmJQNcQNxQHLs5ixfddLbTo2m9nDXTUMv2Af9f7RB3kdmiVrQ4o5t37u2G92a33wJcqdqLi7Xq/Image.jpg)

    - Web: At the top left of the web app, click your avatar, select Craft eXtensions, toggle Craft eXtensions on.

        ![Web](https://secure-res.craft.do/v2/T3gqayd2mhRAhW8PpG7Nnc4Gq8xrWHFjCTvYPogTEoy87dVLP1vhGSzyz9Rkgd1yZwPyv5esAS6AyhFmziQKNF6RwAKNNrTNmqwFTLe3Sq9L2yAhJXKkJEYkLUVwgGEAi7ykNyhVNWGCqWGJv9C6LCJTHYR8ytEjwckfxU75WwKMWsp/image.jpg)

3. At the bottom of the right side bar, the eXtensions logo is now visible. Click it to open the eXtensions panel.

    ![Extension](https://secure-res.craft.do/v2/5DbS6ppn13eXWaikiwEbXZeoSrYsQ4i2tif9qMkWiD3eSKbGhpvknfUvMkEvzFZEDXyEwDDJeWdBBEkLQLgHRGCwtKxs2UYvkooCSBzmekXswUsoLQ1nkPtCr9GL8mNwfQ2vSaYrgqYVipymp3vnBjcQBhfm4qVh9eWQwMc6UA1d2v8Eh2rqDSvVQA9sm6vjxLHC2N4UdCvEzqXuFzjQgsnBeQBaotrs4W9eNGsJujua3owEH/Image.jpg)

## Installation

### Install from release

1.  Download the latest release build file named `tweet-helper.craftx` from [here](https://github.com/thepushkarp/craft-tweet-helper/releases).
2.  Click the eXtensions logo at the bottom of the right side bar of Craft page to open the eXtensions panel.
3.  Click the **+** sign, select the `tweet-helper.craftx` file you just downloaded and click **Open**.
4.  Click **Install**.

### Build from source and install

1. Clone the repository

```bash
git clone https://github.com/thepushkarp/craft-tweet-helper.git
```

2. Build the extension

```bash
zip -vr tweet-helper.craftx icon.png index.html manifest.json
```

A file named `tweet-helper.craftx` will be created.

3. Install the extension

-   Click the eXtensions logo at the bottom of the right side bar of Craft page to open the eXtensions panel.
-   Click the **+** sign, select the `tweet-helper.craftx` file created in the last step and click **Open**.
-   Click **Install**.

## Usage

1. Open a new Craft document or open an existing document.
2. Select the text you want to tweet. **Please note that the text should be in a single block to be identified correctly.**

    ![Selected Text](https://user-images.githubusercontent.com/42088801/215260530-5d777c77-15ad-45b8-88bf-c2c2b5c2cb74.png)

3. Click the eXtensions logo at the bottom of the right side bar of Craft page to open the eXtensions panel and click the **Tweet Helper** extension.
4. The extension will show you a visual indicator of how many characters you have left to write your tweet in.

    ![Extension](https://user-images.githubusercontent.com/42088801/215260594-5d6c7ce1-5cbe-45e3-8886-8d9b01b19344.png)

## Acknowledgements

-   [Twitter Logo](https://github.com/thepushkarp/craft-tweet-helper/blob/main/icon.png) from [Twitter Brand Guidelines](https://about.twitter.com/en/who-we-are/brand-toolkit)
-   [Craft Extension Guide](https://www.craft.do/s/OhmDYXrBwI2wZS)

## License

[MIT](https://github.com/thepushkarp/craft-tweet-helper/blob/main/LICENSE)

<hr>

<p align="center">Made with ❤️ by <a href="https://github.com/thepushkarp" target="_blank" noreferrer noopener>Pushkar Patel</a></p>
