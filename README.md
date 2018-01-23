# POLYROOT


Ok, so I have this one finally done after being puzzled on how to make an effective algorithm for it. What this program does is essentially work like a smarter version of the equation solver that is on the calculator. I devised my own method of using newton's method and horner's method together to reduce any polynomial with real, integer coefficients to its roots. Unfortunately, I've only managed to calculate real, rational roots, as the calculations required for converging on a complex root is too demanding of the calculator, and would require excessive amounts of time to converge. One last note: the calculator has unavoidable rounding error that skews all roots calculated. They are accurate to .00001±.00005% of the original root. For example, 1.0000981 is essentially 1.

The text files allow for easy observation of the code with out the ti connect editor.
