# Converter-SOAP-XML-JSON-Binding-Framework 
## Using the Spring's Object/ XML Mapping, we can convert Object to XML or vise versa.

* XML Marshalling - Convert Object to XML. 
* XML UnMarshalling - Convert XML to Object.
SOAP, REST, XML, JSON, XML Marshaliing, XML UnMarshalling

## JAXB: 
1. JAXB stands for Java Architecture for XML Binding.
2. JAXB provides mechanism to marshal java objects into XML and Unmarshal XML into Java Object.

## @XmlRootElement:
The name of the root XML element is derived from the class name. We can also specify custom name for the root elemnt of the XML by using its name attribute.
## @XmlElement: 
XML element is used to define a specific name for Object property which will be used in XML.

## @XmlAttribure: 
XML attribute is used for defining attributes which can be added in Root element.

## @XmlType: 
For specifiying order of elements which will be followed while writing data into the XML file.
