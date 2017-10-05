[![License](https://img.shields.io/aur/license/yaourt.svg)](https://opensource.org/licenses/gpl-license)

## tConvertXMLToJSON

+ Version 1.0

Converts a XML string to a JSON string.

---

### Overiew of job flow

![Alt text](/doc/job_overview.png?raw=true "Job - Flow Diagram")

### Retrieving an xml content

1. Read XML as string from a xml file

![Alt text](/doc/tFileInputRaw_01.png?raw=true "tFileInputRaw - read file")

2. Append other columns of data and convert xml to string. 

![Alt text](/doc/tMap_01.png?raw=true "tMap - create new schema")

### Convert XML to JSON

3. Synch up the schema in the tConvertXMLToJSON component

![Alt text](/doc/tConvertXMLToJSON_01.png?raw=true "tConvertXMLToJSON - schema")

4. Select the column with the xml string to convert. All other columns will be passed through.

![Alt text](/doc/tConvertXMLToJSON_02.png?raw=true "tConvertXMLToJSON - convert")

### Results

![Alt text](/doc/output_01.png?raw=true "tLogRow - console")
