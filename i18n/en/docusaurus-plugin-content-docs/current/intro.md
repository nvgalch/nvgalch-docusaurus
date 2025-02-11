---
sidebar_position: 1
---

# Types of VK apps

On VK, you can create the following types of apps:

* [Embedded app](#Embedded%20apps)
* [Standalone app](#Standalone%20apps)
* [Website](#Websites)
* [Marusia skill](#Marusia%20skills)

## Embedded apps

**Embedded apps** are web apps that:

* Are hosted outside of VK.
* Have their pages displayed within the VK UI via an iframe or WebView.
* Interact with VK using the open-source [VK Bridge](bridge/overview) library that enables social mechanics and user interactions.

### Mini apps

**VK mini apps** are embedded apps designed to help users complete specific tasks or achieve certain goals. With mini apps, VK users can keep a fitness diary, take quizzes or order lunch together with colleagues.

Examples of mini apps that are available via direct link:

* [Tool 42](https://vk.com/tool42)
* [Zanimarium](https://vk.com/zanimarium)

### Games

**VK games** are embedded apps designed to engage users in playing games. Their purpose is to enable users to have a fun time, compete with each other and feel the thrill of winning, enjoy great graphics and an engaging plot, all while being able to return to the game at any time. Games are launched directly from the VK interface without the need for downloads, installations or registrations.

Examples of games that are available via direct link:

* [Naruto - Ninja Battle](https://vk.com/app7075874)
* [Raccoin](https://vk.com/raccoin)

### Technical aspects of embedded apps

From a technical standpoint, both games and mini apps are simply web apps. Their files are hosted on your server that is connected to the internet. The server-side code operates on the server, while the client-side code is loaded and runs in the browser:

* When launched from the desktop or mobile version of the VK website, apps run in an iframe located on VK.
* In the mobile app for Android and iOS, apps run in a WebView control element opened from the mobile app.

Mini apps and games have different screens for settings. There, some settings may be similar, while others differ in order to fit specific tasks.

To exchange data with VK, the server side of games and mini apps uses requests to the VK API, while the client side employs the [VK Bridge](bridge/overview) library.

## Standalone apps

**VK standalone apps** are apps required for integrating your apps with VK. Such apps use the [VK API](api/overview) to exchange data, but this type of app can't be opened on VK.

## Websites

**VK websites** are apps required for connecting VK widgets to a website. This type of app can't be opened.

## Marusia skills

**Marusia skills** are apps that add skills to Marusia's skill base. This type of app can't be opened.

:::warning
**Attention!** On 24 January 2025, you'll no longer be able to create new Marusia custom skills, but keep access to previously created ones.
:::

