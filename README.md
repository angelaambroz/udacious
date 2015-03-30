Tanzania's new constitution, 2015: A data visualization
=======

### Summary

23 March 2015 - currently in progress. A data visualization, written in `d3.js` of how Tanzanians are likely to vote in the upcoming referendum on the new constitution (_katiba_). This visualization uses data collected from Africa's first nationally-representative mobile phone survey, [_Sauti za Wananchi_](http://twaweza.org/go/sauti-za-wananchi-english) ("Voice of the People"). This also will serve as the final project on the Udacity's [Data Visualization and D3.js](https://www.udacity.com/course/ud507) course.


### Design

The first design idea: I'll use a force layout of each individual observation (anonymized), with voters moving to the left ("NAY") or right ("YEA") on the hypothetical referendum question. 

_Chart type_: [Force layout.](https://github.com/mbostock/d3/wiki/Force-Layout)

_Visual encodings_:

Variable | Visual encoding
--- | ---
Observation | Circle, fixed radius
Vote | `x` location
Draft preference | ~~`y` location~~ `x` location
Rural/Urban | ~~Stroke color~~ Fill color
Gender| Fill color
Party | Fill color
Age | Fill color



### Feedback

First reviewer:
> 1. The labels for which draft people would prefer are not correct; the top should be the second draft by the CRC and the final draft by the Constitution Assembly
> 2. I think you should consider dropping urban in the 3 keys. It is easier for the readers to make a comparison between rural and urban or male and female.
> 3. On the tab that provides data on whether people will vote for or vote against the constitution, I think we should all the responses in the final visualization. The group that is sent away helps in telling the story and if anyone would like to change the outcome they are the determinants of whether the constitution referendum will go through or not. 
> 4. The results on whether people will vote for or vote against the constitution are in a different language. That said, have you considered have the visualization in Swahili. You will get a larger audience because, Tanzanians are more excited about Kiswahili.
> 5. Once it goes live on a different platform from the Twaweza website, we should provide a link to the Twaweza website and the brief.  

Second reviewer:
> I would be interested too in seeing the more substantive questions visualized, eg on what people liked in the previous draft.
> And a more sensitive issue: what the political affiliation is of the yea/nae sayers ...

Third reviewer:
> Include big disclaimer re: no Zanzibar data.
> Put titles/buttons on top.
> Make constitution question horizontal, instead of vertical (text boxes always on the bottom).
> Add age visual encoding (<35 and >=35?).
> Add unknowns bubble.


### Resources
* Resource: [Udacity - Data visualization and D3.js](https://www.udacity.com/course/ud507)
* Resource: [d3.js API - Force layout](https://github.com/mbostock/d3/wiki/Force-Layout)
* Q&A: [StackOverflow - Force layout within a shape](https://stackoverflow.com/questions/15100060/d3-js-force-directed-layout-constrained-by-a-shape?rq=1)
* Q&A: [D3.js GitHub - Speeding up force layouts](https://github.com/mbostock/d3/issues/1519)
* Q&A: [StackOverflow - Speeding up a force layout with many nodes](https://stackoverflow.com/questions/18311818/speed-up-d3-force-layout-with-many-nodes-and-links)
* Q&A: [StackOverflow - Controlling the initial animation](https://stackoverflow.com/questions/17166016/d3-js-controlling-initial-animation-in-force-layout)
* Tutorial: [AirPair - Understanding the force layout](https://www.airpair.com/javascript/posts/d3-force-layout-internals)

### TODO

1. ~~Get `git` set up, etc.~~
2. ~~Template from previous force layout dataviz.~~
3. Add image of design iteration.
4. Prep data for ~~2015~~, 2014, 2013 (all SZW), and 2012 (Afrobarometer).
5. ~~Incorporate Udacity tips re: accessor and visualization functions (get better at understanding callbacks).~~
6. ~~Add draft-preference buttons.~~
7. ~~Style everything.~~
8. Fluidify the force layout - right now it lags a lot. 
9. ~~The problem of sample weights...!~~
10. ~~Add reset button.~~
11. ~~Add tons of explanatory captions.~~
12. ~~Add fancy Sam Pepys YEA/NAY tooltips.~~
13. Add urban/rural, gender highlights + buttons.
14. ~~Are my hard-coded labels right!?~~
15. ~~`d3.sum` and average the percent of people that are in each bucket.~~ (Hard-coding for now... so wrong..?!)
16. ~~Non-italic `Essays 1743` font on the YEA/NAY labels.~~
17. ~~Legend, with circles.~~
18. Add Easter egg: randomly allocate random greetings in Swahili to some of the survey dots ("Hujambo! Habari za siku!", etc.). Maybe `setInterval()` to make them pop up every 5 seconds or so...
19. Correct draft labels.
20. Change rural/urban from stroke to fill color.
21. Add age (<=35, >35), fill color.
22. Political party, fill color.
23. Include big disclaimer re: no Zanzibar data.
24. Put titles/buttons on top.
25. Make constitution question horizontal, instead of vertical (text boxes always on the bottom).
26. Add unknowns bubble.
27. Swahili translation!?!