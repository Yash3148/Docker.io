# Use an official Go runtime as a base image
FROM golang:1.17

# Create a directory for your Go application
WORKDIR /app

# Copy your Go application files into the container
COPY . .

# Build your Go application
RUN go build -o main .

# Expose the port your application will run on
EXPOSE 8080

# Start your Go application
CMD ["./main"]
