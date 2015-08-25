HL7 v2.7 Healthcare messages 
============================

This GitHub repository holds DFDL schemas that model a generic HL7 v2.7 healthcare message. 

To download the repository go to http://dfdlschemas.github.com/HL7-v2.7/.

These schemas are also available as part of the IBM Integration Bus Healthcare Pack (http://www-03.ibm.com/software/products/en/integration-bus-healthcare-pack). The IIB Healthcare Pack additionally contains DFDL schemas that model each individual HL7 message. The IIB Healthcare Pack additionally contains DFDL schemas for HL7 v2.5, v2.5.1 and v2.6.

HL7Format.xsd 
-------------
A DFDL schema that contains default values for DFDL properties that are suitable for HL7 v2.7 data.

datatypes.xsd
-------------
A DFDL schema that provides a set of DFDL-annotated types and groups for HL7 data types.

fields.xsd
----------
A DFDL schema that provides a set of DFDL-annotated elements HL7 fields.

segments.xsd
------------
A DFDL schema that provides a set of DFDL-annotated elements and types for HL7 segments.

GenericHL7.xsd
--------------
A DFDL schema that provides a DFDL-annotated element to model an HL7 message in a generic manner. 
The generic HL7 message consists of an MSH segment followed by any number of other HL7 segments or user-defined Z segments.

Z_Segments.xsd
--------------
A DFDL schema that provides an extension point for the modeling of user-defined Z segments.

----------------
HL7 standards can be obtained from the HL7 website: www.HL7.org

Please observe the copyright notice within each schema.

