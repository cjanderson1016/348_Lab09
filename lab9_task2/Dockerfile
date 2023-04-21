# Set the base image to use
FROM gcc:latest
# Copy the C program into the container
COPY cprgm.c .
# Compile the C program
RUN gcc -o cprgm cprgm.c
# Set the command to run when the container starts
CMD ["./cprgm"]