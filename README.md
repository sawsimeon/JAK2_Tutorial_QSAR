# Quantitative Structure Activity Relationship Using KNIME

In the context of elucidating the underlying physicochemical properties of chemical structures of drugs is required for understanding the origin of their biological activity and pharmacological effects. QSAR is used to address these issues in which the biological activities of several compounds are studied using empirical mathematical approaches that seeks to discern the relationship between the chemical structures and the measured activity. Each compound is represented by a set of chemical descriptors, mathematical representation of chemical structures. This is because at a latter stage the model can then be used as a tool to predict the activities of new compounds before they are synthesized without the need for any physical measurements on them. Many approaches can be used to represent the chemical structures: counting the presence and absence of certain chemical groups, identifying the presence or absence of predified structural fragments in molecules or advanced methods that reflect the physiochemical properties of the chemical compounds. These descriptors were then used to build a mode by relating it to measured biological activities using machine learning approaches. With that, it is possible to reveal what influence a change in the chemical structure of a compound has on its biological activity by considering the biological activity of a compound is dependent on the compounds chemical space. 

Before we dive into perform the analysis, please see the general workflow of the QSAR. ![General QSAR WorkFlow](http://www.mdpi.com/molecules/molecules-21-00151/article_deploy/html/images/molecules-21-00151-g001-1024.png) From the figure, we can see that the molecular structure of the chemical compounds are represented as fingerprint descriptors, which are then used to build the QSAR model to predict the property of chemical compounds. For performing the QSAR analysis, I have selected a Histone Deacetylase inhibitors because cancer is one of the leading causes of death all over the word. A wide range of proetines are found to be related to tumor fomration and metastatis. However, only proteins with widespread biological significance for the tumor cells growth regulation are most possible to be the targets. Histone deacetylase are proved to be new epigenetic target for the treatment of cancer. And it has been shown that inhibitors of histone deacetylase have antitumor effects in both *in vitro* and *in vivo*. Because of this, these inhibitors have become one of the most important research fields of the antitumor drugs, especially during the area of epigenetics. 
 
For today, we will be using KNIME for performing anlaysis, from importing data, standaridizing SMILES, extracting descriptors to building model and generating graphs. ![KNIME LOGO](http://hortonworks.com/wp-content/uploads/2014/12/KNIME_Logo_5000x1303_transp.png). KNIME allows users to create efficient and transparent workflow with interation with various other open-source, including but not limited to Weka, R, CDK, RDkit, ChemAxon, OpenBabel, LIbSVM, making a very popular tools among chemometricians as well as scientists who wants to dive into the fiel of pharmaceutical research and data analysis. 
