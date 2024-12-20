[Home](README.md)
[Week 1](week1.md)
[Week 2](week2.md)
[Week 3](week3.md)
[Week 4](week4.md)
[Week 5](week5.md)
[Week 7](week7.md)
[Week 8](week8.md)
[Week 9](week9.md)
[Week 10](week10.md)

# Week 3 

## Task: Export your score to MusicXML and MEI. Then render your MEI file using Verovio in GitHub

Here is the Satisfied MusicXML file: [Satisfied MusicXML File](Round2XML.musicxml)

Here is the Satisfied MEI file: [Satisfied MEI File](SatisfiedTestXML.mei)

Here is the Satisfied Verovio file: [Satisfied Verovio File](verovio.html)

## Task: Compare 3 elements in the MusicXML file to the corresponding ones in MEI

### The 'Staff' Element
Both files contain the <staff> element which holds the information about the staves within the piece.

- In MusicXML, it indicates on which staff, each element of notation resides.
- In MEI, it also indicates on which staff, each element of notation resides - however it can also display where a note resides over multiple staves. For example, using the element staff n=1. 'N' refers to 'note' and '1' refers to the 'first staff'.

In both MusicXML and MEI, the staff element does not contain and child elements and therefore, it cannot be classed as a parent.

### The 'Note' Element
- In MusicXML, the note tag is a parent element, and contains various child tags within it - which highlight the characteristics of a note. These characteristics include duration, ties, accidentals, pitch, articulations and type.
- In MEI, again the data is slightly more advanced. it includes all of the above characteristics, however it also includes tags such as 'tpc' (tonal pitch class) - and accidentals are defined as 'accids'.

### The 'Pitch' Element
- In MusicXML, the pitch is referred to as a number. For example, pitch=63.
- However, in MEI, the element is referred to as 'pname' and is assigned a letter - for example, 'C'. This suggests that MEI is more comprehensible than MusicXML in terms of understanding notation in an academic environment. However, MusicXML is in a more standardised format, making it more accessible and transferrable.

### Implications
The differences between the two softwares means they are each likely to be utilised for different purposes. For example, MusicXML is more effective in accessing and exchanging the data universally, whereas MEI is perhaps more useful to scholars and researchers/archivists who intend to analyse and study the musical data.
