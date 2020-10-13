An example of a test call:
greedy -f ../Instances/preprocessed instances/MinArea/min-100-1_D1.txt -alg 0 -greedy 3 -w_type 3 -partial

-f: path to instance file;

-alg: type of algorithm:
      0: pure Greedy
      2: Greedy + CPLEX

-greedy: type of the greedy method
         0: existing
         3: novel

-partial: ( partial * n )- solution of a greedy will be 
          included into CPLEX 
          if partial == 0, then run pure CPLEX model 
 
w_type: type of weight involved into benchmarks 
        0: point-based related weights
        1: topologically-based related weights
  


