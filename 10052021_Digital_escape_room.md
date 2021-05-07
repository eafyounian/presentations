layout: true

<div id="footer-content">
    <img src="28092020_digipilot_resources/TUNI_logo.png" style="width: 30px; height: 30px"/>
</div>

---
.centre[

# &#x1F3B2; Digital Escape Room &#x1F3B2;
### a ___gamification___ approach to promote
### interindividual ___interaction___ in teaching ___bioinformatics___ 
#### Ebrahim Afyounian  

#### Tampere - 10-05-2021

## &#x1F31E;&#x1F33A;&#x1F31E;

]

---

## Premises

- Bioinformatics (or computation biology) is an interdisciplinary field
  - biology, statistics, computer science, mathematics, ...
- Each students has a unique life experience and knowledge (schemata)
  - contributing to unique strengths and affinities to each of these fields
- Interindividual __interactions__ potentially ___externalize___ and ___share___ such schemata
- e.g. imagine you and your &#x1F47D; friend are having a chat while cooking &#x1F372; together
      - &#x1F464; __Why__ did you put the brine from the _space tofu_ jar in the pot instead of draining it? 
      - &#x1F47D; ___Because___ salt is rare in our planet and we have learned not to waste it? 
      - &#x1F464; What about high blood pressure then?
      - &#x1F47D; ___I see!___  Well, we do not suffer from it ___because___...

.smaller-font[
- __schema (pl. schemata)__: a mental codification of experience that includes a particular organized way of perceiving cognitively and responding to a complex situation or set of stimuli [Merriam-Webster](https://www.merriam-webster.com/dictionary/schema)
]

---

## What does _education research_ has to say?

- Students __learn more__ when they are __more engaged__ with the learning material
- e.g. the __ICAP framework__ ([Chi and Wylie, 2014](https://doi.org/10.1080/00461520.2014.965823)) predicts the following relation regarding the __amount of learning__ at different __modes of engagement__ 
.center[### interactive \> constructive \> active \> passive]
.smaller-font[
- __Passive__: e.g. listening to a lecture
- __Active__: e.g. taking notes during the lecture (without paraphrasing)
- __Constructive__: e.g. drawing mind maps during the lecture and relating new material with earlier knowledge / updating the ___schema[ta]___
- __interactive__: e.g. asking questions from the teacher or peers, discussing and debating with peers about the material]  
- __Interactive mode__ of learning promotes the __co-creation__ of new knowledge, perspectives, and interpretations ([Chi and Wylie, 2014](https://doi.org/10.1080/00461520.2014.965823)).

---

## How to promote interaction and engagement  

- There are several approaches/techniques to promote interaction, for example:
  - Seminars 
  - Group discussions during a contact session
  - [Jigsaw technique](https://en.wikipedia.org/wiki/Jigsaw_%28teaching_technique%29) during a contact session
  - team-based learning
  - Group work during an exercise session
  - __Gamified__ group work *
<br><br>
- \* ___Gamification___  refers to the introduction of game design building blocks to a context other than a game such as teaching ([Rutledge et al., 2018](https://doi.org/10.1097/ACM.0000000000002183))

---

## Why Gamification?
- [Johan Huizinga](https://en.wikipedia.org/wiki/Johan_Huizinga), a cultural historian, in his book [Homo Ludens (1938)](https://en.wikipedia.org/wiki/Homo_Ludens), argues that play[ing games] predates societies and their culture
- There are a few games known to date back to around __~4600 years__ ago
  - [The Game of Ur](https://en.wikipedia.org/wiki/Royal_Game_of_Ur) played in ancient Mesopotamia by people with __different social status__
  - [Senet](https://en.wikipedia.org/wiki/Senet) played in ancient Egypt
      - This game may have been possibly used __to teach__ people about the _journey to the afterlife_ ([Clarke et al., 2017](http://dx.doi.org/10.17083/ijsg.v4i3.180))
- When we play a particular game, we enter its ___magic circle___, a realm with its ___own rules___ and ___reality___, protected from the rules and realities of our own world. ([Huizinga, 1938](https://en.wikipedia.org/wiki/Homo_Ludens), [Linser et al., 2008](http://www.simplay.net/papers/MagicCircle-Linser-Lindstad-Vold08.pdf))
  - Perhaps, this is why playing games are appealing to many! One can, temporarily, forget about the actual reality, choose a new character, and do whatever is allowed in the game's _magic circle_, without having to worry about the ramifications of ones actions permeating from the _magic circle_ to the actual world! *
  - ~1/3 of world population (~2.7x10<sup>9</sup>) are active gamers [[source](https://newzoo.com/products/reports/global-games-market-report/)]
<br><br><br><br>
.smaller-font[\* Of course, the _magic circle_ is not 100% sealed and protected and it may leak both ways ([Castronova, 2005](https://press.uchicago.edu/ucp/books/book/chicago/S/bo3620704.html)])

---

## Digital escape room
- An ___escape room___ is a room in which you are "locked up" with a group of peers with whom you need to interact and collaborate to discover clues and solve puzzles essential for escaping the room before you run out of time (for other definitions see: [Nicholson, 2015](https://scottnicholson.com/pubs/erfacwhite.pdf) and [Kinio et al., 2019](https://doi.org/10.1016/j.jsurg.2018.06.030))
- A ___digital escape room___ is an escape room implemented digitally, can be accessed virtually and remotely, and does not rely on a physical room
  - Handy e.g. when there are regulations on the maximum number of people allowed in a place and on their distance from one another as the _magic circle_ of the digital escape room will be protecting the participants!    


---

## Let's play! &#x1F0CF;

- I have made the following digital escape room to demonstrate and assess the feasibility of using digital escape rooms in teaching bioinformatics 
  - It is a rather small one, containing only a couple of random puzzles
- We will use the Zoom breakout rooms to form smaller groups
  - Let's form groups containing both biologists and computational members 
  - Everything you need to know to play is explained in the game if needed
  - Let's allocate 25 minutes for completing the game (but it can be done in less time, so __relax and enjoy the experience__!)  
- Here is the link to the game: [Breathless at CEH: A curious case of Christmas party](https://eafyounian.github.io/Breathless_at_CEH/)
- Let's gather in the main room, once we are done, to discuss our experience and collect feedback
- Whenever you have time, please go and fill in the following anonymous survey form (it takes ~10 minutes). 
  - [Survey about your impression and experience of the digital escape room](https://forms.gle/HpFiThYjiUioBiw28)
---

## Implementation

- The game was implemented using [Twine](https://twinery.org/), an open-source tool for telling interactive, nonlinear stories
  - Essentially, a game is composed of several pages (called __passages__) which are connected to each other via __links__
  - This particular game had 30 passages and 71 links
- There are a few ___story formats___ that we can choose from in Twine, affecting how the stroy is displayed  
  - For this game, I used ___Harlowe___, the default format, which does not require knowing scripting/programming
- There are several alternatives (e.g. [ink](https://www.inklestudios.com/ink/)) but may require scripting knowledge
- The output is an HTML file that can be easily uploaded to the Web
  - I am using [GitHub Pages](https://eafyounian.github.io/Breathless_at_CEH/) to host the game
- Contact me for more details about the implementation
<br><br><br><br>
.smaller-font[&#x1F4A1; ___Trivia___ : Twine was used in developing the interactive film [Black Mirror: Bandersnatch](https://en.wikipedia.org/wiki/Black_Mirror:_Bandersnatch)]

---

.centre[

# Thank you for your attention!

# &#x1F49B; &#x1F33A; &#x1F49A;

## &#x2753; &#x270B; **Questions!**


]
