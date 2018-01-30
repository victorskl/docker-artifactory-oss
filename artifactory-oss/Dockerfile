FROM docker.bintray.io/jfrog/artifactory-oss

# Set the timezone - Debian/Ubuntu
ENV TZ=Australia/Melbourne
RUN ln -snf /usr/share/zoneinfo/$TZ /etc/localtime \
 && echo $TZ > /etc/timezone \
 && dpkg-reconfigure -f noninteractive tzdata