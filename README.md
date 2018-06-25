# TapWatir

Watir for testing your Mobile Devices. Powered by Appium.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'tap_watir'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install tap_watir

## Usage

For right now, this is how you access a Chrome browser locally:
```
appium_url = 'http://localhost:4723/wd/hub'
caps = {platformName: 'Android',
        platformVersion: '8.1',
        deviceName: 'Nexus',
        browserName: 'Chrome'}

browser = TapWatir::App.browser(url: appium_url, desired_capabilities: caps)
```

## Development

To get the specs to run:
* Install Android Studio
* Create a Virtual Device with a Nexus using version 8.1
* Install Appium and start the server.
