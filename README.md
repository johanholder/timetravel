# Timetravel  [![CircleCI](https://circleci.com/gh/radekdymacz/timetravel.svg?style=svg)](https://circleci.com/gh/radekdymacz/timetravel)

Simple tool to travel in time.
Batch change modified time of files in given volume/folder if it's in the future.

## Why

Its quite common occurence for files to have corrupted metatadata timestamps like access, modified and created time in the future. This impacts avaiability to properly backup or archive this files hence the need for the tool.


## Usage

```
timetravel /mnt/volume/folder
```
