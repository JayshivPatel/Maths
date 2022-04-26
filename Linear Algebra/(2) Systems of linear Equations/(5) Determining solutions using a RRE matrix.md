For Ax = b with A in RRE form there are three cases:

- $A = I_n$ and so $x_n = b_n \forall n$
- $A = I_n$ followed by 0 rows where we have $0 = b_n+1,...,0 = b_n+k$
	- If any of the {$b_n...b_k$} are non-zero then the system has no solutions and the system is inconsistent.
	- If they are all 0 then the system has a unique solution
- Some columns of A do not contain a leading 1 but there are no zero-rows, then each column without a leading 1 has a free variable which you can set to any value. This is an ==undetermined== system with infinite solution