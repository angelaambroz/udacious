Tanzania's new constitution, 2015: A data visualization
=======

### Summary

23 March 2015. A data visualization, written in `d3.js` of how Tanzanians are likely to vote in the upcoming referendum on the new constitution (_katiba_). This visualization uses data collected from Africa's first nationally-representative mobile phone survey, _Sauti za Wananchi_ ("Voice of the People"). This also will serve as the final project on the Udacity's [Data Visualization and D3.js](https://www.udacity.com/course/ud507) course.


### Design

The first design idea: I'll use a force layout of each individual observation (anonymized), with voters moving to the left ("NAY") or right ("YEA") on the hypothetical referendum question. 

_Chart type_: [Force layout](https://github.com/mbostock/d3/wiki/Force-Layout)

_Visual encodings_: (To complete)

Variable | Visual encoding
--- | ---
Observation | Circle, fixed radius
Vote | `x` location
Rural/Urban | Stroke color
Gender| Fill color



### Feedback

Coming soon.


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
6. Add draft-preference buttons.
7. Style everything.
8. Fluidify the force layout - right now it lags a lot. 

