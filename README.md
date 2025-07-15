# Bring the CS61 Gitlet project back to life

I auditted the [su25](https://cs61bl.org/su25/) version of UC Berkeley's celebrated [CS61B](https://sp21.datastructur.es/).
There was an interesting project in some previous versions of the course, namely 
[Gitlet](https://sp21.datastructur.es/materials/proj/proj2/proj2),
which is not in this summer's curriculum. 
Nevertheless, I decided to try it out.  
This repository contains the cherry-picked project files, 
which I then make small adjustments, to so as to make the project layout the same as su25 material.
I also added a simple logger to the `Utils` class, so that one can more easily do print debugging themselves.

## Getting Started

To do the project for and by yourself
1. Read through the course project material. [\[su24 ver\]](https://cs61bl.org/su24/projects/gitlet/) [\[sp21 ver\]](https://sp21.datastructur.es/materials/proj/proj2/proj2)
2. [Clone](https://github.com/new?template_name=cs61bl-su24.gitlet&template_owner=Gravifer) using this repo as template.
3. Use [IntelliJ IDEA](https://www.jetbrains.com/idea/download/?:~:text=free%20to%20use-%2CIntelliJ%20IDEA%20Community%20Edition).
   The Community version is the one that is recommended for the course, be sure to scroll down the page to see it.  
   The project structure and test-running settings are defined with IDEA configuration files,
   so there would be more work if you use [Gradle](https://gradle.org) or [Maven](https://maven.apache.org/).
4. Pull the starter code from your new repository, and start coding!

-----

**Notes**
- If you want to audit this great course in whole as well, the official recommendation is to use the [sp21](https://sp21.datastructur.es/) version;
there is a publicly available autograder for that version only.
- Note that [the logger](https://github.com/Gravifer/cs61bl-su24.gitlet/blob/1270a3dd7597515d4b26cdd0aa44565010cf2eaa/gitlet/src/Utils.java#L270) I added in `Utils`, is considered a non-trivial field;
   I hacked `GitletTests` to make it work, so your code would fail the actual autograder used in the course at Berkeley.
   But this version of `GitletTest` does have better readability, which will make your life easier.
- To look at my work, see the [demo](https://github.com/Gravifer/cs61bl-su24.gitlet/tree/demo) branch.
  Make sure to check out these other awesome Gitlet implementations as well:
  - https://github.com/Abdelrhmansersawy/Gitlet
  - https://github.com/annetta-zheng/Gitlet
  - https://github.com/hrishikeshh/Gitlet
  - https://github.com/jacobakh/Gitlet
  - https://github.com/pichardo13/gitlet
 
Copyright information: 
  I make no claim to any intellectual property of CS61B and CS61BL staff, or other original authors. 
  I cannot provide a license for this repo, since I cannot be sure of the status of attribution.
