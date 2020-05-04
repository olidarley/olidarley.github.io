**Data Visualisation** | **Visual Communication** | **Generative Art**

I'm Oli. I'm a data visualisation designer, programmer and musician. I also make generative art. This page is a repository for my data sketches, prototypes, analysis and general musings.

*Most of my work is coded in R or p5.js, though I also occasionally use Tableau, Flourish and Raw.*

----------

**Blog entry: 20/04/2020**  
*Illustrative design and data-driven complexity in COVID-19 graphics*  
Some graphics are designed to communicate an idea. They don't have data behind them. The 'flatten the curve' design we're now so familiar with is an example, illustrative in nature, from the stark difference in the curves to the positioning of the horizontal line indicating hospital capacity. In terms of visual communication, it makes it's point clearly, more clearly in fact than if it used statistical models as the message isn't 'restricted' by real data or forecasts. The lines are neat, smooth, the message simple and effective: 'Act, or else'. 

![flattenTheCurve](/flattenTheCurve.png)

The Washington Post scrollable, animated graphic is an interesting case as it is illustrative in design, but uses a simplified model (built on assumptions about the R0, demographics and population behaviour) to simulate disease spread. 

https://www.washingtonpost.com/graphics/2020/health/coronavirus-how-epidemics-spread-and-end/

It visualises infection using a circle packing algorithm, reminiscent of the classic measles vaccination visualisation from the Guardian graphics team in 2015 (https://www.theguardian.com/society/ng-interactive/2015/feb/05/-sp-watch-how-measles-outbreak-spreads-when-kids-get-vaccinated). As a visualization paradigm, circle-packing may still be less familiar to the general public than a bar or line chart but it is a unit-based graphic so it easily interpretable, communicating infection through repetition and colour. 

Sometimes, data visualisations of complex subjects cannot avoid being challenging themselves. 'Simplicity' should not be seen a goal when visualising data. Alberto Cairo has frequently written/spoken of the difference between 'simplicity' and 'clarity' as well as differentiating between 'compexity' vs 'complicatedness' (http://digicult.it/news/the-functional-art-of-alberto-cairo-shaping-data-to-generate-opinions/). It is helpful, even in the world of business where patience can be short, to see visualising data in terms of clarity of design rather than simplicity.

The visual communication of complex, multi-faceted data, can require a degree of data literacy, graphical literacy and patience. There are occasions where it is appropriate to encourage and even demand this patience. The pay-offs can be worth it. For example the log scales used in many representations of trends in COVID-19 cases or deaths (including those by the excellent graphics team at the Financial Times) have become normalised over the last couple of months. Depending on the intended message, using a log scale makes sense when visualising exponential disease spread but the question for the designer must always be, in terms of visual communication, what is the trade-off between visual complexity and understanding? 

There's no straightforward answer of course. Often, the simplest designs can be the most powerful. On the other hand, complexity should not necessarily always be avoided in favour of simplicity. Some visualisations are ‘complex’ and all the better for it. Over-simplification can be misleading. Overlooking detail and ignoring error or uncertainty in favour of the ‘quick and easy’ message can give the wrong impression. 

The key for the designer is to have a firm understanding on their intended message: what they are trying to communicate. Plus a clear picture of their audience: who they are trying to communicate to. Whether illustrative or data-driven, design is always king.


**Tidy Tuesday R data project: Week 12**  
Visualising IMDB ratings for the Office
![officeDotPlot](/officeDotPlot.png)

**The north coast of Cornwall is famous for it's big, sandy beaches**  
A kind of treemap. The leaf nodes in this case are the towns (eg Padstow) and the 'weight' which sizes them is the number of beaches in that area.  
![cornwall](/cornwall.png)


**Visualising complete graphs using a variety of network layout algorithms in ggraph**    
Complete  
![complete20s](/complete20s.png)

Non complete  
![kkNonComplete](/kkNonComplete.png)


**Experimenting with randomization, layering, opacity and colour to create a blended, 'smudge' effect**  
![randomColour](/randomColour.png)


**Manipulating force directed algorithms in ggraph**  
Cats cradle  
![t31](/t31.png)

Chordal  
![t29](/t29.png)

Dandelion
![t35](/t35.jpg)


**'Math art' sketches (mostly using sine and cosine functions)**  
Stave  
![musicCurve](/musicCurve.png)

Rhizome
![narrativeLinesRhizome](/narrativeLinesRhizome.jpg)

Brain
![t27](/t27.jpg)

Curl
![greencurve](/greencurve.png)

Melted
![melted6](/melted6.png)

**Experiments in visualizing growth patterns in 2D and 3D**  
Ink
![ink](/ink.png)

Print sketching 2D Growth
![growth](/growth.png)

3D growth raw data
![tetrahedralMaterials](/tetrahedralMaterials.png)

Model of 3D growth: tetrahedral helix
![tetFinished2](/tetFinished2.png)

----------




