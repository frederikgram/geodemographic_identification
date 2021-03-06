# Geodemographic Identification
<img align="right" src="https://github.com/frederikgram/Geodemographic_Identification/blob/master/example.jpg?raw=true)">

Say that a bussiness wanted to find the region which has the lowest population of elders, highest concentration of libertarian voters and greatest quantity of banks per square kilometer, this web-service ranks municipalicties by these properties using user-provided priorities for each metric, visualizing this as a heatmap of danish counties and exposing the downloadable raw data to the user.

All of the data used can be found on [statistikbanken.dk](https://www.statistikbanken.dk) which makes an incredible amount of very detailed data available to the public free of charge.

📌 It is highly recommended to read the [innovation.pdf](https://github.com/frederikgram/Geodemographic-Identification-Protoype-and-Report/blob/master/innovation.pdf) file as this contains a detailed description of the prototype, business applicability, and potential monitization strategies. 



## Prerequisites
The only requirements barring the requirements.txt file which will be used to install the relevant Python packages, is Python 3.8 and a corresponding PIP installation.
## Installation
Clone the repository
```
$ git clone https://github.com/frederikgram/innovation.git
$ cd innovation
```

Create a virtual environment

```
$ python3 -m venv env
```

Activate the environment
- For Linux Machines

```
$ source ./env/bin/activate
```

- For Windows Machines

```
$ env\Scripts\activate.bat
```

Install dependencies

```
$ pip3 install -r requirements.txt
```

## Usage
To initialize the web-service, change directory into `webservice`
```
$ cd webservice
```

Setup the FLASK environment

- For Linux Machines

```
$ set FLASK_APP=app.py
```
- For Windows Machines

```
$ export FLASK_APP=app.py
```
From here the webservice can be started using:
```
$ flask run
```
and is now accessible at `localhost:5000`
