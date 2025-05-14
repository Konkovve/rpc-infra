FROM alpine:latest
WORKDIR /app
COPY ./bin/user-service .
RUN chmod +x user-service
CMD ["./user-service"]