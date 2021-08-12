# dapr
A repo for learning dapr

## Running
To run the application, use the following code: 

`dapr run --app-id DaprCounter dotnet run`

This will invoke the dapr runtime and start both the app and dapr sidecar. If you omit the app-id, Dapr will generate a unique name for the application. The final segment of the command, dotnet run, instructs the Dapr runtime to run the .NET application.
