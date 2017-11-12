
  _ | 0 | 1 | 2 | 3 | 4 | 5 | 6 | 7
----|---|---|---|---|---|---|---|---
  0 | 0 | 0 | 2 | 2 | 3 | 3 | 3 | 3 
  1 | 0 | 0 | 2 | 2 | 3 | 3 | 3 | 3 
  2 | 2 | 2 | 0 | 0 | 3 | 3 | 3 | 3 
  3 | 2 | 2 | 0 | 0 | 3 | 3 | 3 | 3 
  4 | 3 | 3 | 3 | 3 | 0 | 0 | 3 | 3 
  5 | 3 | 3 | 3 | 3 | 0 | 0 | 3 | 3 
  6 | 3 | 3 | 3 | 3 | 3 | 3 | 0 | 0 
  7 | 3 | 3 | 3 | 3 | 3 | 3 | 0 | 0 

  _ | 0 | 1 | 2 | 3 | 4 | 5 | 6 | 7
----|---|---|---|---|---|---|---|---
  0 | 1 | 1 | 3 | 3 | 4 | 4 | 4 | 4 
  1 | 1 | 1 | 3 | 3 | 4 | 4 | 4 | 4 
  2 | 3 | 3 | 1 | 1 | 4 | 4 | 4 | 4 
  3 | 3 | 3 | 1 | 1 | 4 | 4 | 4 | 4 
  4 | 4 | 4 | 4 | 4 | 1 | 1 | 4 | 4 
  5 | 4 | 4 | 4 | 4 | 1 | 1 | 4 | 4 
  6 | 4 | 4 | 4 | 4 | 4 | 4 | 1 | 1 
  7 | 4 | 4 | 4 | 4 | 4 | 4 | 1 | 1 


  Part | Topo                   | B<sub>C</sub> | b (bits/cycle) | γ<sub>max</sub> | Θ<sub>term</sub> (bits/cycle)
  -----|------------------------|---------------|----------------|-----------------|-----------------------------
  1.A  | Baseline Tree Topology | 2             | 32             | 2               | 16                        
  1.B  | Fat-Tree Topology      | 8             | 32             | 0.5             | 32                        
  
  Part | Topo                   | H<sub>D</sub>   | H<sub>r</sub>          | t<sub>r</sub> (cycles) | H<sub>c</sub> | t<sub>c</sub> | L/b (cycles) | t<sub>0</sub> (cycles)
  -----|------------------------|-----------------|------------------------|------------------------|---------------|---------------|--------------|-----------------------
  1.A  | Baseline Tree Topology | 4               | 5.625                  | 2                      | 2.125         | 1             | 3            | 16.375
  1.B  | Fat-Tree Topology      | 4               | 5.625                  | 3.67                   | 2.125         | 1             | 3            | 25.75