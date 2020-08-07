# Twitter Toolkit for Alfred

The Twitter Toolkit for Alfred is a set of keywords that let you quickly interact with Twitter's website and [Mac app](https://apps.apple.com/us/app/twitter/id1482454543?mt=12&uo=4).

It makes it easy to quickly search and find your own content or the content of people you follow.

Please note that this extension doesn't support programmatic access to Twitter. For that kind of integration, try [AlfredTweet](http://dferg.us/alfredtweet-2/) by David Ferguson.

# Installation

<a href="https://github.com/chrismessina/alfred-app/raw/master/workflows/twitter-toolkit/twitter-toolkit-alfred-workflow.zip"><img src="../../assets/icon-zip.png" alt="Zip File Icon" width="128" height="128" align="center"></a>

1. Download and unzip [this file](https://github.com/chrismessina/alfred-app/raw/master/workflows/twitter-toolkit/twitter-toolkit-alfred-workflow.zip).
2. Double-click `twitter-toolkit.alfredworkflow` to install it.

_You will need to be an [Alfred Powerpack](https://www.alfredapp.com/powerpack/) user to enable this workflow._

# Configuration

## Integration with Twitter for Mac

This workflow supports interacting with Twitter on the web or in the Twitter for Mac app. Unfortunately, the desktop app doesn't support that many intents and will fall back to the web in those cases.

Look for the  symbol below to see which features work with Twitter for Mac.

To enable integration with the Twitter for Mac app:

1. After you've installed the workflow, go to Workflows and select Twitter Toolkit
2. Access the workflow and variables configuration here:

<img src="./assets/workflow-variables-crop.png">

3. Set the `platform` variable in the configuration to `app` (1).

<img src="./assets/workflow-config-crop.png">

To disable this integration, set the 'platform' variable to `web`.


## Set your username

This workflow also makes it easy to search your own tweets or find content from the people you follow ("followees"). To configure this feature, you must set the `account` variable in the configuration (2).



# Keywords

**tweet **

Compose new Tweet

**follow **

Follow {query} on Twitter

**trending **

See what’s happening

**tweets **

Search Twitter for {query}<br>
⌘ Search my tweets for {query}<br>
Search tweets from people I follow for {query}

**my**

Search my tweets for {query}<br>
Search my tweets for #{query}<br>
Search people I follow for {query}

**me **

Go to my profile on Twitter

**#**

Search Twitter for #{query}<br>
⌘ Search my tweets for #{query}

**@ **

Go to Twitter user @{query}<br>
Search Twitter for @{query}

**images**

Search Twitter images for {query}<br>
⌘ Search my Twitter images for {query}

**videos**

Search Twitter videos for {query}<br>
⌘ Search my Twitter videos for {query}

**users**

Search Twitter users for {query}

**embed**

Get embed code for a tweet (requires link to tweet)

**dms **

Go to Twitter messages


# Changelog

## [v0.1.0] - 2020-08-06
- Initial Release

_Inspired by [Keep a Changelog](https://keepachangelog.com/)_

# Contact

This workflow was created by [Chris Messina](https://chrismessina.me). You can contact him via [Twitter](https://twitter.com/@chrismessina) or [his website](https://chrismessina.me/contact).
