# Processing Ribo-Seq Data with RiboGalaxy for [RiboSeq.org](https://riboseq.org/)

<img 
    style="display: block; 
           margin-left: auto;
           margin-right: auto;
           width: 30%;"
    src="https://github.com/JackCurragh/RiboGalaxy-Tutorials/blob/main/screenshots/ribogalaxy_icon.png" 
    alt="Ribogalaxy Icon">
</img>

## About RiboSeq.org

Riboseq.org is an online gateway to a set of integrated resources for the processing and analysis of ribosome profiling (Ribo-Seq) data. Currently these are GWIPS-viz, Trips-Viz and RiboGalaxy.  


**We recommend users process their Ribo-Seq data using RiboGalaxy and then upload their data to Trips-Viz for downstream analysis.**


[GWIPS-viz](https://gwips.ucc.ie) enables users to visualize Ribo-Seq and RNA-Seq data aligned to the genomes of 29 organisms along with auxiliary information such as reference annotations. Currently, pre-processed datasets from over 200 publicly available ribosome profiling studies are made available to users for visualization and download. GWIPS-Viz also supports the creation of user generated custom tracks for private data visualization. 

[Trips-Viz](https://trips.ucc.ie) enables visualization of public and private Ribo-Seq, RNA-seq and MassSpec data aligned to the transcriptomes2. It also enables a range of functionalities for the analysis of ribosome profiling data including footprints length distribution and periodicity, metagene profiles, differential expression, detection of translated ORFs and many more.

[RiboGalaxy](https://ribogalaxy.genomicsdatascience.ie/) is a Galaxy based platform tailored for the online processing of ribosome profiling data. The intuitive galaxy interface enables users who lack scripting skills or sufficient computational resources to process their data. A wide variety of reference sequences are supplied to streamline users' data processing workflows. RiboGalaxy simplifies Ribo-Seq data processing for upload to GWIPS-viz and Trips-Viz.


## Galaxy Basics 

![homepage screenshot](https://github.com/JackCurragh/RiboGalaxy-Tutorials/blob/main/screenshots/homepage.png)

This is the basic Galaxy user interface that you may be familiar with from other Galaxy instances. If not, the most important features are highlighted here. 

### Login/Register 
We **strongly** advise that all users create an account and login prior to carrying out any data processing or analysis. This ensures that information about your analysis is associated with your account and can be accessed from any browser. If you forget to login then there is nothing we can do to help you retrace your steps! 

![login and register tab screenshot](https://github.com/JackCurragh/RiboGalaxy-Tutorials/blob/main/screenshots/login_register.png)

### Tool Panel 
The tool panel on the left hand side is where you will find the RiboGalaxy supported data processing tools. Within this panel tools are grouped into the data processing stages that they are generally used for. However, we will see later on where some tools can be used in other steps also. 

Clicking on the tool name will load a new page where you can input you parameters prior to running the tool. 

![tool panel screenshot](https://github.com/JackCurragh/RiboGalaxy-Tutorials/blob/main/screenshots/tool_panel.png)


### History

Your data processing and analysis history is stored on the panel to the right. Here we can see the output files produced by the jobs we run and based on their colour see how successful that job was. A green output file suggests the process was sucessful. Red suggests un-successful. Yellow means the process is running and grey means it is yet to be run. 

All of the metadata about the job that was run to produce each output can be accessed by clicking on that output. You can also visualise and download the data using various buttons on that panel. 

![history screenshot](https://github.com/JackCurragh/RiboGalaxy-Tutorials/blob/main/screenshots/history.png)

It is always good to create a new history for each general data processing task and to rename it to reflect its purpose. 

![history rename screenshot](https://github.com/JackCurragh/RiboGalaxy-Tutorials/blob/main/screenshots/rename_history.png)



## Getting Data 



## Preprocessing 



## Read Alignment 



## Alignment Processing Prior to Upload

### [GWIPS-Viz](https://gwips.ucc.ie/index.html)




### [Trips-Viz](https://trips.ucc.ie/)