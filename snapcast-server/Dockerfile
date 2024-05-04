# Use Alpine Linux as the base image
FROM alpine:latest
RUN apk add --no-cache snapcast-server
EXPOSE 1704
EXPOSE 1705
EXPOSE 1780
# Start the Snapcast server
# CMD ["snapserver", "--fifo=/snap_source/snapfifo", "--nodaemon"]
# Note source cannot be configured via command line, defults to pipe:///tmp/snapfifo?
ENTRYPOINT ["snapserver"]

