﻿# Twitter estimated revenue per tweet

## Installation

To load an unpacked extension in developer mode:
1. Go to the Extensions page by entering chrome://extensions in a new tab. (By design chrome:// URLs are not linkable.)
   - Alternatively, click the Extensions menu puzzle button and select Manage Extensions at the bottom of the menu.
   - Or, click the Chrome menu, hover over More Tools, then select Extensions.
2. Enable Developer Mode by clicking the toggle switch next to Developer mode.
3. Click the Load unpacked button and select the extension directory.
![extensions-page-e0d64d89a6acf_856](https://github.com/andresbotia/TwitterRevenueChromeExtension/assets/75555223/aa2a2da0-8f69-42f9-a133-4ad7e77ffc12)

Download from the google extension store:
- Coming Soon.... (*Pending Google Store Acceptance)

## Usage

This Google Chrome Extension that changes the views button on a tweet to show the estimated revenue the user made from that specific tweet.
According to Twitter( X? nobody really calls it that lets be honest), A user needs to pass three cases to become eligible for revenue
1. Be subscribed to X Premium or Verified Organizations.
2. Have at least 5M organic impressions on your cumulative posts within the last 3 months.
3. Have at least 500 followers

I wanted to figure out how much a tweet "Could" make per its views. According to CalculateBuddy, there is a rough estimation formula we can use for this which is:

### AdRevenue = 0.0000085 x Number of Impressions

We can receive a tweets number of views(impressions) and use the formula to calculate the potential of revenue received per that individual tweet


Sources: 
- https://help.twitter.com/en/using-x/creator-ads-revenue-sharing
- https://calculatebuddy.com/twitter-money-calculator

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)
