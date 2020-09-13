# 01_seo_refactor

## First Homework

Looking at the sample code i noticed a few issues.

* There was a broken link in the Nav Bar
* There were a lack of symantec html tags
* In the CSS File there appeared to be alot of excess code, ie. Not D.R.Y.


## Steps I took

* Added Symatic tags for [Nav],[aside],[section] where applicable
* Fixed broken nav bar link
* Added Title
* I noticed alot of reapeating css code for the [Aside] and [Section] the code was apply the same criteria but for each element it was calling out a separate code. I removed the duplicated and adjusted the Html of these sections to call out the new css. I then removed the dupicate CSS code
* I added "alt" tags for all images except 1

## Did not do

For the background image is calling a "Hero" css line of code. I saw that the image was linked in the CSS. I thought this might be an inccorrect process, I tried to brink the img into the HTML and continue to call the "Hero" Css but was unable to get it to work.

