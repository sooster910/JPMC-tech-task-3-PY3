<p align="center">
<a href="https://www.insidesherpa.com/virtual-internships/prototype/R5iK7HMxJGBgaSbvk/Technology%20Virtual%20Experience" target="_blank">
<img src="https://insidesherpa-assets.s3-ap-southeast-2.amazonaws.com/icons/jpmorgan/github+repo+images/jpm+gitub+.png"></a>
</p>
<img src="public/images/certification.png" alt="certification">


<h2>Demo</h2>
<img src="public/images/JPMorgan_Demo.gif" alt="demo">
<h1> Introduction</h1> 
<b> Experience Technology at JP Morgan Chase </b>
<p>Try out what real work is like in the technology team at JP Morgan Chase & Co. Fast track to the tech team with your work.</p>

<h2 id="task"> Module 3 Task Overview </h2>
Display data visually for traders.
Use Perspective to create the chart for the trader’s dashboard.

<b>Aim:</b> Use Perspective to generate a chart that displays the data feed in a clear and visually appealing manner for traders to monitor this trading strategy. Basically, you have to modify the existing live chart to be able to (1) track and display the ratio between the two stock prices (2) show the historical upper and lower bounds of the stocks' ratio (3) and finally, show 'alerts'  whenever these bounds are crossed by the ratio.

<ol>
	<li>Please clone this repository to start the task</li>
	<li>From the existing live graph, update it to track the ratio between two stocks over time and NOT the two stocks’ top_ask_price over time.</li>
	<li>Update the graph to also track the historical upper and lower bounds of the stocks' ratio</li>
	<li>Trigger 'alerts' (i.e. draw red lines) on the graph whenever the bounds are crossed by the calculated ratio in a specific time period</li>
	<li>Upload a git patch file as the submission to this task</li>	
  	<li>Upload a video detailing your process and work</li>
</ol>



<h2>How to Run</h2>
<p>Similar to Task 2, start the data feed server by running the python server</p>
<p>Make sure your terminal / command line is in the repository first before doing any of this.</p>
<p>If you are using Windows, make sure to run your terminal/command prompt as administrator.</p>

<code>python datafeed/server3.py</code>

If you encounter an issue with `datautil.parser`, run this command: 

	pip install python-dateutil

If you don't have pip, you can install it from: https://pip.pypa.io/en/stable/installing/

Run <code>npm install && npm start</code> to start the React application.

It's okay to have audit warnings when installing/running the app.

If you don't have `npm` (although you should if you followed the set up / installation part), you can install the recommended version alongside NodeJS from: https://nodejs.org/en/

The recommended version are node v11.0.0 and npm v6.4.1

Open http://localhost:3000 to view the app in the browser. The page will reload if you make edits.

<h2>Known Issues</h2>
Some users seem to be having trouble with the unzipped version of the node_modules back up            for windows. 
This is the alternative unzipped version:
https://drive.google.com/drive/folders/1wzIlt-OeiK6nYEHidsOGlpJ_KmeoPVXz

Note: You may need to (hard) refresh the link to the public gdrive to see all of the files/folders e.g. @jpmorganchase/perspective as it takes gdrive a bit to load them for you.

<h2>How to fix the code to meet the objectives</h2>
<p>To make the changes necessary to complete the objectives of this task, <a href="https://insidesherpa.s3.amazonaws.com/vinternships/companyassets/Sj7temL583QAYpHXD/making_changes_m3_v2.pdf">follow this guide</a>.</p>

