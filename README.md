Readme
======
BNT\_ULx extends the CSPP_Core package of the CS++-Project. 

It contains a derived classes of CSPP\_DeviceActor

Refer to https://git.gsi.de/EE-LV/CSPP for CS++ project overview, details and documentation.

LabVIEW 2020 is the currently used development environment.

Related documents and information
=================================
- README.md
- EUPL v.1.1 - Lizenz.pdf
- Contact: Holger.Brand@BrandNewTechnologies.de
- Download, bug reports... : http://github.com/HB-BNT/BNT_ULx
- Documentation:
  - Refer to package folder

GIT Submodules
==============
This package can be used as submodule.

- Packages\BNT\BNT_ULx:
  - BNT_ULx-MCSV
  - BNT_ULx-MCSV-AIAvg
  - BNT_ULx-MCSV-Ctr2Freq
  - BNT_ULx-MCSV-DOPWM
  - BNT_ULx-MCSV-I
  - BNT_ULx-MCSV-RTD
  - BNT_ULx-MCSV-TC

External Dependencies
---------------------
- CSPP\_Core: https://git.gsi.de/EE-LV/CSPP/CSPP_Core
- ULx Universal Library™ 6.72 – Programming libraries and components for developing 32/64-bit applications, using Windows programming languages.
	- InstaCal 6.72 – Installation and test utility with device drivers.
	- MCC DAQ Software: https://www.mccdaq.com/swdownload
	   - You need to install InstaCal and LabVIEW Support with MCCDAQ.exe in order to use this package.
    - For LabVIEW 2021 support (beta) refer to https://www.mccdaq.com/downloads/LabVIEW2021_ULx/
  
Known Issues
------------
- All actor classes are not yet tested.
- BNT_ULx-MCSV: AI, AO , DI, DO, Counter seems to work.
- BNT_ULx-MCSV-AIAvg: It works.
- BNT_ULx-MCSV-Ctr2Freq: Same configuration for all counters at this time.

Getting started:
=================================
- Add BNT_ULx.lvlib into your own LabVIEW project.
- You need to extend your project specific ini-file.
  - A sample ini-file should be available on disk in the corresponding package folder.

Lizenziert unter EUPL V. 1.1 
  
Author: Holger.Brand@BrandNewTechnologies.de

Copyright 2021  Brand New Technologies

Dr. Holger Brand, Asternweg 12a, 64291 Darmstadt, Germany

Lizenziert unter der EUPL, Version 1.1 oder - sobald diese von der Europäischen Kommission genehmigt wurden - Folgeversionen der EUPL ("Lizenz"); Sie dürfen dieses Werk ausschließlich gemäß dieser Lizenz nutzen.

Eine Kopie der Lizenz finden Sie hier: http://www.osor.eu/eupl

Sofern nicht durch anwendbare Rechtsvorschriften gefordert oder in schriftlicher Form vereinbart, wird die unter der Lizenz verbreitete Software "so wie sie ist", OHNE JEGLICHE GEWÄHRLEISTUNG ODER BEDINGUNGEN - ausdrücklich oder stillschweigend - verbreitet.

Die sprachspezifischen Genehmigungen und Beschränkungen unter der Lizenz sind dem Lizenztext zu entnehmen.