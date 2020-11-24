# Acoustic engineering playground

## Pre-requirements
I have tested it only on Mac OS X, i believe all commands
should be the same on Linux. It might or might not work on
Windows, I do not have a machine at hand to try it. Feedback/support is very welcome!
 - python3
 - virtualenv

## Usage
 - create virtualenv (needed only once, on project setup)

   ```virtualenv -p `which python3` venv```

 - setup python environment (needed each time after logout)

   ```source venv/bin/activate```

 - install requirements (needed only on project setup / reqs update)

   ```pip install -r requirements.txt; pip install -r requirements-dev.txt```

 - run notebook:

   ```jupyter notebook```

## Contents
 - [Custom-shaped room response calculation](notebooks/custom_shaped_room.ipynb)


