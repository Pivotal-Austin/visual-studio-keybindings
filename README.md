# Pivotal Austin Visual Studio Keybindings

Requirements:
- Visual Studio 2017
- Resharper Ultimate with License

## Setup


### 1. Clone this repo

```
cd ~/workspace
git clone https://github.com/Pivotal-Austin/visual-studio-keybindings.git
```

### 2. Import into Visual Studio

1. Go to the Tools menu.
1. Select Import and Export Settings...
1. Browse to the appropriate file for your visual studio version.
1. Import the settings.

The settings should now be imported!

## Notes

Below is the functionality that is supported:

```
Quick Open: CTRL + T                              (Resharper_GoToType)
Close File: CTRL + W                              (CloseFile)
Close All But This File: CTRL + SHIFT + W         (File.CloseAllButThis)
Grow Focus (Smart): CTRL + UP                     (Resharper_ExtendSelection)
Shrink Focus (Smart): CTRL + DOWN                 (Resharperk_ShrinkSelection)
Move Lines Up: CTRL + SHIFT + UP                  (MoveSelectedLinesUp)
Move Lines Down: CTRL + SHIFT + DOWN              (MoveSelectedLinesDown)
Copy Lines Down (Duplicate): CTRL + D             (Resharper_DuplicateText)
Line Delete: ALT + Backspace                      (Edit.LineDelete)
Add To Multi Select: NOT SUPPORTED
Undo Add To Multi Select: NOT SUPPORTED
Redo: CTRL + SHIFT + Z
Undo: CTRL + Z
Recent Files: ALT + E                             (Resharper_GotoRecentFiles)
Split Window Vertically: CTRL + ALT + SHIFT + UP  (NewVerticalTabGroup)
Move File Right: CTRL + ALT + SHIFT + RIGHT       (MoveToNextTabGroup)
Move File Left: CTRL + ALT + SHIFT + LEFT         (MoveToPreviousTabGroup)
Move Left (Group of Files): NOT SUPPORTED
Move Right (Group of Files): NOT SUPPORTED
Reformat Code: CTRL + ALT + ENTER                 (Resharper_Reformat)
```
