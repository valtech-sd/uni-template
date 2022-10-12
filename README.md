# uni-template
Repository template for Unity project (Owner Natan Couture Dumais)

## Included In This Template
1. TextMeshPro

## Software Requirements
1. [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) to use the repository.
1. [Git LFS](https://git-lfs.github.com/) to access the large asset files in the repository.
1. [Unity Hub](https://unity3d.com/get-unity/download) to manage Unity versions and projects and to install the Unity editor.
1. [a script editor](https://www.dunebook.com/best-unity-ide/) to edit scripts.

## How To Pull the Project
1. Download all needed tools from listed software requirements above.
1. [Clone the repostory](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository) from GitHub.
1. Use LFS to pull all files: `git lfs pull`.  Otherwise, you may get errors from missing expected files.
1. In Unity Hub > Installs, install the Unity Editor for the LTS version used by the repository currently, 2021.3.11f1.

## How To Make Changes to the Project
1. Edit the scenes and components via the Unity Editor
1. Edit the scripts via your script editor

## How To Push Chnages to the Project
1. `git status` to check file changed
1. `git restore {file}` to unstage files that should not be commited
1. `git add {file}` to stage files that should be commited
1. `git commit -m "{change info}"` to commit the files
1. `git push` to push changes to GitHub.

## Useful References
- [How to set up a Unity project in GitHub](https://unityatscale.com/unity-version-control-guide/how-to-setup-unity-project-on-github/)
- [Unity SmartMerge Instructions](https://github.com/anacat/unity-mergetool)
- [Unity SmartMerge](https://docs.unity3d.com/Manual/SmartMerge.html)

 
