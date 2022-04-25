## To start:
1. docker build -t sample:dev .
2. docker run \
    -it \
    --rm \
    -v ${PWD}:/app \
    -v /app/node_modules \
    -p 3001:3000 \
    sample:dev