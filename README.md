# flipper_lib
A collection of [Flipper Zero](https://flipperzero.one/) files that can be used to emulate signals of various types.  These files can be loaded onto SD cards and used by Flipper devices.

*Note: This repository is just beginning, pardon our dust ;)*

## Directory Structure
Files are organized into directories according to the modality they were captured in (e.g., `Sub-GHz`, `NFC`, etc.), the type of device, and the specific model.  

For example:

```bash
.
└── Modality/
    └── Type/
        └── Model/Device
```

Individual files ae named with the following convention:


```
<manufacturer name/abbreviation>_<type>_<model number or name>_<function>.sub
```

## File Formats
The various `Flipper Zero` modalities require different file formats to generate signals, such as :

- `.sub` files file `Sub-GHz`
- `.ir` files or Infrared 

among others.  A more comprehensive list can be found [here](https://knowledgebase.beehive.systems/threats/hardware/flipper-zero/firmware/flipper-xtreme/wiki/subghz).
