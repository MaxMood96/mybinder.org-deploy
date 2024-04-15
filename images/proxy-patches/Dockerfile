FROM python:3.12.3-alpine
ADD requirements.txt /tmp/requirements.txt
RUN pip install --no-cache -r /tmp/requirements.txt
ADD proxy-patches /usr/local/bin/proxy-patches
USER nobody
CMD /usr/local/bin/proxy-patches
