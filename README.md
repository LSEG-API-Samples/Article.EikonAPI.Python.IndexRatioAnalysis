# Forward Looking Index Ratio Analysis
Investment bankers, strategists, and analysts frequently need to pull historical forward valuation ratios for indices, including EV multiples that don't exist in our IBES aggregates data sets. Using CodeBook and Python, winners of the Americas Hackathon, the **GBC Angels** were able to overcome the limitations of Excel to create aggregates based on underlying constituents, thus addressing key performance, methodology and use of historical constituents challenges. Their collaboration on creating a scalable solution underscores how workflow knowledge + a little code can create value to meet customer needs.

Refer to the [Forward Looking Index Ratio Analysis](https://developers.refinitiv.com/en/article-catalog/article/forward-looking-index-ratio-analysis) article defined within the Refinitiv Developer Community for more details.

## <a id="disclaimer"></a>Disclaimer

The source code presented in this project has been written by Refinitiv only for the purpose of illustrating the concepts of creating example scenarios using Refinitiv APIs.

***Note:** To [ask questions](https://community.developers.refinitiv.com/index.html) and benefit from the learning material, I recommend you to register on the [Refinitiv Developer Community](https://developers.refinitiv.com)*

## <a name="prerequisites"></a>Prerequisites

To execute any workbook, refer to the following:

License(s):

- A Refinitiv desktop license (Refinitiv Eikon or Refinitiv Workspace) that has API access.  For indices, a direct license with the index provider may be required to pull constituents' data


[Development Environment](https://developers.refinitiv.com/en/api-catalog/eikon/eikon-data-api/tutorials#setting-up-a-python-development-environment)

- Notebook can be directly loaded into Refinitiv CodeBook
- Packages: [eikon](https://pypi.org/project/eikon/) [pandas](https://pypi.org/project/pandas/) numpy plotly [ipywidgets](https://ipywidgets.readthedocs.io/en/latest/)

## <a name="setup"></a>Setup

The package includes a single Jupyter Notebooks demonstrating features of the service.  Depending where you plan to access the content from, you will need provide the proper credentials:

* **Desktop Access**

  The notebook has been set up and tested to access data within the desktop, whether Refinitiv Workspace or Eikon.

  

### <a id="authors"></a>Authors

* **Susan Cluzel**

* **Caroline Andrade**

* **Marian Kelly**

* **Nick Zincone**

  

