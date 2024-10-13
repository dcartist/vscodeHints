To disable the hint pop-ups in Visual Studio Code (VSCode), follow these steps based on the specific type of pop-up you're referring to:

### 1. **Disable Parameter Hints (Signature Help)**
If you want to disable the pop-up that shows function signatures (parameter hints) when you're writing code:
   
1. Open VSCode.
2. Go to **File** > **Preferences** > **Settings** (or press `Ctrl + ,`).
3. In the search bar at the top, type `editor.parameterHints`.
4. Uncheck the option **Editor: Parameter Hints Enabled**.

This will stop VSCode from showing function signatures.

### 2. **Disable Hover Hints**
If the annoying pop-ups appear when you hover over code (e.g., tooltips or documentation):

1. Open **Settings** (`Ctrl + ,`).
2. In the search bar, type `editor.hover.enabled`.
3. Uncheck the box for **Editor: Hover Enabled**.

This will prevent the hover pop-ups from appearing.

### 3. **Disable IntelliSense Suggestions (Auto-Complete Popups)**
If the hint is related to auto-completion, and you want to control or disable that:

1. Open **Settings** (`Ctrl + ,`).
2. Search for `editor.suggestOnTriggerCharacters`.
3. Uncheck the box for **Editor: Suggest on Trigger Characters** to prevent pop-ups when typing trigger characters (like `.` or `(`).
   
Alternatively, you can control the delay or disable auto-suggestions completely by searching for `editor.quickSuggestions` and adjusting the settings.

### 4. **Disable Inlay Hints (for Inline Type Information)**
If you find that inlay hints (which show types or parameter names inline in the code) are the issue:

1. Open **Settings** (`Ctrl + ,`).
2. In the search bar, type `editor.inlayHints.enabled`.
3. Toggle the setting **Editor: Inlay Hints Enabled** to turn them off.

After making these changes, the hint pop-ups should no longer appear or should be significantly reduced depending on the option you've disabled.
