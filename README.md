
### Task I : Create a closing prices graph 
---

#### Task description
Write a Vue component that has a line graph showing the closing prices of a company.
Use apexcharts library for the charting. The plugin is already installed in the project.


A demo of the chart is can be found [here](https://apexcharts.com/react-chart-demos/line-charts/zoomable-timeseries)

Documentation on how to use apexcharts can be found [here(START HERE)](https://apexcharts.com/docs/vue-charts/) 
Ignore the installation part since it is already installed.


We will simulate loading data from backend by loading data from a local file. Load data from stock.json or stockcols.json (whichever is easier) included in the directory. We will be using axios library (an AJAX library) to load the stock.json file. See [this post](https://medium.com/@negarjf/how-to-access-a-static-json-file-in-vue-cli-3-8943dc343f95) on how to do it. Again, axios is already installed so you can ignore the
the installation part.


#### How to run this project

Do this in the commmand prompt/terminal.

1) Clone this repository to your computer

`git clone https://`


2) Install all the dependencies 

Change into the directory where you cloned the project into by:

`cd folder/with/code`

Then run the following to install library dependencies:

`npm install`


make sure the code can run by running:

`npm run serve` 

This runs the development server on http://localhost:8080

3) Write the needed code

Edit the `StockChart.vue` file to put all the needed code there.

To run your code and see it in action run the following:

`npm run serve`

This runs your code on `localhost:8080`


4) Share your code
Once you have completed the task, and your code is running, share your code back
to the remote repository by typing the following commands:

`git add ANY_FILE_YOU_MODIFIED`
`git commit -m "TYPE MESSAGE HERE"`
`git push -u origin master`