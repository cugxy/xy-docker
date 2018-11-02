FROM oscarfonts/geoserver
COPY fonts/* /usr/share/fonts/
RUN cd /usr/share/fonts/
RUN mkfontscale
RUN mkfontdir
RUN fc-cache