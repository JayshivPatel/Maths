Using composition and matrix multiplication, we can change basis over a linear map f : U -> V with bases B, B' for U and C, C' for V

Let:
	M = $_{C}[f]_B$
	N =  $_{C'}[f]_{B'}$
	Q = $_B[P]_{B'}$  (Change of Basis with identity)
	R = $_{C'}[P]_C$ (Change of Basis with identity)


Since $T_N = F^{-1}_C \circ F_{B'} = (F_{C'}^{-1} \circ F_C) \circ (F^{-1}_c \circ f \circ F_B) \circ (F^{-1}_B \circ F_{B'})$
But 
$(F_{C'}^{-1} \circ F_C)$  = $T_R$ 
$(F^{-1}_B \circ F_{B'}) = T_Q$
So $T_N = T_R \circ T_M \circ T_Q$
