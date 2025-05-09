# ESP32 PoE Alarm Board

This repository contains all files related to the ESP32-Alarm board project.

## Project Structure

- **Docs/**  
  Project documentation (LaTeX sources, images, generated PDFs, etc.).

- **Resources/**  
  Manuals, datasheets, reference images, and other useful materials.

- **alarm.yaml**  
  Main ESPHome configuration file, defining the firmware behavior for the ESP32.

- **Case v2.step**  
  3D model of the enclosure for the board.

- **ESP32_Alarm_PCB.kicad_sch**  
  Electrical schematic of the board, created with KiCad.

- **ESP32_Alarm_PCB.kicad_pcb**  
  PCB layout of the board, created with KiCad.

- **ESP32_Alarm_PCB.kicad_pro / .kicad_prl / .kicad_dru**  
  KiCad project files and design rule settings.

- **ESP32_Alarm_PCB.step**  
  3D model of the PCB for mechanical integration and visualization.

- **production/**  
  Folder containing production files such as netlists and fabrication archives.

- **ESP32-POE/**  
  Custom KiCad libraries, footprints, and symbols, including modules and screw terminals.

- **ESP32_Alarm_PCB-backups/**  
  Automatic backups of KiCad project files.

- **fabrication-toolkit-options.json**  
  Options for PCB fabrication toolkit and production file generation.

## Notes

- All KiCad project files are compatible with version 8.0 or newer.
- To build and upload the firmware, edit and use `alarm.yaml` with ESPHome.