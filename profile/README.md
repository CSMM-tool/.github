# CSMM (available soon)

## What is CSMM?
CSMM, or Code Source Module Manager, is a tool for managing C language source code organized into modules. It operates similarly to a package manager, offering many of the same features but tailored specifically for C source code management.

## Features / Commands
- `csmm init` - Initialize a new CSMM project
- `csmm install` - Add a module to the project
- `csmm remove` - Remove a module from the project
- `csmm list` - List all modules in the project
- `csmm search` - Search for a module in the CSMM modules repository
- `csmm update` - (Re)Install the modules in modules.json
- `csmm check` - Check the project for missing modules and dependencies
- `csmm make` - Build the project (generate makefile, generate include files, and call make)
- `csmm clean` - Delete the contents of the modules directory

## Why create CSMM?
As a developer working extensively with C in both firmware and software projects, I had a need for a solution that simplifies code reuse in both personal and professional projects. CSMM is designed to boost productivity by streamlining the management and integration of code modules. Frequently, I find myself re-implementing features I've already developed or copying and pasting code from other projects. While this may seem acceptable, it becomes inefficient when I need to fix a bug in a module that I've already addressed in another project. CSMM allows for easy upgrading and downgrading of modules to any available version, enabling code reuse without the hassle of managing shared code effectively.

## Mascot: Cosmo the Chinchilla
Introducing Cosmo, our cheerful blue and yellow chinchilla with stylish sunglasses! We chose a chinchilla as our mascot for two reasons: their undeniable charm and the fact that "chinchilla" begins with the letter 'C', perfectly aligning with our focus on the C programming language.  
![Cosmo](https://raw.githubusercontent.com/CSMM-tool/.github/refs/heads/main/profile/cosmo.png "Cosmo")


## Why is CSMM written in Python?
The initial version of CSMM was developed in C, however, Python offers a more easy development process thanks to its extensive libraries. Since CSMM is not a performance-critical application, the performance trade-off associated with transitioning to Python is negligible.

## CSMM Source Code
The source code for CSMM is licensed under the MIT License and can be accessed at:  
[CSMM GitHub Repository](https://github.com/CSMM-tool/CSMM)

## Modules Repository
You can find the repository for CSMM modules at:  
[CSMM Modules Repository](https://github.com/CSMM-tool/CSMM-repo)

## License
The code of CSMM itself is licensed under the MIT License.
CSMM core and std modules are licensed under the MIT License, other modules can have their own licenses. 
See specific module for details.

