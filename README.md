# copybuddy

Batch file copying via config files

## Usage
```
copybuddy /path/to/.cb
```

**Note:** only absolute paths are supported

## Config file format
```
src dir
dest dir
  file1
  file2
```

Example:
```
/path/to/src
/path/to/deployment
  file1
  file2

/path/to/src1
/path/to/deployment
  file3
  file4
```
