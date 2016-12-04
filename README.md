# brain-worm

## Who

The team is formed from people coming from significatly different areas of arts, engineering, and psychology:

* **Krystof Kaplan** is an artist and author of kinetic sculpture designed for BCI, neuro-feedback, and for exploring new ways of movement.
* **Vlastimil Koudelka** is an engineer and researcher in neuro-imaging, machine learning, and optimization
* **Dmitri Berzon** is a Concept developer / Light designer, Programmer, Conceptual artist specializing in interactive installations
* **Cyril Kaplan** is a psychologist specializing on EEG correlates of mental and emotional activity, music producer, openVibe and PD programmer. 

## What

![alt text](https://github.com/HackTheBrain/brain-worm/blob/master/worm_pics/P1070909.JPG "A kinetic worm")

A kinetic worm needs your attention! Once it realizes you are concentrating it will use pneumatic mussels and move. On the other hand, if you are not focused enought the worm stops moving and starts breathe frequently. The level of your attention is measured via electrical brain waves (EEG). 

## Why

**Author**
A couple years ago I started thinking about creation of aoy for my doughter. I was interested in making a toy addressing rather abstract form of the world. This realy changed my approach to the sculpturing. The brain worm exhibits slow movements whitch look like a micro-oragnism or a whale on the other side.

**engineer**
Working on this project, its...

jako sochar a muzikant jsem v roce 2009 pracoval na objektech, ktere by propojovaly media jako jsou divadlo, hudba, socha a uzite umeni. tyto tendence vznikly na zaklade skusenosti, ktere jsem ziskal z tvorby hudby k divadelnim predstaveni, socharske prace a jakozto cerstvi otec z uvah o moznych podobach hracky ktera by nezobrayovala vice ci mene stilizovanou skutecnost ale spise abstraktni formy. tyto snahy vyustily  ke vzniku 40ti centimetrovehu dreveneho obektu/loutky slozeneho ze sumy ruzne velkych clanku, ktera pri pohybu vydavala rozmanite zvuky.Po vytvoreni techto obektu ma tvorba nabrala jiny smer a monumentalnejsi rozmery. az v poslednim roce jsem se k tomuto konceptu vratil. brain vorm svym pomalim pohybem evokuje jakousi smes plejtvaka a mikroorganizmu jeho anatomie spis odpovida jednoduchym 


## How

The kinetic worm can move and breathe using its pneumatic mussels made of 24 tires. Extra eight tires are constantly inflated and form a sculpture skeleton. 

Solenoid valves are connected to a computer interface such that a synchronous patterns of movements can be created within [VVVV](https://vvvv.org/) environtment. The IDE can alse recieve UDP messages from realtime EEG analysis tools. OpenVibe and PureData are used and tested in our project.

OpenVibe is connected to NeuroSky Mindwave mobile device and further alyzes the eeg stream to obtain a robust eeg marker of participants concentration. Relative frontal alpha power was chosen to measure a level of concentration. 

Once the participant acceeds same treshold of the parameter VVVV drives the worm in a sequence of movements.


## Ethical considerations
*please share the insights about ethical matters surrounding your work. Some "ethical cards" have been distributed to support the discussion about this subject.*
