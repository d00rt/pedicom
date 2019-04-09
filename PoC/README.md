# PoC 1: PeDi2 File Infector (Virus:Win32/PeDi2.A)
PeDi2 is the first DICOM file infector, this binary is able to infect other DICOM images and convert them into PEDICOM polyglot images, this means that it is able to embed itself in other DICOM images. This allows it to hide in DICOM images in a very stealthy way.

## flowchart
![Alt text](https://github.com/d00rt/pedicom/blob/master/rsc/flowchart.png)

# PoC 2: Polyglot (PEDICOM)

In this proof of concept you can see a demonstration of how two files (cylera.dcm and cylera.exe) have become one (pedicom-cylera.dcm), i.e. a polyglot file (It can be loaded as a DICOM or as a PE executable) taking advantage of the design flaw of the DICOM format.

# Disclaimer
PeDi2 is nothing more than a proof of concept to show what someone with bad intentions could do. The intention of this repository is no more than didactic and allowing the community to anticipate such attacks.
