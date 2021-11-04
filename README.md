# CPP_and_SFML_Menu_and_Login_System
A simple menu and login app I made for midterm project with pure C++ and SFML in VSCode.

### Info
You can switch through menus, and use a username to login. For now, the password
is not constant as this is only a testing app, only the usernames are constant, which
is why the registration system will be added in next version.
Also the only indicator that the field is either empty or error with input is that it turns
its border's color in red, and because of that I have to implement a better visual effect
for conveying the phenomena.

### Version
This is the initial GUI version of my console app project i.e. menu and login system;
does not consist of reusable custom classes which can represent, for instance,
a single button, and is written with sheer SFML classes. The build is for Windows
only.

### Usage
For now it acts well as a menu i.e. switching varying menus, but as a login system it
is way behind as it is only a _pseudologging_ system for now.
It can be used by these steps:
1. First, extract the ZIP file after downloading this.
2. Inside, there is another compressed file, extract it in the same parent folder.
3. The executable file can be launched now.

### Goals
- [ ] Make custom classes
    - [ ] Button (normal, inactive, hovered, clicked, focused)
    - [ ] Input field (normal, inactive, hovered, clicked, error)
    - [ ] Table (normal, hovered, clicked)
- [ ] Registration system (read and write in AppData?)
- [ ] Visual effects
    - [ ] Animation curves
    - [ ] Shaders (if possible without lag spike; fallback system)
- [ ] Make elements responsive with change in window size

### Prerequisites
Stuff I used for building it:
- Andrew **King**'s boilerplate of SFML to work on Visual Studio Code: https://github.com/andrew-r-king/sfml-vscode-boilerplate
- Visual Studio Code
- C++ (cpp17)
- mingw32
- SFML 2.5.1
