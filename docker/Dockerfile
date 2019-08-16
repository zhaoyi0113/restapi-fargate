FROM python
RUN pip install pipenv

ADD . /develop
WORKDIR /develop

RUN pipenv install
CMD pipenv run start