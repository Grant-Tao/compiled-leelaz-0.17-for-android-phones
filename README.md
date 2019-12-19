# compiled-leelaz-0.17-for-android-phones
Compiled leela zero 0.17 for different android phone

Both cpu-only and opencl single precision modes are working


leelaz_855  for Qualcomm snapdragon 855 && Android 9.0 (not tested)

leelaz_820  for Qualcomm snapdragon 820 (not tested)

leelaz_970  for Huawei Kirin 970 && Android 9.0  (tested, work on cpu-only and opencl precision single modes)

leelaz_660  for Redmi Note 7, snapdragon 660 & Android 9.0 (tested, work on all modes)

sai_970  is https://github.com/sai-dev/sai, for Huawei Kirin 970 && Android 9.0 (tested, work on cpu-only and opencl precision single modes)

Running under:

weight file: gzip format (txt not work)

adb shell:  "leelaz -w w.gz --cpu-only"  or  "leelaz -w w.gz --precision single" or "leelaz -w w.gz" (half precision mode) 

Go GridMaster: see GridMaster's help, add leelaz as its engine.

hope you enjoy it.


