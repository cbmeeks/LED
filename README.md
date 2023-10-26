# Template for Pico Project

You can use this simple project for setting up a basic C/C++ project using CLion or whatever IDE you want.

Please not the `pico-sdk` is required and should either be exported as an environment variable or set in the project environment variables.

For example:

```PICO_SDK_PATH=/home/cbmeeks/sdk/pico/pico-sdk```

You should also include the `pico_sdk_import.cmake` file in your project.
If you want to use the optional pico_extras, then include it as well.


