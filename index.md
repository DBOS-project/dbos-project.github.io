## DBOS
The goal of DBOS--the DBMS-oriented Operating System--is to build a completely new operating system (OS) stack for distributed systems.
Currently, distributed systems are built on many instances of a single-node OS like Linux with entirely separate cluster schedulers, distributed file systems, and network managers.
We argue that we should instead use a distributed transactional DBMS as the basis for a scalable cluster OS.
We have shown that such a database OS can do scheduling, file management, and inter-process communication with competitive performance to existing systems. 
It can additionally provide significantly better analytics and dramatically reduce code complexity by building core OS services from standard database queries,
while implementing low-latency transactions and high availability only once.
We are currently working on building a complete end-to-end prototype of DBOS.

The DBOS project includes members from MIT, Stanford, CMU, Google, and VMWare.

## Publications
- [DBOS: A Proposal for a Data-Centric Operating System](https://arxiv.org/abs/2007.11112) (arXiv)
- [Data Governance in a Database Operating System (DBOS)](https://link.springer.com/chapter/10.1007/978-3-030-93663-1_4) (Poly'21, co-located with VLDB 2021)
- [DBOS: A DBMS-Oriented Operating System](https://vldb.org/pvldb/vol15/p21-skiadopoulos.pdf) (VLDB 2022)
- [A Progress Report on DBOS: A DBMS-Oriented Operating System](http://cidrdb.org/cidr2022/papers/p26-li.pdf) (CIDR 2022)

## People

#### Faculty and Senior Industry Partners
- [Michael Cafarella](https://www.csail.mit.edu/person/michael-cafarella) (MIT)
- [Goetz Graefe](https://research.google/people/105119/) (Google)
- [Jeremy Kepner](http://www.mit.edu/~kepner/) (MIT)
- [Christos Kozyrakis](https://web.stanford.edu/~kozyraki/) (Stanford)
- [Michael Stonebraker](https://www.csail.mit.edu/person/michael-stonebraker) (MIT)
- [Lalith Suresh](https://research.vmware.com/researchers/lalith-suresh) (VMware)
- [Matei Zaharia](https://cs.stanford.edu/~matei/) (Stanford)

#### PhD Students
- [Kostis Kaffes](http://stanford.edu/~kkaffes/) (Stanford)
- [Peter Kraft](https://petereliaskraft.net/) (Stanford)
- [Qian Li](https://cs.stanford.edu/people/qianli/) (Stanford)
- [Athinagoras Skiadopoulos](?) (Stanford)

#### Masters and Undergraduate Students
- [Danny Cho](?) (Stanford)
- [Deeptaanshu Kumar](?) (CMU)
- [Jason Li](?) (MIT)
- [Robert Redmond](?) (MIT)
- [Nathan Weckwerth](?) (MIT)
- [Brian Xia](?) (MIT)

#### Alumni
- Shana Mathew (MIT)
- Daniel Hong (MIT)

## Sponsors
- ???
