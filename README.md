# KurtGroup

To update the package please first go into the setup.py file and update the version number

You need twine to update the package: pip install twine

You will also need a PyPi account

After this you may use: python setup.py sdist

To update the package you then use: twine upload dist/*

After which you will have to type in your username and password
