# Week 3 

## Task: Export your score to MusicXML and MEI. Then render your MEI file using Verovio in GitHub

Here is the Satisfied MusicXML file: [Satisfied MusicXML File](SXML.txt)

Here is the Satisfied MEI file: [Satisfied MEI File](SatisfiedTestXML.mei)

Here is the Satisfied Verovio file: [Satisfied Verovio File](verovio.html)

## Task: Compare 3 elements in the MusicXML file to the corresponding ones in MEI

### The <staff> Element
Both files contain the <staff> element which holds the information about the staves within the piece.

- In MusicXML, it indicates on which staff each element of notation resides.
- In MEI, it also indicates on which staff each element of notation resides - however it can also display which of multiple staves it resides. For example, using the element <staff n="1">. 'N' refers to 'note' and '1' refers to the 'first staff'.

In both MusicXML and MEI, the staff element does not contain and child elements and therefore, it cannot be classed as a parent.
