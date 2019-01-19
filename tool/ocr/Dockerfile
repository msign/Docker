FROM ubuntu:14.04

RUN apt-get update
RUN apt-get install tesseract-ocr

ADD ./assets/lang/chi_sim.traineddata /usr/share/tesseract-ocr/

VOLUME [ "/data" ]