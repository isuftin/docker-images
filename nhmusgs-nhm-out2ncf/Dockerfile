FROM nhmusgs/base

LABEL maintainer="ashalper@usgs.gov"

USER $USER

WORKDIR /home/$USER

ENV NUMDAYS=60

ENTRYPOINT \
  ["/opt/conda/bin/python", "-u", "/usr/local/src/onhm-runners/out2ncf/prms_outputs2_ncf.py"]