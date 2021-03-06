+++
title = "Parse Condition: Symbolic Encoding of LL(1) Parsing"
date = 2018-10-23T00:00:00-04:00
draft = false

abstract = "In this work, we propose the notion of a Parse Condition—a logical condition that is satisfiable if and only if a given string w can be successfully parsed using a grammar G. Further, we propose an algorithm for building an SMT encoding of such parse conditions for LL(1) grammars and demonstrate its utility by building two applications over it: automated repair of syntax errors in Tiger programs and automated parser synthesis to automatically synthesize LL(1) parsers from examples. We implement our ideas into a tool, Cyclops, that is able to successfully repair 80% of our benchmarks (675 buggy Tiger programs), clocking an average of 30 seconds per repair and synthesize parsers for interesting languages from examples. Like verification conditions (encoding a program in logic) have found widespread applications in program analysis, we believe that Parse Conditions can serve as a foundation for interesting applications in syntax analysis."
publication = "_22nd International Conference on Logic for Programming, Artificial Intelligence and Reasoning (LPAR)_"
authors = ["admin", "Palak Agarwal", "Saket Jhunjhunwala", "Subhajit Roy"]
url_pdf = "files/papers/lpar2018.pdf"

tags = ["SMT", "parsing", "LL1", "constraint solving"]
categories = ["parsing"]

+++


