# How to Contribute #

We'd love to hear your feedback. Please open new issues describing any bugs,
feature requests or suggestions that you have.

## Setting the project up

Clone the repository:

```bash
git clone https://github.com/FlorianRauscha/android-lib-boilerplate.git
cd android-lib-boilerplate
```

Point Gradle to your copy of the Android SDK:

```
echo "sdk.dir=/path/to/my/android/sdk" > local.properties
```

Run the tests:

```
./gradlew test
```

## Building the library AAR

```
./gradlew aar
```
