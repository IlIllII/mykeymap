# MyKeymap


Custom keymap that remaps keyboard navigation to jkli. Influenced by vim, but still VSCode.

<br>

## **Warning**

---

### This keymap involves the remapping of much of the right hand side of the keyboard away from stock VSCode bindings. Because of this, some other extensions' shortcuts will become incompatible with this keymap. This can be resolved by remapping the colliding bindings as needed.

---

<br>

## Table of Contents
  - [Navigation](#navigation)
  - [Selection](#selection)
  - [Deletion](#deletion)
  - [Editing](#editing)
  - [Multi-Cursor](#multi-cursor)
  - [Searching](#searching)
  - [F Keys](#f-keys)
  - [Markdown](#markdown)
  - [File](#file)
  - [View Navigation](#view-navigation)
  - [Misc](#misc)
  - [Keys Currently Unbound](#keys-currently-unbound)

<br>

## Navigation

| Command                  | Key                       |
| ------------------------ | ------------------------- |
| cursorLeft               | ctrl + J                  |
| cursorRight              | ctrl + L                  |
| cursorUp                 | ctrl + I                  |
| cursorDown               | ctrl + K                  |
| cursorWordLeft           | ctrl + U                  |
| cursorWordPartLeft       | alt + U                   |
| cursorWordRight          | ctrl + O                  |
| cursorWordPartRight      | alt + O                   |
| cursorLineStart          | ctrl + M                  |
| cursorLineEnd            | ctrl + .                  |
| goToNextBlankLine        | ctrl + 9                  |
| goToPrevBlankLine        | ctrl + 8                  |
| goToNextFoldingRange     | ctrl + shift + alt + 8    |
| goToPreviousFoldingRange | ctrl + shift + alt + 9    |
| goToTop                  | ctrl + ; `chord` ctrl + I |
| goToMiddle               | ctrl + ; `chord` ctrl + J |
| goToBottom               | ctrl + ; `chord` ctrl + K |
| recenterCursor           | ctrl + ; `chord` ctrl + L |
| goToBracket              | ctrl + -                  |
| goToLine                 | ctrl + G                  |
| scrollLineUp             | alt + 8                   |
| scrollLineDown           | alt + 9                   |
| goToLastEditLocation     | ctrl + N `chord` ctrl + E |
| goBack                   | ctrl + alt + M            |
| goForward                | ctrl + alt + .            |
| goToFile                 | alt + G `chord` alt + F   |

<br>

## Selection

Simply press `shift` in addition to the movement command for most keybinings. Exceptions include:

| Command                  | Key                                       |
| ------------------------ | ----------------------------------------- |
| selectToTop              | ctrl + shift + ; `chord` ctrl + shift + I |
| selectToMiddle           | ctrl + shift + ; `chord` ctrl + shift + J |
| selectToBottom           | ctrl + shift + ; `chord` ctrl + shift + K |
| selectLine               | ctrl + shift + ; `chord` ctrl + shift + ; |
| expandSelection          | ctrl + ,                                  |
| shrinkSelection          | ctrl + shift + ,                          |
| selectAll                | ctrl + A                                  |
| setSelectionAnchor       | ctrl + ; `chord` ctrl + ;                 |
| selectFromAnchorToCursor | ctrl + ; `chord` ctrl + shift + ;         |
| jumpToSelectionAnchor    | ctrl + ; `chord` J                        |

<br>

## Deletion

Deletions are achieved by performing a chord with `ctrl + D` in the direction you want to delete.

| Command                  | Key                       |
| ------------------------ | ------------------------- |
| deleteLeft               | ctrl + D `chord` ctrl + J |
| deleteRight              | ctrl + D `chord` ctrl + K |
| deleteWordLeft           | ctrl + D `chord` ctrl + U |
| deleteWordRight          | ctrl + D `chord` ctrl + O |
| deleteWordPartLeft       | ctrl + D `chord` O        |
| deleteWordPartRight      | ctrl + D `chord` O        |
| deleteAllLeft            | ctrl + D `chord` ctrl + M |
| deleteAllRight           | ctrl + D `chord` ctrl + . |
| deleteBetweenParentheses | ctrl + D `chord` ctrl + - |
| deleteWord               | ctrl + D `chord` D        |
| deleteLine               | ctrl + D `chord` ctrl + D |

<br>

## Editing

| Command                    | Key                               |
| -------------------------- | --------------------------------- |
| indentLine                 | ctrl + ]                          |
| outdentLine                | ctrl + [                          |
| indentBlock                | ctrl + shift + ]                  |
| outdentBlock               | ctrl + shift + [                  |
| toggleFold                 | alt + [                           |
| foldAll                    | alt + ]                           |
| unfoldAll                  | shift + alt + ]                   |
| moveLinesUp                | alt + I                           |
| moveLinesDown              | alt + K                           |
| insertLineAfter            | ctrl + enter                      |
| insertLineBefore           | ctrl + shift + enter              |
| undo                       | ctrl + Z                          |
| redo                       | ctrl + shift + Z                  |
| cursorUndo                 | ctrl + Y                          |
| cursorRedo                 | ctrl + shift + Y                  |
| cut                        | ctrl + X                          |
| copy                       | ctrl + C                          |
| paste                      | ctrl + P                          |
| commentLine                | ctrl + /                          |
| formatDocument             | shift + alt + F                   |
| triggerParameterHints      | ctrl + shift + space              |
| triggerSuggest             | ctrl + space                      |
| toggleSuggestionDetails    | ctrl + space                      |
| showHover                  | ctrl + alt + space                |
| showDefinitionPreviewHover | ctrl + shift + alt + space        |
| toggleExplainMode          | ctrl + /                          |
| quickFix                   | ctrl + N `chord` ctrl + F         |
| autoFix                    | ctrl + N `chord` F                |
| fixAll                     | ctrl + N `chord` ctrl + shift + F |
| refactor                   | ctrl + N `chord` ctrl + R         |
| increment                  | ctrl + N `chord` ctrl + B         |
| organizeImports            | ctrl + N `chord` ctrl + O         |
| transformToLowercase       | alt + T `chord` alt + L           |
| transformToSnakecase       | alt + T `chord` alt + S           |
| transformToTitlecase       | alt + T `chord` alt + T           |
| transformToUppercase       | alt + T `chord` alt + U           |
| transposeCharacters        | ctrl + N `chord` ctrl + M         |

<br>

## Multi-Cursor

| Command                             | Key                    |
| ----------------------------------- | ---------------------- |
| addCursorAbove                      | ctrl + alt + I         |
| addCursorBelow                      | ctrl + alt + K         |
| cursorColumnSelectDown              | ctrl + shift + alt + K |
| cursorColumnSelectUp                | ctrl + shift + alt + I |
| cursorColumnSelectLeft              | ctrl + shift + alt + J |
| cursorColumnSelectRight             | ctrl + shift + alt + L |
| addSelectionToNextFindMatch         | alt + U                |
| addSelectionToPreviousFindMatch     | alt + O                |
| insertCursorAtEndOfEachLineSelected | ctrl + N `chord` E     |
| selectHighlights                    | ctrl + f2              |
| addCursorsToBottom                  | ctrl + N `chord` B     |
| addCursorsToLineEnds                | ctrl + N `chord` E     |
| addCursorsToTop                     | ctrl + N `chord` T     |
| addCursorsToSearchResults           | ctrl + N `chord` S     |

<br>

## Searching

| Command                         | Key                     |
| ------------------------------- | ----------------------- |
| find                            | ctrl + F                |
| findWithSelection               | alt + F                 |
| findInFiles                     | ctrl + shift + F        |
| replace                         | ctrl + R                |
| replaceAll                      | ctrl + alt + enter      |
| selectAllMatches                | alt + enter             |
| toggleMatchCase                 | alt + C                 |
| toggleWholeWord                 | alt + W                 |
| toggleRegex                     | alt + R                 |
| addSelectionToNextFindMatch     | ctrl + alt + 9          |
| addSelectionToPreviousFindMatch | ctrl + alt + 8          |
| goToSymbolInEditor              | alt + G `chord` alt + S |
| goToSymbolInWorkspace           | alt + G `chord` S       |

<br>

## F Keys

To go to previous, just hold shift during command.

| Command                 | Key                |
| ----------------------- | ------------------ |
| goToDefinition          | F12                |
| peekDefinition          | alt + F12          |
| goToImplementation      | ctrl + F12         |
| peekImplementation      | ctrl + shift + F12 |
| goToReferencecs         | shift + F12        |
| findAllReferencecs      | shift + alt + F12  |
| goToNextDifference      | F7                 |
| goToNextProblemInFiles  | F8                 |
| goToNextProblem         | alt + F8           |
| goToNextReference       | F4                 |
| focusNextSearchResult   | F4                 |
| goToNextSymbolHighlight | F7                 |
| moveToNextChange        | F5                 |
| renameSymbol            | F2                 |
| showAllCommands         | F1                 |
| showEditorContextMenu   | shift + F10        | list button on keyboard |
| showNextChange          | alt + F3           |
| showPreviousChange      | shift + alt + F3   |

<br>

## Markdown

These keybindings are for the Markdown All in One extension.

| Command              | Key                             |
| -------------------- | ------------------------------- |
| toggleBold           | alt + M `chord` alt + B         |
| toggleItalic         | alt + M `chord` alt + I         |
| togglePreview        | alt + M `chord` alt + P         |
| openPreviewToSide    | alt + M `chord` alt + S         |
| addSectionNumbers    | alt + M `chord` alt + N         |
| removeSectionNumbers | alt + M `chord` alt + shift + N |
| createToC            | alt + M `chord` alt + T         |
| updateToC            | alt + M `chord` alt + U         |
| printToHtml          | alt + M `chord` alt + H         |
| toggleCodeBlock      | alt + M `chord` alt + C         |
| toggleCodeSpan       | alt + M `chord` C               |
| toggleList           | alt + M `chord` alt + L         |
| toggleMathEnv        | alt + M `chord` alt + M         |

<br>


## File

| Command                    | Key                       |
| -------------------------- | ------------------------- |
| save                       | ctrl + S                  |
| saveAs...                  | ctrl + shift + S          |
| newFile                    | ctrl + B `chord` ctrl + N |
| newUntitledFile            | ctrl + B `chord` ctrl + U |
| newFolder                  | ctrl + B `chord` ctrl + F |
| newWindow                  | ctrl + B `chord` ctrl + W |
| quickOpenRecent            | ctrl + B `chord` O        |
| openFile                   | ctrl + B `chord` ctrl + O |
| openFolder                 | ctrl + B `chord` F        |
| openRecent                 | ctrl + B `chord` ctrl + R |
| compareActiveFileWithSaved | ctrl + B `chord` ctrl + D |
| compareActiveFileWith...   | ctrl + B `chord` D        |
| saveAllFiles               | ctrl + B `chord` ctrl + S |

<br>

## View Navigation

| Command                         | Key                           |
| ------------------------------- | ----------------------------- |
| toggleVertical/HorizontalLayout | shift + alt + 0               |
| focusNextPart                   | F6                            |
| closeEditor                     | ctrl + F4                     |
| moveEditorToFirstGroup          | shift + alt + 1               |
| moveEditorToLastGroup           | shift + alt + 9               |
| moveEditorToNextGroup           | shift + alt + rightArrow      |
| moveEditorToPrevGroup           | shift + alt + leftArrow       |
| moveEditorLeft                  | ctrl + shift + pageUp         |
| moveEditorRight                 | ctrl + shift + pageDown       |
| openNextEditor                  | ctrl + tab                    |
| openPrevEditor                  | ctrl + shift + tab            |
| toggleTerminal                  | ctrl + `                      |
| toggleFullScreen                | F11                           |
| zoomIn                          | ctrl + numPadAdd              |
| zoomOut                         | ctrl + numPadSubtract         |
| showCallHeirarchy               | shift + alt + H               |
| toggleZenMode                   | alt + Z                       |
| increaseViewSize                | ctrl + shift + numpadAdd      |
| decreaseViewSize                | ctrl + shift + numpadSubtract |
| decreaseEditorWidth             | ctrl + numpad4                |
| increaseEditorWidth             | ctrl + numpad6                |
| decreaseEditorHeight            | ctrl + numpad2                |
| increaseEditorHeight            | ctrl + numpad8                |
| closePeek                       | shift + escape                |
| focusNextEditorGroup            | alt + N `chord` alt + O       |
| focusPreviousEditorGroup        | alt + N `chord` alt + U       |
| focusEditorGroupAbove           | alt + N `chord` alt + I       |
| focusEditorGroupBelow           | alt + N `chord` alt + K       |
| focusEditorGroupLeft            | alt + N `chord` alt + J       |
| focusEditorGroupRight           | alt + N `chord` alt + L       |
| toggleSideBar                   | alt + N `chord` alt + S       |
| focusIntoSideBar                | alt + N `chord` S             |
| nextSideBarView                 | alt + N `chord` alt + W       |
| previousSideBarView             | alt + N `chord` alt + Q       |
| threeColumnLayout               | alt + N `chord` 3             |
| twoColumnLayout                 | alt + N `chord` 2             |
| toggleDebugConsole              | alt + N `chord` alt + D       |
| splitEditorRight                | alt + N `chord` L             |
| splitEditorLeft                 | alt + N `chord` J             |
| splitEditorDown                 | alt + N `chord` K             |
| splitEditorUp                   | alt + N `chord` I             |
| openView                        | alt + N `chord` alt + V       |
| moveEditorIntoNextGroup         | ctrl + shift + rightArrow     |
| moveEditorIntoPreviousGroup     | ctrl + shift + leftArrow      |
| navigateBetweenEditorGroups     | alt + N `chord` alt + N       |
| moveView                        | alt + N `chord` M             |
| joinAllEditorGroups             | alt + N `chord` alt + M       |
| closeEditorGroup                | alt + N `chord` alt + G       |
| focusFolderView                 | alt + N `chord` E             |
| focusOutlineView                | alt + N `chord` O             |
| toggleContextLines              | alt + N `chord` alt + C       |
| focusNextResult                 | F4                            |
| focusPreviousResult             | shift + F4                    |
| replaceInFiles                  | alt + N `chord` alt + R       |
| revealActiveFileInSideBar       | alt + N `chord` alt + A       |

<br>

## Misc

| Command    | Key                       |
| ---------- | ------------------------- |
| colorTheme | ctrl + N `chord` ctrl + T |

<br>

## Keys Currently Unbound

| Key     |
| ------- |
| =       |
| q       |
| w       |
| e       |
| t       |
| num 1-7 |
| \       |
| '       |