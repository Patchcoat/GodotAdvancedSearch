# Godot Advanced Search
An addon for the Godot game engine version 3.5 that makes it easier to find scenes in your project that contain specific nodes.

![Screenshot 1](/Screenshot1.png) ![Screenshot 2](/Screenshot2.png) ![Screenshot 3](/Screenshot3.png)

# Installation
Put the advanced_search folder and all its contents in your project's addons folder, then go to Project->Project Settings->Plugins and set enabled to true. It should appear in the bottom left pannel, next to the File System tab if you are using the default Godot layout.

# Usage
In the Scene List tab you can type text into the search box. This is useful for searching for nodes by name, and will filter out all scenes that do not contain a node with that text string in the name. The searching should happen automatically as you type, but a search button is provided just in case.

The Node Tab contains a short list of nodes in alphabetical order. Selecting a node will filter out all scenes that do not contain at least one node of that type. Selecting and de-selecting will also automatically search through the scenes in your project.

Once you have a list of scenes, you can click any one of them. Godot will open the scene if it is not already open, or switch your view to it if it is.

# Hidden Files
Files and folders beginning with '.', and the contents of folders named "addons" or "builds" in res:// will be ignored by the search.

# Additional Work
Currently, the list of available node types to filter by is quite small. If there are specific nodes you would like me to add, open an issue. Hopefully this is a temporary situation until I can figure out how to generate a list from all available nodes in Godot.
