# translateNvdaAddonsWithCrowdin

The goald of this add-on is help translators work more efficiently when using this [project to translate NVDA add-ons with Crowdin](https://crowdin.com/project/nvdaaddons).

## Settings
Though most translators won`t need to use this feature, a dialog is provided to save the Crowdin token, and to select the directory where documentation and interface message files will be stored.
To open this dialog, go to NVDA menu, Preferences submenu, Settings dialog, Translate NVDA add-ons with Crowdin category.

Also, a gesture can be assigned to open the add-on settings from the Input gestures dialog.

## Translate add-ons with Crowdin
This dialog can be accessed from NVDA menu, Tools submenu, or assigning a gesture from the Input gestures dialog.

The following controls are available:

* A combo box to select the translation language.
* An edit box to filter the list of files available to translate.
* A list of files with po and xliff extensions. This will be focused when the dialog is opened. Press enter to open the selected file.
* A button to open the selected file. The file will be opened with Poedit, if po and xliff files are associated with this program on your system.
* A button to upload the Upload the selected translated file.
* A button to download translations for the selected language.
* A button to download all translations
* A button to close the dialog.


## Downloading and uploading translations
* This process may take several minutes, and may not be available if you reach your Crowdin token limits.
* NVDA may block during a few seconds when these processes are started. After that, you can work normally, and a message should be presented when the process has finished.


