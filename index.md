# Abstract

<p style="text-align: justify;">Bad Smells are indicators of code structure problems that may be solved via refactoring.
Refactoring is a process of improving the internal structure of the software system by 
improving code maintenance without changing the external behavior of the source code. 
However, the refactoring process takes effort, so it should be done in a disciplined manner 
in order to minimize the chances of introducing code errors. In this paper, we present a 
systematic literature review with the purpose to identify the explicit relationship between 
refactoring from bad smell detection. As a result, we have identified 20 papers that show the 
direct relationship between 31 different refactorings and 16 bad smells proposed by Fowler. 
Analyzing these papers, we have found that (1) the relationship between Move Method applied to 
Feature Envy bad smell appears as the most discussed issues in these studies; (2) there are 
different refactoring strategies than those proposed by Fowler to address bad smells; and (3), 
we have identified ten tools, which refactor from bad smell detection.</p>



# Filtering Databases

| Database            | Step 1 | Step 2 | Step 3 | Step 4 | Step 5 | Step 6 |
|:--------------------|:--------:|:--------:|:--------:|:--------:|:--------:|:--------:|
| ACM Digital Library | 97 | 68  | 33 | 25 | 12 | 03 |
| Engineering Village | 20 | 13  | 06 | 04 | 03 | 03 |
| IEEE Xplore         | 28 | 18  | 12 | 05 | 02 | 00 |
| Science Direct      | 02 | 02  | 01 | 01 | 01 | 00 |
| Scopus              | 17 | 11  | 06 | 04 | 03 | 01 |
| Springer            | 2,016 | 210  | 95 | 95 | 43 | 08 |
| Web of Science      | 02 | 02  | 01 | 01 | 01 | 00 |



# Places of Publication

| Place            | Total |
|:-----------------|:------:|
| Book Chapter     | 01 |
| Conference       | 08 |
| Journal          | 09 |
| Symposium        | 02 |



# Events

| Event                                                                             | Total |
|:----------------------------------------------------------------------------------|:------:|
| Frontiers of Computer Science                                                     | 01 |
| IEEE Transactions on Software Engineering	                                        | 03 |
| Innovations Syst Softw Eng                                                        | 01 |
| International Conference on Agile Software Development (XP)	                      | 02 |
| International Conference on Enterprise Information Systems (ICEIS)              	| 01 |
| International Conference on Product Focused Software Process Improvement (PROFES)	| 01 |
| International Conference on Software Analysis, Evolution, and Reengineering	      | 01 |
| International Conference on Software Quality (SWQD)                             	| 01 |
| International Journal of System Assurance Engineering and Management            	| 01 |
| International Symposium on Empirical Software Engineering                       	| 01 |
| Joint Meeting on Foundations of Software Engineering	                            | 01 |
| Journal of Software: Practice and Experience	                                    | 01 |
| Journal of Systems and Software                                                 	| 01 |
| Recommendation Systems in Software Engineering	                                  | 01 |
| Requirements Eng                                                                	| 01 |
| Simpósio Brasileiro de Engenharia de Software (SBES)	                            | 01 |
| Working Conference on Reverse Engineering (WCRE)                          	      | 01 |



# Tools found in the Literature

| Tool | Refactoring Tool Used | Bad Smell Tool Used | Reference |
|:-----|:----------------------|:--------------------|:----------:|
| RESYS | OSORE                | OCEAN               | [37]       |
| MMRUC3 | Integrated          | Integrated          | [33]       |
|        | Refactoring Miner   | Own Metric Developed | [7]      |
|        | JDeodorant          | JDeodorant and DECOR | [35]      |
|        | Ref-Finder          | Own Metric Developed | [3]      |
| Methodbook | Integrated      | Integrated           | [5]      |
| DCRA   | Integrated          | NiCad                | [13]      |
|        | JDeodorant          | JDeodorant           | [9]      |
| Extract Method Detector | Integrated | Integrated   | [23]      |
|       | ARIES and JDeodorant | JDeodorant | [4]      |
| CCShaper | Integrated          | CCFinder             | [18]      |
|  | Ref-Detector               | Metrics to Detect Smell | [8] |
| Liu's Approach | Integrated    | Integrated         | [21]      |
| Tsantalis's Methodology  | Integrated  | Integrated | [42]      |
| HIST   |                     | Integrated           | [30]      |
| JMove    | Integrated      | Integrated             | [34]      |


# List of Papers

#### Filtering Steps

[13] A Duplicated Code Refactoring Advisor

[37] An Approach for Semantically-Enriched Recommendation of Refactorings Based on the Incidence of Code Smells

[3] An Experimental Investigation on the Innate Relationship Between Quality and Refactoring

[35] Analysis of Code Smell to Quantify the Refactoring

[10] Common Refactorings, a Dependency Graph and some Code Smells: An Empirical Study of Java OSS

[9] Investigating the Evolution of Code Smells in Object-Oriented Systems

[17] Learning to Rank Extract Method Refactoring Suggestions for Long Methods

[32] Leveraging Code Smell Detection with Inter-smell Relations

[23] Major Motivations for Extract Method Refactorings: Analysis Based on Interviews and Change Histories

[5] Methodbook: Recommending Move Method Refactorings via Relational Topic Models

[33] MMRUC3: A Recommendation Approach of Move Method Refactoring Using Coupling, Cohesion, and Contextual Similarity to Enhance Software Design

[4] Recommending Refactoring Operations in Large Software Systems

[18] Refactoring Support Based on Code Clone Analysis

[24] Supporting Requirements to Code Traceability Through Refactoring

[7] Understanding the Impact of Refactoring on Smells: A Longitudinal Study of 23 Software Projects


#### Snowballing

[8] Does Refactoring Improve Software Structural Quality? A Longitudinal Study of 25 Projects

[21] Domino Effect: Move More Methods Once a Method is Moved

[42] Identification of Move Method Refactoring Opportunities

[30] Mining Version Histories for Detecting Code Smells

[34] Recommending Move Method Refactorings Using Dependency Sets


## Publication

Experimental Software Engineering Track (ESELAW)

23rd Iberoamerican Conference on Software Engineering (CIbSE 2020)

Curitiba, Brazil, May 4 - 8, 2020
