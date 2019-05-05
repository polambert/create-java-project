
# create-java-project

cjp is a lightweight Java IDE (by definition) that uses make to help compile your large java programs.

cjp depends on:
- bash
- make

cjp is a terminal Java IDE, written in bash and makefile.

- [Introduction](#introduction)
	- [Installation](#installation)
	- [Getting Started](#getting-started)
- [How to use](#how-to-use)
- [Upcoming Features](#upcoming-features)

## Introduction
### Installation
Copy the `create` script to your Java project directory.

```
cd ~/Projects/Java
git clone https://github.com/polambert/create-java-project.git
mv create-java-project/create ./create
rm -rf create-java-project
```

The result:

```
Projects
	Java
		create
		Project1
		Project2
		Project3
```

### Getting Started
With the create script added, you can run `./create` to create a new Java project.

When running the script, enter the name of the project you're going to create.

## How to use
By definition, cjp is a Java IDE. Use cjp to create projects, compile binaries, and to debug your code.

While cjp has no debugging features built in, those [will be coming in the future](#upcoming-features).

After creating your project, you can run these commands from within the project's directory.

```
make			Build, compile, delete classes, and run jar.
make keep		Build, compile, and run jar.
make compile 	Build and compile jar.
make upack 		Extract jar contents to folder jar-extract/.
make clean		Delete classes, jar-extract/, and other useless items.
```

## Upcoming Features
- Debugging Java Programs







