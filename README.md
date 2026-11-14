
# 🧠 SlangTrack Word Sense Disambiguation (ST-WSD) Dataset

> A diachronic dataset for **Word Sense Disambiguation** in both slang and standard English across multiple decades.

---

## 📚 Overview

The **SlangTrack Word Sense Disambiguation (ST-WSD) Dataset** is a curated **Word Sense Disambiguation (WSD)** subset of the larger **Bi-Directional Lexical Semantic Change (BD-LSC)** dataset.

It focuses on **10 carefully selected words**, each manually annotated with **standard** and **slang senses** across three key time periods:

- **T1:** 1980–1999 (pre-Internet era)
- **T2:** 2000–2009 (early Internet era)
- **T3:** 2010–2020 (social media era)

It captures both the **emergence of new senses** and the **persistence of old ones**, making it a benchmark for evaluating **semantic change in slang**.

---

## 🔑 Key Features

- **10 Target Words** annotated for all occurrences in their contexts.
- **Three Timelines:** T1, T2, T3, covering 40 years of language evolution.
- **12,712 total instances** across the dataset.
- **Fine-grained sense annotation** with slang and standard senses.
- **High annotation quality:** Inter-annotator agreement ranging from 76% to 89%.

---

## 🌍 Significance of the Dataset

- A temporal WSD dataset that explicitly includes slang senses.
- Enables benchmarking of **supervised, unsupervised, and LLM-based WSD models**.
- Supports research in **lexical semantic change**, **slang evolution**, and **sociolinguistics**.
- Provides empirical evidence of **language change influenced by digital culture**.

---

## 🎯 Target Word Selection

Words were selected based on:

- Evidence of both **slang and standard senses**.
- Coverage across **different semantic domains** (food, drugs, people, feelings, etc.).
- Rich usage in corpora over multiple decades.

**Target words:** *BMW, Brownie, Chronic, Climber, Cucumber, Eat, Germ, Mammy, Rodent, Salty*

---

## 📂 Data Sources and Collection

- **COHA (Corpus of Historical American English)** – for T1 and T2.
- **Twitter corpus (2010–2020)** – for T3.
- **Sense inventories** were built from:
  - Oxford English Dictionary (standard senses).
  - Urban Dictionary, Green's Dictionary of Slang, and Online Slang Dictionary (slang senses).

---

## 📊 Data Statistics

**Instance counts across timelines (Reported Total = 12,712):**

| Word | T1 | T2 | T3 | TOTAL |
|---|---:|---:|---:|---:|
| BMW | 91 | 141 | 865 | 1097 |
| Brownie | 73 | 72 | 819 | 964 |
| Chronic | 482 | 380 | 823 | 1685 |
| Climber | 75 | 50 | 517 | 642 |
| Cucumber | 74 | 85 | 892 | 1051 |
| Eat | 975 | 995 | 1000 | 2970 |
| Germ | 112 | 70 | 650 | 832 |
| Mammy | 172 | 22 | 876 | 1070 |
| Rodent | 101 | 67 | 905 | 1073 |
| Salty | 214 | 165 | 887 | 1266 |
| **TOTAL** | **2369** | **2047** | **8234** | **12712** |

---

## 📝 Sample Texts by Word and Timeline

The texts below are a small number of **illustrative excerpts only**, shown to convey target-word usage across the three periods; they are **not** the released dataset. The dataset distributes the T1/T2 (CCOHA) contexts in lemmatised form and the T3 (Twitter) instances as **Tweet IDs only**. In these examples punctuation has been removed and word order preserved. T1 and T2 are shown lemmatised (matching the released form); the T3 tweets are shown as short readable excerpts with usernames removed. Some excerpts contain slang that is offensive or derogatory; they are retained because such usage is itself an object of study in this dataset.

| Word | T1 (CCOHA, lemmatised) | T2 (CCOHA, lemmatised) | T3 (Twitter, illustrative) |
|---|---|---|---|
| **BMW** | fresh meat I be not crazy there s a mermaid in there Shut up what mermaid I be a scientist where s the goddamn car the gray BMW shout Indistinct hey I know that guy I see he on Cape Cod he be crazy then there she be there she be Don t let he shoot that be that a gun hold it no get that thing out of his hand Grab that hose grab he get he right Behold the mermaid Crowd gasp let I out of here who be you | take Jesus into your heart now because you never know even if you don t have a condition you might have a situation he ask if I be a killer too I tell he no he press have I ever go to war Korea Vietnam ever do a hit and run with the BMW Black Man Working ever tell the wifey to get an abortion or slip a piece of chicken on the side three hundred dollar with the word take care of it he say I have that look that ice in my eye I tell he he be wrong be I now he say Mr Armstrong let s see who we re talk to be you married | My BMW played lil dude too BMW Black Mexican White pimpin lil niggas |
| **Brownie** | we eat I be starvation central see ya bye Carrie how do you know Nina Katz how do you know her everybody know she she book Saturday Night Live she s also the face girl great that face be about to be all over Vogue and SNL Nina Katz love to talk 15 30 I m go to need a weed brownie for this the next day Samantha do some personal shopping very personal May I help you yes I d like to return this vibrator after I come down from that brownie | watch tv make a cake with my new Perfect Brownie pan lol and every time I hear brownie I think of the backdoor not dessert go to get the kid to bed and cozy up to my baby tonight love my life one cheeky think at a time | I laughed to myself as I typed the message telling him I was about to grab a brownie and test this crap out |
| **Chronic** | the frustration in the community stem not from hasidic Jews but from the chronic lack of service and program impact everyone dress in a Nehru suit and sporting ponytailed dreadlock he point out that their anger be be stoke by hatemonger like the Rev Al Sharpton Green always navigate the scene have help set up the meeting to address these deep seat chronic tension | the post 1960 growth of a small but costly underclass have often be attribute to chronic structural problem such as systemic discrimination vanish industrial job and the exodus of the black middle class other argue that it stem from cultural shift and the influence of change ethnic dynamic the Wilson team s analysis examine these chronic issue in depth seek to untangle the interplay between economic structure and cultural transformation that perpetuate cycle of hardship | Why did the duvet cover fall into the camera case Because he was a chronic guy Follow me I m seriously random |
| **Climber** | care to make any wager it may not be that easy they get through that pass they can pick up reinforcement at the mine we ll fly there first and scatter those worker for good Tell Scheckter we ll back they up at the mine Hannibal you two all right Amy Yeah Amy Murdock be you okay I think I hear some buzzing what else do you expect from the human fly the climber of wall source of annoyance ruiner of picnic sticky of foot Hannibal B a face | June 2001 cover story for Boys Life I ve shoot from horseback in Peru s Cordillera Blanca set up tripod in Tuolumne Meadows at Yosemite dangle over California s North Coast and even work above the action like when I photograph a climber in Indian Creek Utah but in this rewrite the climber isn t on sandstone it s a cat burglar scale hotel wall slip through window and my lens catch he mid heist turning adventure photography into a stakeout of shadow and crime | Taking a break from studying Wheel to work out Reading about categories on the tread climber thank God for the paperwork holder on the machine |
| **Cucumber** | now more than ever absolutely I could show you a picture from three year ago thank you thank you you d kill yourself thank you thank you I m tell you look I know thing could be bad I could be Tommy what what s wrong with Tommy I m go to try that cucumber water nothing oh just that you know at least I don t have an infant can you imagine date and breastfeed Ugh Ugh well Tommy s not breastfeed what be you | this sweet face what have we get in here a saucer over here would you like some old ketchup to eat would you like a lime no okay how about a cucumber not the salad kind but straight up penis talk slip in with the same ease as offer a banana do you know two week old oyster want some of those I use to have a puddy like you but my wife sneeze so I can t have one anymore here you want some rope it s top of the line I don t need rope what other kind of light do you have Ligh | What helps the best is cucumber with fresh lemon juice and a bit of salt and after that a warm cup of tea with honey |
| **Eat** | pull your leg Mister who be that oh just somebody what d they want nothing maybe daddy s get a girlfriend you well watch it mom yeah maybe I well well do you Dad what have a girlfriend Nah nobody serious but you know what People out here just wanna eat you alive they see what you ve get and they want a piece of it | just think of it as an act lesson Cool right Tomorrow night at eleven o clock right it ll work right Graveyard Gloria right right cool right right you could be the big fairy of they all eat my short hey it s just a phrase Don t let it eat at you you know how people like to talk but I m not one to let someone s word eat I alive let they say what they want but don t let it eat away your confidence and honestly no one can eat up your pride unless you let they | Esmi barked at the group We can t stop There are no restaurants out here and you ll just have to eat that fact for now The bald man groaned Fine but my stomach is ready to eat itself |
| **Germ** | the fat be mainly compose of essential fatty acid a membranous tissue call the scutellum separate the germ and the endosperm it be exceedingly rich in the vitamin thiamine and contain about 60 percent of all the thiamine present in the grain the endosperm be mainly starch and be intend as a reserve of food for the germ it be by far the large component and make up about 80 to 90 percent of the wheat grain the starch granule be embed in a matrix of protein and the periphery of the endosperm | I read Babies from Sperm to Germ or something like that and I see Angelique blow her birthday candle Shut up shut up Agnes s back plate click with the tremor of her tail smack the floor not that I want to distract you say Doc but you come up here to ask Preston something didn t you yes right yes Axel step over to Preston can I have five thousand dollar Agnes gasp what five thousand dollar that s all and | I ve been sleeping nearly all day Except for that hour that I went to work So sick Go away you germ |
| **Mammy** | their clothe come from a fashionable modiste but I always say oh this be a little something Mammy run up for I so when I walk into the great hall at Winston I Mammy s there wasn t any mammy to it the word burst from Dessa she know even as she say it what the white woman mean Mammy be a servant a slave Dorcas who have nurse the white woman just as Carrie have nurse Young Mistress s baby before it die but goad by the white woman s open mouth | the eye light with laughter yet for a moment Rufel sense some hesitation feel the dark eye question May I be it all right Disturbed by the servant s obvious assurance rufel be relieve by that hint of uncertainty it make the woman seem more natural and herself a bit more comfortable Rufel have be lonely have feel herself ugly and awkward Mammy talk with she admire her hair and rather full lipped smile and show she how to walk erectly she praise where Mrs Car | The amount of clothes I just folded made me feel like I m a mammy back in the deep South b never againnn |
| **Rodent** | which be the disguise of the man who will love you that would be a rodent then fail that Charlene continue ignore Trudi I would like a cat as big as a man a cat as big as a man Trudi frown try to picture a man sized cat yes imagine if man have fur the waitress ask they if they want more of the weak green tea for myself the waitress say uninvited I prefer dog Charlene and Trudi swoon with delight at the idea of dog instead | hello Mrs Houston it s Keefer yes the reason I m call be a little strange Mrs Houston but there s this old book I have back in Germany in the 1600 it tell about a thing call the Das Teufel Nagetier Das what Claire who be it Das Teufel Nagetier I be go to tell you about it today but Mr Houston didn t seem much in the mood for listen who be that it s late well what be this Das Teufel whatever it be it translate into the devil rodent | My sister smells like a rodent And I m ten feet away from her |
| **Salty** | the cotton of his colorful sport shirt still seem load near its tensile strength where it stretch over his middle Franks roll the stump of a dead cigar from one corner of his mouth to the other and wink at Jake with his shoulder throw back and his genial air of self assurance and command Franks remind Jake of the salty chief petty officer he have grow to respect and admire when he be a junior officer Franks certainly be no modern naval officer or chief in mufti not with that gut | he tell she what his mother have arrange the job in Nethermede s kitchen the room in the sophomore dormitory and that be what she think of of he kiss she against the refrigerator and his salty knowingness slide onto her tongue and so against every other obvious next step Cody s family have present to she the job as an assistant cook at Nethermede Academy seemingly ill suit though it be pleased she of course she suspect as little as he | I just can t wait for 9 o clock that s when MY unranked terrible salty team plays I couldn t care less about the UL game bbn gocats |
---

## 🔖 License and Source-Data Restrictions

The ST-WSD dataset combines original research annotations with material derived from third-party corpora and dictionaries. The original source materials remain subject to their respective providers' terms; preprocessing does not itself establish redistribution permission.

- **Historical contexts (T1 and T2):** Selected CCOHA-derived examples are shown in preprocessed form, with word order preserved. 
- **Twitter contexts (T3):** The released dataset uses Tweet IDs for reconstruction, subject to the X/Twitter platform terms. The illustrative tweet-derived examples displayed above are excerpts, not a complete Twitter corpus; any public display of tweet text must also comply with the relevant terms.
- **Dictionary sources:** Third-party dictionary entries and definitions retain their original rights and licensing conditions.
- **Synthetic training data:** See the separate CC BY 4.0 licensing notice for the synthetic training file, if applicable to this repository and formally adopted by the rights holder.


---

## 📥 Download & Citation

To access the dataset, visit the [SlangTrack Repository](https://github.com/SlangTrack/SlangTrack-ST-Dataset-Word-Sense-Disambiguation-WSD-/blob/main/SlangTrack-ST-Dataset-Word-Sense-Disambiguation-WSD.csv).
