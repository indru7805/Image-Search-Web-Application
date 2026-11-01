# Image Search App

A responsive web app that searches Unsplash and shows matching photos in a clean grid.

**Live demo:** https://indru7805.github.io/Image-Search-Web-Application/

## Features
- Keyword search over Unsplash images via the Unsplash REST API
- "Show More" button to load more results (pagination)
- Asynchronous requests (async/await) so the page stays responsive

## Tech Stack
- HTML5, CSS3, JavaScript (ES6+) 
- Unsplash API (REST, JSON)

## Getting Started
1. `git clone https://github.com/indru7805/Image-Search-Web-Application.git`
2. Get a free access key at unsplash.com/developers.
3. Add the key in [file name], for example `const accessKey = "YOUR_KEY";`
4. Open `index.html` in a browser.

## How It Works
1. The user types a keyword and presses Search.
2. The app calls the Unsplash search endpoint with `fetch`.
3. The JSON response is turned into image cards on the page.
4. "Show More" requests the next page of results.

## Project Structure
[run `tree` and paste it]

## Limitations
- Unsplash's free API has a request limit per hour.

## Credits
Photos by Unsplash photographers via the Unsplash API.

## Author
Indrajeet Patil – github.com/indru7805
