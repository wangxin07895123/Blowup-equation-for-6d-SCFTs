Format:

degreelistListByTotalDegree[d]: List of degree lists which have non-vanishing refined BPS invariants.

dlist4[d_1, d_2, ...] : List of BPS contents where the BPS contents are stored in the format {2*j_l,2*j_r,(-1)^(2*j_l+2*j_r) N^d_{j_l,j_r}}, here j_l, j_r are the left and right spin of BPS particles, N^d_{j_l,j_r} is the BPS invariant with spin (j_l,j_r) and degree d.

How to read in Mathematica:
1. Get["filename"];
2. Get the degrees by loading degreelistListByTotalDegree[d].
3. dlist4[Sequence@@{d_1,d_2,...}]