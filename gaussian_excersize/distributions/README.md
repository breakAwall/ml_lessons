# info about the project

this is me trying to use pypi, create a python package

Instrution to creating pypi file

cd 5_exercise_upload_to_pypi
python setup.py sdist
pip install twine

# commands to upload to the pypi test repository
twine upload --repository-url https://test.pypi.org/legacy/ dist/*
pip install --index-url https://test.pypi.org/simple/ distributions

# command to upload to the pypi repository
twine upload dist/*
pip install distributions