# GrapheneData
The data in the zipped files relations_data.tsv.zip, rules_data.tsv.zip in this repository have been generated with Graphene (https://github.com/Lambda-3/Graphene). 

Each row in the file relations_data.tsv, includes an example sentence and as a label, a rhetorical relation that occurs in that sentence. These data were generated using the Discourse Simplification (https://github.com/Lambda-3/DiscourseSimplification) component of Graphene. The rhetorical relations are the ones identified after the application of the first simplification rules that matches the example sentence. Some examples from the data file:

id	label	alpha	sentence
2	BACKGROUND	a	It is very fast , as package solving complexity is very low compared to other areas where SAT solvers are used .
55	CAUSE	a	It has reduced predation since the fly can not locate the males .


Each row in the file rules_data.tsv, includes an example sentence and as a label, the first simplification rule that matches for that sentence. These data were generated using the Discourse Simplification (https://github.com/Lambda-3/DiscourseSimplification) component of Graphene. Some examples from the data file:

id	label	alpha	sentence
1	CoordinationExtractor	a	The Boolean satisfiability problem is a well - researched problem with many exemplar solvers available ; it is very fast , as package solving complexity is very low compared to other areas where SAT solvers are used .
477	PurposePostExtractor	a	Short stories were taken from Islamic history to illustrate the eternal spiritual truths in the teachings of Islam .
518	RestrictiveAppositionExtractor	a	Menino , the council president at the time , became acting Mayor for four months before being elected to his first term in November 1993 , defeating State Representative James Brett 64 % to 36 % .
