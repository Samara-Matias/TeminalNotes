# Commands 01:


📌 I'm using *Powershell*.

#### Let's get started! ✨

---

</br>


```powershell
    gl // Get-Location
```
- This command **shows all the path to the current directory** you're in.

</br></br>

```powershell
   cd path // Set-Location path
```

- This command lets you move to a different directory by specifying its path. To go up one level in the directory structure, use ``cd ..``.

</br></br>

```powershell
    cd dirNameOrPathToDir
```
- This command lets you **change your current directory** by specifying the directory name. You can also use ``cd ..`` to go back one directory level.

</br></br>

```powershell
    dir // Get-ChildItem
```
- This command **shows all the files** in the current location/dir.

</br></br>

```powershell
    ni // New-Item
    ni file.txt -Type File
    ni folder1 -Type Directory
```
- This command **creates a new file or a new directory**.

</br></br>

```powershell
    cls
```
- This command **clears the contents of the terminal window**.

</br></br>

```powershell
    cp // Copy-Item
    cp documentOrDir dirName
```
- This command **makes a copy of the document or directory to other directory**.

</br></br>

```powershell Exemple 1
     mv documentName.format newDocName.format
```
```powershell Exemple 2
     mv documentName.format otherDir
```
- Example 1: The code above can be used to **change the document name**.
- Example 2: The ``mv`` command can be used to **move a file to another directory**.

</br></br>

```powershell
    help // Get-Help
    help commandName
```
- This command **displays the reference page for another command**.