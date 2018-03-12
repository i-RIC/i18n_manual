Overview
=========

iRIC support multiple languages. Language setting can be changed with
the following menu.

[Option] --> [Preferences...]

When you change language setting,
you have to restart iRIC to apply the setting.

This document describes the procedure to prepare
translation dictionaries of iRIC.

Language dictionary files you need to prepare translation for
iRIC software are shown in :numref:`table_dic_files`.

.. list-table:: Dictionary files
   :name: table_dic_files
   :header-rows: 1

   * - Extension
     - Description
     - Solver
     - GUI

   * - \*.ts
     - | Xml text file
       | This file contains the translated texts used in iRIC.
     - x
     - x

   * - \*.qm
     - | Binary file
       | This file is created from "\*.ts" by "lrelease.exe".
       | "lrelease.exe" is a executable program which is
       | included in Qt SDK. Refer to Appendix for detail.
     - 
     - x

You can find the translation file(\*.ts and \*.qm) for iRIC GUI
at the following folder:

  (Install folder)\\iRIC\\guis\\prepost\\languages

The languages currently supported in iRIC, and the file names of
translation files for each language are shown in
:numref:`table_languages`. If you want to add translation for
additional languages, please contact us.

.. list-table:: Languages currently supported
   :name: table_languages
   :header-rows: 1

   * - Language
     - File name

   * - Japanese
     - \*_ja_JP.ts

   * - Korean
     - \*_ko_KR.ts

   * - Thai
     - \*_th_TH.ts

   * - Indonesian
     - \*_id_ID.ts

   * - Chinese
     - \*_zh_CN.ts
