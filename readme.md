# PinballPDX Website

This project is a possible replacement for the PinballPDX website hosted at:

https://pinballpdx.org/

## Early Development

> [!WARNING]
> This project is in early development and should be considered a prototype or proof of concept.
> It is not ready for general use.

## Prerequisites

You need a Java JDK and [Apache Maven](https://maven.apache.org/) to build and run this project.
We use the [Eclipse Temurin](https://adoptium.net/temurin/) Java JDK, but other JDKs may also work.

This project works with following versions, but other versions may also work:

- Eclipse Temurin:
    - `25.0.1+8-LTS`
- Apache Maven:
    - `3.9.12`

## Building and Running

To build this project: `mvn package`

To run this project: `mvn spring-boot:run`

To access the match page: http://localhost:8080/league/match

## License

```text
Copyright 2026 Jeffrey J. Weston <jjweston@gmail.com>

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
