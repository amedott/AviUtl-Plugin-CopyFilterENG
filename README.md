# AviUtl Plugin - Copy-Paste Filter

Original [plugin](https://github.com/hebiiro/AviUtl-Plugin-CopyFilter) by Hebiiro
i only translated menu items into english. it just works for me:tm:

## how 2 install

1. Put this file to your AviUtl's Plugins folder.
	* CopyFilter.auf

## how 2 use

1. Right click on a filter effect on ExtendedFilter window
2. Additional menu items below `<[filter]>` should be there.

## limitations

### object classifications

* Video Media Object(Can use Grouping)
* Video Filter Object
* Audio Media Object
* Audio Filter Object
* Camera control

Objects are classified into these categories and can only be copied and pasted between objects of the same category.

### Main filters

u can't copy the main (very top) fiilers

## requirements

* (Need) AviUtl 1.10 & 拡張編集 (ENG: Advanced Editing/Adv.Edit) 0.92 http://spring-fragrance.mints.ne.jp/aviutl/
* (Can use with) patch.aul r21 https://scrapbox.io/ePi5131/patch.aul

## credits

* Microsoft Research Detours Package https://github.com/microsoft/Detours
* aviutl_exedit_sdk https://github.com/ePi5131/aviutl_exedit_sdk
* Common Library https://github.com/hebiiro/Common-Library
