NORB_4
======

Welcome to the repository for all NORB 4 board software.


Introduction
============

The NORB 4 board is part of the NORB float series project which requires a whole new type of PCB. The NORB 3 board being the most equipped, with temperature/humidity sensing equipment and a micro SD socket to log all the data. However, despite it's 0.8mm thickness, the NORB 3 board when fully equipped is far too heavy to pass for a float, where the target total payload weight is only 30 grams maximum.

  

Therefore, a board was needed that would be absolutely tiny and far more lightweight in comparison. It's small ceramic chip antenna being only a fraction of the size and weight, replaced the huge heavy Taoglas patch antenna on the NORB 3 board. Having no temperature/humidity sensor, but its very own SI446x based radio circuit, coupled with a super-efficient LTC3526 regulator and FET driven Ublox Max 7 GPS module, this board is without doubt the most power efficient module developed by NORB!



Current software
================

The current v1.0 software is the initial commit for this project and has not yet been 100% tested. The software currently transmits 300 baud interrupt driven RTTY but is soon to hopefully support interrupt driven MFSK modes such as DominoEx and THOR. The baud rate can be set to any desired value by modifying the BAUD_RATE value at the top of the main script.


For more information, be sure to visit:

                                                    www.norb.co.uk
 
 
