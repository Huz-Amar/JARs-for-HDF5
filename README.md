# JARs-for-HDF5
Contains JARs needed to get HDF5 working on an IDE

### Reasoning
HDF5 has its own download page where you can get the zip file [here](https://www.hdfgroup.org/downloads/hdf5/), but I, along with many other users I believe, could not get this working. I decided instead to directly import the JARs for HDF5 into an IDE and use the library that way. 

The reason for this Github page is not just to give instructions to users looking to use HDF5 but to also provide a place to grab the JARs (and dll files), since links and download pages can quickly become dead. 

### JARs
There are two available HDF5 JARs in this project, for versions 2.6.1 and version 3.3.2. Use which one is needed for your project. My own personal recommendation is 3.3.2

Note that with version 3.3.2, it is necessary to also use the slf4j library, which has also been provided with the hdf5 3.3.2 files. 

### Instructions
To get the library working with an IDE (I have tested this on both Eclipse and IntelliJ), create a folder in your project to hold the necessary files, and then import the JARs in from your project settings. Plenty of tutorials can be found online for this
