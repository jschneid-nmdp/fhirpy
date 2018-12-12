# fhirpy

An exploration of HL7 FHIR using Python.  Topics include the **fhirclient**
package, OpenID Connect and OAuth 2, and SMART on FHIR.

## Overview

See also:

https://smart-on-fhir.github.io/client-py  
https://github.com/smart-on-fhir/client-py

## Setup

Clone the Git repository.

```
git clone https://github.com/jschneid-nmdp/fhirpy.git
cd fhirpy
```

Create, activate, and initialize a Python virtual environment.

```
virtualenv -p python3 venv
source venv/bin/activate
pip install fhirclient
pip install jupyter
```

Start Jupyter notebook.

```
jupyter notebook
```

Use web browser to interact with fhirclient.ipynb notebook.
