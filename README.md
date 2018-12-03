# decisions-games-ai

This repository contains Jupyter Notebooks used for slides for a mini-course on decision and game theory for undergraduate students in artificial intelligence at Universiteit van Amsterdam.  

To follow along (on UNIX-based systems, but only minor modifications required for Windows):

1. Install Python 3.X via the Anaconda Distribution: https://www.anaconda.com/download

2. Make environment for the course:

	`conda create --name cgd`

3. Install packages:

	`conda install numpy jupyter matplotlib pytorch -c pytorch`

4. To view Jupyter Notebooks as slides:

	`conda install -c conda-forge rise`

5. Get the course materials from GitHub:

	`git clone https://github.com/shanest/decisions-games-ai.git`
	
	or download as a zip file using the green "Clone or Download" button above.  (Note that the slides will change over the duration of the course, so you will need to do this more than once.)

6. View:

	`cd decisions-games-ai`
  
	`jupyter notebook`
	
	Open the relevant file.  To view as slides, press `ALT+R` or the icon on the right of the toolbar in Jupyter.

## Other Useful Materials

* Brian Weatherson, "Lecture Notes on Decision Theory": http://brian.weatherson.org/DTBook-15.pdf
* Brian Weatherson, "Lecture Notes on Game Theory": http://brian.weatherson.org/StA-GameTheoryNotes.pdf
* Michael Resnik, _Choices_
* Martin Peterson, _An Introduction to Decision Theory_
* Ken Binmore, _Playing for Real_
* Shoham and Leyton-Brown, _Multiagent Systems: Algorithmic, Game-Theoretic, and Logical Foundations_.  Downloadable at: http://www.masfoundations.org
