### Research 

The purpose of this repository is to guide our research into developing good content for the project. This part of the project welcomes casual and professional researchers to make input. One does not need to have any knowledge of computer programming to make a contribution. 

The research repository consists of a single file named 'research.txt'. This will be the base file for contribution input and presentation to the community. Producers for content episodes will also use this file as a guide to develop the intellectual direction of a production. 

Given how vast research is, the technique for deducing and stating specific areas of our interest will use the [BNF](https://en.wikipedia.org/wiki/Backus%E2%80%93Naur_form) convention. Whereas BNF maybe new to some, we want to state the way it works is understandable. Research planning will be done for 3 seasons (covering episodes) at a time.

Common Initials in the research documentation are as follows; 
- TA  - Thematic Area (Relating to a broad topic of research)
- PRA - Particular Research Area (Relating to subtopic under a thematic area)
- PD  - Possible Destination (Relating to required physical travel)
- PI  - Person of Interest (Relating to interating with a particulr professional or personality)

The Backus–Naur Form (BNF) convention to be used in the research documentation are as follows; 
- <> symbol will contain a variable or constant (short) information text. 
- ::= symbol means what is on the left must be replaced with what is on the right.
- | symbol means seperate alternatives

Example. 

< full-name > ::= < first-name > < middle-name > < last-name >

< middle-name > ::= < day-born-name > < ethnic-name > | < day-born-name > | <ethnic-name >

This will translate as: 

Full name consists of first name followed by middle name and then last name. 

Middle name consist of day name followed by an ethnic name or only day name or only ethnic name. 

In the midst of varied intellectual opinions, we encourage the following as much as possible
1. The goal of the research isn't perfection, it will continuously improve its margin of error, be encouraged to make a contribution.
2. Contributors must tolerate viewpoints and communicate clearly, briefly and share resources as much as possible when making a pull request. 
3. Knowledge development has a lot of dependencies involved and we encourage everyone to have some patience towards a 'quick' understanding. We assume all audience have a beginner understanding.
