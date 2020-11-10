# Spring Boot & Vite+React App

A simple demo app of those two technologies working together

## Dependencies
```console
npm, node, vite (from npm)
```

## Building
### Client
To build the client you need to run the following command within the client directory:
```console
# for dev run
npm run-script dev
# for compiling
npm run-script build
```
### Server
To build the server you need to run the following command within the server directory:
```console
# for dev run
./gradlew bootRun
# for compiling
./gradlew assemble
```
### Full App
To build the full app into a single jar:
```console
./gradlew assembleJar
```

## Notice
If you want to run the frontend and backend separately, you'll need to proxy frontend port to backend port

## Variants
Master branch for Kotlin variant
<br>
Java branch, well you guess it

