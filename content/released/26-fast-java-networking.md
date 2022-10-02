---
title: "Fast java Serialization and Networking"
date: 2022-10-01T22:43:43-07:00
weight: 25
draft: false
---
Serialization can be a big deal in Java (or any other language for that matter). Some libraries can take  10s of microseconds while others can be as fast as 20 nanoseconds.\
[Simple Binary Encoding (SBE)](https://github.com/real-logic/simple-binary-encoding) is used together with [Aeron](https://github.com/real-logic/aeron) and is crazy fast. \
[Fast Binary Encoding (FBE)](https://github.com/chronoxor/FastBinaryEncoding)

Other than Aeron [KryoNet](https://github.com/EsotericSoftware/kryonet) is a Java library that provides a clean and simple API for efficient TCP and UDP client/server network communication using NIO. KryoNet uses the [Kryo serialization library](https://github.com/EsotericSoftware/kryo).

- {{< tag latency >}} {{< tag networking >}} {{< tag serialization >}}
