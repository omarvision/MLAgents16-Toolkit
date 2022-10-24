# MLAgents16-Toolkit
version 16 of the MLAgents toolkit. Useable yo make Artificial Intelligence / Neural Network training and brains for Unity game objects


====================================================
How to setup to use MLAgents as of Oct 2022
====================================================

-- Visual Studio Install ----------------------------------
Install Visual Studio 2022 personal edition	(with support for Unity tools)  
	Install Unity Tools for Visual Studio:
	- run visual studio installer
	- from your installed version > Modify 
	- check 'Game development with Unity'
	- install
	
	
-- Unity 2021 Install -------------------------------------
* Install Unity Hub (latest version)
* From Unity Hub, Install Unity 2021 (latest version)
	Ensure Unity calls Visual Studio for C# scripts:
	- run unity editor
	- Edit > Preferences > External Tools 
		External Script Editor = Microsoft Visual Studio 2022
		- Embedded Packages = yes
		- Local Packages = yes
		- press button "Regenerate project files"			  
	  
	
-- Anaconda Install ---------------------------------------
* Download/Install Anaconda (latest version has python 3.9)
* Create MLAgents Environment
  Start Anaconda Prompt (base environment is default)
	(base) C:\...   
	(base) conda 			<--- to list all conda commands
	(base) conda create -n mlagents python=3.9
           The following NEW packages will be installed:
           Proceed ([y]/n)?  y  
	(base) conda activate mlagents
	(mlagents) C:\...	
	
	
-- MLAgent Toolkit Install --------------------------------
Type these commands in the Anaconda Prompt / MLAgents environment window / press enter
* Install mlagents fro PyPi	
	pip3 install mlagents==0.16.1	<--- will install the mlagents toolkit to your local computer

* test:
	mlagents-learn --help 		<--- shows help. proof install of toolkit successful
	mlagents-learn 			<--- starts the toolkit running. shows unity ascii logo on success

	

	  	  
