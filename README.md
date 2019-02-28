# *The Big Bang Theory* corpus

This corpus provides the manual transcripts of all episodes from season 1 to season 10 from the tv series *The Big Bang Theory*, in the *transcripts* folder.
Each season folder contains a file for each episode of the season, annotated with name entity recognition.

## Annotated episode file

For a given annotated episode file, each line is a word from the transcript. Separator is a space, fields are:
- Word from transcript
- normalized name of the speaker 
- entity type of the word, X if not an entity
- normalized name of the mentionned entity, X if not an entity
- class of the mentionned entity. 1 for first person, 2 for second person, 3 for third person
