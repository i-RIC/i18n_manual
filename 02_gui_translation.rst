GUI translation
================

Step 1
------

Find the translation file (\*.ts) you want to edit, which is located in:

  (Install folder)\\iRIC\\guis\\prepost\\languages


Step 2
-------

Open the translation file with text editor and add translations for each English word.
Please refer to :numref:`code_ts_before_editing` and
:numref:`code_ts_after_editing`.

.. code-block:: xml
   :caption: *.ts before editing
   :name: code_ts_before_editing

   <message>
     <location filename="../main/animationcontroller.cpp" line="48"/>
     <source>Animation ToolBar</source>
     <translation type="unfinished"></translation>
   </message>

.. code-block:: xml
   :caption: *.ts after editing
   :name: code_ts_after_editing

   <message>
     <location filename="../main/animationcontroller.cpp" line="48"/>
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

1. Launch "Qt 5.5 64-bit for Desktop (MSVC 2013)" from menu below:

      [Windows Start Menu] --> [Qt] --> [5.5] --> [MSVC 2013 (64-bit)]

2. Move to the folder which contains "*.ts" file.
3. Execute the following command.

.. code-block:: batch

   lrelease.exe (dictionary file name)

After you execute the command, you'll see that *.qm is created in the same folder.

Step 4
-------

You can check the translated text in the iRIC GUI after restarting it.

