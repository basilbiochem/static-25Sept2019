---
title: "Structural Alignment with Dali"
teaching: 30
exercises: 90
questions:
- "How are similar protein structures identified?"
objectives:
- "Students will distinguish between sequence and structure alignments and also between local and global alignments."
- "Students will interpret Dali output (specifically: Z-score, RMSD, and sequence identity) to identify structurally similar proteins."
- "Students will infer functional information about a query/unknown protein based on a hit/known protein."

keypoints:
- "Dali searches identify backbone structure similarity between a query protein and 3D structures of proteins from the PDB."
- "Backbone structure similarity may not guarantee similarity in function since side chains are important for function."

---
<img src="../fig/dali.png" alt="Dali" width="100" style="float: left; margin-top: 0px; margin-right: 10px" />
Dali is a structural alignment tool that aligns entire protein structures.  The quality of the match is indicated by the z-score.  Other information that can be determined from a Dali search includes the RMSD between the query structure and the similar protein, the length of the alignment, and the sequence similarity between the proteins.
<br/><br/><br/><br/><br/><br/>

> ## Module Resources
>[Download student module here](https://docs.google.com/document/d/e/2PACX-1vSYZSKglB4rNIT8Shw0CYJy9zaBXhr8nqJpn0XLghYZ39XP1JBkq-Z-vk8o43Gnyth4SoH9JMn5AggP/pub)
{: .callout}
