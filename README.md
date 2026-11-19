# MP3 Tag Reader and Editor
A command-line-based MP3 Tag Reader and Editor developed in C. It allows users to view and modify ID3 metadata such as Title, Artist, Album, Year, Genre, and Comments using file handling operations.
# 🎵 MP3 Tag Reader and Editor in C

A command-line application developed using **C programming** that allows users to read and edit ID3 metadata stored in MP3 audio files.

The project uses file handling concepts to extract and modify MP3 tag information.

## 🚀 Features

- **View MP3 Tags:** Display metadata from MP3 files.
- **Edit Title:** Modify the song title.
- **Edit Artist:** Update the artist name.
- **Edit Album:** Change the album name.
- **Edit Year:** Modify the release year.
- **Edit Genre:** Update the content type.
- **Edit Comments:** Modify the comment information.
- **Colourful Terminal Output:** Display messages using terminal colours.

## 🛠️ Technologies Used

- C Programming
- File Handling
- Structures
- Pointers
- Command-Line Arguments
- ID3 Tag Format

## 📂 Project Structure

```text
MP3-Tag-Reader-and-Editor/
│
├── main.c
├── view.c
├── view.h
├── edit.c
├── edit.h
├── types.h
├── color.h
└── README.md
```

## ⚙️ Compilation

Compile the project using GCC:

```bash
gcc *.c -o mp3reader
```

## ▶️ How to Run

**Display help:**

```bash
./mp3reader -help
```

**View MP3 details:**

```bash
./mp3reader -v song.mp3
```

**Edit song title:**

```bash
./mp3reader -e -t "New Song" song.mp3
```

**Edit artist:**

```bash
./mp3reader -e -a "New Artist" song.mp3
```

## 🏷️ Available Modifiers

| Modifier | Description |
|---|---|
| `-t` | Title |
| `-a` | Artist |
| `-A` | Album |
| `-y` | Year |
| `-d` | Genre / Content Type |
| `-c` | Comments |

## 🎯 Learning Outcomes

Through this project, I gained practical experience in:

- Working with binary file operations.
- Understanding MP3 ID3 metadata.
- Reading and writing data using file pointers.
- Handling command-line arguments.
- Using structures and functions in C.
- Managing file data using temporary files.

## 👩‍💻 Author

Developed as a C programming project to improve practical knowledge of file handling and system-level programming.

**Thank you for visiting my project!** ⭐
