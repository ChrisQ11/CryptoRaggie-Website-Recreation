# CryptoRaggie-Website-Recreation
Intro

The challenge was to recreate the navigation side bar on this website:https://cryptoraggies.io/index.html

To line uo the items to the left I initally used the a tag to create links. Then I changed the display value to block but that didmt do anything. I looked at the website's code and found that they used unordered lists. So i used the ul tag and all the items stacked.

Next step was to shift the items down so I increased the line height of the list itmes and increased height of the ul

Problems
1. could not close gap between top of purple bar and top of page
  -SOLVED: I put the image into a link tag and adjusted margin-left to -25px
2. Alignment of list items is not equal to the list items on the original page
3. Need a content delivery library to use the proper icons. Will dowload at a later time
4. Could not find font-style nor font-size using "inspect" on the original website
5. I had trouble positioning flex items of different height. I also could close the immense gap between the nav bar and the flex items
  -SOLVED: I commented out the original code and reconstructed the homepage using divs. 
