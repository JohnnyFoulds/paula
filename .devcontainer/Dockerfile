FROM tensorflow/tensorflow:2.11.0-gpu

 COPY requirements.txt /tmp/pip-tmp/
 RUN pip3 --disable-pip-version-check --no-cache-dir install -r /tmp/pip-tmp/requirements.txt \
    && rm -rf /tmp/pip-tmp