
# Universal ROM Cleaner 2 3 This software allows you to easily clean your romsets based on the parentheses and brackets attributes of your files. 4 5 - It is multilingual (English / French) 6 - It is easy to use (everything works with the mouse by simply dragging and dropping) 7 8 __How does it work: __ 9 10 1 - Download the latest version : [Universal Rom Cleaner] (https://github.com/Universal-Rom-Tools/Universal-ROM-Cleaner/releases) 11 2 - Unzip the archive and run the EXE file. 12 3 - In the File / Load roms menu, choose the directory of your set to clean. 13 4 - In the table on the left, order your preferences (what you want to keep the most at the top, the least in the base) 14 5 - Move in the table at the top on the right what you do not want to keep 15 6 - Move in the table at the bottom right which should not be taken into account in the sorting 16 7 - In the action menu you can either simulate the sorting (you will then have a text file with OK which is kept, KO which is not 'is not kept) or do the cleaning directly 17 8 - It's finished, you have a nice clean romset for your recalbox) 18 19 __Additional information: __ 20 The software does not delete anything, it only moves to a directory “ROM_CLEAN” the selected and sorted roms 21 22! [Universal ROM Cleaner Interface] (http://zupimages.net/up/16/10/xd29.jpg "Interface") 23 24 In the example of screenshot here is what it does if you have: 25 26 - mario (USA) (En, Fr, De) .zip 27 - mario (Europe) (En, Fr, De) .zip 28 - mario ( Europe) (In, Fr, De, Es) .zip 29 - mario (Europe) (En, Fr, De) (Beta) .zip 30 - mario (Japan) .zip 31 The only file kept will be “mario (Europe) (En, Fr, De) .zip ”32 33 Because: I ask him not to keep the“ Beta ”or the“ Japan ”and that in order, I keep the“ Europe ”files before the“ USA ”files and afterwards this first choice, I keep in priority those in “En, Fr, De” before those in “En, Fr, De, Es” 34 35 Do not hesitate to make simulations if you are not sure of your choice 😉 36 37 __UDF used__ 38 [GUIListViewEx] (https://www.autoitscript.com/forum/topic/124980-guilistviewex-new-version-7-mar-16/) by Melba23 39 [Extended Message Box] (https : //www.autoitscript.com/forum/topic/109096-extended-message-box-bugfix-version-9-aug-15/) by Melba23 40 [ArrayMultiColSort] (https://www.autoitscript.com/forum / topic / 155442-arraymulticolsort-new-release-15-sep-15 /) by Melba23 41 [MultiLang] (https://www.autoitscript.com/forum/topic/118495-multilangau3/) by BrettF 42 [Trim] (https: //www.autoitscript. com / forum / topic / 14173-new-string-trim-functions /) by blitzer99 43
