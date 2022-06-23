# DDIPred
## DDIPred: Graph Convolutional Network-based Drug-drug Interactions Prediction using Drug Chemical Structure Embedding


A drug-drug interaction (DDI) describes a circumstance in which drugs affect the activity of each other. Drugs may interact with each other to cause side effects that are unexpected or more severe than anticipated. Drugs may also interact and oppose the results of one another, leading to one (or both) medications not having their intended effect. Most drug interactions are negligible, but some can be significantly harmful if not discovered and appropriately overseen. DDI data can be helpful for other drug-related research topics such as drug repurposing and drug-target interaction, which leads to improving the drug development process. This paper presents a new method for DDI prediction named DDIPred.It is based on drug chemical structure embedding and graph convolutional networks for predicting new DDIs. DDIPred First extracts a representation of Simplified Molecular Input Line Entry System (SMILES) strings using SELF-referencIng Embedded Strings (SELFIES) and Doc2Vec. Then the representation, along with the DDI network structure, is used to predict new DDIs. Our method achieved acceptable performance when tested on the BIOSNAP DDI network dataset while outperforming other existing methods.

\includegraphics[scale=0.5] {DDI-pipeline.pdf}
