# PES Version Control System (PES VCS)

## Overview
PES VCS is a simplified version control system implemented in C.  
It supports basic operations similar to Git such as adding files, committing changes, and viewing commit history.

---

## Features
- Blob storage using hashing  
- Tree structure for directory representation  
- Index (staging area)  
- Commit creation with metadata  
- Log to display commit history  

---

## Project Files
- object.c  → Handles file storage (blobs)  
- index.c   → Manages staging area  
- tree.c    → Builds directory structure  
- commit.c  → Creates commits  
- pes.c     → Main program  

---

## How to Run

### Compile

make

### Initialize Repository

./pes init

### Add Files

./pes add file1.txt

### Commit Changes

./pes commit -m "message"

### View Commit History

./pes log

## Example
echo "hello" > file1.txt
./pes add file1.txt
./pes commit -m "first commit"
./pes log

## Summary
This project demonstrates how a version control system tracks changes, stores data using hashing, and maintains history through commits.

