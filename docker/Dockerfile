FROM python:3.11.5-slim-bookworm

RUN apt update
RUN apt install git -y

# Project initialization:
RUN pip install git+https://github.com/open-dis/open-dis-python 

# Creating folders, and files for a project:
COPY ./examples/ /code

