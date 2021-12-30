+++
title = "About"
+++

## About Me

I am a cryptography analyst at [Trail of Bits](https://www.trailofbits.com/).
{{< figure class="avatar" src="/photo.jpeg">}}

Previously, I was an Invited Assistant Professor at the Department of Informatics of the Faculty of Sciences, University of Lisbon.

I have a PhD in Information Security from [IST](https://tecnico.ulisboa.pt/), Universidade de Lisboa. In my thesis, I studied conditions that allow the combination of satisfiability solvers, as well as probabilistic logics and their satisfiability procedures.


## Interests

I am interested in cryptography, vulnerability research, logic, automated reasoning and type theory.

I have played CTF's since 2014 with [STT](https://sectt.github.io/).


## Vulnerability Research
 - I participated in the [EU-FOSSA](https://joinup.ec.europa.eu/collection/eu-fossa-2) program and audited {{< link "PuTTY" "https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html" >}}, an SSH client. I found a critical vulnerability which allowed to MITM SSH sessions, and an out-of-bounds write during the RSA key exchange:
     - **DSA signature bypass allows to MITM SSH sessions**: More details [here](https://www.chiark.greenend.org.uk/~sgtatham/putty/wishlist/vuln-dss-verify.html).
     - [CVE-2019-9894](https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2019-9894): Integer overflow to OOB write during RSA key exchange. More details [here](https://www.chiark.greenend.org.uk/~sgtatham/putty/wishlist/vuln-rsa-kex-integer-overflow.html).




## Blogposts

(2021) {{< link "Disclosing Shamir’s Secret Sharing vulnerabilities and announcing ZKDocs" "https://blog.trailofbits.com/2021/12/21/disclosing-shamirs-secret-sharing-vulnerabilities-and-announcing-zkdocs/" >}}.

(2018) {{< link "GSoC 2018 Final: Debugging and Emulation Support for Cutter" "https://radareorg.github.io/blog/posts/cutter_debug/" >}}: how I implemented debugging in [Cutter](https://cutter.re/) for my Google Summer of Code.

## Publications

{{< references >}}

## Theses

- **[Combining Satisfiability Procedures and Probabilistic Satisfiability](/papers/phd_thesis.pdf)**, PhD in Information Security, 2018. Advised by [João Rasga](https://scholar.google.com/citations?user=teFGWr4AAAAJ&hl=en) @ IST, Universidade de Lisboa
- **[On Nelson-Oppen Techniques](papers/13-C-MScThesis.pdf)**, MSc in Mathematics and Applications, 2013. Advised by [João Rasga](https://scholar.google.com/citations?user=teFGWr4AAAAJ&hl=en) @ IST, Universidade de Lisboa.
- **[Gröbner Basis and Applications](/papers/bsc_thesis.pdf)**, BSc in Applied Mathematics and Computation, 2010. (in portuguese) Advised by Margarida Mendes Lopes @ IST.