# Named-Entity-Recognition-
A Deep Learning NER model for English Language. Similar approach can be applied for other language annotated text.

I have build the Bi-Directional LSTM model to find the Named Entities of English Language using GMB(Groningen Meaning Bank) corpus. There are 8 different named entities as following -

geo = Geographical Entity
org = Organization
per = Person
gpe = Geopolitical Entity
tim = Time indicator
art = Artifact
eve = Event
nat = Natural Phenomenon

The given dataset contains 4 columns - sentence, word, Pos, Tag.
The same model can be applied for different languages if we have the annotated data for any language.
