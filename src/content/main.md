+++
title = "A Pragmatic Introduction to Secure Multi-Party Computation"
type = "index"
+++

# A Pragmatic Introduction to<br> Secure Multi-Party Computation

### [David Evans](//www.cs.virginia.edu/evans), [Vladimir Kolesnikov](https://www.scs.gatech.edu/people/vladimir-kolesnikov) and [Mike Rosulek](http://web.engr.oregonstate.edu/~rosulekm/)

<a href="https://www.nowpublishers.com/article/Details/SEC-019"><img src="/images/nowcover.jpg" align="right" width="100" style="padding-left: 20px"></a>
Secure multi-party computation (MPC) has evolved from a theoretical
curiosity in the 1980s to a tool for building real systems today. Over
the past decade, MPC has been one of the most active research areas in
both theoretical and applied cryptography. This book introduces
several important MPC protocols, and surveys methods for improving the
efficiency of privacy-preserving applications built using MPC. Besides
giving a broad overview of the field and the insights of the main
constructions, we overview the most currently active areas of MPC
research and aim to give readers insights into what problems are
practically solvable using MPC today and how different threat models
and assumptions impact the practicality of different approaches.

NOW Publishers, December 2018: [Publishers Page](https://www.nowpublishers.com/article/Details/SEC-019)

[**Full Text (PDF)**](/docs/pragmaticmpc.pdf) (Last update: 11 June 2022; [Errata](/docs/errata.pdf)) (scroll down for links to PDFs of individual chapters)

## News

**May 2022:** Lúcás Meier includes Pragmatic MPC in his list of [_Some Cryptography Books I Like_](https://cronokirby.com/posts/2022/05/some-cryptography-books-i-like/):

<blockquote><em> I read this one quite recently, and I’d highly
recommend it. ... I highly recommend this book if you’re interested in
MPC. It’s also a short read, so if you’re not interested in MPC, you
should still give it a look, and you might change that.  </em>
</blockquote>

<a href="https://item.jd.com/13302742.html">
<img src="/images/chinese-cover.png" width=30% align="right"></a>

**June 2021:** A Chinese translation of the book is now available from China Machine
Press!

Thanks to Weiran Liu and Sengchao Ding for all the work they
did on the translation (which also substantially improve the English
version with all the [mistakes they
found](http://securecomputation.org/docs/errata.pdf) in their careful
translation work).

To order: [JD.com book link](https://item.jd.com/13302742.html)

**January 2021:** For a quick introduction to MPC, read Yehuda Lindell's article: [_Secure Multiparty Computation_](https://dl.acm.org/doi/pdf/10.1145/3387108) (Communications of the ACM, January 2021). There's even a movie:

<center>
<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/Li2QJ8yImoY" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</center>


## Contents

<div class="row">
    <div class="column small-10 medium-5">

<div class="toc_chap">1 Introduction <span class="pdf">[<a href="/docs/ch1-introduction.pdf">PDF</a>]</span></div>
<div class="toc_sec">1.1 Outsourced Computation</div>
<div class="toc_sec">1.2 Multi-Party Computation</div> 
<div class="toc_sec">1.3 MPC Applications</div>
<div class="toc_sec">1.4 Overview</div>

<div class="toc_chap">2 Defining Multi-Party Computation <span class="pdf">[<a href="/docs/ch2-definingmpc.pdf">PDF</a>]</span></div>
<div class="toc_sec">2.1 Notations and Conventions </div>
<div class="toc_sec">2.2 Basic Primitives </div>
<div class="toc_sec">2.3 Security of Multi-Party Computation </div>
<div class="toc_sec">2.4 Specific Functionalities of Interest </div>
<div class="toc_sec">2.5 Further Reading </div>

<div class="toc_chap">3 Fundamental MPC Protocols <span class="pdf">[<a href="/docs/ch3-fundamentalprotocols.pdf">PDF</a>]</span></div>
<div class="toc_sec">3.1 Yao's Garbled Circuits Protocol</div>
<div class="toc_sec">3.2 Goldreich-Micali-Wigderson (GMW) Protocol</div>
<div class="toc_sec">3.3 BGW protocol</div>
<div class="toc_sec">3.4 MPC From Preprocessed Multiplication Triples</div>
<div class="toc_sec">3.5 Constant-Round Multi-Party Computation: BMR</div>
<div class="toc_sec">3.6 Information-Theoretic Garbled Circuits</div>
<div class="toc_sec">3.7 Oblivious Transfer</div>
<div class="toc_sec">3.8 Custom Protocols</div>
<div class="toc_sec">3.9 Further Reading</div>

<div class="toc_chap">4 Implementation Techniques <span class="pdf">[<a href="/docs/ch4-implementationtechniques.pdf">PDF</a>]</span></div>
<div class="toc_sec">4.1 Less Expensive Garbling</div>
<div class="toc_sec">4.2 Optimizing Circuits</div>
<div class="toc_sec">4.3 Protocol Execution</div>
<div class="toc_sec">4.4 Programming Tools</div>
<div class="toc_sec">4.5 Further Reading</div>

</div>
<div class="column small-10 medium-5">

<div class="toc_chap">5 Oblivious Data Structures <span class="pdf">[<a href="/docs/ch5-obliviousdata.pdf">PDF</a>]</span></div>
<div class="toc_sec">5.1 Tailored Oblivious Data Structures</div>
<div class="toc_sec">5.2 RAM-Based MPC</div>
<div class="toc_sec">5.3 Tree-Based RAM-MPC</div>
<div class="toc_sec">5.4 Square-Root RAM-MPC</div>
<div class="toc_sec">5.5 Floram</div>
<div class="toc_sec">5.6 Further Reading</div>

<div class="toc_chap">6 Malicious Security <span class="pdf">[<a href="/docs/ch6-malicioussecurity.pdf">PDF</a>]</span></div>
<div class="toc_sec">6.1 Cut-and-Choose</div>
<div class="toc_sec">6.2 Input Recovery Technique</div>
<div class="toc_sec">6.3 Batched Cut-and-Choose</div>
<div class="toc_sec">6.4 Gate-level Cut-and-Choose: LEGO</div>
<div class="toc_sec">6.5 Zero-Knowledge Proofs</div>
<div class="toc_sec">6.6 Authenticated Secret Sharing: BDOZ and SPDZ</div>
<div class="toc_sec">6.7 Authenticated Garbling</div>
<div class="toc_sec">6.8 Further Reading</div>

<div class="toc_chap">7 Alternative Threat Models <span class="pdf">[<a href="/docs/ch7-alternativethreatmodels.pdf">PDF</a>]</span></div>
<div class="toc_sec">7.1 Honest Majority</div>
<div class="toc_sec">7.2 Asymmetric Trust</div>
<div class="toc_sec">7.3 Covert Security</div>
<div class="toc_sec">7.4 Publicly Verifiable Covert (PVC) Security</div>
<div class="toc_sec">7.5 Reducing Communication in Cut-and-Choose Protocols</div>
<div class="toc_sec">7.6 Trading Off Leakage for Efficiency</div>
<div class="toc_sec">7.7 Further Reading</div>

<div class="toc_chap">8 Conclusion <span class="pdf">[<a href="/docs/ch8-conclusion.pdf">PDF</a>]</span></div>

<div class="toc_chap">References <span class="pdf">[<a href="/docs/references.pdf">PDF</a>]</span></div>
</div>
</div>

## Adoptions

We are aware of parts of this book being used in the following courses:


Jonas Spenger has notes from an MPC study group that follows some parts of the book including [Yao's Garbled Circuits](https://jonasspenger.github.io/blog/yaos-garbled-circuits), [BGW Protocol and Beaver Triples](https://jonasspenger.github.io/blog/bgw-protocol-and-beaver-triples), [Malicious BGW and SPDZ](https://jonasspenger.github.io/blog/spdz-malicious-bgw-mpc-protocol), [GMW Protocol](https://jonasspenger.github.io/blog/gmw-protocol), [Oblivious Transfer Extension](https://jonasspenger.github.io/blog/oblivious-transfer-extension), and more. 

Boston University CS 791/JD 673 / UC Berkeley CS 294, [Law for Algorithms](https://docs.google.com/document/d/e/2PACX-1vTuiFeRgaCFiHS04PmPFNgh4BOSlW1_SBhNEtaxL5DSHzmFxNsWD0-_yffhnZn5y65QiUqnKuMOJZ4u/pub)  
Ran Canetti (BU CS), Stacey Dogan (BU Law), Aloni Cohen (BU CS & Law), Shafi Goldwasser (UC Berkeley CS), Frank Partnoy (UC Berkeley Law)

Brown CS 2950, [Topics in Applied Cryptography: Crypto for Social Good](http://cs.brown.edu/~seny/2950v/)  
Seny Kamara

George Washington University GWU CSIC 3907-83/6907-81, [Advanced Cryptography](https://www2.seas.gwu.edu/~arkady/teaching/advanced_crypto/s20/)  
Arkady Yerukhimovich

Stanford  CS 355, [Topics in Cryptography](https://crypto.stanford.edu/cs355/20sp/schedule/)  
Saba Eskandarian, Dima Kogan, and Florian Tramèr

University of Bern and Swiss Joint Master in Computer Science, 
[Cryptographic Protocols](https://mcs.unibnf.ch/courses/cryptographic-protocols/)/[Cryptographic Protocols](https://crypto.unibe.ch/courses/)  
Christian Cachin
  
University of Maryland, [CMSC 858T &mdash; Introduction to Secure Distributed Computation](http://www.cs.umd.edu/~jkatz/gradcrypto2/s21/)  
Jonathan Katz

University of Missouri, CMP_SC 8001 &mdash; [Wei Jiang](http://faculty.missouri.edu/wjiang/) has shared slides he developed for his course following the book:

- [1. Introduction](/docs/jiang-slides/1-intro.pdf)
- [2. Defining SMC](/docs/jiang-slides/2-defining-smc.pdf)
- [3-1. Fundamental MPC Protocols](/docs/jiang-slides/3-1-fundamental-mpc.pdf)
- [3-2. Fundamental MPC Protocols](/docs/jiang-slides/3-2-fundamental-mpc.pdf)
- [3-3. Fundamental MPC Protocols](/docs/jiang-slides/3-3-fundamental-mpc.pdf)

University of Vermont, [UVM CS 295/395: Secure Distributed Computation](https://jnear.github.io/cs295-secure-computation/)  
Joe Near

##
#

If you know of other courses using the book, please [let me know](mailto:evans@virginia.edu).
