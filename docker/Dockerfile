FROM python
RUN pip install pipenv

EXPOSE 5000

ADD . /develop
WORKDIR /develop

RUN pipenv install
CMD pipenv run start