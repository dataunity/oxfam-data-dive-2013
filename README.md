oxfam-data-dive-2013
====================

Code for DataKind DataDive 27 July 2013

Disclaimer: code has been hacked together! Don't expect to see best practices - the code could generally do with a tidy up.

The data was transformed using Python Pandas then prepared as a flat CSV file for D3. This means the data can be viewed on a static site (like GitHub 'Pages' as used below).

The next stage is to put checkboxes/dropdowns to fiilter the number of series that appear on the chart (there's too much data presented at one time).

The GitHub repository contains a directory called 'Data Processing' containing an IPython Notebook. To run the Notebook, navigate to the 'Data Processing' folder in the command line and run the following command:

ipython notebook --pylab=inline

Run the notebook files to prepare the data for D3 visualisation (the files were converted manually from Excel to CSV beforehand). The processed files were then copied into the root dir of the site.
