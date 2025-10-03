🎸 Guitar Chord Diagram Generator
📌 Overview

This project generates guitar chord diagrams programmatically using Python + Matplotlib.
It supports both open chords and barre chords, with custom string colors, fret markers, and string labels.

Each chord diagram is exported as a high-resolution .jpg image and saved to the specified folder.

⚙️ Features

Supports Major and Minor chords (A, B, C, D, E, F, G with sharps and flats).

Distinguishes between:

Muted strings (X)

Open strings (O)

Fretted notes (blue dots)

Automatically detects barre chords and draws fret bars.

Colored string lines for better visualization:

6E → Indigo

5A → Cobalt Blue

4D → Deep Green

3G → Orange

2B → Rose Red

1e → Violet

📂 Project Structure
chord-diagram-generator/
│
├── chord_generator.py   # Main script (your provided code)
├── README.md            # Documentation
└── output/              # Auto-generated chord images (.jpg)

🔧 Requirements

Make sure you have Python installed with the following packages:

pip install matplotlib

🚀 How to Run

Clone or download the repository.

Update the save_path in the script to your desired output folder:

save_path = r"D:\Backup\Music recog versions\Raga lib"


Run the script:

python chord_generator.py


✅ All chord diagrams will be saved in the folder as high-resolution .jpg files.

📊 Example Output

A Major

E Minor

F Major (Barre)

Each diagram shows:

Strings labeled (E, A, D, G, B, e)

Open (O) and muted (X) strings

Frets numbered

Colored string lines for clarity

🎯 Customization

To add new chords, edit the chords dictionary:

chords['New Chord'] = ['x', 2, 4, 4, 3, 2]


To change string colors, modify string_colors.

To change output format, replace .jpg with .png in the filename line.

📌 Future Enhancements

Support for 7th, maj7, sus, and dim chords.

CLI interface for generating diagrams on demand.

Export diagrams directly into PDF chord charts.

📄 License

This project is for educational and personal use. Feel free to modify and extend.
