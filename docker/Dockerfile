FROM python
RUN pip install pipenv

ADD . /develop
RUN pipenv install
CMD pipenv run start