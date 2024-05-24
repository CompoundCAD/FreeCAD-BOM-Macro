# Define the content of the README file
readme_content = """
# FreeCAD Bill of Materials (BOM) Macro

## Overview
This FreeCAD Macro generates a Bill of Materials (BOM) for your FreeCAD projects, providing a convenient way to organize and export information about the components and assemblies in your design.

## Features
- **Automatic BOM Generation:** Automatically generates a BOM based on the objects in the active FreeCAD document.
- **Flexible Export Options:** Export the generated BOM to a CSV file for easy sharing and integration with other tools.
- **Interactive User Interface:** Provides a user-friendly interface for viewing and managing the BOM data.
- **Customizable Columns:** Easily manage and customize the columns displayed in the BOM table according to your preferences.
- **Search and Filtering:** Quickly search and filter BOM data based on specific criteria.
- **Selection Integration:** Seamlessly integrates with FreeCAD's selection mechanism for easy object selection and highlighting.

## Installation
To use this macro, follow these steps:

1. **Download the Macro:** Download the Python script containing the BOM Macro.
2. **Load the Macro:** Open FreeCAD and load the Macro script using the Macro editor or the Macros menu.
3. **Run the Macro:** Execute the Macro to generate the BOM for the active FreeCAD document.

## Usage
- **Generate BOM:** Click the "Generate BOM" button to create a BOM based on the objects in the active FreeCAD document.
- **View and Modify BOM:** Use the interactive BOM table to view and modify the generated BOM data. Customize the columns, search for specific items, and manage the display according to your requirements.
- **Export BOM:** Export the BOM to a CSV file using the "Export to CSV" button for sharing or further analysis.
- **Manage Columns:** Click the "Manage Columns" button to customize the columns displayed in the BOM table. Choose from a variety of available columns to tailor the view to your needs.
- **Search and Filter:** Use the search box and dropdown menus to search and filter BOM data based on specific criteria such as object type, name, label, quantity, or material.

## License
This FreeCAD Macro is distributed under the GNU General Public License v3.0 (GPL-3.0) to ensure that it remains open-source and freely accessible to the community.

## Credits
This Macro was developed by Compound CAD to enhance the functionality of FreeCAD for users working with complex assemblies and designs. 
"""

# Write the content to a README.md file
with open("README.md", "w") as readme_file:
    readme_file.write(readme_content)

print("README file generated successfully!")
