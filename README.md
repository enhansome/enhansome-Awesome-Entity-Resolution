# Awesome Entity Resolution Resources with stars

* [Open-Source Software](#open-source-software)
  * [End-to-End Entity Resolution](#end-to-end-entity-resolution)
  * [Evaluation](#evaluation)
  * [String Comparison](#string-comparison)
  * [Embeddings](#embeddings-focused-pairwise-comparison)
  * [Data Cleaning and Parsing](#data-cleaning-and-parsing)
  * [Data Quality Control](#data-quality-control)
  * [Blocking, Candidate Selection, and Search](#blocking-candidate-selection-and-search)
* [Commercial Solutions](#commercial-solutions)
* [Books](#books)
* [Contributors](#contributors)

***

## Open-Source Software

### End-to-End Entity Resolution

* [dedupe](https://github.com/dedupeio/dedupe) ⭐ 4,502 | 🐛 90 | 🌐 Python | 📅 2025-07-29 (Python) - Active learning and flexible Python tooling for entity resolution.
* [Splink](https://github.com/moj-analytical-services/splink) ⭐ 2,345 | 🐛 224 | 🌐 Python | 📅 2026-08-13 (Python, SQL, Spark) - Scalable Fellegi-Sunter and rule-based entity resolution using your choice of SQL or Spark backend.
* [Zingg](https://github.com/zinggAI/zingg) ⭐ 1,234 | 🐛 100 | 🌐 Java | 📅 2026-08-19 (Python, Java) - Scalable, active learning model for entity resolution.
* [RecordLinkage](https://github.com/J535D165/recordlinkage) ⭐ 1,059 | 🐛 64 | 🌐 Python | 📅 2024-02-21 (Python) - Toolkit for prototyping entity resolution systems.
* [DeepMatcher](https://github.com/anhaidgroup/deepmatcher) ⭐ 622 | 🐛 75 | 🌐 Python | 📅 2024-06-18 (Python) - Deep learning-based entity ersolution
* [FastLink](https://github.com/kosukeimai/fastLink) ⭐ 293 | 🐛 36 | 🌐 R | 📅 2026-02-28 (R) - Easy, scalable Fellegi-Sunter entity resolution on your laptop.
* [PyJedAI](https://github.com/AI-team-UoA/pyJedAI) ⭐ 101 | 🐛 1 | 🌐 Python | 📅 2026-03-22 (Python, Java) - State-of-the-art entity resolution clustering algorithms.
* [dblink](https://github.com/cleanzr/dblink) ⭐ 60 | 🐛 4 | 🌐 Scala | 📅 2021-06-10 (R, Spark) - Scalable Bayesian graphical entity resolution.
* [exchanger](https://github.com/cleanzr/exchanger) ⭐ 8 | 🐛 0 | 🌐 C++ | 📅 2024-01-07 (R, C++) - More flexible Bayesian graphical entity resolution on your laptop.
* [MatchFlow](https://github.com/madmatcher/matchflow) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2026-07-21 (Spark, Python) - Library for composing entity matching workflows.
* [RELAIS](https://www.istat.it/en/methods-and-tools/methods-and-it-tools/process/processing-tools/relais) (R, SQL, Java) - Record linkage software used at the Italian National Statistics Institute.

### Evaluation

* [ER-Evaluation](https://github.com/Valires/er-evaluation) ⭐ 38 | 🐛 4 | 🌐 Python | 📅 2023-12-03 (Python) - End-to-End evaluation, including summary statistics for monitoring, principled performance metric estimators, and error analysis.
* [clevr](https://github.com/cleanzr/clevr) ⭐ 15 | 🐛 1 | 🌐 R | 📅 2023-09-23 (R) - Performance metrics and error tables.

### String Comparison

* [textdistance](https://github.com/life4/textdistance) ⭐ 3,540 | 🐛 10 | 🌐 Python | 📅 2025-04-18 (Python) - Very large collection of sequence comparison functions, including token-based distances.
* [jellyfish](https://github.com/jamesturk/jellyfish) ⭐ 2,230 | 🐛 7 | 🌐 Jupyter Notebook | 📅 2026-07-24 (Python, C) - Fast string distance and phonetic matching.
* [py\_stringmatching](https://github.com/anhaidgroup/py_stringmatching) ⭐ 144 | 🐛 29 | 🌐 Python | 📅 2026-02-18 (Python, C) - Large set of string comparison functions and tokenizaztion methods.
* [StringCompare](https://github.com/OlivierBinette/StringCompare) ⭐ 21 | 🐛 13 | 🌐 Python | 📅 2025-09-21 (Python, C++) - Time and space efficient implementation of common string distance functions. Architectured for maintainability and extendability.
* [Comparator](https://github.com/ngmarchant/comparator) ⭐ 19 | 🐛 3 | 🌐 R | 📅 2025-09-23 (R, C++) - Efficient string comparison functions in R.
* [SecondString](https://secondstring.sourceforge.net/) (Java) - Java implementation of string comparison functions.

### Embeddings (for pairwise comparison)

* [FaceNet-PyTorch](https://github.com/timesler/facenet-pytorch) ⭐ 5,162 | 🐛 85 | 🌐 Python | 📅 2025-09-16 (Python, PyTorch) - Embeddings for facial identity resolution.
* [Entity Embed](https://github.com/vintasoftware/entity-embed) ⭐ 161 | 🐛 4 | 🌐 Jupyter Notebook | 📅 2022-11-18 (Python, PyTorch) - Pytorch text embedding model for blocking.

### Data Cleaning and Parsing

* [libpostal](https://github.com/openvenues/libpostal) ⭐ 4,872 | 🐛 299 | 🌐 C | 📅 2026-05-13 (C, and bindings for Python, Java, Go, Ruby, PHP, and NodeJS) - Multinational address parsing.
* [Ftfy](https://github.com/rspeer/python-ftfy) ⭐ 4,059 | 🐛 25 | 🌐 Python | 📅 2024-10-30 (Python) - Fixes text (unicode artifacts) for you.
* [python-nameparser](https://github.com/derek73/python-nameparser) ⭐ 713 | 🐛 33 | 🌐 Python | 📅 2026-08-19 (Python) - Separate names into individual components.
* [ProbablePeople](https://github.com/datamade/probablepeople) ⭐ 623 | 🐛 67 | 🌐 Python | 📅 2025-05-15 - Western name parser.
* [cleanco](https://github.com/psolin/cleanco) ⭐ 360 | 🐛 16 | 🌐 Python | 📅 2026-06-23 (Python) - Company name cleaning.
* [Nominally](https://github.com/vaneseltine/nominally) ⭐ 41 | 🐛 6 | 🌐 Python | 📅 2025-09-03 - Name parser for record linkage.
* [PyJanitor](https://pyjanitor-devs.github.io/pyjanitor/) (Python) - Clean code for clean data.

### Data Quality Control

* [GreatExpectations](https://docs.greatexpectations.io/docs/) (Python) - Data quality checks.
* [validate](https://github.com/data-cleaning/validate) ⭐ 434 | 🐛 52 | 🌐 R | 📅 2025-12-10 (R) - Data quality checks in R.

### Blocking, Candidate Selection, and Search

* [ElasticSearch](https://github.com/elastic/elasticsearch) ⭐ 77,833 | 🐛 5,989 | 🌐 Java | 📅 2026-08-19 - Search text.
* [StarSpace](https://github.com/facebookresearch/StarSpace) ⚠️ Archived (C++, Python) - Embedding model suitable for similarity learning.
* [DeezyMatch](https://github.com/Living-with-machines/DeezyMatch) ⭐ 152 | 🐛 30 | 🌐 Jupyter Notebook | 📅 2024-10-16 (Python) - Deep embedding and approximate nearest-beighbor blocking for entity resolution.
* \[BlockingPy)(<https://github.com/ncn-foreigners/BlockingPy> ⭐ 21 | 🐛 1 | 🌐 Python | 📅 2026-03-09) (Python) -- Blocking based on approximate nearest neighbours.
* [blocking](https://github.com/ncn-foreigners/blocking) ⭐ 14 | 🐛 2 | 🌐 R | 📅 2026-08-14 (R) - Blocking based on approximate nearest neighbours.
* [Delex](https://github.com/anhaidgroup/delex) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2026-04-27 (Spark, Python) - Open-source tool for blocking rules.

## Commercial Solutions

* [Automated Data Inc](https://www.automated-data.io/) - AI driven, low-code.
* [Tilores](https://tilores.io/) - Flexible entity resolution platform.
* [Senzing](https://senzing.com/) - Pre-configured entity resolution and entity management for people and organizations.
* [Match Data Pro](https://matchdatapro.com/) - Batch entity resolution in the browser. Integrates with Senzing.
* [Reltio](https://www.reltio.com/) - Cloud master data management with ER functionality.
* [Quantexa](https://www.quantexa.com/) - Entity resolution and graph analytics.
* [Dataladders Data Match](https://dataladder.com/products/datamatch-enterprise/)
* [WinPure Clean and Match](https://winpure.com/products/clean-match/)
* [AWS Entity Resolution](https://aws.amazon.com/entity-resolution/) - Rule-based entity resolution
* [Google Cloud Entity Reconciliation](https://cloud.google.com/enterprise-knowledge-graph) - Part of Enterprise Knowledge Graph.
* [Syntini Data Matching](https://www.syniti.com/solutions/data-matching/)
* [Amperity](https://amperity.com/)
* [MadMatcher](madmatcher.ai)

## Books

* [Hands-On Entity Resolution with Splink](https://www.oreilly.com/library/view/hands-on-entity-resolution/9781098148478/) - Practical entity resolution with Splink and cloud computing.
* [Linking Sensitive Data](https://link.springer.com/book/10.1007/978-3-030-59706-1) - Introduction to privacy-preserving record linkage.
* [The Four Generations of Entity Resolution](https://link.springer.com/book/10.1007/978-3-031-01878-7) - Review of academic research in the field.
* [Data Matching: Concepts and Techniques for Record Linkage, Entity Resolution, and Duplicate Detection ](https://link.springer.com/book/10.1007/978-3-642-31164-2)

## Contributors

* [Olivier Binette](https://github.com/OlivierBinette)
* [Nishamathi Kumaraswamy](https://github.com/nishamathi)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-19._
