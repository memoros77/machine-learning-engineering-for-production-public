install:
	pip install --upgrade pip &&\
		pip install -r requirements.txt

lint:
	pylint --disable=R,C ./app/*.py

format:
	black ./app/*.py

test:
	python -m pytest -vv --cov=main ./app/test_clf.py