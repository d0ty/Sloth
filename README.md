# Sloth
Our official ground porcessing engine.

This python project was made in vs code and is tied to a virtual environment. To access the environment:

To install the required libraries:
```bash
pip install -r requirements.txt
```

On linux you might need to install tkinter (see your distribution's docs)

On windows:
- Enable access in terminal by:
Set-ExecutionPolicy Unrestricted -Scope Process
- Input the path to Sloth, for example:
cd "C:\Users\Felhasznalo\Roli\Celeritas\Sloth"
- activate the virtual environment:
.venv\Scripts\activate
- Input the path to \interpreter, for example:
cd "C:\Users\Felhasznalo\Roli\Celeritas\Sloth\interpreter"
- Run Sloth:
python Sloth.py


Version: 1.1

Options:
1. Write / communication loop
- Serial communication with Celeritas through the OBC emulator, type the desired commands
2. Read and store data
- Draw information from Celeritas through the OBC emulator quickly and store it in memory locally
3. Evaluate and Display data
- Evaluate Selftest and Header information, display Spectrums
4. Print stored data
- Check the data in local memory
5. Save data
- Save local memory to a .cel ("Celeritas extension") file
6. Import data
- Import to local memory from a .cel ("Celeritas extension") file
7. Dump memory
- Dump the local memory
8. Clear console
- Clear the terminal for a fresh sheet
9. Exit program
- To exit
