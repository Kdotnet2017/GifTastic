# GifTastic
### What is GifTastic?
* It is  [GIPHY API](https://developers.giphy.com/).
* It is a small and cool app for sending  request to the largest GIF library website.
* It is a fun app to display the response of 10 animate GIFs.

### How it works?
* GifTastic app includes one [html file](index.html) and one [Javascript file](assets/javascript/GiphyJS.js).
* This app uses Bootstrap and jQuery libraries.
* createButton(keyWord) and initialButtonList() functions do add any keywords interested in at top of the page as a button.
* Clicking on a button calls apiCall function to use jQuery ajax function for sending a request to GIPHY API server for retrieving data. The request is formed in queryUrl variable by adding search keyword as "q=" argument in the queryString.

#### see a demo [here](https://kdotnet2017.github.io/GifTastic/).

