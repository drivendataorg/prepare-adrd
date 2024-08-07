## Data access

To access the data in STATA, SAS or SPSS you need to Sign up at: https://www.mhasweb.org/Home/index.aspx, once you signed up you have inmidate access to all the data.
The term uses are as following:

By registering you are agreeing to the following terms and conditions

* User will not attempt to identify subjects/study participants.
* User will not distribute his/her MHAS username and password.
* User will not transfer MHAS public release data to a third party(-ies), with the exception of staff or students for whom said user is directly responsible.
* User must properly credit MHAS for the use of any data and the link to the public data must be included.

Once signed up you can download the harmonized MHAS in: https://www.mhasweb.org/DataProducts/HarmonizedData.aspx, under the title 'Harmonized MHAS File (H MHAS) (Latest release: Version C.2)'. You can dowload the cognitive ancillary studies at: https://www.mhasweb.org/DataProducts/AncillaryStudies.aspx, under the title 'Cognitive Aging Ancillary Study (Mex-Cog)' for years 2021 and 2016. The best way to loading it into pandas without losing any of the information is to export a CSV file directly from STATA.

## Environment Config

To run the notebook cells you need the following data from the MHAS repository:

* Main harmonized MHAS data
* Raw MexCog 2016 data
* Harmonized MexCog 2016 data
* Raw MexCog 2021 data

Then,

Create a virtual environment:

```
python -m venv virtual_env
```

Activate virtual environment:

```
source virtual_env/bin/activate
```

Install required packages to run code properly:

```
pip install -r requirements.txt
```

After this process, you should connect the environment to the jupyter notebook to successfully run the notebook cells to your convenience.
