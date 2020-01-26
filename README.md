# Hebrew Diacritization Test Corpora 

We offer up to the public domain 3 test sets for Hebrew diacritization, following a system-demonstration submission to ACL 2020. 

Each test set represents a different genre:

- Modern: A random selection of Hebrew wikipedia articles.

- Rabbinic: A sample from the Bet Yosef text, a 16th century commentary on Jewish law.

- Poetry: A set of liturgical poems of the 'yotzer' genre, transcribed from Cairo Genizah manuscripts. (full data on these texts is available [here](http://weekdayyotzrot.com))

## Format of the files

The files are fully diacritized Hebrew texts. Since undiacritized Hebrew is written in plene form (with added matres-lectionis), a proper diacritization test entails input of plene text and output of normalized texts, with matres-lectionis identified and removed. Therefore, we mark the matres-lectionis in these corpora with a special marking, encompasing them in angle brackets:

- E.g., the plene form "דיבר" when diacritized will be reduced to "דִּבֵּר", and there will be marked in the corpus as "דִּ<י>בֵּר".

When using these test corpora please input the Hebrew text letters as is (removing diacritics and angle brackets); and when checking the output please verify both that the correct diacritics have been selected and also that the matres-lectionis have been identified correctly and removed.
