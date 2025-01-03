Important note: This application is a command line tool which don't have any user interface. To use this application, basic knowledge of how to run and send arguments to CLI applications is a must.

This application can run on macOS, Windows & Linux for Arm64, x64, x86 architectures. Executable types varies depending on OS.

# macOS

You can install by Homebrew (preferred) or as .NET tool.

#### Homebrew tap configuration & package installation
```shell
brew tap test-alp/homebrew-nuget-publish-action && brew install NugetPublishAction
```

Ref: https://github.com/test-alp/homebrew-nuget-publish-action

# Windows && Linux

You can install by .NET CLI (preferred) or standalone executable that can be found on assets.

# Install by .NET CLI

.NET tool can be installed by .net cli (preferred), could be downloaded manually from https://nuget.org/packages/NugetPublishAction/ or directly from assets.

#### .NET CLI
```shell
dotnet tool install NugetPublishAction -g
```

# Accessing Application

Installing the application globally provides access to the `nugetpublishaction` command in your terminal.

```
nugetpublishaction [command]

nugetpublishaction help [command]
```

## Command Not Found Issue Solution

For macOS and Linux You should add your `.dotnet/tools` (path may change for your installation choices) to your PATH environment variable.

For macOS - Z Shell add the following line to your `~/.zshenv` file.
```shell
export PATH="$PATH:/Users/[your-account-name]/.dotnet/tools"
```

For Linux Bash add the following line to your `~/.profile` file.
```shell
export PATH="$PATH:/home/[your-account-name]/.dotnet/tools"
```
