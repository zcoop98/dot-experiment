# This is a README!
This is where I'll keep track of all steps taken to make my project, including useful links and tidbits of info that I've found handy 
## Steps
1. Create repo in github, make sure "Initialize this repository with a README" checkbox is checked!
2. Clone repo to local using *Clone or download* button on github
3. Download .NET Core **SDK**: https://dotnet.microsoft.com/download
4. Open command prompt and navigate to local repo directory
6. Execute `dotnet new console`
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
6. Execute `dotnet build`
7. Execute `dotnet run`

This should print `Hello World!` in the command prompt.

---
General Useful Links:
* `.gitignore` template for various project types https://github.com/github/gitignore
 * VS project `.gitignore` template https://github.com/github/gitignore/blob/master/VisualStudio.gitignore
* *What not to save into a Git repo* https://zellwk.com/blog/what-not-to-save-into-a-git-repo/
* git documentation https://git-scm.com/doc
* Creating and managing ssh keys https://clubmate.fi/how-to-setup-and-manage-multiple-ssh-keys/
* `ssh-keygen` documentation https://www.ssh.com/ssh/keygen/#sec-What-Is-ssh-keygen
