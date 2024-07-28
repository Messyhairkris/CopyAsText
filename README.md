# CopyAsText
Copy files to the clipboard as text without opening them using the context menu in Windows.

How to Use the CopyAsText Context Tool Manager

**Last Updated: July 28, 2024 **

The CopyAsText Context Tool Manager is a powerful tool that allows you to view various Programming languages in the Preview Pane for Windows and copy selected but not opened files to the clipboard for easier coding shenanigans. This guide will show you how to use the Manager to customize your context menu, manage preview handlers, and more.

This is currently an Autohotkey V1 script. I might adapt it to V2 eventually, since you run it once and its done I figure that is future guy's problem...
Part 1: Running the Setup Manager

    Launch CopyAsText context Tool Manager with CopyAsText.ahk in the same folder.

    Note: The script will automatically request admin rights if needed.

    Use the graphical user interface with various buttons and options to have better control of your data.

Managing the Context Menu

    Locate the context menu buttons.
        Find the "Add To Context Menu" and "Remove Context Menu" buttons in the Setup Manager interface.

    Click "Add To Context Menu".
        This will add the "Copy as Text" option to your Windows right-click menu.
        Note: If the option has already been added, this button will be disabled.

    Click "Remove Context Menu".
        This will remove the "Copy as Text" option from your Windows right-click menu.
        Note: If the option is not currently added, this button will be disabled.

    Check the status text.
        The Setup Manager will display a message confirming whether the action was successful.

Part 3: Managing Preview Handlers

    Find the preview handler buttons.
        Look for the "Preview as Text" and "Remove Preview" buttons in the interface.

    Click "Preview as Text".
        This will enable preview handlers for various code file types in Windows Explorer.

    Click "Remove Preview".
        This will disable the preview handlers for code files.

    Verify the changes.
        Open Windows Explorer and check if you can preview code files directly in the preview pane.

Part 4: Accessing the Registry

    Locate the "Open Registry Location" button.
        Find this button in the Setup Manager interface.

    Click "Open Registry Location".
        This will open a warning message about editing the registry.

    Read the warning message.
        Carefully review the risks associated with editing the registry.

    Confirm or cancel.
        Click "OK" to proceed to the registry editor, or "Cancel" to return to the Setup Manager.

    Click "Exit".
        This will close the Setup Manager cleanly.

    Verify the program has closed.
        Check your system tray to ensure the AutoHotkey icon associated with the Setup Manager has disappeared.

Tips

    Keep an eye on the status text in the Manager for real-time updates on operations.
    The Setup Manager dynamically enables or disables buttons based on your system's current state.
    If you can't find the CopyAsText.ahk file, the CopyAsText Context Tool Manager will prompt you to select its location manually.

Warnings

⚠️ Be cautious when editing the registry, as incorrect changes can cause system issues.
⚠️ Your virus protection is likely to trigger due to the registry contact, I trust me but you make an informed choice by examining the code fully before using.
