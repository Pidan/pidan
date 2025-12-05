# ⚠️ Project Archived

This repository is no longer actively maintained.  
The project has been upgraded and moved to a new solution.

👉 **Please visit the new repository for the latest updates and ongoing development:**  **[https://binhua.org/pidan](https://binhua.org/pidan)**  

Thank you for your support!

# Pidan
A Git helper

## Intro

Pidan is a Git helper that simplifies various Git tasks, making them more user-friendly. For example, it assists in tasks like initializing a `.gitignore` file and more.

## Installation

```
curl https://raw.githubusercontent.com/Pidan/pidan/master/pidan | bash
```

## Usage

```
USAGE: pidan [global options] command [command options] [arguments...]

COMMANDS:
   init  Initialize Pidan, need to run first

   export  Export Git repository contents

   gitignore  Initialize or update .gitignore file
    Options:
    -o  Overwrite existing .gitignore (default: true)
    -a  Append to existing .gitignore (default: false)
    
    Subcommands:
    config  Configure custom .gitignore file
        Usage: pidan gitignore config [-o | -a] [remote_gitignore]
        Options:
        -o  Overwrite existing content (default: false)
        -a  Append to existing content (default: true)

GLOBAL OPTIONS:
   --upgrade   Check for script upgrade and install the latest version (default: false)
   --info      Show all information about Pidan (default: false)
   --help, -h  show help
```

## Contribution

If you have any questions or feature suggestions, please feel free to submit them in [issues](https://github.com/Pidan/pidan/issues).

## License

[MIT](LICENSE)

Copyright (C) 2023-present, Bin Hua
