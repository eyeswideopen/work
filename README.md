# work
is a simple command line utility to quickly start working on projects by automating the startup procedure like opening folders, IDEs, starting the development environment, etc ...

### Installation (OSX)
- clone this project into $HOME/.work
- make it executable with ```chmod +x work```
- add the script to your PATH by executing (OSX) ```echo 'export PATH="$HOME/.work:$PATH"' >>~/.bash_profile```

### Usage
write your own <project_name>.sh shell scripts and place them in the .work folder
```sh
$ work <project_name>
```
then executes scripts named identical. For example ```work example``` executes the "example.sh" script included in the repo