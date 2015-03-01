# MSML User Repository for CLI (executables)

This repository is a kick-start template for getting CLI (CommandLineInterface) executables into the 
[Medical Simulation Markup Language](http://github.com/CognitionGuidedSurgery/msml).


     Author: Alexander Weigl <uiduw@student.kit.edu>
     Date: 2015-03-01
     Version: 0.3
     License: GPLv3

## Getting Started

1. Clone the latest version of this repository:

        $ git clone --depth 0 https://github.com/CognitionGuidedSurgery/mup-empty.git
   
2. Install dependencies:

        $ pip install --user --pre msml2cli
    

3. Exclude `alphabet/`, `bin`, `py` from `.gitignore` file if necessary.

4. Add executable into `bin` by linking or copying.

5. Generate wrapper

    $ msml2cli -o alphabet bin/* 

Optional for sharing your MSML USER PACKAGE (MUP):

5. Set a new origin with your `<user>` and `<repo>`:

        $ git remote set-url origin https://github.com/<user>/<repo>.git
        $ git commit && git push origin master
