This Github project contains course material for GMS7930: ChIP-seq data analysis practice.

We are using Rmarkdown file in this class to demonstrate the data analysis modules.
In this project, all ChIP-seq sequencing reads for demonstration are
stored as [BAM](https://en.wikipedia.org/wiki/Binary_Alignment_Map)
files in the
[**data**](https://github.com/tengmx/gms7930/tree/master/data)
folder, while the rmarkdown file (*gms7930-rgs.Rmd*) and
its output file (*gms7930-rgs.html*) are located in the project root folder.

To open and run the Rmarkdown file,
 [*rstudio*](https://posit.co/download/rstudio-desktop/)
 has to be installed firstly. 
Make sure you have the lastest R release version installed in your computer.
Also, if [*rstuio*](https://posit.co/download/rstudio-desktop/) 
is not running on MAC or Linux system, one edit is  needed in 
the *gms7930-rgs.Rmd* file before starting: the value of **workdir** on row 86 has
to be changed into system compatible file path, such as 'C:\\' on Windows system.
Also, if you are running rstudio on Windows, make sure you run it as system administrator.

After all set above, you are ready to explore the data analysis modules documented in
the *gms7930-rgs.Rmd* file. Details of module instruction and function are embedded
inside the *gms7930-rgs.Rmd* file.

If you find it hard to read/edit the Rmarkdown file, you can also focus on the html file
 (*gms7930-rgs.html*). To view the html file, you will need to download it to your computer,
then open it using any web browser.
   
