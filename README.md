# Media Bias Check Extension
By Maya Frame - July 2019

## Description
Empowers the user to make informed choices about their media consumption. Color-coded links depict the general political bias and factual accuracy of an online news source according to ![AdFontes Media Bias Chart](https://www.adfontesmedia.com/?v=402f03a963ba).
Mousing over the link generates a context menu with more information about the source's axis placement on the Media Bias Chart.
![Media Bias Chart 4.0](/images/Media-Bias-Chart_4.0.jpg)

## Known Issues
I'm learning as I go and I have a lot of stretch goals!
Currently, sources are hard-coded into background file, as is the context menu html. Future versions will read and display object information from sources.json file.

## Specs 
1. Create manifest.json according to Chrome Extension documentation
2. Search DOM for string matches 
3. Create color components for certain string matches
4. Create popup color key on chart background when icon is clicked
5. Create mouseover context menu item for more info

## Setup and Use
From your command line:

```bash
# Clone this repository
$ git clone https://github.com/meyerclemon/media-bias-chrome-ext
# Navigate to chrome://extensions
# Select 'Developer Mode'
# Drag media-bias-chrome-ext folder to extensions page
# OR
# Click 'Load Unpacked' and choose media-bias-check folder from the directory
```
# Built With
* JavaScript
* jQuery 3.4.1
* CSS
* HTML
* Visual Studio Code (Text Editor)

Maya Frame(mayacframe@gmail.com)
If you have any feedback or concerns, please contact any of the contributors.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT). Copyright (C) 2019 Maya Frame. All Rights Reserved.
