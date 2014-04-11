Regional-Plan-Association-Commuter-Sankey
=========================================

Regional Plan Association Commuter Data

<h3>Data Sources</h3>
The data is hosted on http://nycdata.pediacities.com/organization/regional-plan-association.

Two data sets are used in this visualization:  "Residence to Workplace Commute Patterns, RPA Counties" and "Workplace to Residence Commute Patterns, RPA Counties".
<h3>To run locally</h3>
To run a local copy of Jersey City Budget, clone this github project and run local server:

    git clone https://github.com/adlukasiak/Regional-Plan-Association-Commuter-Sankey 
    cd Regional-Plan-Association-Commuter-Sankey
    python -m SimpleHTTPServer

For visualization, in your Google Chrome browser:  

    http://localhost:8000/

<h3>JSON file</h3>
This project includes [ipython notebook](http://ipython.org/notebook.html) file that takes the csv file and builds json for the visualization.

You won't need to do this step, the result json file is [data/rpa_commute_res_emp.json](https://github.com/adlukasiak/Regional-Plan-Association-Commuter-Sankey/blob/gh-pages/data/rpa_commute_res_emp_top_100.json) and [data/rpa_commute_emp_res.json](https://github.com/adlukasiak/Regional-Plan-Association-Commuter-Sankey/blob/gh-pages/data/rpa_commute_emp_res_top_100.json).


This project is based on work by Mike Bostock:  http://bost.ocks.org/mike/sankey/
