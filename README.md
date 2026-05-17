<h1>SPHINCS+ Post-Quantum Cryptography Review</h1>

<h2>Scientific Review Paper on Stateless Hash-Based Post-Quantum Signatures</h2>

<p>
  This repository contains a scientific review paper I worked on with my teammates
  as part of an academic cryptography and cybersecurity assignment. The paper focuses
  on <strong>SPHINCS+</strong>, a stateless hash-based post-quantum digital signature
  algorithm designed to resist attacks from future quantum computers.
</p>

<hr>

<h2>📘 About The Paper</h2>

<p>
  With the advancement of quantum computing, traditional public-key cryptographic
  systems such as RSA, ECC, and discrete logarithm-based systems may eventually become
  vulnerable to quantum attacks. In this paper, we reviewed SPHINCS+ as a
  post-quantum signature scheme that relies on cryptographic hash functions instead
  of algebraic assumptions.
</p>

<p>
  The review explains the main components of SPHINCS+, its security properties,
  performance trade-offs, parameter sets, and improvements over the original SPHINCS
  algorithm.
</p>

<hr>

<h2>🔬 Topics Covered</h2>

<h3>SPHINCS+ Components</h3>

<ul>
  <li>FORS (Forest of Random Subsets)</li>
  <li>WOTS+ (Winternitz One-Time Signature Plus)</li>
  <li>XMSS Trees</li>
  <li>Hypertree Structures</li>
  <li>SPHINCS+ Addressing Scheme</li>
</ul>

<h3>Security Concepts</h3>

<ul>
  <li>Post-Quantum Cryptography</li>
  <li>Quantum-resistant digital signatures</li>
  <li>Multi-target attack protection</li>
  <li>Stateless cryptographic design</li>
  <li>Hash-based security assumptions</li>
</ul>

<h3>Performance Analysis</h3>

<ul>
  <li>Signature size</li>
  <li>Signing speed</li>
  <li>Verification efficiency</li>
  <li>Security parameter optimization</li>
  <li>Trade-offs between speed, size, and security</li>
</ul>

<hr>

<h2>🛠 Technologies & Concepts</h2>

<ul>
  <li>Post-Quantum Cryptography</li>
  <li>Hash-Based Cryptography</li>
  <li>Digital Signatures</li>
  <li>Merkle Trees</li>
  <li>SHA-256</li>
  <li>SHAKE256</li>
  <li>Haraka</li>
  <li>XMSS</li>
  <li>WOTS+</li>
</ul>

<hr>

<h2>📂 Repository Structure</h2>

<pre>
SPHINCS-PostQuantum-Review/
│
├── README.md
├── paper/
│   └── SPHINCS_Plus_Review_Paper.pdf
├── images/
│   ├── sphincs-diagram.png
│   ├── hypertree-structure.png
│   └── parameter-analysis.png
├── docs/
│   ├── security-analysis.md
│   ├── performance-analysis.md
│   └── references.md
└── presentation/
    └── SPHINCS_Presentation.pptx
</pre>

<hr>

<h2>🚀 What I Learned</h2>

<ul>
  <li>How quantum computing could affect current cryptographic systems</li>
  <li>How post-quantum digital signature schemes are designed</li>
  <li>The role of hash functions in long-term cryptographic security</li>
  <li>How SPHINCS+ uses FORS, WOTS+, XMSS, and hypertrees</li>
  <li>The trade-offs between performance, signature size, and security</li>
  <li>Why stateless designs are important in hash-based signature schemes</li>
</ul>

<hr>

<h2>📊 Key Takeaways</h2>

<ul>
  <li>SPHINCS+ provides strong resistance against quantum attacks</li>
  <li>Its security is based on well-studied cryptographic hash functions</li>
  <li>It improves on the original SPHINCS algorithm</li>
  <li>It is not the fastest or smallest signature scheme, but it is conservative and secure</li>
  <li>Different parameter sets allow users to balance security, speed, and signature size</li>
</ul>

<hr>

<h2>📄 Paper Information</h2>

<table>
  <tr>
    <td><strong>Title</strong></td>
    <td>SPHINCS+: A Stateless Hash-Based Post-Quantum Cryptographic Algorithm</td>
  </tr>
  <tr>
    <td><strong>Type</strong></td>
    <td>Scientific Review Paper</td>
  </tr>
  <tr>
    <td><strong>Topic</strong></td>
    <td>Post-Quantum Cryptography</td>
  </tr>
  <tr>
    <td><strong>Focus</strong></td>
    <td>Hash-Based Digital Signatures</td>
  </tr>
  <tr>
    <td><strong>Course Area</strong></td>
    <td>Cryptography / Cybersecurity</td>
  </tr>
</table>

<hr>

<h2>👥 Contributors</h2>

<ul>
  <li>Tiemar Berhe</li>
  <li>Xhelion Dedelli</li>
  <li>Anna Ivanytska</li>
  <li>Assan Jallow</li>
  <li>Sarah Sumrall</li>
</ul>

<hr>

<h2>🎯 Conclusion</h2>

<p>
  This project gave me practical exposure to post-quantum cryptography research and
  helped me better understand how cryptographic systems are evolving to address future
  quantum computing threats. Through this review, I learned how SPHINCS+ uses
  hash-based structures to provide strong digital signature security without relying
  on traditional public-key assumptions.
</p>

<p>
  Overall, this assignment helped strengthen my understanding of modern cryptography,
  post-quantum security, and the importance of preparing cybersecurity systems for
  future quantum-based attacks.
</p>

<hr>

<h2>🏷 Tags</h2>

<p>
  <code>post-quantum-cryptography</code>
  <code>sphincs-plus</code>
  <code>cryptography</code>
  <code>hash-based-signatures</code>
  <code>pqc</code>
  <code>digital-signatures</code>
  <code>cybersecurity</code>
  <code>quantum-resistant</code>
  <code>xmss</code>
  <code>wots-plus</code>
</p>
