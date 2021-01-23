---
layout: post
title: "Masterplanning with IMP Tools"
categories: tools
author: 
- Ong See Hai
---

Industrial park master planning involves several stages of work:
* Planning Parameters Specification
* Existing Conditions Analysis
* Concept Formulation
* Concept Evaluation
* Concept Finalization
* Report Production

### Analysis and Parameters
The first two stages of work are critically important in the masterplanning of industrial parks. The aims are:
* to firm up the type and scale of the envisaged industrial park landuses and facilities
* to analyze the suitability of the existing conditions for the envisaged development and to identify any mitigating measures and infrastructure enhancements that would be necessary 


Sufficient time and manpower should be allocated to these stages.  The experience and skills of experienced planners are essential to ensure high quality analysis and specification work.  Even with artificial intelligence in future work digitalization, it will very difficult to replace the role of skilled and experienced planners for many of the tasks in these two initial work stages.


Input for this stage could be in the form of a written design brief, and/or verbal discussions with the client on their vision, target clients and desired concepts for the proposed development. 


Usually, a market positioning study would have been completed before the masterplanning assignment.  The analysis and recommendations from the market positioning study could provide a firm basis for working out the planning parameters.
For instance, in the project providing the basis for the [IMP Tools Tutorial](/resources.html), some of the key parameters firmed up in the first two stages of work include:
* Large land plots (at least 40 hectares) targeting foreign chemical producers and automotive manufacturers
* Land plots of around 20 hectares targeting local construction material and seafood processing enterprises, based on existing industrial development trends in the surrounding area
* Road connection points to a future port and a regional toll highway
* Separation buffers between the proposed industrial development sand surrounding villages
* Drainage channels to divert stormwater from the future industrial park and mitigate flooding in the surrounding areas

### Concepts
The ultimate aim is to create the optimal layout for the proposed industrial park, that satisifes all the planning parameters (as well as other broader implicit goals such as sustainability and complementarity with the surrounding communities) _at the lowest development cost_.   


Alternative layout designs should be formulated, evaluated and compared.  The best of these alternatives can be selected for further improvement as often the evaluation process for the different designs reveals new and valuable insights.

The design process typically evolves from initial concept to final design through a process of refinement and engagement with the client.  This process must be applied to the formulation of all the alternative layouts, at least up to an intermediate evaluation presentation and discussion with the client.


It is easy to understand why many planners are loathe to provide multiple alternative layouts. In many masterplanning projects, time and budget are under-allocated for analysis and layout work.  Given short masterplanning project durations, a relatively high proportion of time is allocated to ensure the completion of time-consuming graphic illustrations and infrastructure schemas.   This is unfortunate, as the analysis and alternative layout evaluation stages are most critical in delivering an optimal design with significant financial, social and environmental impacts.  

### IMP Tools
[IMP Tools](/resources.html) support planners designing alternative layouts, especially for industrial sites in hilly terrain.   These tools automate some of the most time-consuming and computation-intensive design tasks such as creating road casings, adjusting road gradients over a network, calculating cut-and-fill earthworks volume, adjusting platform and road access point elevations etc. Work that usually take weeks can now be done in minutes or hours.  Within a short period of time, many alternative layouts can be developed, evaluated and compared.

<br>
![](/assets/img/adjustgradient.gif)
<br> Automated adjustment of road gradients and elevations
<br>


A quick three-dimensional visualization tool shows the road gradients, platform elevation and slopes generated.  This visualization facilitates presentation and discussion between the planner and the client.  By exploring the quick 3D model the planner can better appreciate the physical environment formed by the roads, slopes and platforms and draw implications for urban design, truck movement, drainage and so forth.



### Alternative Layouts
Three initial layouts (B2, G2 and T2) from the [Tutorial](/resources.html) project are illustrated below.  The platforms, slopes and roads have been created with IMP Tools from initial two-dimensional line drawings.

Earthworks volumes have been estimated with IMP Tools and provide a first-cut appreciation of the scale and cost of earthworks involved.

<table width="100%">
    <tr>
		<td width="48%">
			<img src="/assets/img/Picture1.png" alt="B2">
			<figcaption> Layout B2 </figcaption>
		</td>
		<td width="48%">
			<img src="/assets/img/Picture2.png" alt="G2">
			<figcaption> Layout G2 </figcaption>
		</td>
	</tr>

	<tr>
	</tr>

	<tr>
		<td width="48%">
			<img src="/assets/img/Picture3.png" alt="T2">
			<figcaption> Layout T2 </figcaption>
		</td>
	</tr>
</table>


<table>
    <tr>
        <td width="16%">Layout</td>
        <td width="28%">B2</td>
        <td width="28%">G2</td>
        <td width="28%">T2</td>
    </tr>
    <tr>
        <td>Concept</td>
        <td>Fewer large platforms</td>
        <td>Platform and elevation aligned with terrain </td>
        <td>East-west orientation</td>
    </tr>
	    <tr>
        <td>Earthworks volume</td>
        <td>51 million cubic meters</td>
        <td>52 million cubic meters</td>
        <td>59 million cubic meters</td>
    </tr>
    <tr>
        <td>Area</td>
        <td>689 hectares</td>
        <td>689 hectares</td>
        <td>688 hectares</td>
    </tr>
</table>


The three alternatives are refined further, providing platforms for land plots in accordance with the planning parameters.  The range of platform sizes in the three alternatives can be compared in terms of minimum and maximum platform sizes, coefficient of variation etc - these statistics can be computed with the QGIS statistics tool.

Layout | B4 | G8 | T6
Minimum platform size | 6 hectares | 2.2 hectares | 2.3 hectares
Maximum platform size | 65.4 hectares | 60.4 hectares | 60.7 hectares
Median platform size | 24.3 hectares | 7.3 hectares | 8.5 hectares
Coefficient of variation | 0.6 | 1.0 | 0.9
Earthworks volume| 42 million cubic meters | 34 million cubic meters | 41 million cubic meters

G8 and T6 are similar in terms of the range of platforms.  B4 has bigger platforms by design.


In terms of earthworks volume, which is by far the major cost and a critical financial feasibility determining component in the development of the industrial park, layout G8 is the most optimal.
<br>


<table width="100%">
    <tr>
		<td width="48%">
			<img src="/assets/img/Picture4.png" alt="B4">
			<figcaption> Layout B4 </figcaption>
		</td>
		<td width="48%">
			<img src="/assets/img/Picture5.png" alt="G8">
			<figcaption> Layout G8 </figcaption>
		</td>
	</tr>

	<tr>
	</tr>

	<tr>
		<td width="48%">
			<img src="/assets/img/Picture6.png" alt="T6">
			<figcaption> Layout T6 </figcaption>
		</td>
	</tr>
</table>








 


