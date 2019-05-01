# Extract critical-path CSS
Script for extracting the critical path css with Puppeteer

In order to make it work:
1. Install puppeteer `npm install puppeteer`

Then, edit the scripts on the package.json and type the URL to be tracked and run one of the following commands:
* `npm findCritical` to extract the critical css path through the terminal.
* `npm findCriticalAndSave` to save the extracted critical path css into a file. Name it whatever you want.
