FROM python:3.6-slim

RUN pip install benchsuite.rest benchsuite.backends benchsuite.stdlib

EXPOSE 5000

ENV BENCHSUITE_CONFIG_FOLDER /

ENTRYPOINT ["benchsuite-rest", "run"]
