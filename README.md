# TabTranslate

## purpose 
Since I'm tired of rewriting parts for electric guitar I decided to create this little program with the aim of being able to transpose a Tablature for electric guitar by changing key and tuning of the guitar. 

## tablature format 
here is a classic example saso to explain how the tblatures for electric guitar are normally written 


e|----------5/6-6-6-5/6-6-6-6-6-6------------------------------------|

B|-------6--5/6-6-6-5/6-6-6-6-6-6-9-8-6-6----------------------------|

G|---6h7--------------------------------6h7--------------------------|

D|-8----------------------------------------8-6--8-8-8-8-8-8-8-8-----|

A|-----------------------------------------------8-8-8-8-8-8-8-8-----|

E|-------------------------------------------------------------------|

each number represents the fret of the guitar to be used, the letters at the beginning are the tuning of the guitar. 
ù
## first version - 4/4 

At the moment the program can successfully transpose the tablature, rewrite and update the tuning, and save the tablature in a .txt file by adding information about the transposition. 

### Problem : 
when scaling the note in question below the lowest fret. the weights are updated by adding the note to the next string. However, in this way the "pattern" can be lost.   
