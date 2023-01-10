# FileZip
A library for creating **basic** zip files (based on this: https://gist.github.com/rvaiya/4a2192df729056880a027789ae3cd4b7)

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
