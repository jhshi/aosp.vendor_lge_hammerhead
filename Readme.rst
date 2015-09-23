LGE Vendor Blobs For Nexus 5 (hammerhead)
=========================================

Usage
----------

Check out specific tags for the AOSP release.

 - ``for_android-4.4.4_r1``: KitKat
 - ``for_android-5.1.1_r3``: Lollipop

Why Do We Need This?
------------------

Ironically, the `official LGE binary blobs
<https://developers.google.com/android/nexus/drivers>`_ do not work out of the
box (at least for Sprint phones): no cellular data, can not update cellular
profile and PRL.

What's Different?
-----------------

This blob repo was based on the official LGE binaries, but updated with the ones
in factory image. Additionally, a ``apns-conf.xml`` was also pulled from the
factory image, which fixes the cellular data issue.
