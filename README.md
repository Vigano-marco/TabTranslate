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

## first version - 4/4 

At the moment the program can successfully transpose the tablature even when it contains part of the text, rewrite and update the tuning, and save the tablature in a .txt file by adding information on the transposition. 

###problem : 
when scaling the note in question below the lowest fret. the weights are updated by adding the note to the next string. However, in this way you can lose the "pattern" and lose the closeness of the notes to be played. 

## txt file in output with translated notes 

song : translate_Jhonny_prova.txt


 transposed from E to D


original tuning : ['e', 'a', 'd', 'g', 'b', 'e']

final tuning : ['d', 'a', 'f#', 'd', 'a', 'd']






d|----------5/6-6-6-5/6-6-6-6-6-6------------------------------------|

a|-------6--5/6-6-6-5/6-6-6-6-6-6-9-8-6-6----------------------------|

f#|---5h6--------------------------------5h6--------------------------|

d|-6----------------------------------------6-4--6-6-6-6-6-6-6-6-----|

a|-----------------------------------------------6-6-6-6-6-6-6-6-----|

d|-------------------------------------------------------------------|


