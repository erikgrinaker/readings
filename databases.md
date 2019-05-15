# Databases

## General

- [x] 📄 [**Architecture of a Database System**](http://db.cs.berkeley.edu/papers/fntdb07-architecture.pdf) (JM Hellerstein, M Stonebraker, J Hamilton 2007)
- [ ] 🎥 [**CMU 15-445 Intro to Database Systems**](https://www.youtube.com/playlist?list=PLSE8ODhjZXja3hgmuwhf89qboV1kOxMx7) (A Pavlo 2018)
- [ ] 🎥 [**CMU 15-721 Advanced Database Systems**](https://www.youtube.com/playlist?list=PLSE8ODhjZXjYgTIlqf4Dy9KQpQ7kn1Tl0) (A Pavlo 2017)
- [x] 📖 [**Designing Data-Intensive Applications**](https://dataintensive.net/) (M Kleppmann 2017)
- [ ] 🛠 [**Let's Build a Simple Database**](https://cstack.github.io/db_tutorial/) (C Stack 2017)
- [ ] 📄 [**Readings in Database Systems**](http://www.redbook.io) (P Bailis, JM Hellerstein, M Stonebraker) _"The Red Book"_
- [ ] 🎥 [**UC Berkeley CS186 Introduction to Database Systems**](https://archive.org/details/UCBerkeley_Course_Computer_Science_186#) (J Hellerstein 2012)
- [ ] 📖 [Data and Reality](https://www.amazon.com/Data-Reality-Perspective-Perceiving-Information/dp/1935504215) (W Kent, S Hoberman 2012)
- [ ] 📖 [Database System Concepts](https://www.db-book.com/db7/index.html) (A Silberschatz, HF Korth, S Sudarshan 2019)
- [x] 📖 [Fundamentals of Database Systems](https://www.amazon.com/Fundamentals-Database-Systems-Ramez-Elmasri/dp/0133970779) (R Elmasri, SB Navathe 2015)

## Transactions

- [x] 🔗 [**Consistency Models**](https://jepsen.io/consistency) (Jepsen 2016)
- [ ] 📖 [**Transaction Processing: Concepts and Techniques**](https://www.amazon.com/Transaction-Processing-Concepts-Techniques-Management/dp/1558601902#customerReviews) (J Gray, A Reuter 1992)
- [ ] 📄 [A Critique of ANSI SQL Isolation Levels](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/tr-95-51.pdf) (H Berenson et al 1995)
- [ ] 📄 [Calvin: Fast Distributed Transactions for Partitioned Database Systems](http://cs.yale.edu/homes/thomson/publications/calvin-sigmod12.pdf) (DJ Abadi et al 2012)
- [ ] 📄 [Consistency in Non-Transactional Distributed Storage Systems](https://arxiv.org/pdf/1512.00168.pdf) (P Viotti, M Vukolić 2016)
- [ ] 📄 [Generalized Isolation Level Definitions](http://pmg.csail.mit.edu/papers/icde00.pdf) (A Adya, B Liskov, P ONeil 2000)
- [ ] 📄 [Highly Available Transactions: Virtues and Limitations](http://www.vldb.org/pvldb/vol7/p181-bailis.pdf) (P Bailis, JM Hellerstein et al 2013)
- [ ] 📄 [Naming and Synchronization in a Decentralized Computer System](https://dspace.mit.edu/bitstream/handle/1721.1/16279/05331643-MIT.pdf) (DP Reed 1978) _"The MVCC paper"_
- [ ] 📄 [Serializable Isolation for Snapshot Databases](https://courses.cs.washington.edu/courses/cse444/08au/544M/READING-LIST/fekete-sigmod2008.pdf) (MJ Cahill, U Röhm, AD Fekete 2008)
- [ ] 📄 [Serializable Snapshot Isolation in PostgreSQL](https://drkp.net/papers/ssi-vldb12.pdf) (DRK Ports, K Grittner 2012)

## Queries

- [ ] 📖 [Building Query Compilers](http://pi3.informatik.uni-mannheim.de/~moer/querycompiler.pdf) (G Moerkotte 2014)
- [ ] 📄 [How to Architect a Query Compiler, Revisited](https://www.cs.purdue.edu/homes/rompf/papers/tahboub-sigmod18.pdf) (RY Tahboub, GM Essertel, T Rompf 2018)
- [ ] 📄 [Access Path Selection
in a Relational Database Management System](https://www2.cs.duke.edu/courses/compsci516/cps216/spring03/papers/selinger-etal-1979.pdf) (PG Selinger et al 1979)
- [ ] 📄 [An Overview of Query Optimization in Relational Systems](https://web.stanford.edu/class/cs345d-01/rl/chaudhuri98.pdf) (S Chaudhuri 1998)
- [ ] 📄 [Optimization of Queries with User-Defined Predicates](http://www.vldb.org/conf/1996/P087.PDF) (S Chaudhur, K Shim 1999)

## Storage

- [ ] 📄 [Aries: A transaction recovery method supporting fine-granularity locking and partial rollbacks using write-ahead logging](https://cs.stanford.edu/people/chrismre/cs345/rl/aries.pdf) (C Mohan et al 1992)
- [ ] 📄 [bLSM: A General Purpose Log Structured Merge Tree](http://www.eecs.harvard.edu/~margo/cs165/papers/gp-lsm.pdf) (R Sears, R Ramakrishnan 2012)
- [ ] 📄 [The Log-Structured Merge Tree](https://www.cs.umb.edu/~poneil/lsmtree.pdf) (P O'Neil, E Cheng, D Gawklik, E O'Neil 1996)
- [ ] 📄 [The Ubiquitous B-Tree](http://cgi.di.uoa.gr/~ad/M149/ubiquitous_btree.pdf) (D Comer 1979)
- [ ] 📄 [WiscKey: Separating Keys from Values in SSD-Conscious Storage](https://www.usenix.org/system/files/conference/fast16/fast16-papers-lu.pdf) (L Lu, TS Pillai, AC Arpaci-Dusseau, RH Arpaci-Dusseau 2016)

## Vendors

### CockroachDB

- [x] 🔗 [**Architecture Overview**](https://www.cockroachlabs.com/docs/stable/architecture/overview.html)
- [x] 💬 [**Serializable, Lockless, Distributed: Isolation in CockroachDB**](https://www.cockroachlabs.com/blog/serializable-lockless-distributed-isolation-cockroachdb/) (M Tracy 2016)
- [x] 💬 [How We Built a Cost-Based SQL Optimizer](https://www.cockroachlabs.com/blog/building-cost-based-sql-optimizer/) (A Kimball 2018)
- [x] 💬 [Living Without Atomic Clocks](https://www.cockroachlabs.com/blog/living-without-atomic-clocks/) (S Kimball 2016)

### FaunaDB

- [x] 💬 [Time-Traveling Databases: Exploring Temporality in FaunaDB](https://fauna.com/blog/time-traveling-databases) (M Freels 2016)
- [x] 💬 [Unifying Relational, Document, Graph, and Temporal Data Models](https://fauna.com/blog/unifying-relational-document-graph-and-temporal-data-models) (C Anderson 2018)

### Google Bigtable

- [ ] 📄 [**Bigtable: A Distributed Storage System for Structured Data**](https://static.googleusercontent.com/media/research.google.com/en//archive/bigtable-osdi06.pdf) (F Chang et al 2006) _"The Bigtable paper"_

### Google Spanner

- [ ] 📄 [**Spanner: Google's Globally-Distributed Database**](http://static.googleusercontent.com/media/research.google.com/en//pubs/archive/39966.pdf) (J Corbett et al 2012) _"The Spanner paper"_
- [x] 📄 [Spanner, TrueTime & The CAP Theorem](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/45855.pdf) (E Brewer 2017)
