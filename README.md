**Activate the virtual environment**
```
Mac users:
source blockchain-env/bin/activate

Windows users:
(make sure to install conda)
conda activate blockchain-env
```

**Install all packages**
```
pip install -r requirements.txt
```

**Run the tests**
Make sure to activate the virtual environment.
```
python -m pytest backend/tests
```

**Run the application and API**

Make sure to activate the virtual environment.
```
python -m backend.app
```

**Run a peer instance**
Make sure to activate the virtual environment
```
Mac users:
export PEER=True && python -m backend.app

Windows users:
set PEER=True
optional: echo %PEER%  to confirm it was set
python -m backend.app
```

**Run the frontend**
While in the frontend directory:
```
npm run start
```

**Seed the backend with data**

Make sure to activate the virtual environment.

```
Mac
export SEED_DATA=True && python -m backend.app
Windows
set SEED_DATA=True
optional: echo %SEED_DATA% to confirm it was set
python -m backend.app
```
