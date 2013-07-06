CCDA_To_CCD-Conversion:
==================================
CCDA stands for Consolidated Clinical Document Architecture <br>
CCD stands for Continuity of Care Document<br> 
This repository contains program that <b>converts</b> any given CCDA document to CCD Document, 

Note: The program in this repository doesn't convert all sections of CCDA document.

About CCDA:
===========
The Consolidated CDA is based on components of two standard formats that were previously required for certified EHRs: 
the Continuity of Care Record (CCR) and the Continuity of Care Document (CCD). This format was chosen as the standard 
for communicating the summary of care since it can accommodate all data elements that CMS proposes providers give their 
patients after office visits. Health Level 7 (HL7), an accredited standards development organization, created a single 
implementation guide for the Consolidated CDA, which was released in December 2011 in an effort to reduce ambiguity and 
eliminate conflicts in documentation.
The Consolidated CDA solution encompasses a library of reusable CDA templates, setting the stage for streamlined 
development and quicker implementation. The templates allow for incremental interoperability and easier 
machine-to-machine communication, thereby facilitating the transfer and storage of more data.

About CCD:
=========
The Continuity of Care Document (CCD) specification is an XML-based markup standard intended to 
specify the encoding, structure, and semantics of a patient summary clinical document for exchange.<br>
<b>Structure:</b><br>
The CCD specification is a constraint on the HL7 Clinical Document Architecture (CDA) standard. The CDA 
specifies that the content of the document consists of a mandatory textual part (which ensures human 
interpretation of the document contents) and optional structured parts (for software processing). The 
structured part is based on the HL7 Reference Information Model (RIM) and provides a framework for 
referring to concepts from coding systems, such as the SNOMED or the LOINC.
The patient summary contains a core data set of the most relevant administrative, demographic, and 
clinical information facts about a patient's healthcare, covering one or more healthcare encounters. It 
provides a means for one healthcare practitioner, system, or setting to aggregate all of the pertinent data 
about a patient and forward it to another practitioner, system, or setting to support the continuity of care. 
Its primary use case is to provide a snapshot in time containing the pertinent clinical, demographic, and 
administrative data for a specific patient.

Visit link for more info. on CCD: http://en.wikipedia.org/wiki/Continuity_of_Care_Document

Source Code File:
================= 
ccdaConverter.java      &nbsp;&nbsp;&nbsp;   in 'src' folder

Examples of Input & Output File:
================================
Input_BlueButtonPlusSample.xml --- Output File
Output_CCDA_To_CCD_Converted_BlueButtonPlusSample.xml --- Input File (CCDA Format)

For more Info.:
===============
Read comments in ccdaConverter.java