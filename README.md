# CSCI340 Inquiry Based Final Project

## Goals
This project has the following goals:

* Student sets out to answer a question about a topic related to Operating Systems. 
* Students devise a way to test and/or gain understanding about the question they are trying to ask through a hands on implementation of the concept.
	* Should come up with a procedure or method for testing the effectiveness of known solutions or their solutions.
* Students write up a document with their findings


## Sample Questions
Recommended questions, you are welcome to propose a different one but these are pre-approved, if you want to answer a different question you need to get approval so email me with your question and how you plan to test it:

* How does the performance of threads in C compare to one of the following languages?
	* Python (multi-process)
	* Rust
	* Go
	* Java
	* Other (get approval)
* What file system performs best for small files on Linux? Or alternatively what about for large files? (using dd for benchmarks, don't use IOzone or bonnie++) 
	* Consider at least 5 of the following filesystems:
		* ext4
		* ext2
		* xfs
		* FAT32
		* ZFS
		* BTRFS
		* NTFS (might be CIFS under linux)
* How does the performance of differing IPC mechanisms compare in C to one of the following languages?
	* Python
	* Rust
	* Go
	* Java
	* Other (get approval)
* As an Extra Credit question: How much does Docker virtualization impact the performance of threads compared to a native system in one of the following languages?
	* C
	* Python
	* Rust
	* Go
	* Java
	* Other (get approval)

## Evaluation

Your project will be graded based on the following components.

* Paper - You will submit a short paper describing the following:
	* What is your question
	* Your experimental setup (machine, etc)
		* Are there any side effects or artifacts related to your experimental setup that might impact your results?
	* How you ran your tests to answer your question
	* Test results:
		* How accurate are they? 
			* Make sure you run enough tests that your results are accurate enough. 
		* Do you have variation in your test code? 
			* DNS threads, matrix multiplication threads, other threaded applications?
			* Variations in block and file sizes?
			* Variations in size of data sent via IPC?
	* Your conclusion/answer to the question
	* What you learned from answering the question
* Code - You must submit the code for your project along with the paper submission. 

## Project Submission

You will submit a tar.gz to INGInious system, the tar.gz should have the following:

* PDF of your paper that discusses your results, analysis, motivation, conclusions, etc. 
* All of the code for you used for your project. 
	* Alternatively you can add me to a repository with all your code for the project, and just put a README in the tar.gz with the link to this repository. 
	
## Extra Credit

You can get an additional 10 points of extra credit for every additional question you answer. 
