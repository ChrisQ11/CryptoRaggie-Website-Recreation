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

Home Page Recreation

Problems
1. I had trouble positioning flex items of different heights. I also could not close the immense gap between the nav bar and the flex items. Whenever I place the nav bar and then the flex items below it a huge gap would form between them.
  -SOLVED: I commented out the original code and reconstructed the homepage using divs. I First enclosed the nav bar and the content under the nav bar in two separate divs and used "flex-direction: column". Then I separated the left column of content from the content grouping on the right in two separate divs. For the content on the right I separated the top and bottom content boxes in two separate divs and used the column value for the flex direction property. I further separated each individual content block with divs and then styled them.

Initially I did not want to use so many divs to control the layout of my flex items. In the end i could not figure out any other way. 
