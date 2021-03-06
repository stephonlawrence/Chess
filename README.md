# Chess

**This project is still under development**

This is a *mostly* functional game of chess written in java. The project is being
developed under the *Model-View-Controller (MVC)* design pattern. There are also
some uses of the *factory* design pattern. The goal is to hopefully use machine learning algorithms to 
play chess instead of using the traditional brute force method 
of searching a decision tree. As of now, supervised learning by artificial neural
networks seems to be the way of attacking this problem.

### To Be Implemented:
* ~~castling~~
* ~~pawn on pawn en passante~~
* players, ~~clocks~~, movelogs
* pawn promotion
* player turns
* a brute force engine
* a more aesthetic gui
* ability to play online
* a machine learning algorithm

## Goals
> The primary goal of this project is to create well organized and well documented software.


### Cloning

To import this chess software, execute the following line of code in your command console

```
 git clone https://github.com/haxdds/Chess.git
```

## Running

To run the current version of this chess software, execute the following lines of code
in your command console in the .../Chess/src/chess directory:
```
 javac Test.java
 java Test
```
This should cause the chess gui to pop up. 

### If using bash

in your terminal run

`make`

from this projects root directory.
then it should be compiled then the gui should show up.

If your on windows checkout:

https://gist.github.com/evanwill/0207876c3243bbb6863e65ec5dc3f058

to install make for git bash.

## Authors

* **Rahul Chowdhury** - [haxdds](https://github.com/haxdds)



