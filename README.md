#Custom LaTeX Report Generator with PyQt
Overview
This project provides a GUI-based tool using PyQt that allows users to select specific components from a given LaTeX (.tex) file and generate a custom PDF report. The tool is built using PyLaTeX for LaTeX generation and PyQt for the graphical interface.

Features
✔ GUI to display LaTeX file components
✔ User can select specific sections to include in the PDF
✔ Automatic PDF generation using PyLaTeX
✔ Custom report creation based on selected components

#Project Structure
graphql
Copy
Edit
📂 Project Root  
│── 📜 main.py                  # Main Python script (GUI implementation)  
│── 📜 report_generator.py       # Handles LaTeX file parsing and PDF generation  
│── 📜 components_list.json      # Stores component details (optional)  
│── 📂 input  
│   ├── report_template.tex      # Base LaTeX file  
│── 📂 output  
│   ├── custom_report.pdf        # Generated PDF report  
│── 📜 requirements.txt          # Dependencies for setup  
│── 📜 README.md                 # Project documentation  
Installation
Clone the Repository

bash
Copy
Edit
git clone <repository_link>
cd <repository_folder>
Create a Virtual Environment (Optional but Recommended)

bash
Copy
Edit
python -m venv venv  
source venv/bin/activate  # On macOS/Linux  
venv\Scripts\activate     # On Windows  
Install Dependencies

bash
Copy
Edit
pip install -r requirements.txt
Usage
Run the GUI

bash
Copy
Edit
python main.py
Select the components from the GUI.

Click 'Generate PDF' to create a custom report.

The output file (custom_report.pdf) will be saved in the output/ folder.

#Input & Output
Input:
report_template.tex (LaTeX template with multiple sections)

User-selected components from the GUI

#Output:
custom_report.pdf (PDF report containing only selected sections)

#Contributing
Feel free to submit pull requests or open issues for improvements.

#License
This project is licensed under the MIT License.
