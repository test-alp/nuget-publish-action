Important note: This application is a command line tool which don't have any user interface. To use this application, basic knowledge of how to run and send arguments to CLI applications is a must.

This application can run on macOS, Windows & Linux for Arm64, x64, x86 architectures. Executable types varies depending on OS.

# macOS

You can install by Homebrew (preferred) or by [.net tool](#install-as-net-tool)

Homebrew tap configuration & package installation
```shell
brew tap photo-cli/homebrew-photo-cli && brew install photo-cli
```

Ref: https://github.com/test-alp/homebrew-nuget-publish-action

## .NET tool (refer to following section)

# Windows && Linux

You can install by [.net tool](#install-as-net-tool) (preferred) or standalone executable that can be found on assets.

# Install as .NET tool

.NET tool can be installed by .net cli (preferred) and could be downloaded manually from https://nuget.org/packages/NugetPublishAction/${{env.VERSION}} or directly from assets.

.NET CLI
```shell
dotnet tool install photo-cli -g
```
