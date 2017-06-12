---
layout: tutorial_page
permalink: /pathways_2017_prework
title: Pathways
header1: Workshop Pages for Students
header2: Pathway and Network Analysis of -Omics Data 2017
image: /site_images/CBW_pathway_icon.jpg
home: https://bioinformaticsdotca.github.io/pathways_2017
---

Read these before coming to the workshop:

* [iRegulon: From a Gene List to a Gene Regulatory Network Using Large Motif and Track Collections](http://www.ncbi.nlm.nih.gov/pubmed/25058159)
  
  * [The GeneMANIA prediction server: biological network integration for gene prioritization and predicting gene function](http://www.ncbi.nlm.nih.gov/pubmed/20576703)
  
  * [GeneMANIA Prediction Server 2013 Update](http://www.ncbi.nlm.nih.gov/pubmed/23794635)
  
  * [How to visually interpret biological data using networks](http://www.ncbi.nlm.nih.gov/pubmed/19816451)
  
  * [g:Profiler--a web-based toolset for functional profiling of gene lists from large-scale experiments](http://www.ncbi.nlm.nih.gov/pubmed/17478515)
  
  * [g:Profiler--a web server for functional interpretation of gene lists (2011 update)](http://www.ncbi.nlm.nih.gov/pubmed/21646343)
  
  * [Gene set enrichment analysis: a knowledge-based approach for interpreting genome-wide expression profiles](http://www.ncbi.nlm.nih.gov/pubmed/16199517)
  
  * [Expression data analysis with reactome](http://www.ncbi.nlm.nih.gov/pubmed/25754994)  

Do these before coming to the workshop:

1) [Sequencing Terminology](http://www.ncbi.nlm.nih.gov/projects/genome/glossary.shtml)

2)  **Cytoscape Preparation tutorials**: Complete the [introductory tutorial to Cytoscape](http://opentutorials.cgl.ucsf.edu/index.php/Portal:Cytoscape3)

* Introduction to Cytoscape3 - User Interface

* Introduction to Cytoscape3 - Welcome Screen

* Filtering and Editing in Cytoscape 3

Install these before coming to the workshop:

1) A robust text editor.   

* For Windows/PC - [notepad++](http://notepad-plus-plus.org/)  
* For Linux - [gEdit](http://projects.gnome.org/gedit/)  
* For Mac – [TextWrangler](http://www.barebones.com/products/textwrangler/download.html)

2) A file decompression tool.  

* For Windows/PC – [7zip](http://www.7-zip.org/).  
* For Linux – [gzip](http://www.gzip.org).   
* For Mac – already there.

3) A robust internet browser such as Firefox or Safari (Internet Explorer and Chrome are not recommended because of Java issues).

4) Java -The visualization program that we will be using (IGV) requires Java. Check if you have Java installed: https://www.java.com/verify/ and download Java if you do not have it installed (Java 8).

5) A PDF viewer (Adobe Acrobat or equivalent).

6) Install [Cytoscape 3.4.0](http://chianti.ucsd.edu/cytoscape-3.4.0/).  

Choose the version corresponding to your operating system (OS, Windows or UNIX) 
Cytoscape requires Java8: check your version at  https://www.java.com/verify/ and download Java8 if you do not have it installed. Contact your system administrator if you have trouble with Java installation. 

7) Within the Cytoscape program, install the following Cytoscape apps.  

From the menu bar, select ‘Apps’ , ‘Manage Apps’.
 
Within all apps, search for the following and install:  

 * EnrichmentMap 
 * EnrichmentMap Pipeline Collection (it will install ClusterMaker2, WordCloud and AutoAnnotate) 
 * GeneMania 
 * Iregulon  
 * ReactomeFIPlugin - http://apps.cytoscape.org/apps/reactomefiplugin  
 
 
8) Install the data set within GeneMANIA.

Select GeneMania from Apps Manager and Choose Another Data Set.  
From the list of available data sets, select the most recent (2014-08-12/1 June 2014) and under ‘Include only these networks’: select ‘all’. Click on ‘Download’.  
An ‘Install Window’ will pop-up. Select H.Sapiens Human (2384 MB). Click on ‘Install’.  
This requires time and a good network connection to download completely, so be patient (around 15mins).  

  
9) Install GSEA.  

Go to the [GSEA page](http://www.broadinstitute.org/gsea/index.jsp)    
Register  
Login  
In menu, choose Downloads  
Go to the javaGSEA Java Jar file section and download the gsea2-2.2.3.jar file and save in your Documents folder (do not leave it in the “Downloads”folder).  
 
To run GSEA during the workshop, you must use the command line. You will need to open a terminal and execute the install commands. Since we will need to run GSEA this same way each time, it will be a good idea to save this information on how to run GSEA.
 
**MAC/Linux Computer** 

* On a MAC, the Terminal window is located in Applications/Utilities. Tip: add the terminal window to your dock so it is easy to open when needed.  
* At the prompt, type the command in your terminal window and hit enter:

```
java -Xmx2G -jar ~/Documents/gsea2-2.2.3.jar
```

**PC/Windows Computer** 

* On Windows, go to the start icon and type cmd (for command prompt) in the search box.  
* At the prompt, type the following commands, hitting enter in between each command and waiting for the prompt before the next command:

```
cd Documents
java -Xmx2G -jar gsea2-2.2.3.jar
```
