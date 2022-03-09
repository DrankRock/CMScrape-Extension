# CMScrape-Extension
CMScrape-Extension is a firefox add-on made to easily create list of links from CardMarket. It was specially developped to keep track of all your collection's price using [CMScrape](https://github.com/DrankRock/CMScrape).

## Install
CMScrape-Extension is available [directly on Firefox](https://addons.mozilla.org/en-US/firefox/addon/cmscrape/), or you can install it as a temporary add-on on your broswer of choice.

### Load a temporary add-on
#### Firefox
Open the about:debugging page, click the This Firefox option, click the Load Temporary Add-on button, then select any file in your extension's directory.

The extension now installs, and remains installed until you restart Firefox.
Source : [developer.mozilla.org](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/Your_first_WebExtension)

*it should work on other browsers, I will test later this week*

## Use
As soon as the add-on is loaded into the browser, you will see the icon on the top right

![The add-on's icon](https://user-images.githubusercontent.com/32172257/157489120-7adc4bcb-2257-4169-a973-d2e36fb3ea95.png)

When visiting [www.cardmarket.com](https://www.cardmarket.com/en), and more precisely on a collectible's page, the page will be altered to look like that (*red rectangle added for clarity*) :

![Black Lotus Altered](https://user-images.githubusercontent.com/32172257/157504054-5d5c12ef-006b-4fc0-a7fb-1eea595b64d4.png)

Go on any collectible that you want to add to your list, precise the url using the `filter` tab from cardmarket, to choose a specific langage, the minimum condition, etc. Then click on the ![Screenshot 2022-03-09 19:21:09](https://user-images.githubusercontent.com/32172257/157506229-8c43e9b5-53d3-4794-8d6d-299125a053aa.png) and it will add the link of the current page to the list.   
You can clear this list using ![Screenshot 2022-03-09 19:24:06](https://user-images.githubusercontent.com/32172257/157506646-edebf94c-f6cb-4a97-9c5c-a6b2752bf948.png)  
