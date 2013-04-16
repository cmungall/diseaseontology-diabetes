This a TEMPORARY repository for experimenting with a merge of the
diabetes subset of the Orphanet rare disease classification with DO.

Please see the commit history for an explanation of the steps
involved.

## Explanation of what we did

 * Placed the rare diabetes subset of Orphanet from EFO and added it to DO
 * Made a subset of the resulting ontology
 * Added has_phenotype associations between DOIDs and HPs
 * Added has_secondary_complication associations between DOIDs and HPs
 * Added new candidate HP terms in the DOCJM namespace

## Modeling

Frequency data was added as axiom annotations using the has_frequency
property and an ad-hoc list of semi-controlled strings (Frequent,
Hallmark, Less fequent).

Note that OWL does not support frequency - axioms are true or
false. This means that associations to subclasses 

 
