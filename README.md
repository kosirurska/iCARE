# iCARE Study Repository

This repository contains most of the iCARE study website information and infographics codes and materials. The files are primarily utilized internally, but data is free and available to anyone - you just need to register your project and request it.

To learn more about the study and how to access data, [click here](http://www.icarestudy.com/).


### Structure of the repository

Individual files are all placed in the same folder. Each .rmd file has the corresponding html file. So, all the files can be accessed without using R!

* Files prefixed with *Global_* are files used to inform individual web pages for survey specific results. There is some thematic organization. They might not directly correspond to what is presented on the website as the information online is organized and finalized by the team responsible for that.

* Files prefixed with *Infographic_* are files that were used for individual inforgaphics, which you can access [here](https://mbmc-cmcm.ca/covid19/research/infog/). Majority of the infographics were not developed by me, therefore there is no corresponding code on this repo. If you wish to request more information, you can try to reach team members who will be able to help.

* Files prefixed with *Other-* are additional files that were developed when we were exploring data or developing our analyses and inforgaphics.

* *Core-website-file* is the information plugged into the main overview of the study on the website and is updated with each incoming survey round. The data presented only contains information of the Global Convenience sample.


### **Note for collaborators**:
Several Markdown files are self-contained and as long as you plug in the right data the code should run seamlessly. Where appropriate, the code contains notes as to how to deal with any variable name changes. These files were written as we went along, so in case of any variable name change, the code may have to be updated with the latest variable name for it to run.

*NB* - Additionally, you may have to change the working directory, or just make sure your data file is in the correct folder and labelled accordingly.

For any further questions please [reach me via email](mailto:dr.urska.kosir@gmail.com)! and I will try to help the best I can.