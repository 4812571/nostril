FROM fuzzers/atheris:2.0.7-python3.9
COPY . /nostril

WORKDIR /nostril
RUN pip install .
RUN chmod +x /nostril/mayhem/fuzz.py