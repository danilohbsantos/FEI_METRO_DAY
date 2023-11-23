This is collection of G-NetTrack Pro logfiles in text and kml format from measurement with active mixed test sequence (data, voice, SMS). The measurement is done in outdoor, indoor (in subway) and auto indoor (in tunnel) mode.

Logfiles description:

Text logfiles:
- A1_BG_2018.05.30_18.04.31.txt - main text logfile. The name convention is [operator]_[time].txt. The file is in tab delimited format.
- events.txt - tab delimited file with events (handovers reselections, calls etc...)
- stats.txt - statistic for voice calls and SMS test during the measurement
- cellinfo.txt - information about change of cell data (LAC, frequency) during measurement compared to cellfile information.
- datatest.txt - data sequence and data test results.In file there is one row for each test written at the end of the test.

Kml logfiles: Kml logfiles can be opened with Google Earth. They contain measurement information and coloring is based on different measurement entity.
- antennabearing - coloring is based on serving antenna bearing
- arfcn - frequency channel
- band - frequency band
- cellid - serving CELLID
- cqi - CQI
- distance - serving distance
- dlbitrate - current downlink bitrate in kbps
- events - file contains all events (reselection, handovers, calls etc...)
- filemarks - filemarks saved during measurement
- ip - IP
- lac - CELLID
- cellid - serving cell LAC
- layer - serving cell layer from cellfile
- locationmode - GPS, indoor or auto indoor mode during measurement
- lterssi - LTE RSSI
- ncell1 - ncell6 - neighbor cells CELLID
- nlev1 - nlev6 - neighbor cells level
- pc - BSIC (2G), PSC (3G), PCI (4G)
- phonestate - idle (I), voice call active (V), data active (D)
- qual - RxQual (2G), ECNO (3G), RSRQ (4G)
- rnc - RNC (3G), eNodeBID (4G)
- rxlev - RxLev (2G), RSCP (3G), RSCP (4G)
- snr - SNR
- speed - speed of movement
- ta - timing advance
- technology - technology - 2G, 3G, 4G
- technology mode - technology mode - EDGE, HSPA etc...
- ulbitrate - current uplink bitrate in kbps

Data measurement kml files:
- datatest - information from datatest made by Menu - Data test and Data sequence. In text file datatest.txt there are results in table view.
- datateststate - ping, upload, download
- testul - uplink bitrate in kbps for data tests made using Data sequence
- testdl - downlink bitrate in  for data tests made by using Data sequence
- ping - ping (avg, min, max, standard deviation) made by using Data sequence
- pingloss - ping loss

