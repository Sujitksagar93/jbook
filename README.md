# BWnote
It is an interactive coding environment. You can write Javascript, see it executed, and write comprehensive documentation using markdown.

- You can click any text cell to edit it.
- The code in each code editor is all joined together into one file. If you define a variable in Cell #1 you can refer it in any cell!
- You can show any React component, string, number or anything else by calling the `show` function. This is a function built into this environment.
- You can reorder and delete cells.
- You can add new cells by hovering over the divider between each cell. 


# Installation Guide

```bash
npm i -g bwnote 
```

Or, you can directly run it by

```bash
npx bwnote serve
```

# Commands

```bash
bwnote serve [filename] [-p] [-h]
```
Usage 
-  `-h, --help`                  display help for command
-  `-p, --port`                  specify the port
  
### Start the application

```bash
bwnote serve
```

This will start the application at port `4005` and all the changes will be saved at `notebook.js`  

### Starting the application at a specific port 

```bash
bwnote serve -p 3000
```

### Opening a file 

```bash
bwnote serve [filename]
```
 


