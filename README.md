# MLAgents16-Toolkit
version 16 of the MLAgents toolkit. Useable yo make Artificial Intelligence / Neural Network training and brains for Unity game objects



====================================================
How to setup to use MLAgents16 as of Oct 2022
====================================================

-- Visual Studio -----------------------------------
Install Visual Studio 2022 personal edition	(with support for Unity tools)
  
	Install Unity Tools for Visual Studio:
	- run visual studio installer
	- from your installed version > Modify 
	- check 'Game development with Unity'
	- install
	
	
	
-- Unity 2021 --------------------------------------
* Install Unity Hub (latest version)
* From Unity Hub, Install Unity 2021 (latest version)

	Ensure Unity calls Visual Studio for C# scripts:
	- run unity editor
	- Edit > Preferences > External Tools 
		External Script Editor = Microsoft Visual Studio 2022
		- Embedded Packages = yes
		- Local Packages = yes
		- press button "Regenerate project files"
			  
	  
	
-- Anaconda ----------------------------------------
* Download/Install Anaconda (latest version has python 3.9)

* Create MLAgents Environment
  Start Anaconda Prompt (base environment is default)
	(base) C:\...   
	(base) conda 		<--- to list all conda commands
	(base) conda create -n mlagents16 python=3.9
           The following NEW packages will be installed:
           Proceed ([y]/n)?  y  
	(base) conda activate mlagents19 
	(mlagents19) C:\...
	
	
	
-- MLAgent16 ----------------------------------------
* Download MLAgents from github
	(mlagents16) pip install -e ml-agents
	(mlagents16) pip install -e ml-agents-envs
	(mlagents16) pip install torch
* test:
	(mlagents16) mlagents-learn --help   	<--- this will show help
	(mlagents16) mlagents-learn 	
	result: should see unity ascii logo
	  	  
