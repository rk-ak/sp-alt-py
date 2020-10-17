# sp-alt-py
How to speed up the sharepoint connection in Alteryx workflow using Python script.

Requirement:
	To extract data from sharepoint list in Alteryx we have SP List connector tool. However, this connection is slow and mostly gets disconnected while extracting the data from a sharepoint list. Few options can be explored to resolve this issue and to speed up this data extraction.
 One of the options available was to use an existing excel macro file which connects to the sharepoint list and extracts the data. Another option was to use Python script within Alteryx workflow. Both these options resulted in similar performance, faster data extraction time and no disconnections.
	Here, we will see only the second option, on how to use basic Python script within Alteryx workflow to speed up sharepoint list data extraction.

Solution:
	There are two ways to use python script within Alteryx. If we have Alteryx version 2018.3 and above, we can use “Python” tool directly within Alteryx to run python scripts. For earlier versions of Alteryx, we can use “Run Command” tool to call the Python program to run python scripts. For older version of Alteryx, so can use the second approach. However, its applicable for latest versions of Alteryx as well. Additionally, for this to work we should have basic Python modules (Anaconda Python 3 is recommended) already installed.

	Alteryx workflow steps and python script is provided in-detail in a seperate file.
