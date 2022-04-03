# License
Copyright (c) 2022, Tristan Carpenter (Trisiegt)
All rights reserved.

This source code is licensed under the BSD-style license found in the
LICENSE file in the root directory of this source tree. 


# What is iGet?
iGet (pronounced eye-get) is a simple package manager for the Microsoft Windows operating system, similar to Winget, but written in the Batch (.bat, .cmd) programming language.
It's creator, Tristan Carpenter is fine with people creating so-called "forks" of this project, as described in the LICENSE file.

# How to install
To install iGet, download the setup file and the registry file under the Releases tab.
Then, open the installer (exe) file.
Just spam-click "Next" until the end screen.
Uncheck "Run iGet Package Manager", because we aren't finished with the installation process.
Next, open the .reg file.
The registry editor will come up with a warning asking if you want to install the hive since it may be malicious.
![Error box](https://i0.wp.com/techdirectarchive.com/wp-content/uploads/2020/09/unload-confirm-Capture.png?resize=508%2C144&ssl=1)
The message looks similar to this.
Don't worry though, there's no malware on this repository.
After the hive has finished installing, click OK.
Next, we need to add iGet to PATH.
Doing so will let iGet run anywhere, so you don't need to ***cd*** into the install directory.
Open the start menu, and type in "path".
If it comes up with "Edit environment variable", click on it.
Then, at the top, click Path then Edit.
On the first EMPTY line, copy "C:\Program Files (x86)\Tristan Carpenter\iGetPM" WITH the speechmarks.
Click Done.

Eureka! iGet is installed!
Run iGet by typing "iGet" in the Command Prompt.

## What can you do with iGet?
Currently, iGet is a COMPLETELY experimental project.
It only has ONE command, and relies on Microsoft Edge.
That command is "OperaBrowser" (cAsE SeNsItIvE!), and it downloads Opera.
Every single command tells Microsoft Edge to visit a MediaFire page that automatically downloads your file without any user input.
Every downloaded file goes automatically to your "Downloads" folder.

###### REMEMBER!
iGet is still in Alpha pre-release.
That means that the package manager can have unexpected bug splats.



# Help and support
If you need help with the iGet package management tool, submit an issue.

# How can I contribute?
If you would like to contribute (edit) to the iGet project, send me an e-mail [here](mailto:tristan4@mail.com).
Remember, if you would like to modify iGet's contents without modifying the actual repository, you can always **fork** the project under 1 condition:
You license it under the BSD 3 Clause License!
