# Sovol-SV07-Default-Klipper-Config

For the Sovol SV07, ***NOT*** the SV07 Plus or Klipperized SV06/Plus.

Generated from the image obtained from the "Flash SV07 Mirror Software and Mirror Files Tutorial Video" link at https://www.sovol3d.com/pages/download

Bricked my SV07's klipper board when I accidently removed a usb stick from my board while a firmware update was running (UI provided no indication it had started)
Was able to resurrect it with Tomas Olsson's guide (https://github.com/TomasOlsson/BrickedSv07-Sv07Plus) but was anable to find an unmodified SV07's printer.cfg to replace the included one for the SV07 Plus.

I then followed the same guide but with the mirror files provided by Sovol, to mixed success. It now runs, but will not write to the emmc module and instead now just runs of the USB drive.
For me, it's a good-enough solution for now.
