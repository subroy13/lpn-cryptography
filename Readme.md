# Learning Parity with Noise (LPN)

This is a reading project I did in my second year during B.Stat. at Indian Statistical Institute, Kolkata.


## Abstract

The Learning Parity with Noise (LPN) problem is special case of Learning with Errors (LWE) problem that has recently been studied in the world of cryptography due to its hardness assumptions. It is believed that the LPN problem is `NP-hard' and is resistant to quantum computers. Also, due to its simplicity, it is a good candidate to implement in light-weight devices.
Till today, the best known algorithm to solve LPN problem is due to Blum, Kalai and Wasserman, called BKW algorithm. However, Levieil and Fouque has provided two improved version of that called LF1 and LF2. In IACR-EUROCRYPT 2016, a general version of LF1 and LF2 is proposed called LF(k) due to Zhang, Jiao and Wang. In this paper, the complexity of LF(k) is deeply analyzed. Finally, a method for solving LPN using Hadamard code (LFHC) has been proposed. A heuristic complexity result is also given for LF-HC. Although LF-HC is not better than subsequent LF(k) in terms of query complexity, it may perform better in terms of memory and time complexity. This gives an incentive to use LF-HC in practical problems.