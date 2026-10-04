# Settings IDEs - Keymap

Settings IDEs - Keymap is an IDE extension from the "Settings IDEs" Series. It provides a custom, handmade keymapping for the IDE, which is designed to improve productivity and the enjoyment of the coding experience.

Currently available for Visual Studio Code and JetBrains IDEs.

All the keybindings have been carefully handpicked to optimize the primary necessity of a full-focused developer: **keeping the hands on the keyboard**.

The keymap removes most of the default keybindings to avoid conflicts, although some "extra" keybindings are still there. Almost all mapped commands just require the vanilla IDE to work, a very small subset might require external extensions to be installed.

## Full Mapping:

Note: When there is a `|` pipe char in `Command` or `Desc` columns, it means that the left side of the pipe is related to VS Code and the right side of the pipe is related to JetBrains IDEs.

| Key     | Binding                      | Command                                         | Desc                                                   | Context                  |
|---------|------------------------------|-------------------------------------------------|--------------------------------------------------------|--------------------------|
|         |                              |                                                 |                                                        |                          |
| Q       | Ctrl + Q                     | Rename Symbol                                   |                                                        |                          |
|         | Ctrl + Shift + Q             | Rename File                                     | | +Refactor Quick List                                 |                          |
|         | Ctrl + Alt + Q               | Refactor                                        | | //Contextual Refactor                                |                          |
| W       | Ctrl + W                     | Expand Selection                                |                                                        |                          |
|         | Ctrl + Shift + W             | Shrink Selection                                |                                                        |                          |
| E       | Ctrl + E                     | Recent Files                                    |                                                        |                          |
|         | Ctrl + Shift + E             | Reveal in File Explorer View                    |                                                        |                          |
|         | Ctrl + Alt + E               | Tool Window Picker                              | //"Open View"; needs also Shift |                      |                          |
| R       | Ctrl + R                     | Replace                                         |                                                        |                          |
|         | Ctrl + Shift + R             | Replace in Files                                |                                                        |                          |
|         | Ctrl + Alt + R               | Replace One | []                                | | //No Replace One option in {Jetbrains}               | {Search Widget Visible}  |
|         | Shift + Alt + R              | Find Prev                                       |                                                        | {Search Widget Visible}  |
|         | Alt + R                      | Find Next                                       |                                                        | {Search Widget Visible}  |
| T       | Ctrl + T                     | Reformat Code                                   |                                                        |                          |
|         | Ctrl + Shift + T             | Reformat File                                   |                                                        |                          |
|         | Ctrl + Shift + Alt + T       | Convert Indentation to Spaces                   |                                                        |                          |
|         | Ctrl + Alt + T               | Convert Indentation to Tabs                     |                                                        |                          |
| Y       | Ctrl + Y                     | Redo                                            |                                                        |                          |
|         | Ctrl + Shift + Y             | Cursor Redo                                     | | //Is Actually "Go Forward; Half-Bugged               |                          |
|         | Ctrl + Alt + Y               | Next Edit Location                              |                                                        |                          |
| U       | Ctrl + U                     | Insert Code Snippet                             |                                                        |                          |
|         | Ctrl + Shift + U             | Surround With                                   |                                                        |                          |
|         | Ctrl + Alt + U               | Generate Code                                   |                                                        |                          |
| I       | Ctrl + I                     | Trigger Inline Suggestion                       |                                                        |                          |
|         | Ctrl + Shift + I             | Inline Chat                                     |                                                        |                          |
|         | Ctrl + Shift + Alt + I       | Copilot Multiple Suggestions                    |                                                        |                          |
|         | Ctrl + Alt + I               | Toggle Chat                                     | | //"Agent" in {Android Studio}                        |                          |
| O       | Ctrl + O                     | New File                                        |                                                        |                          |
|         | Ctrl + Shift + O             | New Folder                                      |                                                        |                          |
|         | Ctrl + Alt + O               | Toggle File Read-only Attribute                 |                                                        |                          |
| P       | Ctrl + P                     | Parameters Hints                                |                                                        |                          |
|         | Ctrl + Shift + P             | Quick Documentation                             |                                                        |                          |
|         | Ctrl + Shift + Alt + P       | Increase Hover Verbosity | Toggle Rendered View |                                                        |                          |
|         | Ctrl + Alt + P               | [] | Type Info                                  |                                                        |                          |
| A       | Ctrl + A                     | Select All                                      |                                                        |                          |
|         | Ctrl + Shift + A             | Select All Occurrences                          |                                                        |                          |
|         | Ctrl + Alt + A               | Add Cursor at End of Selected Lines             |                                                        |                          |
| S       | Ctrl + S                     | Save File                                       |                                                        |                          |
|         | Ctrl + Shift + S             | Save All | []                                   |                                                        |                          |
|         | Ctrl + Alt + S               | Save File As | []                               |                                                        |                          |
| D       | Ctrl + D                     | Duplicate Line/Selection                        |                                                        |                          |
|         | Ctrl + Shift + D             | Delete Line                                     |                                                        |                          |
| F       | Ctrl + F                     | Find                                            |                                                        |                          |
|         | Ctrl + Shift + F             | Find in Files                                   |                                                        |                          |
|         | Ctrl + Shift + Alt + F       | Peek Usages                                     |                                                        |                          |
|         | Ctrl + Alt + F               | Find Usages                                     |                                                        |                          |
|         | Alt + F                      | Toggle Find in Selection                        |                                                        | {Search Widget Visible}  |
| G       | Ctrl + G                     | Git Add All | Git Quick List                    | | //No Staging Area in {Jetbrains}                     |                          |
|         | Ctrl + Shift + G             | Git Commit                                      |                                                        |                          |
|         | Ctrl + Shift + Alt + G       | Git Push                                        |                                                        |                          |
|         | Ctrl + Alt + G               | Git Pull                                        |                                                        |                          |
| H       | Ctrl + H                     | Type Hierarchy                                  |                                                        |                          |
|         | Ctrl + Shift + H             | [] | Method Hierarchy                           |                                                        |                          |
|         | Ctrl + Alt + H               | Call Hierarchy                                  |                                                        |                          |
| J       | Ctrl + J                     | Toggle Panel                                    | | //Actually "Terminal"                                |                          |
|         | Ctrl + Shift + J             | Toggle Primary Side Bar                         | | //Actually "Project"                                 |                          |
|         | Ctrl + Shift + Alt + J       | Toggle Secondary Side Bar                       |                                                        |                          |
|         | Ctrl + Alt + J               | Maximize Tool Window                            |                                                        |                          |
| K       | Ctrl + K                     | {RESERVED} | History Quick List                 |                                                        |                          |
|         | Ctrl + Shift + K             | Toggle Git Panel                                |                                                        |                          |
|         | Ctrl + Shift + Alt + K       | Compare Files                                   |                                                        |                          |
|         | Ctrl + Alt + K               | Show Diff                                       | HEAD <--> Local                                        |                          |
| L       | Ctrl + L                     | Accept Left Change                              | +Revert Change                                         |                          |
|         | Ctrl + Shift + L             | Accept All Left Changes                         | +Revert File                                           |                          |
|         | Ctrl + Shift + Alt + L       | Accept All Right Changes                        |                                                        |                          |
|         | Ctrl + Alt + L               | Accept Right Change                             |                                                        |                          |
|         | Shift + Alt + L              | Prev Change                                     |                                                        |                          |
|         | Alt + L                      | Next Change                                     |                                                        |                          |
| Z       | Ctrl + Z                     | Undo                                            |                                                        |                          |
|         | Ctrl + Shift + Z             | Cursor Undo                                     | | //Is Actually "Go Back"; Half-Bugged                 |                          |
|         | Ctrl + Alt + Z               | Prev Edit Location                              |                                                        |                          |
| X       | Ctrl + X                     | Cut                                             |                                                        |                          |
|         | Ctrl + Shift + X             | {}                                              |                                                        |                          |
| C       | Ctrl + C                     | Copy                                            |                                                        |                          |
|         | Ctrl + Shift + C             | Copy File Abs Path                              |                                                        |                          |
|         | Ctrl + Alt + C               | Copy File Rel Path                              |                                                        |                          |
| V       | Ctrl + V                     | Paste                                           |                                                        |                          |
|         | Ctrl + Shift + V             | Paste as Text                                   |                                                        |                          |
| B       | Ctrl + B                     | Build Project                                   | | //'Assemble Project' in {Android Studio}             |                          |
|         | Ctrl + Shift + B             | Sync Project Gradle                             | | //Only {Android Studio}                              |                          |
|         | Ctrl + Shift + Alt + B       | Rebuild Project                                 | | //Broken in {Android Studio}                         |                          |
|         | Ctrl + Alt + B               | Clean Project                                   | | //Only {Android Studio}                              |                          |
| N       | Ctrl + N                     | Sort Lines Ascending                            | Should not be used on Code                             |                          |
|         | Ctrl + Shift + N             | Sort Lines Descending                           | Should not be used on Code                             |                          |
|         | Ctrl + Alt + N               | [] | Analysis Quick List                        |                                                        |                          |
| M       | Ctrl + M                     | {}                                              |                                                        |                          |
|         | Ctrl + Shift + M             | {}                                              |                                                        |                          |
| 1       | Ctrl + 1                     | {}                                              | | +Go to Bookmark 1                                    |                          |
|         | Ctrl + Shift + 1             | [] | Toggle Bookmark 1                          |                                                        |                          |
|         | Alt + 1                      | View/Explorer                                   |                                                        |                          |
| 2       | Ctrl + 2                     | {}                                              | | +Go to Bookmark 2                                    |                          |
|         | Ctrl + Shift + 2             | [] | Toggle Bookmark 2                          |                                                        |                          |
|         | Alt + 2                      | View/Search                                     |                                                        |                          |
| 3       | Ctrl + 3                     | {}                                              | | +Go to Bookmark 3                                    |                          |
|         | Ctrl + Shift + 3             | [] | Toggle Bookmark 3                          |                                                        |                          |
|         | Alt + 3                      | View/Commit Panel                               |                                                        |                          |
| 4       | Ctrl + 4                     | {}                                              | | +Go to Bookmark 4                                    |                          |
|         | Ctrl + Shift + 4             | [] | Toggle Bookmark 4                          |                                                        |                          |
|         | Alt + 4                      | View/Run                                        |                                                        |                          |
| 5       | Ctrl + 5                     | Toggle Block Comment                            | | +Go to Bookmark 5                                    |                          |
|         | Ctrl + Shift + 5             | [] | Toggle Bookmark 5                          |                                                        |                          |
|         | Alt + 5                      | View/Extensions | View/TODO                     |                                                        |                          |
| 6       | Ctrl + 6                     | {}                                              | | +Go to Bookmark 6                                    |                          |
|         | Ctrl + Shift + 6             | [] | Toggle Bookmark 6                          |                                                        |                          |
|         | Alt + 6                      | View/Problems                                   |                                                        |                          |
| 7       | Ctrl + 7                     | Toggle Line Comment                             | | +Go to Bookmark 7                                    |                          |
|         | Ctrl + Shift + 7             | [] | Toggle Bookmark 7                          |                                                        |                          |
|         | Alt + 7                      | View/Debug                                      |                                                        |                          |
| 8       | Ctrl + 8                     | {}                                              | | +Go to Bookmark 8                                    |                          |
|         | Ctrl + Shift + 8             | [] | Toggle Bookmark 8                          |                                                        |                          |
|         | Alt + 8                      | View/Terminal                                   |                                                        |                          |
| 9       | Ctrl + 9                     | {}                                              | | +Go to Bookmark 9                                    |                          |
|         | Ctrl + Shift + 9             | [] | Toggle Bookmark 9                          |                                                        |                          |
|         | Alt + 9                      | View/Git Panel                                  |                                                        |                          |
| 0       | Ctrl + 0                     | Close Editor Tab                                |                                                        |                          |
|         | Ctrl + Shift + 0             | Close Editor Tabs Right                         |                                                        |                          |
|         | Ctrl + Shift + Alt + 0       | Close All Editor Tabs                           |                                                        |                          |
|         | Ctrl + Alt + 0               | Close Other Editor Tabs                         |                                                        |                          |
|         | Alt + 0                      | View/Notifications                              |                                                        |                          |
| '       | Ctrl + '                     | Focus Editor                                    |                                                        |                          |
|         | Ctrl + Shift + '             | Focus Panel                                     | | //Tool Window in {Jetbrains}                         |                          |
|         | Ctrl + Alt + '               | Focus Primary Side Bar                          | | //Tool Window in {Jetbrains}                         |                          |
| \       | Ctrl + \                     | Split Right                                     |                                                        |                          |
|         | Ctrl + Shift + \             | Split Down                                      |                                                        |                          |
|         | Ctrl + Alt + \               | Unsplit                                         |                                                        |                          |
| <       | Ctrl + <                     | {}                                              | //Should be for ad-hoc uses                            |                          |
|         | Ctrl + Shift + <             | {}                                              | //Should be for ad-hoc uses                            |                          |
| TAB     | Ctrl + TAB                   | Switcher                                        | (""View: Quick Open Recently Used Editor in Group"") | |                          |
|         | Ctrl + Shift + TAB           | Switcher                                        | (""View: Quick Open Recently Used Editor in Group"") | |                          |
|         | Ctrl + Alt + TAB             | {OS RESERVED}                                   | OS Window Switcher                                     |                          |
|         | Alt + TAB                    | {OS RESERVED}                                   | OS Window Instant Switcher                             |                          |
| ,       | Ctrl + ,                     | Toggle Fold                                     |                                                        |                          |
|         | Ctrl + Shift + ,             | Toggle Soft-Wrap                                |                                                        |                          |
|         | Ctrl + Shift + Alt + ,       | Unfold All                                      |                                                        |                          |
|         | Ctrl + Alt + ,               | Fold All                                        |                                                        |                          |
| .       | Ctrl + .                     | Open Settings                                   |                                                        |                          |
|         | Ctrl + Shift + .             | Restart IDE                                     |                                                        |                          |
|         | Ctrl + Alt + .               | [] | Invalidate Caches                          |                                                        |                          |
| -       | Ctrl + -                     | Font Size Decrease                              |                                                        |                          |
|         | Ctrl + Shift + -             | Font Size Reset                                 | | //Broken                                             |                          |
|         | Ctrl + Alt + -               | Zoom Reset                                      |                                                        |                          |
|         | Alt + -                      | Zoom Out                                        |                                                        |                          |
| +       | Ctrl + +                     | Font Size Increase                              |                                                        |                          |
|         | Ctrl + Shift + +             | Toggle Zen Mode                                 |                                                        |                          |
|         | Alt + +                      | Zoom In                                         |                                                        |                          |
| Esc     | Ctrl + Esc                   | {OS RESERVED}                                   | Open Start Menu; Equivalent to Windows Key             |                          |
|         | Ctrl + Shift + Esc           | {OS RESERVED}                                   | Open Task Manager                                      |                          |
|         | Alt + Esc                    | {OS RESERVED}                                   | Cycle Open Windows                                     |                          |
| Ins     | Ctrl + Ins                   | Copy                                            | //Should not be changed                                |                          |
|         | Ctrl + Shift + Ins           | Paste as Text                                   | //Should not be changed                                |                          |
| BS      | Ctrl + BS                    | Delete Word Left                                |                                                        |                          |
|         | Ctrl + Shift + BS            | Delete All Left                                 |                                                        |                          |
| Del     | Ctrl + Del                   | Delete Word Right                               |                                                        |                          |
|         | Ctrl + Shift + Del           | Delete All Right                                |                                                        |                          |
|         | Ctrl + Alt + Del             | {OS RESERVED}                                   | Open Windows Security Screen                           |                          |
| ENTER   | Ctrl + ENTER                 | Run                                             |                                                        |                          |
|         | Ctrl + Shift + ENTER         | Stop                                            |                                                        |                          |
|         | Ctrl + Alt + ENTER           | Debug                                           |                                                        |                          |
|         | Alt + ENTER                  | Quick Fix                                       |                                                        |                          |
| SPACE   | Ctrl + SPACE                 | Trigger Code Completion                         |                                                        |                          |
|         | Ctrl + Shift + SPACE         | [] | Trigger Type-Matching Code Completion      |                                                        |                          |
|         | Alt + SPACE                  | {OS RESERVED}                                   | Open Window Context Menu                               |                          |
| UP      | Ctrl + UP                    | Scroll Line Up                                  |                                                        |                          |
|         | Ctrl + Shift + UP            | Select Page Up                                  | | //Half-Bugged                                        |                          |
|         | Ctrl + Alt + UP              | Move Line Up                                    | | //Move Statement; Keeps Identation                   |                          |
|         | Ctrl + Shift + Alt + UP      | Select to Text Start                            | +Stretch Up                                            |                          |
|         | Shift + UP                   | Select Up                                       |                                                        |                          |
|         | Shift + Alt + UP             | Select Up                                       |                                                        |                          |
|         | Alt + UP                     | Go to Previous Function                         |                                                        |                          |
| DOWN    | Ctrl + DOWN                  | Scroll Line Down                                |                                                        |                          |
|         | Ctrl + Shift + DOWN          | Select Page Down                                | | //Half-Bugged                                        |                          |
|         | Ctrl + Alt + DOWN            | Move Line Down                                  | | //Moves Statement; Keeps Identation                  |                          |
|         | Ctrl + Shift + Alt + DOWN    | Select to Text End                              | +Stretch Down                                          |                          |
|         | Shift + DOWN                 | Select Down                                     |                                                        |                          |
|         | Shift + Alt + DOWN           | Select Down                                     |                                                        |                          |
|         | Alt + DOWN                   | Go to Next Function                             |                                                        |                          |
| LEFT    | Ctrl + LEFT                  | Move Cursor Word Left                           |                                                        |                          |
|         | Ctrl + Shift + LEFT          | Select Word Left                                |                                                        |                          |
|         | Ctrl + Alt + LEFT            | Move Cursor to Line Start                       |                                                        |                          |
|         | Ctrl + Shift + Alt + LEFT    | Select to Line Start                            | +Stretch Left                                          |                          |
|         | Shift + LEFT                 | Select Left                                     |                                                        |                          |
|         | Shift + Alt + LEFT           | Select Left                                     | | //Broken                                             |                          |
|         | Alt + LEFT                   | Open Previous Tab                               |                                                        |                          |
| RIGHT   | Ctrl + RIGHT                 | Move Cursor Word Right                          |                                                        |                          |
|         | Ctrl + Shift + RIGHT         | Select Word Right                               |                                                        |                          |
|         | Ctrl + Alt + RIGHT           | Move Cursor to Line End                         |                                                        |                          |
|         | Ctrl + Shift + Alt + RIGHT   | Select to Line End                              | +Stretch Right                                         |                          |
|         | Shift + RIGHT                | Select Right                                    |                                                        |                          |
|         | Shift + Alt + RIGHT          | Select Right                                    | | //Broken                                             |                          |
|         | Alt + RIGHT                  | Open Next Tab                                   |                                                        |                          |
| ì       | Ctrl + ì                     | {}                                              |                                                        |                          |
|         | Ctrl + Shift + ì             | {}                                              |                                                        |                          |
| è       | Ctrl + è                     | {}                                              |                                                        |                          |
|         | Ctrl + Shift + è             | {}                                              |                                                        |                          |
| ò       | Ctrl + ò                     | {}                                              |                                                        |                          |
|         | Ctrl + Shift + ò             | {}                                              |                                                        |                          |
| à       | Ctrl + à                     | {}                                              |                                                        |                          |
|         | Ctrl + Shift + à             | {}                                              |                                                        |                          |
| ù       | Ctrl + ù                     | {}                                              |                                                        |                          |
|         | Ctrl + Shift + ù             | {}                                              |                                                        |                          |
|         |                              |                                                 |                                                        |                          |
|         | Ctrl + C                     | Copy Line                                       |                                                        | {NO Selection}           |
|         | Ctrl + X                     | Cut Line                                        |                                                        | {NO Selection}           |
|         | Alt + F                      | Toggle Find in Selection                        |                                                        | {Search Widget Visible}  |
|         | Alt + R                      | Find Next                                       |                                                        | {Search Widget Visible}  |
|         | Shift + Alt + R              | Find Prev                                       |                                                        | {Search Widget Visible}  |
|         | Ctrl + Alt + R               | Replace | []                                    |                                                        | {Search Widget Visible}  |
|         | Ctrl + T                     | New Terminal                                    |                                                        | {Terminal Focus}         |
|         | Ctrl + Shift + T             | Close Terminal                                  | | //Half-Broken; Use Alt instead                       | {Terminal Focus}         |
|         | Ctrl + RIGHT                 | Accept Next Word of Inline Suggestion           |                                                        | {Inline Suggestion}      |
|         | Ctrl + Alt + RIGHT           | Accept Next Line of Inline Suggestion           |                                                        | {Inline Suggestion}      |
|         |                              |                                                 |                                                        |                          |
|         | [Drag & Drop]                | Move Selection to Drop Loc                      |                                                        | {Editor && Selection}    |
|         | Ctrl + [Drag & Drop]         | Copy Selection to Drop Loc                      |                                                        | {Editor && Selection}    |
|         | Ctrl + Shift + Alt + UP      | Stretch Up                                      |                                                        | {Non-Editor View Focus}  |
|         | Ctrl + Shift + Alt + DOWN    | Stretch Down                                    |                                                        | {Non-Editor View Focus}  |
|         | Ctrl + Shift + Alt + LEFT    | Stretch Left                                    |                                                        | {Non-Editor View Focus}  |
|         | Ctrl + Shift + Alt + RIGHT   | Stretch Right                                   |                                                        | {Non-Editor View Focus}  |
| MWheel+ | Shift + MWheel+              | Open Tabs Left | []                             |                                                        | {Tab Bar && Hovering}    |
|         | Alt + MWheel+                | Fast Scroll Up | []                             |                                                        |                          |
|         | Ctrl + MWheel+               | Scroll Left                                     |                                                        |                          |
|         | ctrl + Shift + Alt + MWheel+ | [] | Stretch to Top; Stretch to Right           |                                                        | {Cursor on Tool Window}  |
| MWheel- | Shift + MWheel-              | Open Tabs Right | []                            |                                                        | {Tab Bar && Hovering}    |
|         | Alt + MWheel-                | Fast Scroll Down | []                           |                                                        |                          |
|         | Ctrl + MWheel-               | Scroll Right                                    |                                                        |                          |
|         | ctrl + Shift + Alt + MWheel- | [] | Stretch to Bottom; Stretch to Left         |                                                        | {Cursor on Tool Window} |
| Mouse4  | Mouse4                       | Go Back                                         |                                                        |                          |
| Mouse5  | Mouse5                       | Go Forward                                      |                                                        |                          |
| LMB     | Ctrl + Click                 | Go to Declaration or Show Usages                |                                                        | {Cursor on Element}      |
|         | Ctrl + Shift + LMB           | [] | Go to Type Declaration                     |                                                        | {Cursor on Element}      |
|         | Ctrl + Alt + LMB             | [] | Go to Type Definition                      |                                                        | {Cursor on Element}      |
|         | Shift + Alt + LMB            | Create Rectangular Selection                    |                                                        | {Mouse Drag}             |
|         | Alt + Click                  | Multiple Selections                             |                                                        | {Mouse Drag}             |
|         | Alt + Click                  | Add/Remove Cursor                               |                                                        |                          |
|         | Esc Esc                      | {BROKEN} | Hide Active Tool Window              |                                                        |                          |
|         | Shift Shift                  | Search Bar                                      | | //"Search Everywhere"                                |                          |
|         | Ctrl Ctrl                    | Run Command                                     | | //"Run Anything"                                     |                          |



## Check out more from the Settings IDEs Series

- **Settings IDEs - ColorTheme** --> [GitHub](https://github.com/filippochinni/settings-ides--color-theme) | [VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=filippochinni.settings-ides--color-theme) | [Jetbrains Marketplace](https://plugins.jetbrains.com/plugin/34753-settings-ides--colortheme)

My VS Code Marketplace Profile: [Visual Studio Marketplace Publishers](https://marketplace.visualstudio.com/publishers/filippochinni)

My Jetbrains Marketplace Profile: [Jetbrains Marketplace](https://plugins.jetbrains.com/vendor/filippochinni)

<!-- <a href="https://www.flaticon.com/free-icons/gaming" title="gaming icons">Gaming icons created by Flat Icons - Flaticon</a> -->
