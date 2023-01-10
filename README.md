# FileZip
A library for creating **basic** zip files

## Get the library
```
var zip = new FileZip();
````

## Create a new folder
```
var folder = zip.new("folder","folderName");
````

## Create a new file
```
var file = folder.new("file","fileName",Blob);
````

## Generate the zip
```
var zipBlob = zip.generate();
````
