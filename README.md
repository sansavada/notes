# Notes

### Entry Template


__command__ - _Description_

__Examples:__

```
bash code in here
```
---

## File Management

__mv__ - _Move file or Rename file_

__Examples:__

```
mv sourceFile destinationFile
mv sourceFile destinationLocation
mv myFile.txt myFolder/
```
---

__cp__ - _Copy file or folder_

__Examples:__

```
cp filename.cpp myCopy.cpp
cp -r myFolder/ myNewFolder
```
---

* cp (folder and individual files)

__rm__ - _Delet files or directories__

__Examples:__

```
rm filename.txt mySortedfile.cpp
rm -r myFolder/ myNewFolder
```
---

__rmdir__ - _Command delets one or more empty directories you name_

__Examples:__

```
rmdir /tmp/junk
rmdir /cs210/lab04
```
---

__ln -s__ - _Symbolic link which is reference to another file by its path_

__Examples:__

```
ln -s myfile mysoftlink
```
---

__scp__ - _Secure copy command copied files and directories from one computer to another in batch_

__Examples:__

```
scp myfile remote.example.com:newfile
scp -r mydir remote.example.com:
scp remote.example.com:myfile
```
---

__pwd__ - _print name of current/woring directory_

__Examples:__

```
pwd
```
---

__ls__ - _Lists attributes of file and directories_

__Examples:__

```
ls dir1
ls -a (list all files, including those whose names begin with a dot)
```
---

__tar__ - _Backing up files onto a tape drive and pack multiple files and directories into a single file for transport, optionally compressed_

__Examples:__

```
tar -czvf myarchive.tar.gz mydir (Create)
tar -tzvf myarchive.tar.gz (List of contens)
tar -xzvf myarchive.tar.gz (Extract)
```
---

## File Transfer

__curl__ - _Writes to standard output by default, which duplicates the original page and file names by default_

__Examples:__

```
curl http://www.yahoo.com > mypage.html
```
---

__wget__ - _Command hits a URL and downloads the data to a file or standard output_

__Examples:__

```
wget http://www.yahoo.com
```
---

__rsync__ - _Copies a set of files wiht exact copy, including file permissions and other attributes, or just copy the data_

__Examples:__

```
rsync -a D1 D2
```
---

## Pipe tools

__cat__ - _Print out the contents of the commands file to the screen_

__Examples:__

```
cat filename.txt > copiedOutput.txt
```
---

__sort__ - _Prints lines of text in alphabetical order, or sorted by some other rule you specify_

__Examples:__

```
sort myfile.txt
sort -n myDate.txt (sort by numerically, ex: 10, 9,..,1)
```
---

__uniq__ - _Operates on consecutive, duplicate lines of text_

__Examples:__

```
uniq myfile.txt
uniq -c myfile.txt
```
---

__grep__ - _Given one or more files, print all lines in those files that match a particular regular expression pattern_

__Examples:__

```
grep diff myfile.txt
```
---

