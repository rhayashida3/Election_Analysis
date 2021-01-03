{\rtf1\ansi\ansicpg1252\cocoartf2577
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica-Bold;\f1\fswiss\fcharset0 Helvetica;\f2\fnil\fcharset0 LucidaGrande;
}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
{\*\listtable{\list\listtemplateid1\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{square\}}{\leveltext\leveltemplateid1\'01\uc0\u9642 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid1}
{\list\listtemplateid2\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{square\}}{\leveltext\leveltemplateid101\'01\uc0\u9642 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid2}
{\list\listtemplateid3\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{square\}}{\leveltext\leveltemplateid201\'01\uc0\u9642 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid3}
{\list\listtemplateid4\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{square\}}{\leveltext\leveltemplateid301\'01\uc0\u9642 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid4}
{\list\listtemplateid5\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{square\}}{\leveltext\leveltemplateid401\'01\uc0\u9642 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid5}}
{\*\listoverridetable{\listoverride\listid1\listoverridecount0\ls1}{\listoverride\listid2\listoverridecount0\ls2}{\listoverride\listid3\listoverridecount0\ls3}{\listoverride\listid4\listoverridecount0\ls4}{\listoverride\listid5\listoverridecount0\ls5}}
\margl1440\margr1440\vieww15500\viewh10160\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\b\fs36 \cf0 # Election_Analysis
\f1\b0\fs24 \
\
\

\f0\b\fs28 Overview of Election Audit
\f1\b0\fs24 \
In this assignment, I am asked to assist a Colorado Board of Elections employee, Tom, in an election audit of a tabulated results for U.S. Congressional precinct in Colorado. I am tasked with reporting the total number of votes cast, the total number of votes for each candidate, the percentage of votes for each candidate and the winner of the election based on popular vote. This task is usually done on excel, but Tom\'92s manager is looking to automate this process using Python. If this audit is done successfully with Python, the code will be used to audit not only other Congressional districts but also Senatorial districts and local elections. \
\
First, we learn about the basics of coding using Python. We start off by downloading and installing necessary tools and softwares such as Terminal and Visual Studio Code. We then move on to writing our first Python script by creating variables, lists, objects, dictionaries, etc. We then apply the use of formulas, decision statements, repetition statements and many other operators. We also learn about formatting and presenting data in appropriate styles. Next, we move on to importing and inspecting the data set in CSV file format. In this activity, we dissect the data used to generate the information requested per above. We also learned about creating a .txt file in order to effectively communicate the end result with the audience. After analyzing the data set, we then write pseudocode, which is a technique commonly used by programmers to write steps in their code, to outline the process and write the script to dive into the core task of the project. Reference images below for some of the newly acquired knowledges throughout this activity.\
\
\

\f0\b\fs28 Election-Audit Results
\f1\b0 :\

\fs24 \
How many votes were cast in this congressional election?\
\pard\tx220\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\li720\fi-720\pardirnatural\partightenfactor0
\ls1\ilvl0\cf0 {\listtext	
\f2 \uc0\u9642 
\f1 	}369,711\
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0
\cf0 \
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0
\cf0 Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.\
\pard\tx220\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\li720\fi-720\pardirnatural\partightenfactor0
\ls2\ilvl0\cf0 {\listtext	
\f2 \uc0\u9642 
\f1 	}Jefferson: 10.5% (38,855)\
{\listtext	
\f2 \uc0\u9642 
\f1 	}Denver: 82.8% (306,055)\
{\listtext	
\f2 \uc0\u9642 
\f1 	}Arapahoe: 6.7% (24,801)\
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0
\cf0 \
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0
\cf0 Which county had the largest number of votes?\
\pard\tx220\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\li720\fi-720\pardirnatural\partightenfactor0
\ls3\ilvl0\cf0 {\listtext	
\f2 \uc0\u9642 
\f1 	}Largest County Turnout: Denver\
{\listtext	
\f2 \uc0\u9642 
\f1 	}Winning County Vote: 306,055\
{\listtext	
\f2 \uc0\u9642 
\f1 	}Winning County Percentage: 82.8%\
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0
\cf0 \
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0
\cf0 Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.\
\pard\tx220\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\li720\fi-720\pardirnatural\partightenfactor0
\ls4\ilvl0\cf0 {\listtext	
\f2 \uc0\u9642 
\f1 	}Charles Casper Stockham: 23.0% (85,213)\
{\listtext	
\f2 \uc0\u9642 
\f1 	}Diana DeGette: 73.8% (272,892)\
{\listtext	
\f2 \uc0\u9642 
\f1 	}Raymon Anthony Doane: 3.1% (11,606)\
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0
\cf0 \
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0
\cf0 Which candidate won the election, what was their vote count, and what was their percentage of the total votes?\
\pard\tx220\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\li720\fi-720\pardirnatural\partightenfactor0
\ls5\ilvl0\cf0 {\listtext	
\f2 \uc0\u9642 
\f1 	}Winner: Diana DeGette\
{\listtext	
\f2 \uc0\u9642 
\f1 	}Winning Vote Count: 272,892\
{\listtext	
\f2 \uc0\u9642 
\f1 	}Winning Percentage: 73.8%\
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0
\cf0 \
\

\f0\b\fs28 Election -Audit Summary\

\f1\b0\fs24 The script used to reporting the breakdowns of election audit for the U.S. Congressional precinct in Colorado not only successfully provided the necessary information to determine the winner of the election but can also be used (with some modification) for any election such as other Congressional districts and Senatorial districts and local elections. For example, if this script were to be used for other Congressional districts, we will simply choose a different CSV file with information needed (but must be in the same exact format), change the variable to load a file from a path by adjusting file_to_load = os.path.join("/Users/ruihayashida/Documents/Bootcamp/Module3/Election_Analysis/Resources/election_results.csv") and running the script. Another method of using this script for other (let\'92s say larger) election is by modifying the script based on what data set may contain. In this example, we gathered county-based information regarding the election. If this script were to be ran for a Presidential election, we would most likely need to exchange the term \'93counties\'94 to \'93states\'94 within the entire script.\
}