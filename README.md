# scap-fisma-ready-ubuntu-lts
SCAP content for FISMA-Ready ubuntu-lts

## About

This is a release of SCAP content for GSA [18F's FISMA-Ready Ubuntu LTS](https://github.com/fisma-ready/ubuntu-lts).


## Files

### data stream
`datastream/Ubuntu_14.04_LTS_Server_Datastream_v0.0.1.xml` file includes all of the content of the 16 xml files in one huge xml file. This is the current best practice for packaging and distributing content, but it’s kind of a mess to actually look at. You can import and run this file using Joval or any other SCAP engine that supports SCAP 1.2 Datastreams.

### Zip Bundle
`zip/Ubuntu_14.04_LTS_Server_SCAP_Bundle_v0.0.1.zip` includes the 16 XCCDF and OVAL files that we reviewed this morning. You can import the zip into Joval or any other SCAP engine that supports SCAP Bundles and run it.

### Source files
The directory `source` contains the individual OVAL xml files and associated CPE files.

