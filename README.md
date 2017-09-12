# PeaceMap_MathModel_1
MathModel from ORANGE_5, V_3d, V_3e and data files

V_3d is little plot

V_3e is BIG plot

BOTH HAVE BUG THAT ORIGINALLY LARGER BOX, MADE SMALLER AFTER A CACLULATION, ARE STILL *GHOSTS* THAT CAN BE CLICKED ON


HOW TO RUN THESE PROGRAMS


Run Python Scripts in this order:

1. data.py (this only needs to be done once)


For little plot then run python script:

2. orangeclass_V_3d

3. orange_V_3d


For BIG PLOT then run python script:

2. orangeclass_V_3e

3. orange_V_3e


When asked for "ONLY NUMBER n and I will find cn.txt, etc. (#/a, Def=a)"

	type either: 105 (return) or 8 (return)

		105=24 factor model
		8=6 factor model

When asked for "Want to CHANGE parameters (y/n), def=n"
	
	type: (return)


NOTE: for OS10.9.5 or Linux the programs should run, but for WINDOWS you may need to change the comment in orangeclass APP: 

        # self.mainloop() TO THE EXECUTABLE STATEMENT self.root.mainloop()
