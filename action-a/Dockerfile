FROM ubuntu
RUN apt-get -y update
RUN apt-get -y install apt-utils
RUN apt-get -y install g++
RUN apt-get -y install libglew-dev
RUN apt-get -y install freeglut3-dev
ADD script.sh /script.sh
ADD solarSystem.cpp /Hut.cpp
RUN chmod +x /script.sh
CMD /script.sh
