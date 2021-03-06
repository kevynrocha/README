# Producers

Producer are the source of data, typically generated by an external system in the application. Producers are responsible of putting the data into the stream with the proper schema. This layer contains a mix of services that communicates with certain streams to emit data.

## Guidelines

- Batch writes to the streams with [`PutRecords`](https://docs.aws.amazon.com/kinesis/latest/APIReference/API_PutRecords.html).

## Tools

- [Kiner](https://github.com/bufferapp/kiner): Kinesis Python Producer with error handling.
