FROM      ubuntu

# Copy testrun.sh files into the container

add	./testrun.sh       /tmp/

run cp /tmp/testrun.sh /usr/local/bin/ && chmod +x /usr/local/bin/testrun.sh

CMD ["testrun.sh"]
