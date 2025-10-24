#Crazy-Text-Editor

A simple Python-based text editor for fun / “crazy” text transformations.

About

Crazy-Text-Editor is a lightweight Python application that allows you to open, edit and save text files with a twist: you can apply “crazy” text transformations (e.g., weird fonts, Unicode tricks) to make your text look unusual, funky or stylised.

Features

Open existing .txt files for editing.

Apply various text transformations (e.g., flip text, weird Unicode fonts, reversed text).

Save your edited and transformed text back to a file.

Easy to use and extend (written in Python).

Getting Started
Prerequisites

Python 3.x installed on your system.

Basic familiarity with running Python scripts.

Installation

Clone this repository:

git clone https://github.com/Bhagvati-Gaikwad/Crazy-Text-Editor.git


Change into the project directory:

cd Crazy-Text-Editor


(Optional) Create and activate a virtual environment.

Run the main script:

python main.py


(Replace main.py with the actual entry script name if different.)

Usage

From the menu or prompt, open a text file you want to edit.

Make your edits as desired.

Choose a transformation option to apply “crazy” text effects.

Save the output to a new file or overwrite the existing one.

Customising / Extending

You can add new transformations by editing the transformations.py (or equivalent) module.

Define a new function that takes a string and returns a transformed string, then add an option in the UI.

You can integrate GUI frameworks (Tkinter, PyQt) if you prefer a graphical interface instead of console.

Project Structure
Crazy-Text-Editor/
├── main.py              # Entry point of the application
├── README.md            # This file
└── sample_files/        # Sample input / output text files (optional)

Contributing

Contributions are welcome! If you’d like to contribute:

Fork the repository.

Create a feature branch (git checkout -b feature/new-transform).

Commit your changes (git commit -m "Add new transformation: invert text").

Push to your branch (git push origin feature/new-transform).

Submit a Pull Request describing your changes.

License

Specify the licence you want to use (e.g., MIT License).

MIT License
Copyright (c) 2025 Bhagvati Gaikwad

Contact

If you have questions, suggestions or issues, please open an issue on GitHub or contact me (Bhagvati Gaikwad).
