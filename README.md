# fbcp-st7789
- It's a fork from fbcp-ili9341, view origin [README.md](README_orig.md)
- Added support for st7789 2.0inch 320x240
    - cmake cmd: `cmake -DWAVESHARE_ST7789VW_HAT ON -DGPIO_TFT_DATA_CONTROL=24 -DGPIO_TFT_RESET_PIN=25 -DSPI_BUS_CLOCK_DIVISOR=30 -DSTATISTICS=0 -DDISPLAY_BREAK_ASPECT_RATIO_WHEN_SCALING=ON .. && make -j && sudo ./fbcp-st7789`
