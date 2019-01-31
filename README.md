# intro-to-tensorflow

This notebook was made by me and was used as a resource to help members of the HandsOn Data Science Meetup Group (Malmo, Sweden) learn 
the basics of using the TenorFlow framework. This notebook provides knowledge needed to understand and write simple TensorFlow code in 
Python. This notebook does NOT cover deep learning. The techniques chosen for this notebook do not necessarily, and most likely, 
will NOT transer well to other problems. There are many different methods and approaches that could have been used to solve the 
simple problem of this notebook and the methods chosen for this notebook are not necessarily the best either; they were chosen to 
simplify the content. Therefore, try not to become too engulfed in all the details of this notebook and instead 
just try to get the overall picture of what's going on.

Content:

1. Computational Graphs
2. Tensors
    - variables
    - constants
    - placeholders
    - performing operations
    
3. Initialize variables + run session
4. Cost function, optimizer, and forward and backward propagation
5. Excercise: Solving a Linear Regression Model


Bonus: TensorBoard


* I undid pushed commits. 
Vib2006's answer was the only one that worked for me https://stackoverflow.com/questions/22682870/git-undo-pushed-commits. Revert did not work.
This moved the local head to the commit and cleans all the commits after it.
git log --oneline --decorate --graph
git reset --hard <commit id here>
git clean -f -d
This updates all the indexes and shows what's behind compared to the remote branch
git fetch --all
This pushes forcefully with the "+" in front of the branch to the remote
git push -u origin +<branch here>