Code adapted from [python-doc2txt](https://github.com/ankushshah89/python-docx2txt) for image detection and moving use-case (move all Word documents [.docx] containing images to a subfolder).

NOTE: This code will only work with .docx files (at the moment!)

To work, place the images_script.py file in the directory with the docx documents. Also, create a new subfolder called "image_docx" in the same directory. Run the Python script with Python 3. ([Here are some hints](https://www.pythoncentral.io/execute-python-script-file-shell/) if this is your first time running a Python script or using the shell/bash/command line interface)

Currently, the script looks for the following file types: [".jpg", ".jpeg", ".png", ".bmp", ".gif", ".tiff"]. If you would like to include more filetypes, simply add the extensions to the list on line 73 of the program.

If you have any further questions, please reach out. Hope this helps!
