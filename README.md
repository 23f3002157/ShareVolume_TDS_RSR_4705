# Church & Dwight Stock Information Project

This project fetches stock information for Church & Dwight (CHD) and displays the maximum and minimum shares outstanding from the SEC's XBRL data.

## Getting Started

### Prerequisites

You need a web browser to view the HTML file. No additional installations are required.

### Files

- `index.html`: The main HTML file which includes JavaScript for data fetching and rendering.
- `data.json`: Contains the entity name and the max/min shares outstanding.
- `uid.txt`: Contains an identification UID for the project.

### Usage

1. Open `index.html` in your web browser.
2. The page will display the entity name, maximum shares outstanding, and minimum shares outstanding for Church & Dwight by default.
3. To view data for a different CIK, append the CIK to the URL like this: `index.html?CIK=0001018724`.

### Running the Application

Simply open `index.html` in your favorite web browser. It will automatically fetch and display the shares outstanding data.

## License

MIT License

```
MIT License

Copyright (c) [year] [your name]

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

1. The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

2. THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```

## Acknowledgements

- [SEC Data API](https://data.sec.gov/api/xbrl/companyconcept/) for the source of financial data.
- Bootstrap for styling the HTML elements.