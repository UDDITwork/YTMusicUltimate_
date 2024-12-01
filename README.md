<p align="center">
<img src="https://user-images.githubusercontent.com/38832025/235781424-06d81647-b3db-4d9b-94dc-cd65cdf09145.png?raw=true" />
</p>    
<p align="center">
<img src="https://user-images.githubusercontent.com/38832025/235781207-6d1ad44e-0c32-4aec-9c75-cb928ca8a0d3.png?raw=true" />
</p>

<p align="center">
The best tweak for YouTube Music on iOS.
</p>

<p align="center">
<a href="https://twitter.com/UdditRise">
    <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" />
</a>
<a href="https://github.com/UDDITwork">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" />
</a>
</p>

<p align="center">
📱 Contact: <a href="tel:+917456886877">+91 7456886877</a> | 
📧 Email: <a href="mailto:udditalerts247@gmail.com">udditalerts247@gmail.com</a>
</p>

## Download Links

<p align="center">
<a href="https://ginsu.dev/repo" target="_blank">
    <img src="https://img.shields.io/badge/Add_to_Repository-FF4500?style=for-the-badge&logo=apple&logoColor=white" />
</a>
<a href="https://github.com/UDDITwork/YTMusicUltimate/releases" target="_blank">
    <img src="https://img.shields.io/badge/Download_Release-00B2FF?style=for-the-badge&logo=github&logoColor=white" />
</a>
</p>

* **Jailbreak:**
Add **[https://ginsu.dev/repo](https://ginsu.dev/repo)** to your favorite installer and download latest version from there, or from **[Releases](https://github.com/UDDITwork/YTMusicUltimate/releases)** page.
(arm.deb version for Rootful and arm64.deb version for Rootless devices)

* **Sideloading:**
We no longer provide a sideloading IPA but you can build one yourself, keep reading:

## How to build a YTMusicUltimate IPA by yourself using Github actions

If this is your first time here, start from step 1. If you built a YTMU IPA before, skip steps 1 and 2. Instead, click on the "Sync fork" button to get the latest version of the tweak and continue through step 3.

1. Fork this repository using the fork button on the top right.
2. On your forked repository, go to Repository Settings > Actions, enable Read and Write permissions.
3. Go to the Actions tab on your forked repo, click on "Build and Release YTMusicUltimate" located on the left side. Click "Run workflow" button located on the right side.
4. Find a decrypted YTMusic .ipa file (we cannot provide you this due to legal reasons) and upload it to a file provider(filebin.net or Dropbox is recommended). Paste the url to the necessary field and click "Run workflow".
5. Wait for the build to finish. You can download the tweaked IPA from the releases section of your forked repo.

## IPA building troubleshooting

99.9% of the time, the culprit is the IPA URL you provided. You HAVE TO provide a decryped IPA. It cannot be any other extension, it has to be a **.ipa** file. Find a decrypted YTMusic IPA(we can't help you with that), upload it to filebin.net or Dropbox, give the direct link to the GitHub action. If you find a working ipa and upload it properly, everything will start working perfectly, pinky promise.

If the github action works and you cannot find where you can download the result, you need to add /releases to the url of your forked repository. It'll probably look like this: https://github.com/UDDITwork/YTMusicUltimate/releases

## How to build the package by yourself on your device

1. Install **[Theos](https://theos.dev/docs/installation)**
2. Clone this repo **[using git](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository)**
3. Cd your YTMusicUltimate folder and run:
   • '**make clean package**' to build deb for rootful device
   
   • '**make clean package ROOTLESS=1**' to build deb for rootless device
   
   • '**make clean package SIDELOADING=1**' to build deb for injecting in to ipa
   
   • To learn how to inject tweaks in to ipa visit **[here (Azule)](https://github.com/Al4ise/Azule)**

<p align="center">
Made with ❤️ by <a href="https://github.com/UDDITwork">UDDIT</a>
<br>
Based on original work by Ginsu and Dayanch96
</p>
