# Slic3r Configurations for the DSP Informatik AG 3D Printer

The following repository stores a set of configurations optimized for the DSP Informatik AG 3D Printer.

## Configuration Files

Due to the rather questionable choice of components used for our 3D printer, uncalibrated firmware and gcode will ultimately result it nothing but gibberish.

As a result, configurations files have been provided for a range of print sizes:

**Sizes**

|File|Size|Reference Object|
|----|----|----------------|
|[DSP_InfoAG_3DPrinter_Config_S.ini](Slic3r-Configs/blob/master/DSP_InfoAG_3DPrinter_Config_S.ini)|Small|[10mm test cube](https://www.thingiverse.com/thing:56671)|
|[DSP_InfoAG_3DPrinter_Config_M.ini](Slic3r-Configs/blob/master/DSP_InfoAG_3DPrinter_Config_S.ini)|Medium|[20mm test cube](https://www.thingiverse.com/thing:56671)|

## Downloading

To download the configuration files, you may download this repository as a ZIP from [here](https://github.com/DSP-Informatik-AG/Slic3r-Configs/archive/master.zip), or clone this repository using `git`

```
git clone https://github.com/DSP-Informatik-AG/Slic3r-Configs.git
```

## Applying configuration files

To apply configuration files, use the `CTRL + L` shortcut, or select `File > Load Config...` from the top menubar. From there, select the desired configuration from your print.
