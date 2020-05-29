<p align="center">Click below to start a ready-to-code IDE for java using <a href="https://quarkus.io/"> Quarkus </a>

<p align="center">
  <a href="https://gitpod.io/#https://github.com/ArthurFritz/quarkus-start-code">
    <img src="https://img.shields.io/badge/Click-and%20code-blue?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAYAAAAf8/9hAAABI0lEQVQ4T2NkIAH8T67+j66ckRj9v97cAGtkLV+Movz5tasMeA34/ebGzv8MDG7IumCGgDSDAE4DYLaiuxBkAEwzTgN+vb3xi+E/AytIQdZXFhQzJny7DOZ/SlqI2wXItiMbMOf5G4Yv/M/hBvJoBjLCvQAL4d+dsSg2wgwAaQYBrAbg0gzS8Oo/A4PM3Q9wQ2EGgGwHhwFy3KLbDlLw6/V1jJhmZGK5z63uq4QSiDXNHeC4rssMgMf31xITrMkEZjtWA5offAZrAkUV37x4DAOQNWNEI8w7YM1tQQwMErwoIY7NORixANJcqCYCVju3whse51LHN2BNdCgGgDSDFIbHp4DDo/8WJOpAgKAB2Jz3zDIAbBAuzRhhgG4IyAB8mkHqAfEChKXnwSewAAAAAElFTkSuQmCC"/>
  </a>
</div>

<p align="center">🎉 <a href="https://github.com/db1group/click-and-code/blob/master/CONTRIBUTING.md">Click here to contribute</a> 🥳</p>

# quarkus-getting-started project

This project uses Quarkus, the Supersonic Subatomic Java Framework.

If you want to learn more about Quarkus, please visit its website: https://quarkus.io/ .

## Running the application in dev mode

You can run your application in dev mode that enables live coding using:
```
./mvnw quarkus:dev
```

## Packaging and running the application

The application can be packaged using `./mvnw package`.
It produces the `quarkus-getting-started-1.0.0-SNAPSHOT-runner.jar` file in the `/target` directory.
Be aware that it’s not an _über-jar_ as the dependencies are copied into the `target/lib` directory.

The application is now runnable using `java -jar target/quarkus-getting-started-1.0.0-SNAPSHOT-runner.jar`.

## Creating a native executable

You can create a native executable using: `./mvnw package -Pnative`.

Or, if you don't have GraalVM installed, you can run the native executable build in a container using: `./mvnw package -Pnative -Dquarkus.native.container-build=true`.

You can then execute your native executable with: `./target/quarkus-getting-started-1.0.0-SNAPSHOT-runner`

If you want to learn more about building native executables, please consult https://quarkus.io/guides/building-native-image.
