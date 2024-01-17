# Revit Hello World Repository

This repository contains two Revit API code samples that demonstrate how to display a "Hello World" message in different ways within Autodesk Revit.

## Folder 1: Display Popup Window

### Description
- File: `Class1.cs`
- Namespace: `Demo`

This code sample shows how to create a simple Revit external command that displays a popup window with the message "Hello World!"

### Usage
1. Build the project.
2. Load the resulting add-in (`DLL`) into Autodesk Revit.
3. Run the command to see the "Hello World!" popup.

## Folder 2: Add Button to Ribbon Panel

### Description
- Files: `CsAddPanel.cs` and `HelloWorld.cs`
- Namespace: `AddPanel`

This code sample demonstrates how to add a custom button to a ribbon panel in Revit, and upon clicking the button, it triggers the display of the "Hello World!" message.

### Usage
1. Build the project.
2. Load the resulting add-in (`DLL`) into Autodesk Revit.
3. Locate the "Hello World" button in the "NewRibbonPanel" panel.
4. Click the button to see the "Hello World!" popup.

## Additional Information

- Both code samples utilize the Revit API and are implemented as external commands.
- Code is written in C#.
- Make sure to update the image path in `CsAddPanel.cs` to the correct location on your machine.
