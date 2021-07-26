# ARMA Conference 2021
Material to accompany on-demand webinar "How to harness the power of automation and APIs in your day-to-day RMA job"

In order to import the Power Automate Desktop (PAD) flow, simply open the flow_code file in this repository and copy the code. In your PAD, click Create a New Flow, and after clicking on the empty flow body, press CTRL+V to paste. It should populate the flow with the code, and all you need to do is save it, close and then click the Play icon to run. It will ask you for two variables:
- a document path to your Excel spreadsheet comprising of a list of DOIs in Column A, without a header, and an empty column B where the flow will log the responses from the API
- and your email address so it can append it to the API query, which is something Unpaywall asks us to do when using their API

If you have any questions or issues with the above, please feel free to contact me at FPabstSilva@cardiffmet.ac.uk
