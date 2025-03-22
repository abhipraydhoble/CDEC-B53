# Linux Directory and File Creation


## Creating Files
````
touch file1.txt 
````
- touch file1.txt  → Creates empty file file1.txt 


- cat > file2.txt → Creates a new file file3.txt and waits for input. Press Ctrl+D to save.
````
cat > file2.txt
````
**Note:**
-  > will override file content
- >> will append (both old data and new will stay in file)

- echo "Hello World" > greetings.txt → Creates a file greetings.txt and writes Hello World into it.
````
echo "Hello World" > greetings.txt
````

**Displaying File Content**
````
cat greetins.txt
````

### 1. Creating Directories
```sh
mkdir pune
cd pune
mkdir kothrud wakad
```
- `mkdir pune` → Creates a directory named `pune`.
- `cd pune` → Navigates into the `pune` directory.
- `mkdir kothrud wakad` → Creates two subdirectories `kothrud` and `wakad` inside `pune`.

### 2. Navigating and Listing Directories
```sh
ls
cd kothrud/
ls
```
- `ls` → Lists the contents of the current directory.
- `cd kothrud/` → Moves into the `kothrud` directory.

### 3. Creating a File
```sh
cat > cloudblitz.txt
```
- `cat > cloudblitz.txt` → Creates a new file named `cloudblitz.txt` and waits for input. Press `Ctrl+D` to save.

### 4. Displaying File Content
```sh
cat cloudblitz.txt
```
- `cat cloudblitz.txt` → Displays the contents of `cloudblitz.txt`.

### 5. Moving a File to Another Directory
```sh
mv cloudblitz.txt /pune/wakad/
```
- `mv cloudblitz.txt /pune/wakad/` → Moves `cloudblitz.txt` from `kothrud` to `wakad`.

### 6. Renaming a File
```sh
cd wakad
mv cloudblitz.txt edublitz.txt
```
- `mv cloudblitz.txt edublitz.txt` → Renames `cloudblitz.txt` to `edublitz.txt` in `wakad`.

### 7. Moving a File and Renaming in Another Directory
```sh
mv edublitz.txt /pune/kothrud/devops.txt
```
- `mv edublitz.txt /pune/kothrud/devops.txt` → Moves `edublitz.txt` from `wakad` to `kothrud` and renames it to `devops.txt`.

### 8. Displaying the Final File
```sh
cd ../kothrud
cat devops.txt
```
- `cat devops.txt` → Displays the contents of `devops.txt` in `kothrud`.

### Remove files/Dir

````
rm -rvf pune
````
````
rm -rvf greetings.txt
````


