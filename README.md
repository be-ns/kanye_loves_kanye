# kanye_loves_kanye
A Lyrical excursion to find recursive mentions in Kanye West music, but Kanye West, about Kanye West.

Ideally to presented as an infographic.


I'll need to:
Make each song's lyrics a csv file.
create database to capture each
will need to have perfect tense written out for each album name to avoid long chains (written as (namename))
 create classes for Kanye Albums
  Kanye_TLOP for example: (Model)
      Famous' is instance of Kanye_TLOP


name.regex is instance of Kendrick and name = song _title(AS (namename))
    basically where chain of 4 or more words are referenced between songs. 
    reference is given in album class under song title
  
Kanye_TLOP.famous.reference1
    reference1-10 = dictionary with info for other song referenced


create regex pattern for matching words in 4-word chains
    Run each song against one another in for Loop where I exclude verse_by (if Jay-Z makes reference to Kanye,it doesn't
    count)
Verse_by as class - reference1.create(perfect tense of every song, album)



Exclusions
    exclude collaborations
        aka - WHEN REFERENCE IS VERSE_BY not Kanye

    INCLUDE when one is producer of other
    BUT MUSIC REFRENCES OTHER [SONG IN (PRODUCER/CLASS)]
    AS REFERENCE FOR PRODUCER WITH DATE TIME EARLIER
    (if kanye produces song for jay give kanye the reference, not jay)


    Include every 4-chain word and note reference across all songs


I'll have to manually ensure all 4-word chains are legitimate and not coincidence

