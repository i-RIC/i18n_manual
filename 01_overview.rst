Overview
=========

iRIC support multiple languages. Language setting can be changed with
the following menu.

[Option] --> [Preferences...]

When you change language setting,
you have to restart iRIC to apply the setting.

This document describes the procedure to prepare
translation dictionaries of iRIC.

Dictionary files you need to prepare are shown in :numref:`table_dic_files`.

.. list-table:: Dictionary files
   :name: table_dic_files
   :header-rows: 1

   * - Extension
     - Description
     - Solver
     - GUI

   * - \*.ts
     - | XML text file
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

You can find the translation file(\*.ts) for iRIC GUI
at the following URL:

  https://github.com/i-RIC/prepost-gui/tree/develop_v4/languages


The files with name "iRIC_xx_XX.ts" are the files to translate. They are the files
created from dictionary files for each libraries by merging.

The languages currently supported in iRIC, and the file names of
translation files for each language are shown in
:numref:`table_languages`.

.. list-table:: Languages currently supported
   :name: table_languages
   :header-rows: 1

   * - Language
     - File name

   * - Arabic
     - iRIC_ar_EG.ts

   * - Basque
     - iRIC_eu_ES.ts

   * - Bosnian
     - iRIC_bs_BA.ts

   * - Bulgarian
     - iRIC_bg_BG.ts

   * - Catalan
     - iRIC_ca_ES.ts

   * - Chinese (China)
     - iRIC_zh_CN.ts

   * - Chinese (Taiwan)
     - iRIC_zh_TW.ts

   * - Czech
     - iRIC_cs_CZ.ts

   * - Danish
     - iRIC_da_DK.ts

   * - Dutch
     - iRIC_nl_NL.ts

   * - Estonian
     - iRIC_et_EE.ts

   * - Finnish
     - iRIC_fi_FI.ts

   * - French
     - iRIC_fr_FR.ts

   * - German
     - iRIC_de_DE.ts

   * - Galician
     - iRIC_gl_ES.ts

   * - Greek
     - iRIC_el_GR.ts

   * - Hindi
     - iRIC_hi_IN.ts

   * - Hungarian
     - iRIC_hu_HU.ts

   * - Icelandic
     - iRIC_is_IS.ts

   * - Indonesian
     - iRIC_id_ID.ts

   * - Italian
     - iRIC_it_IT.ts

   * - Japanese
     - iRIC_ja_JP.ts

   * - Korean
     - iRIC_ko_KR.ts

   * - Latvian
     - iRIC_lv_LV.ts

   * - Lithuanian
     - iRIC_lt_LT.ts

   * - Norwegian
     - iRIC_nb_NO.ts

   * - Polish
     - iRIC_pl_PL.ts

   * - Portuguese (Brazil)
     - iRIC_pt_BR.ts

   * - Portuguese (Portugal)
     - iRIC_pt_PT.ts

   * - Romanian
     - iRIC_ro_RO.ts

   * - Russian
     - iRIC_ru_RU.ts

   * - Slovenian
     - iRIC_sl_SI.ts

   * - Spanish
     - iRIC_es_ES.ts

   * - Swedish
     - iRIC_sv_SE.ts

   * - Thai
     - iRIC_th_TH.ts

   * - Turkish
     - iRIC_tr_TR.ts

   * - Ukrainian
     - iRIC_uk_UA.ts
