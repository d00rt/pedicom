# PEDICOM
PEDICOM is the name given to the polyglot file created by combining the PE executable file format and the DICOM image format in a single file.

The PE executable file format, is a file format used by Windows for its programs and applications, while the DICOM format is used in medicine to store images, such as x-rays.

![Alt text](https://github.com/d00rt/pedicom/blob/master/rsc/poc.gif)

## Content
In this repository there is a paper in which it is documented and explained how it is possible to create a PEDICOM polyglot file. (in the doc folder)
In addition, you can find two PoC (under the PoC folder), one of them is simply a polyglot file PEDICOM, which has the name pedicom-cylera.dcm. The other is a binary which is used to self-replicate and infect other DICOM images. We could say that it is the first fileinfector that affects this file format. The name I have given to this file infector is PeDi2.

## Disclaimer 
The purposes for which this project has been created are didactic, and must be used by the community to improve protection against possible attacks of this type.
PeDi2 PoC is not malicious but it is advisable to use it in secure environments and virtual machines. I am not responsible for the bad use of the content in this repository.

## Contact/Maintainer 
Twitter: @D00RT_RM | Email: d00rt.fake@gmail.com | http://d00rt.eus

*[Cylera Labs](https://labs.cylera.com)*
