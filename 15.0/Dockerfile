FROM ubuntu:20.04
MAINTAINER Brindsoft Technologies <info@brindsoft.com>

# Generate locale C.UTF-8 for postgres and general locale data
ENV LANG C.UTF-8
# Install some deps, lessc and less-plugin-clean-css, and wkhtmltopdf
RUN apt-get update && apt-get install -y tzdata

ENTRYPOINT ["tail"]
# CMD ["-f","/dev/null"]