# Abstract

Bad Smells are indicators of code structure problems that may be solved via refactoring.
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
we have identified ten tools, which refactor from bad smell detection.



# Filtering Databases

| Database            | Step 1 | Step 2 | Step 3 | Step 4 | Step 5 | Step 6 |
|:--------------------|:--------|:--------|:--------|:--------|:--------|:--------|
| ACM Digital Library | 97 | 68  | 33 | 25 | 12 | 03 |
| Engineering Village | 20 | 13  | 06 | 04 | 03 | 03 |
| IEEE Xplore         | 28 | 18  | 12 | 05 | 02 | 00 |
| Science Direct      | 02 | 02  | 01 | 01 | 01 | 00 |
| Scopus              | 17 | 11  | 06 | 04 | 03 | 01 |
| Springer            | 2,016 | 210  | 95 | 95 | 43 | 08 |
| Web of Science      | 02 | 02  | 01 | 01 | 01 | 00 |



# Places of Publication

| Place            | Total |
|:-----------------|:------|
| Book Chapter     | 01 |
| Conference       | 08 |
| Journal          | 09 |
| Symposium        | 02 |



# Events

| Event                                                                             | Total |
|:----------------------------------------------------------------------------------|:------|
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
|:-----|:----------------------|:--------------------|:----------|
| RESYS | OSORE                | OCEAN               | [1]       |
| MMRUC3 | Integrated          | Integrated          | [1]       |
|        | Refactoring Miner   | Own Metric Developed | [1]      |
|        | JDeodorant          | JDeodorant and DECOR | [1]      |
|        | Ref-Finder          | Own Metric Developed | [1]      |
| Methodbook | Integrated      | Integrated           | [1]      |
| DCRA   | Integrated          | NiCad                | [1]      |
|        | JDeodorant          | JDeodorant           | [1]      |
| Extract Method Detector | Integrated | Integrated   | [1]      |
|       | ARIES and JDeodorant | ARIES and JDeodorant | [1]      |
| CCShaper | Integrated          | CCFinder             | [1]      |
|  | Ref-Detector and Ref-Finder | Ref-Detector and Ref-Finder | [1] |
| Liu's Approach | Integrated    | Integrated         | [1]      |
| Tsantalis's Methodology  | Integrated  | Integrated | [1]      |
| HIST   |                     | Integrated           | [1]      |
| JMove    | Integrated      | Integrated             | [1]      |
