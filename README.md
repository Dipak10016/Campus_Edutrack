# Campus EduTrack 📁 🐍 📊

Campus EduTrack is a Python-based application designed to automate student data management at SIES Graduate School of Technology, Nerul, Navi Mumbai. Using Python 🐍 and the xlwings library, it streamlines processes by handling student data and generating Mentee Information Sheets efficiently 📑.

## Features ✨
- Automates student data processing, including personal and academic records 🧑‍🎓 📋.
- Generates output files for individual students in a structured, organized manner 📁 🗃️.
- Eco-friendly by eliminating paper-based record-keeping 🌳.
- Intuitive GUI for selecting database files, defining row ranges, and executing operations 🖱️ ⚙️.

## Prerequisites ⚡
- Python 3.6 or later 🐍
- xlwings library (`pip install xlwings`) 📦
- Microsoft Excel (Office 2021 or later recommended) 📊

## Installation 🔧
1. Create a folder for the project 📁.
2. Download the following files:
   - `Database.xlsx` 📑
   - `Campus_Edu.py` 🐍
   - `template.xlsx` 📑
3. Alternatively, clone the repository:
   ```bash
   git clone https://github.com/png-bash/CampusEduTrack.git
   ```
   
## How to Run 🚀
1. Navigate to the project folder in your terminal 🧭.
2. Run the program:
   ```bash
   python Campus_Edu.py
   ```
3. The program will create an output folder for saving processed student files 📁 💾.

## Using the Application 🖱️
1. **GUI**: After running the script, the graphical user interface is launched.
2. **Select Database**: Click the "Browse Database" button and select `Database.xlsx` 📁.
3. **Set Row Range**: Input the starting and ending row to process specific students 🔢.
4. **Select Operation**: Choose an operation (e.g., "Fill Page 1 and Page 2") from the dropdown 🖱️.
5. **Process Files**: Click "Process Selected Operation" to process the data 🖱️.
6. **View Output**: Processed files are saved in the output folder, named by student roll number 📁.

## Generating Additional Pages 🔄
- To process other pages (e.g., Semester 1 data), change the operation in the dropdown and repeat the steps.

## Sample Data 📋
The provided `Database.xlsx` includes sample data for 10 students to test the program.

## Notes 📝
- Follow the sequence of operations in the dropdown for accurate file generation.
- Ensure all required files (`Database.xlsx`, `Campus_Edu.py`, `template.xlsx`) are in the same folder before running the script 📁.

## Contributing 🤝
Contributions are welcome! If you encounter issues or have ideas for improvement, feel free to submit an issue or a pull request to the repository.

## Acknowledgments 🙏
- Developed using Python and the xlwings library 🐍 📊.
- Inspired by the need for efficient, eco-friendly student data management 💡 🌳.

## License 📜
This project is licensed under the MIT License. See the LICENSE file for more details.

## Contact 📧
For questions, suggestions, or feedback, please contact **Dipak Ghadge** at [dipakghadge2004@gmail.com](mailto:dipakghadge2004@gmail.com).
