# MP3 Tag Reader – C Programming Project

## 📌 Description
The MP3 Tag Reader is a **C-based application** that reads and displays metadata
(ID3 tags) from MP3 audio files.  
It parses binary data from MP3 files to extract information such as **song title,
artist, album, and year**.

This project focuses on **binary file handling, data parsing, and low-level
understanding of file formats**, which are important skills for system-level
and embedded software development.

---

## 🧠 Concepts Used
- Binary file handling
- File pointers
- Structures
- Byte-level data parsing
- String manipulation
- Modular programming

---

## 📁 File Structure

```
MP3_tag_reader/
├── main.c        # Program entry point
├── mp3.c         # MP3 tag parsing logic
├── mp3.h         # Structure definitions and declarations
├── sample.mp3    # Sample MP3 file (optional)
└── README.md
```



*(File names may vary based on implementation)*

---

## ▶️ Build and Run

Compile the program using GCC:

```bash
gcc *.c -o mp3_tag_reader
