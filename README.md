# RPA_Ex-09

# Exercise-9-Keyboard-Automation---Simulate-Keystrokes
~~~
Name : Subikshan p
Reg.No : 212223240161 
~~~

## Aim
To create a UiPath workflow that opens Notepad and simulates keyboard typing and shortcuts like saving a file using simulated keystrokes.

## Materials Required
UiPath Studio (Community or Enterprise Edition)

Windows OS

Notepad (built-in Windows app)

Basic knowledge of keyboard automation using UiPath

## Procedure

### Step 1: Create a New Process
Open UiPath Studio and create a new process named KeyboardAutomation.

### Step 2: Open Notepad
Drag and drop Start Process activity.

Set the properties:

FileName: "notepad.exe"

### Step 3: Add Delay (Optional but Recommended)
Add a Delay activity to wait for Notepad to open.

Duration: 00:00:02 (2 seconds)

### Step 4: Use Type Into Activity
Drag and drop a Type Into activity.

Click Indicate on Screen and select the Notepad window.

Text to type:
~~~
Hello! This text is typed by UiPath using keyboard automation.
💡 Enable ClickBeforeTyping and Activate options in the Properties panel for accuracy.
~~~
### Step 5: Use Keyboard Shortcuts (e.g., Save)
Drag and drop a Send Hotkey activity.
Indicate the same Notepad window.
Set the key to Ctrl + S (hold Ctrl, then choose S).

### Step 6: Type File Name and Press Enter
Add a Type Into activity to type file name (e.g., MyFile.txt).
Add another Send Hotkey for pressing Enter.

## OUTPUT:
Notepad will open.
Text will be typed automatically.
Ctrl + S will be triggered to save.
The file will be saved with the name MyFile.txt.

![9-1](https://github.com/user-attachments/assets/9969dc12-e6b4-4a01-94c3-c6ebcf0c112a)

![9-2](https://github.com/user-attachments/assets/06bb5366-1078-492b-ae42-4feef1908024)

![9-3](https://github.com/user-attachments/assets/7ae3a242-bbfd-4f90-8b25-ed9ba16fa331)

![9-4](https://github.com/user-attachments/assets/dde137f6-687b-45cf-acfb-f38d9b129b95)


## Result:
The workflow successfully simulates human-like typing in Notepad and saves the file using keyboard shortcuts through UiPath's keyboard automation capabilities.

