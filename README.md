# Introduction to AI-Native Vector Databases
This is the repository for the LinkedIn Learning course `Introduction to AI-Native Vector Databases`. The full course is available from [LinkedIn Learning][lil-course-url].

![course-name-alt-text][lil-thumbnail-url] 

The primary purpose of vector databases is to provide fast and accurate similarity search or nearest neighbor search capabilities. The integration of AI techniques in vector databases enhances their capabilities, improves search accuracy, optimizes performance, and enables more intelligent and efficient management of high-dimensional data. In this course, Zain Hasan introduces this foundational technology—which is already being used in industries like ecommerce, social media, and more. Zain covers everything from foundational concepts around AI-first vector databases to hands-on coding labs for question answering using LLMs.


## Instructions
This repository has branches for each of the videos in the course. You can use the branch pop up menu in github to switch to a specific branch and take a look at the course at that stage, or you can add `/tree/BRANCH_NAME` to the URL to go to the branch you want to access.

## Branches
The branches are structured to correspond to the videos in the course. The naming convention is `CHAPTER#_MOVIE#`. As an example, the branch named `02_03` corresponds to the second chapter and the third video in that chapter. 
Some branches will have a beginning and an end state. These are marked with the letters `b` for "beginning" and `e` for "end". The `b` branch contains the code as it is at the beginning of the movie. The `e` branch contains the code as it is at the end of the movie. The `main` branch holds the final state of the code when in the course.

When switching from one exercise files branch to the next after making changes to the files, you may get a message like this:

    error: Your local changes to the following files would be overwritten by checkout:        [files]
    Please commit your changes or stash them before you switch branches.
    Aborting

To resolve this issue:
	
    Add changes to git using this command: git add .
	Commit changes using this command: git commit -m "some message"

## Installing
1. To use these exercise files, you must have the following installed:
	- [Weaviate Python Client](https://pypi.org/project/weaviate-client/)
    - [Anaconda](https://www.anaconda.com/)
    - [Jupyter](https://jupyter.org/)
    - [Docker](https://www.docker.com/)
2. Clone this repository into your local machine using the terminal (Mac), CMD (Windows), or a GUI tool like SourceTree.
3. To setup the above tools please refer to the instructions below.

- [Anaconda](https://www.anaconda.com/) can be downloaded and installed using this [link](https://www.anaconda.com/download). We will only be using the base environment. This will give you packages like numpy, matplotlib and jupyter which we will be using as the main coding environment for this course.

- [Jupyter](https://jupyter.org/) will come pre-installed in the base environment of Anaconda and does not to be seperately installed. You can start up jupyter by going into a terminal and typing `jupyter notebook`. This will launch jupyter notebooks in your browser, if it doesn't automatically launch copy and paste the URL provided in the terminal into your browser.

- [Weaviate Python Client](https://pypi.org/project/weaviate-client/) can be installed after you have docker by using the command `python -m pip install weaviate-client`. Following this you should be able to run the command `import weaviate` in a newly launched jupyter notebook.

- [Docker](https://www.docker.com/) will be used to create containers in which our vector database(Weaviate) will run. We recommend that you setup [Docker Desktop](https://www.docker.com/get-started/). Once Docker Desktop is setup, for certain videos and challenges you will be able to spin up docker containers using the provided `docker-compose.yml` files by opening a terminal where this file is located and typing `docker compose up`. Once finished with using the container you can bring it down simply by going into the same terminal and pressing `Ctrl + C`


### Instructor

**Zain Hasan**

_Data Scientist, Lecturer_   



[lil-course-url]: https://www.linkedin.com/learning/introduction-to-ai-native-vector-databases
[lil-thumbnail-url]: https://media.licdn.com/dms/image/D4D0DAQFc3phQ64lAsA/learning-public-crop_675_1200/0/1702341179674?e=2147483647&v=beta&t=73HFdwWEvt0yxV3hHg8Rsx7MlXIXdkMde20UHxs6Qcg

