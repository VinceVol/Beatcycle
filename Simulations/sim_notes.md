# FreeCad 1.1.1 FEM Learnings
Basically I've fought with setting things up in freecad to do an effective FEM so here are some of the findings

## Meshing
Export all relavent bodies to a step file.
*reopen the file and switch to Part workbench*

Use [Part -> Compound -> Compound] after reoping step file to combine all bodies into one.

*switch back to the FEM workbench* 

Netgen mesh the entire compound
