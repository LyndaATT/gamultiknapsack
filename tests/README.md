<h1>GNAP Tests</h1>
Please run the bash scripts after cloning the repository. You may have to change the bash binary path in the scripts.<br>
<br><ul>
  <li>Run testjava.sh to test the java code</li>
  <li>Run testcpp.sh to test the C++ code</li>
</ul>
<br>
Please note that since the code is randomized, it will not find the optimum every time it is run (unless it is run for a very large number of iterations). The data.DAT file is the WEING1 instance. If the code gets stuck in a solution which is not the optimum for a very long time, please terminate it and re-run.
<br><br>
<pre>
The <b>weing</b> formatted files are available <a href="http://people.brunel.ac.uk/~mastjjb/jeb/orlib/files/mknap2.txt">here</a>.
The <b>orlib</b> formatted files are available <a href="http://people.brunel.ac.uk/~mastjjb/jeb/orlib/mknapinfo.html">here</a> (used by P.C.Chu and J.E.Beasley).

The orlib formatted files are available <a href="http://people.brunel.ac.uk/~mastjjb/jeb/orlib/files/">here</a> which are named mknapcb1.txt, mknapcb2.txt and so on.

Please note that these files contain multiple instances, so to run the algorithm, 
please use any <b>one</b> of the instances.

<b>The format of all files is described <a href="http://people.brunel.ac.uk/~mastjjb/jeb/orlib/mknapinfo.html">here</a>.</b>

The distributions of the files are quite different between orlib and weing. 
If the algorithm is stuck, please increase Constants.DIFF_TOLERANCE on line 31 of GeneticAlgorithm.java.
</pre>
<br>
<pre>
 //This is the WEING1.DAT data file plus some comments, that are NOT part of the problem instance.
 
 
 2 28 // 2 knapsacks, 28 objects
 1898 440 22507 270 14148 3100 4650 30800 615 4975
 1160 4225 510 11880 479 440 490 330 110 560
 24355 2885 11748 4550 750 3720 1950 10500 // 28 weights
 600 600 // 2 knapsack capacities
 45 0 85 150 65 95 30 0 170 0
 40 25 20 0 0 25 0 0 25 0
 165 0 85 0 0 0 0 100 // #1 constr.
 30 20 125 5 80 25 35 73 12 15
 15 40 5 10 10 12 10 9 0 20
 60 40 50 36 49 40 19 150 // #2 constr.
 
 141278 // optimum value
</pre>

(The comments are only for the purpose of explaining the format. Please remove all comments before running the algorithm)

