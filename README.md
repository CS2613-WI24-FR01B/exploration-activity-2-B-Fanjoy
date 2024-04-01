# Chart.js

## 1. Which package/library does the sample program demonstrate?

    The sample program demonstrates the usage of Chart.js, a JavaScript library for creating interactive and customizable charts and graphs on web pages.

## 2. How does someone run your program?

    To run the program, you can follow these steps:

    1. Download the provided chart.html file.
    2. Open the HTML file in a web browser.

## 3. What purpose does your program serve?

    The program serves to demonstrate how to create a simple line chart using Chart.js. It showcases the basic structure of using Chart.js to render a chart on a web page with some sample data.

## 4. What would be some sample input/output?

### Sample Input:
```javascript
const data = {
  labels: ['January', 'February', 'March', 'April', 'May', 'June', 'July'],
  datasets: [{
    label: 'Sample Data',
    data: [10, 20, 30, 25, 15, 40, 35], // Sample values
    backgroundColor: 'rgba(54, 162, 235, 0.2)', // Background color
    borderColor: 'rgba(54, 162, 235, 1)', // Border color
    borderWidth: 1 // Border width
  }]
};
```
### Sample Output:

    A line chart rendered on the web page, displaying the provided sample data with labels for each month and data points connected by lines. The chart is interactive, allowing users to hover over data points to view tooltips with additional information.