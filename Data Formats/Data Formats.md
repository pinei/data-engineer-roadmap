# Data Formats

| Row Based                                                    | Column Based                                                 |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| Better to use when all fields needs to be accessed           | Better to use when you only need to access specific fields   |
| Suitable for write intensive operation (logging, streaming)  | Suitable for data exploration (read intensive, complex or analytical querying, low latency data) |
| Storage size optimization limited due to reduced ability of data compression | Better storage size optimization capabilities due to little distinct or unique values in columns |
| Records are easy to read and write                           | Read and write operations are slower                         |
| Not efficient in performing operations applicable to the entire datasets (e.g. aggregation) | Efficient in performing row-wise operations based on column values |

