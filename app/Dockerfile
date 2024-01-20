FROM python:3.9-buster
ENV PYTHONUNBUFFERED=1

WORKDIR /src
RUN pip install --upgrade pip

RUN python -m pip install streamlit requests

CMD [ "streamlit","run","main.py" ]