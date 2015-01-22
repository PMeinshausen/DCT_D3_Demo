# DCT_D3_Demo
D3 Demo for DCT 2015

This README will contain a few cursory instructions. There are many great D3 intro tutorials floating around the web. I also highly recommend the book ["Interactive Data Visualization for the Web"](http://shop.oreilly.com/product/0636920026938.do) by Scott Murray. And of course, if you have any questions, please feel free to email me at paul.meinshausen@teradata.com

## Set up a Python web server

The best way to get started with D3 is to run visualizations from a Python miniserver running in your project directory. This is a fairly simple process (assuming you're using Python version 2.x. Also, if you're using Windows, you'll need to make sure you have Python installed):

1) Using the command line, navigate to the directory/folder where you will store your visualization scripts/files.

2) Run the following script: python -m SimpleHTTPServer 8888 &

Once you've started the SimpleHTTPServer, open a browser and navigate to http://localhost:8888/. This is where you'll be able to view the visualization you build. 
