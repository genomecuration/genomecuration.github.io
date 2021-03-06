Functional assignment refers to the annotation of biological function to genetic elements identified during structural annotation and feature curation. In most cases it is not feasible to establish function experimentally for the majority of genome features identified. As such, most annotations are putative and rely upon either:

1. Similarity searches in sequence space to identify orthologs in other species which do have functional annotation. This might be accomplished using a simple BLAST search or more sophisticated phylogenetically-aware alogrithms.
2. Model-based approaches (typically hidden-markov-model) rely on the identification of specific patterns to group proteins into functional classes. 

Typically both approaches will be used during functional assignment to provide multiple sources of evidence. However it is important to remember that any prediction is an untested hypothesis. All of these approaches rely upon similarity bourne of evolution. However common ancestry does not always imply common function. Gene duplication events given sufficient time can result in paralogs. 

Controlled vocabularies organised into hierachies, often referred to as ontologies, provide a useful framework into which functional and other information can be compared across species. Additional biochemical pathway databases can also used to characerise the metabolic potential of an organism. These can be particularly valuable when performing comparative genomics, or assessing whether the assembly and/or structural annotation may be incomplete.

Some important points to remember:

* Remember that different types/families of genes evolve in different ways so there is no one-stop solution to set any sort of cutoff for whether inferences can/cannot be made.
* Always consider the differences between general (membrane protein) and specific (Na/K pump of the golgi) functions - think where to draw the line when making a hypothesis. How conservative do you want to be?
* Consider treating the agreement/disagreement between different approaches as a proxy for globally assessing the quality of functional annotations, even if subsequent manual curation provides the real quality control.


Learn about pros & cons of the major sources of functional data: GO, KEGG, InterPro, PANTHERdb, SwissProt; e.g. hierarchies, levels of manual curation, availability.
Be aware of the limitations of similarity-based approaches - functional inferences based on sequence homology - because common ancestry ? common function.
Consider treating the agreement/disagreement between different approaches as a proxy for globally assessing the quality of functional annotations, even if subsequent manual curation provides the real quality control.

