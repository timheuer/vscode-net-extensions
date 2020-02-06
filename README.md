# .NET Core extensions.json
This repo is for an [extensions.json](https://code.visualstudio.com/docs/editor/extension-gallery#_workspace-recommended-extensions) file for .NET Core repositories to keep in their code base's `.vscode` directory to help those using the repository ensure they have the best experience for current extensions ecosystem and their particular .NET Core experience

## File variants
This repo contains several variants and encourages contributions to ensure those are the best experiences.

- extensions.json: A base file that serves as a 'minimum' set of extensions for the most common .NET Core experience (e.g., debuggers, etc)
- extensions-fsharp.json: Specific for F# sharp development experiences

## What this repo is NOT and Contributing
There are MANY extensions out there for VS Code that are amazing.  Individuals have also created wrapper extensions to try to encapsulate a single package that basically is just a dependency extension to install others.  These are great!  This is not what this repo is for to create more of those or to declare any 'winner' in those.  Often those include not only some core functionality but items of preference (icons, fonts, highlighting rules) that may differ from developer to developer.  When contributing ideas to the files in this repo, I don't want to include those extension preference pack style recommendations but identify specific core 'leaf' extensions.