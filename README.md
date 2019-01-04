# DMS_Projects
The source files have been developed for MSVC version 2017, but they are all compatible with linux. There are two main applications: BIAP1D (for MEG and EEG) and BIAP4D (for MRI, fMRI, surfaces, etc). These applications need Qt 4.8.6 and are output in DMS_Projects\Exe\Biap64. 
Input file:
DMS_Projects\Qt4Projects\Biap.sln

Qt binaries provided are:
DMS_Projects\Exe\Biap64\QtGui4.dll
DMS_Projects\Exe\Biap64\QtCore4.dll

DMS_Projects\Qt4Projects\Lib\qtmain4_64_R.lib   (64 bits, release)
DMS_Projects\Qt4Projects\Lib\qtmain4_64_D.lib   (64 bits, debug)
DMS_Projects\Qt4Projects\Lib\qtmain4_32_R.lib   (32 bits, release)
DMS_Projects\Qt4Projects\Lib\qtmain4_32_D.lib   (32 bits, debug)

DMS_Projects\Qt4Projects\Lib\QtGui4_64_R   (64 bits, release)
DMS_Projects\Qt4Projects\Lib\QtGui4_64_D   (64 bits, debug)
DMS_Projects\Qt4Projects\Lib\QtGui4_32_R   (32 bits, release)
DMS_Projects\Qt4Projects\Lib\QtGui4_32_D   (32 bits, debug)

DMS_Projects\Qt4Projects\Lib\QtCore4_64_R   (64 bits, release)
DMS_Projects\Qt4Projects\Lib\QtCore4_64_D   (64 bits, debug)
DMS_Projects\Qt4Projects\Lib\QtCore4_32_R   (32 bits, release)
DMS_Projects\Qt4Projects\Lib\QtCore4_32_D   (32 bits, debug)

These binaries can be created by compiling source files from Qt 4.8.6
They are seperately stored in Qt4_MSVC2017_libs.zip

Mananuals for BIAP are stored in _BiapManual.zip

Help files to create Biap for linux can be found in: 
DMS_Projects\Qt4Projects\MakeBiap

Various smaller console applications can be found in:
DMS_Projects\Console\Console.sln

Test applications showing how the objects work:
DMS_Projects\Test\TestVarious.sln
