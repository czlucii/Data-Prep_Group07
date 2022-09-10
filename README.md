# Project motivation

The start of the academic year for university students can be a stressful period for many reasons, finding housing is one of them. In this current research we aim to investigate how the AirBnb market is affected in different Western-European cities by the start of the academic year. The Berlin Spectator recently described the ease with which students can find housing in Berlin is largely base on luck. In a popular Belgian student city, after publishing an advertisement for student rooms, housing agents needed to ignore students' phone calls, as distress among them for rooms and studios was increasing. NL Times published an article in which University of Amsterdam is warninh students not to come to the Netherlands without housing. It is obvious that in all these three countries finding student accomodation is a serious problem for newcomers. However, it is less obvious how this crisis affects the AirBnb market as a possible alternative for students looking for (temporary) accomodation. To what extent does the situation differ across cities in different countries? As a result of our research, we hope to answer the following main research question and sub-questions:

How is the AirBnb market affected in student cities in Europe by the start of the academic year?
Sub-questions:
- How are the prices impacted in this period?
- Does the number of renters increase?
- Are more rental locations available?

- Major European cities with universities: The Netherlands (Amsterdam, Rotterdam), Belgium (Antwerp, Ghent, Brussels?), Germany (Berlin, Munich?)




# Example of reproducible research workflow 

This is a basic example repository using Gnu make for a reproducible research workflow, as described in detail here: [tilburgsciencehub.com](http://tilburgsciencehub.com/). 

The main aim of this to have a basic structure, which can be easily adjusted to use in an actual project.  In this example project, the following is done: 
1. Download and prepare data
2. Run some analysis
3. Present results in a final pdf generated using LaTeX

## Dependencies
- R 
- R packages: 
	install.packages("stargazer")
- Gnu make 
- TeX distribution (I use TeX Live 2019) 
- For the `makefile` to work, R, Gnu make and the TeX distribution (specifically `pdflatex`) need to be made available in the system path 
- Detailed installation instructions can be found here: [tilburgsciencehub.com](http://tilburgsciencehub.com/)


## Notes
- `make clean` removes all unncessary temporary files. 
- Tested under Linux Mint (should work in any linux distro, as well as on Windows and Mac) 
- IMPORTANT: In `makefile`, when using `\` to split code into multiple lines, no space should follow `\`. Otherwise Gnu make aborts with error 193. 
- Many possible improvements remain. Comments and contributions are welcome!
