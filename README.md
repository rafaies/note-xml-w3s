# Ejemplos validación xml con DTD y XML Schema

## Referencias:
- [Ejemplos de **XML Tutorial w3schools.com**](http://www.w3schools.com/xml)
    - [DTD Tutorial](https://www.w3schools.com/xml/xml_dtd_intro.asp)
    - [XML Schema Tutorial](https://www.w3schools.com/xml/schema_intro.asp)
- [Apuntes DTD y XML Schema](http://ocw.uc3m.es/ingenieria-informatica/ingenieria-de-la-informacion/material-de-clase-1/03-DTD_y_XML_SCHEMA.pdf) de la [Universidad Carlos III de Madrid OpenCourseWare: Ingeniería de la información](http://ocw.uc3m.es/ingenieria-informatica/ingenieria-de-la-informacion)

## Validación mediante DTD
- **note.xml**  --> Documento xml validado mediante *DTD externa* (**note.dtd**)
- **note.dtd**  --> DTD que valida el documento (**note.xml**)
- **note-internal-dtd.xml**  --> Documento xml validado mediante *DTD interna*

## Validación mediante XML Schema
- **note-xsd.xml**  --> Documento xml validado mediante XML Schema (**note-xsd.xsd**) con *espacio de nombres* especificado en el atributo *schemaLocation*
- **note-xsd.xsd**  --> XML Schema que valida el documento (**note-xsd.xml**)
- **note-nonamespace.xml** -->  Documento xml validado mediante XML Schema (**note-nonamespace.xsd**) sin espacio de nombres atributo *noNamespaceSchemaLocation*
- **note-nonamespace.xsd**  -->  XML Schema que valida el documento (**note-nonamespace.xml**)