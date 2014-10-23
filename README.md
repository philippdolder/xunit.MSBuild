MSBuild integration for xUnit
=============================

Runs [xunit tests](https://github.com/xunit/xunit) using the official xunit MSBuild task with every build. Includes official xUnit MSBuild task binaries.
The xunit.MSBuild.targets is added to your Visual Studio Projects that reference the xunit.MSBuild nuget package.
A new version will be provided for every version of xunit. The xunit.MSBuild will always exactly match the version of xunit.

By default the xunit tests are run when building in `Release`configuration.
You can change when the xunit tests are executed by overriding the value of `RunXunitTests` in your `csproj`, `msbuild` or `targets` file.

Grab the version matching your xunit version from [NuGet](https://www.nuget.org/packages/xunit.MSBuild).
If the version is missing, please create an issue here, and I will upload a suitable package to NuGet.
