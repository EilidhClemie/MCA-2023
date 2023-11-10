|[ WEEK 1 ](Week1.md)|[ WEEK 2 ](Week2.md)|[ WEEK 3 ](Week3.md)|[ WEEK 4 ](Week4.md)|[ WEEK 5 ](Week5.md)|[ WEEK 6 ](Week6.md)|[ WEEK 8 ](Week8.md)|[ WEEK 9 ](Week9.md)|[ WEEK 10 ](Week10.md)|
## Week 3: Encoding Basics for Notation
In order to explore types of standards for music data, I generated both XML and MEI files from my transcribed score.
The rendering of my MEI file within Verovio is available at: https://eilidhclemie.github.io/MCA-2023/verovio.html

In analysing MusicXML and MEI as two types of encoding standards, I observed three elements in order to compare how the two standards operate:
* The two standards differ in how they are structured, with MusicXML largely structuring by each measure, with the elements follwing. However, MEI structures within its measures by stave. The structures again allow for differing ways of identifying elements/attributes such as notes pitch and duration, and key and time signature.
* To determine note/pitch, MusicXML organises chord, pitch, duration, voice, type of note, stem, and staff withing each note element. MEI organises notes within the chord elements and then includes abbreviated attributes for duration, octave, pitch, and stem within the note element.
* MusicXmL organises notes more commonly on an individual basis, whereas MEI often does not. Notes which are connected by beams therefore include each note and its attribute within a <beam> element.
There is a clear distinction in readability between the two standards. MusicXML allows for much easier recognition of elements of the score from a human perspective, whereas, MEI is largely more abbreviated, which is indicative of a more semantic, machine readable structure.
