# 3D modeling projects repository

## Description

This collection houses a variety of projects created using Blender, AutoCAD, SolidWorks and other 3D modeling tools.
Intentions for creating them may be:

- to serve as an idea project for showing to clients or a manufacturer.
- to substitute engineering drawings when working with non-engineers.
- to be implemented as static or animated object in a website.

## Conventions

To maintain a consistent and organized structure within this repository, I follow a set of conventions:

### File & Folder Structure

- **/root:** This directory contains individual project folders. Each substantial project should have its own dedicated folder with a main project file and its own file and subfolder structure. If a file is just laying around then it is too small to be considered a project but I still want to keep it in VC.

- **/\<project-name>/textures:** These directories as the name implies are to hold the images used for texture materials in the project.

- **/\<project-name>/measurements:** These directories hold mostly screenshots with dimensions and different-sided views of a key object from the project.

- **/\<project-name>/old:** If such folder exists then this means that the initial concept of the project changed notably and all references, measurements and screenshots of it need to go in a separate folder in order not to mix with anything up to date. Such practice avoids extreme filename versioning and saves a lot of time.

- **/\<project-name>/resources:** These directories usually exist if I had some other models or assets I used for reference or to copy from. It is best practice to keep such assets intact.

- **/\<project-name>/export:** These are folders holding models variations for exporting and the resulting exports.

### Naming Conventions

I use naming conventions acquired through a carrer of programming and game development that have proven to be useful and worth it when searching for something, trying to animate an object or a group of parts. Naming of similar objects may vary in convention depending on what they are intended for. In the end the most general rule is to differentiate between things with similar names and ultimately avoid spaces (somebody really didnt think spaces through in the early 90s).

- **Project File Naming:** Pascal Case (PascalCase) - Community Standard. If additional annotation is necessary Snake Case (eg. BoatDeck_workfile).

- **File Exports Naming:** Camel Case (camelCase) - Because usually it makes sense for exports to have the same name as the project file. Also I implement my loaders in games to auto-load and expose assets by variables named same as the source file, therefore camel case makes even more sense.

- **Reference & Other Images Naming:** Snake Case (snake_case) often mixed with Kebab Case (kebab-case) for better context.

- **Objects in Files:** Kebab Case for multi-word names followed by Snake Case for attributions and assignments (eg. assembly-line_conveyor-belt_3).

- **Materials & Fonts:** Pascal Case for multi-word names still Pascal Case (eg. LightBrownWood).

### Documentation

- **README.md:** Each project folder should include its own README.md file that provides a brief overview of the project and what it is intended to serve for.

## Contributing

Anyone is welcome to share constructive criticism in a comment or give an example like so:

1. Fork this repository.
2. Create a new branch for your suggestion.
3. Add or change the necessary files.
4. Update the main README.md of your 'fork' with a brief description of your intentions and what the changes should achieve.
5. Submit a pull request.
