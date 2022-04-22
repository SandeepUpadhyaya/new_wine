setup:
	python3 -m venv ~/.new_wine

	#source ~/.new_wine/bin/activate

install:
	pip install --upgrade pip &&\
		pip install -r requirements.txt

test:
	#python -m pytest -vv --cov=myrepolib tests/*.py

lint:
	pylint --disable=R,C,W1203,W0702 app.py

run:
	python new_app.py

all: install lint test