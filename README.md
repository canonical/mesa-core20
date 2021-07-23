# mesa libraries for core20 snaps

A content snap providing the mesa userspace libraries and drivers for core20

This supplies the graphics-core20 content interface:

    .../lib contains the mesa shared libraries (add to LD_LIBRARY_PATH)
    .../drv contains the mesa drivers (set LIBGL_DRIVERS_PATH/LIBVA_DRIVERS_PATH to this)
    .../etc/mir-quirks contains any Mir configuration for driver support (none for mesa)

----

For details of the graphics-core20 content interface see:

https://discourse.ubuntu.com/t/the-graphics-core20-snap-interface/23000