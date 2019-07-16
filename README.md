# This is a README!
## This is where I'll keep track of all steps taken to make my project, including useful links and tidbits of info that I've found handy 
---
## Steps


1. Create repo 
2. Download .NET Core **SDK**: https://dotnet.microsoft.com/download
3. Open command prompt and navigate to local repo directory
4. Execute `dotnet new console`
  * Details: https://docs.microsoft.com/en-us/dotnet/core/tools/dotnet-new?tabs=netcore22
  * Useful options for command: https://docs.microsoft.com/en-us/dotnet/core/tools/dotnet-new?tabs=netcore22#options
    * `-h | --help`: Displays help for invoked command
    * `--dry-run`: Displays a summary of what would happen if the given command were run if it would result in a template creation
    * `--force`: Forces content to be generated even if it would change existing files. *Required* when output directory already contains a project
    * `-i|--install <PATH|NUGET_ID>`: Installs a source or template pack from the `PATH` or `NUGET_ID` provided
    * `-lang|--language {C#|F#|VB}`: The language of the template to create; language accepted varies by the template
    * `-n|--name <OUTPUT_NAME>`: The name for the created output. If no name is specified, the name of the current directory is used
    * `--nuget-source`: Specifies a NuGet source to use during install
    * `-o|--output <OUTPUT_DIRECTORY>`: Location to place the generated output, default is current directory
    * *NOTE:* Depending on the args, this command can be used to display possibilities rather than generate a new project immediately
5. Execute `dotnet build`
6. Execute `dotnet run`

This should print `Hello World!` in the command prompt.
