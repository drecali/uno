# Guidelines for authoring tests


## integration testing

### Concepts

- `Constants.cs`
- `Run(xxxx)` specifics the full class path to the control
- `SamplesApp*`
- https://github.com/unoplatform/Uno.UITest

### Dev Loop

1. Start emulators and deploy application (iOS and Android)
1. Start without debugging to ensure the webserver is running (webasm)
1. Adjust https://github.com/unoplatform/uno/blob/dev/ghuntley/doc/testing-guidelines/src/SamplesApp/SamplesApp.UITests/Constants.cs to specify which platform to test
1. Run the test via test explorer (or resharper)

### See Also

- https://github.com/unoplatform/uno/blob/dev/ghuntley/doc/testing-guidelines/src/SamplesApp/SamplesApp.UITests/Constants.cs
- https://github.com/unoplatform/Uno.UITest
