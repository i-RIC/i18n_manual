GUI translation
================

Step 1
------

Find the translation file (\*.ts) you want to edit, which you can find at the following URL:

  https://github.com/i-RIC/prepost-gui/tree/develop_v4/languages

Step 2
-------

Open the translation file with text editor and add translations for each English word.
Please refer to :numref:`code_ts_before_editing` and
:numref:`code_ts_after_editing`.

.. code-block:: xml
   :caption: *.ts before editing
   :name: code_ts_before_editing

   <message>
     <source>Animation ToolBar</source>
     <translation type="unfinished"></translation>
   </message>

.. code-block:: xml
   :caption: *.ts after editing
   :name: code_ts_after_editing

   <message>
     <source>Animation ToolBar</source>
     <translation>アニメーションツールバー</translation>
   </message>

What you should do is as follows:

1. Delete "type=unfinished"
2. Add translated text between <translation> and </translation>
3. Save the file

Step 3
-------

Compile "*.ts" file using "lrelease.exe"

**You should install Qt SDK to get lrelease.exe. See Appendix for detail.**

1. Launch "Qt 5.15.2 (MSVC 2019 64-bit)" from menu below:

      [Windows Start Menu] --> [Qt]

2. Move to the folder which contains "\*.ts" file.
3. Execute the following command.

.. code-block:: batch

   lrelease.exe (dictionary file name)

After you execute the command, you'll see that \*.qm is created in the same folder.

Step 4
-------

You can check the translated text in the iRIC GUI by the following steps:

1. Remove all dictionary files in (iRIC install folder)/guis/prepost/languages
2. Copy the \*.qm file you've compiled with Step 3 to the folder above.
3. Switch the language from the menu Option -> Preference
4. Restart iRIC GUI
