<img src="./docs/logo.png" height="128">

# Secret Twitter Features: Chrome Extension
Enable upcoming twitter features before their official release.

## Requirements
To use this extension, will you need:
* Twitter account
* Chrome browser


## Manual installation
1. Clone this repo to your machine
2. Open [chrome://extensions/](chrome://extensions/) in your browser
3. Check the box for Developer mode in the top right
4. Press __Load Unpacked__ button and select the folder with the code

You can start using the extension now.

## Why Twitter Has Secret Features
It's a good idea to test a major feature before releasing it to the public. One of the ways Twitter team is doing this is by releasing changes to a small amount of people first.

To determine who can see an upcoming feature, they use a mechanism called "feature flags". Only accounts that have certain feature flag enabled, will see that feature.

Luckily, with this extension we can get a full list of the available feature flags and enable them to try new functionality. 

## How to use Secret Features
When you open a new tab with Twitter, you will see this item near your account:

<img src="./docs/how_to_find.png" height="250">

When you activate it, the browser will enter a "debug" mode and a list of available feature flags will be shown. 

<img src="./docs/list.png" width="600">

Here you can filter by feature name and modify feature flags. If you want to reset all your changes, press "Clear State" button in bottom right. To exit without saving, just click outside the modal.

You can always go back to this list by pressing "Secret Features" text.

Once you've finished testing the features, you can switch the toggle to "off", to hide the "debugger" warning.

## Which Feature Flags to Try First
Because twitter constantly updates it's code, the features in testing are also changing. Please follow [@512x512](https://twitter.com/512x512) or [@TitterTakeover](https://twitter.com/TitterTakeover) to learn about latest features and how to activate them.

## Feedback
If you have feedback, please create an issue in the repository or simply send me a DM in Twitter: [@512x512](https://twitter.com/512x512)