# Solving-a-Jigsaw-Puzzle
Current personal project.

Final goal: write a program which can intake pictures of (individual?) pieces of a puzzle, then put them together.

Current thoughts:
* Project may be best written in MATLAB or Python for ease of mathematical functions
* Biggest issue will be making an algorithm that does not just compare every side of every piece to every other side of every other piece
  * Could group pieces based on color around the puzzle locks?
  * Could divide a piece into its four edges, then store the edges separately to compare among only those that would fit?
    * e.g. only compare those sides with external locks against those with internal locks
* A measuring device in the picture may be helpful
* Will need a way to determine differences between locks
  * Could measure distance from edge boundary to lock boundary?
  * Could figure out a way to determine how circular or noncircular the locks are?
