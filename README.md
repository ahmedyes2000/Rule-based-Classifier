In “Lexica," I added two files: pos.wn (positive sentiwordnet itesm) and neg.wn (negative sentiwordnet items).
SentiWordNet is here: http://sentiwordnet.isti.cnr.it/ and you can acquire it from authors. I extracted the entries in the two files from the original source, to facilitate processing for you. But I also suggest that you get familiar with the original. Also, we cannot share these files beyond the class as it is used under a license. 
The format of each of this is one word or phrase per line.
Phrases are concatenated with an underscore (so you will need to write a script or use unix to replace the underscore with a space).
For example, you have the phrase "twilight_of_the_gods" in the neg.wn file.
In “Data," you have 1000 posTweets.txt (with 1000 tweets with a ":)" face
 
and 1000 negTweets.txt (with 1000 tweets with a ":(" face)
 
You also have a third file from Twitter that has the following format:
 
— Emotion label (e.g., “HAPPY”, “ANGRY”) \t Tweet_id \t Tweet_text

a rule-based classifier for sentiment (or emotion, although we still don’t have emotion dictionaries) exploiting these resources. 
