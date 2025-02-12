# Mozart Deconstructions: Musical Experiments wit AI

[![CC BY 4.0][cc-by-nc-nd-image]][cc-by-nc-nd] <!--[![CC BY-NC-ND 4.0][cc-by-nc-nd-shield]][cc-by-nc-nd]-->

[cc-by-nc-nd]: https://creativecommons.org/licenses/by-nc-nd/4.0/
[cc-by-nc-nd-image]: https://licensebuttons.net/l/by-nc-nd/4.0/88x31.png
[cc-by-nc-nd-shield]: https://img.shields.io/badge/License-CC%20BYNCND%204.0-lightgrey.svg
[aggreement]: https://github.com/axelberndt/Mozart-Deconstructions/tree/master/LICENSE

Programmer, Arranger, Composer: [Axel Berndt](https://github.com/axelberndt)<br>
Tonmeister: Holger Schlegel

### Ensemble Ixora
1st violin: Eun Sun Kim<br>
2nd violin: Hyunho Gi<br>
1st viola: Zhuochen Sun<br>
2nd viola: Juyoung Kim<br>
Cello: Maciej Wlodarski

### The Music
Create concert music using AI (artificial intelligence) that is at least 10 minutes long and relates to the [String Quintet in C major KV 515](https://dme.mozarteum.at/DME/nma/nma_cont.php?vsep=169&p1=27) by Wolfgang Amadeus Mozart! This was the task Axel Berndt was faced with in November 2022. The commissioner was the [Stuttgarter Kammerorchester](https://stuttgarter-kammerorchester.com) (Stuttgart Chamber Orchestra, SKO). The date set for the concert performance was May 10, 2023.

After some experimenting with the then current pretrained AI models, it was clear that there was no convincing one-click solution. Each technology has its own approach to musical (combinatorial) creativity and produces material that works better in one type of musical conception than in another. This is where the human composer comes into play, selecting the technology and integrating its outputs into a coherent musical form. 

It was also clear from the outset that no style copies would be generated. No AI has yet been able to completely convince in this discipline. Criticism and ridicule were guaranteed. Instead of letting AI compose like a human, it should compose like a human would not, thus becoming a creative tool that enriches human composing rather than imitating it. With this principle in mind, the focus of work shifted away from technologies based on Deep Learning and towards generative technologies that enable more diverse and differentiated interaction. The control parameters of these technologies thus themselves constitute a compositional domain. Markov models became a central technology in the pieces created. 

In reference to the naming of the first computer-generated music, the *Illiac Suite* by Lejaren Hiller and Leonard Isaacson, the pieces here are also entitled [Experiments](/Experiments/). Each experiment employs a different approach.
1. **Experiment Canon Crossover** begins with W. A. Mozart's instrumental canon *KV 562c Anh. Nr. 191* (smooth, melodious, long notes) and ends with J. S. Bach's instrumental canon *BWV 1073* (rhythmic, fast, short notes), two very contrasting canons. AI was used to generate a transitioning canon between the two. A Markov model was trained with both canon melodies to generate possible canon beginnings. A combination of models from the [*tonica fugata*](https://www.capella-software.com/de/index.cfm/download/tonica-fugata/download-tonica-fugata/) suite by Capella Software was then used to set out the full canon for four voices.
2. **Experiment Polyphonic Skeleton** utilizes a Markov model trained with polyphonic slices taken from the two string quintets [KV 515](https://dme.mozarteum.at/DME/nma/nma_cont.php?vsep=169&p1=27) and [KV 516](https://dme.mozarteum.at/DME/nma/nma_cont.php?vsep=169&p1=63). The length of the slices varies throughout the piece. The contents of the slices, i.e. the musical details, are taken away so that only the notes at the beginning and end are played and lengthened to fill up their whole slice. As the piece progresses, the slices become shorter. More and more details of Mozart's original emerge until the piece finally ends in a quotation. This way the piece provides a musical insight into the inner workings of the technology.
3. **Experiment Deconstruction - Recombination - Order** utilizes the same Markov model as the previous piece, but this time retains the musical details and recombines them in creative ways. The compositional domain is spanned by several algorithmic parameters. The *order* of the Markov model is modulated, starting with order 0, i.e. complete randomness. The *length* of the polyphonic slices is varied, giving voice leadings more or less freedom to dissolve harmonic integrity. In the later sections of the piece the *transition probabilities* of the model get inverted emphasizing less frequent musical progressions from the two Mozart quintets.

Part of the concert program and hence of this music production is also the performance of the full [String Quintet in C major KV 515](/KV_515/).

### Recording Sessions
The recordings presented here were made during a concert performance on November 28, 2024. Additional recordings were made on November 30, 2024. The performance venue was audience chamber of the Residenzmuseum Schloß Neuhaus in Paderborn, Germany.

### Funding Notice
This music production was kindly funded by [Kreativ Campus Detmold e.V.](https://kreativ-campus-detmold.de/). The performance venue, audience chamber of the Residenzmuseum Schloß Neuhaus, Paderborn, was provided by the city of [Paderborn](https://www.paderborn.de).

This work is further supported by [KreativInstitut.OWL](https://kreativ.institute): a consortium consisting of OWL University of Applied Sciences and Arts, Detmold University of Music, and Paderborn University, funded by the Ministry of Economic Affairs, Industry, Climate Action and Energy of the State of North Rhine-Westphalia, Germany.
