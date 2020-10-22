COMMAND: dotnet --version
COMMAND: dotnet --info
COMMAND: dotnet -h
COMMAND: dotnet new sln [creates a solution]
COMMAND: dotnet new classlib -n Domain [a template class library is created]
COMMAND: dotnet new classlib -n Application
COMMAND: dotnet new classlib -n Persistence

.NET Core SDK (3.1.403)
Usage: dotnet [runtime-options] [path-to-application] [arguments]

Execute a .NET Core application.

runtime-options:
--additionalprobingpath <path> Path containing probing policy and assemblies to probe for.
--additional-deps <path> Path to additional deps.json file.
--fx-version <version> Version of the installed Shared Framework to use to run the application.
--roll-forward <setting> Roll forward to framework version (LatestPatch, Minor, LatestMinor, Major, LatestMajor, Disable).

path-to-application:
The path to an application .dll file to execute.

Usage: dotnet [sdk-options] [command] [command-options] [arguments]

Execute a .NET Core SDK command.

sdk-options:
-d|--diagnostics Enable diagnostic output.
-h|--help Show command line help.
--info Display .NET Core information.
--list-runtimes Display the installed runtimes.
--list-sdks Display the installed SDKs.
--version Display .NET Core SDK version in use.

SDK commands:
add Add a package or reference to a .NET project.
build Build a .NET project.
build-server Interact with servers started by a build.
clean Clean build outputs of a .NET project.
help Show command line help.
list List project references of a .NET project.
msbuild Run Microsoft Build Engine (MSBuild) commands.
new Create a new .NET project or file.
nuget Provides additional NuGet commands.
pack Create a NuGet package.
publish Publish a .NET project for deployment.
remove Remove a package or reference from a .NET project.
restore Restore dependencies specified in a .NET project.
run Build and run a .NET project output.
sln Modify Visual Studio solution files.
store Store the specified assemblies in the runtime package store.
test Run unit tests using the test runner specified in a .NET project.
tool Install or manage tools that extend the .NET experience.
vstest Run Microsoft Test Engine (VSTest) commands.

Additional commands from bundled tools:
dev-certs Create and manage development certificates.
fsi Start F# Interactive / execute F# scripts.
sql-cache SQL Server cache command-line tools.
user-secrets Manage development user secrets.
watch Start a file watcher that runs a command when files change.

Run 'dotnet [command] --help' for more information on a command.
PS C:\Users\ALIA\Documents\ASP.NET Projects\social_media>
