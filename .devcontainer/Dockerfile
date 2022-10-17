FROM qmcgaw/latexdevcontainer:latest-full

COPY ./requirements.txt /tmp/pip-tmp/

RUN apt update -y && apt install fontconfig python3 python-is-python3 python3-pip -y
RUN python -m pip install -r /tmp/pip-tmp/requirements.txt