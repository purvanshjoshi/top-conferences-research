# Graph Report - PAPER  (2026-10-29)

## Corpus Check
- Corpus is ~14,010 words - fits in a single context window. You may not need a graph.

## Summary
- 167 nodes · 183 edges · 16 communities
- Extraction: 83% EXTRACTED · 17% INFERRED · 0% AMBIGUOUS · INFERRED: 31 edges (avg confidence: 0.79)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- Computer Vision Venues
- SE, Security & Crypto
- ML & AI Flagships
- NLP Conferences
- Systems, Arch & Tracks
- OS & ML Systems
- AAAI & Symbolic AI
- Security Venues
- Database Venues
- HCI & CHI
- Data Mining & ICDE
- IR & Web
- FOCS & Theory
- STOC & Algorithms
- Networking & SIGCOMM
- UIST & Interfaces

## God Nodes (most connected - your core abstractions)
1. `Top Global Research Conferences Master Index` - 14 edges
2. `ACL conference` - 11 edges
3. `CVPR conference` - 11 edges
4. `ICCV conference` - 11 edges
5. `AAAI conference` - 9 edges
6. `ECCV conference` - 9 edges
7. `EMNLP conference` - 9 edges
8. `ASE conference` - 8 edges
9. `FSE conference` - 8 edges
10. `SOSP` - 8 edges

## Surprising Connections (you probably didn't know these)
- `ICDE Industry and Practice Track` --semantically_similar_to--> `NAACL Industry Track`  [INFERRED] [semantically similar]
  top-conferences-research/icde.md → top-conferences-research/naacl.md
- `KDD Applied Data Science (ADS) track` --semantically_similar_to--> `ICSE SEIP and NIER tracks`  [INFERRED] [semantically similar]
  top-conferences-research/kdd.md → top-conferences-research/icse.md
- `ACL conference` --semantically_similar_to--> `EMNLP conference`  [INFERRED] [semantically similar]
  top-conferences-research/acl.md → top-conferences-research/emnlp.md
- `ASE conference` --semantically_similar_to--> `FSE conference`  [INFERRED] [semantically similar]
  top-conferences-research/ase.md → top-conferences-research/fse.md
- `CVPR conference` --semantically_similar_to--> `ECCV conference`  [INFERRED] [semantically similar]
  top-conferences-research/cvpr.md → top-conferences-research/eccv.md

## Hyperedges (group relationships)
- **Computer vision flagship conferences** — top_conferences_research_cvpr_cvpr, top_conferences_research_eccv_eccv, top_conferences_research_iccv_iccv [EXTRACTED 1.00]
- **ARR-based NLP conferences** — top_conferences_research_acl_acl, top_conferences_research_emnlp_emnlp, top_conferences_research_acl_arr_acl_rolling_review [EXTRACTED 1.00]
- **Big Three ML conferences (ICML, ICLR, NeurIPS)** — top_conferences_research_icml, top_conferences_research_iclr, top_conferences_research_neurips [EXTRACTED 1.00]
- **Computer architecture venues (ISCA, MICRO)** — top_conferences_research_isca, top_conferences_research_micro, top_conferences_research_micro_microarchitecture_compilers_ilp, top_conferences_research_isca_accelerators [INFERRED 0.85]
- **Applied/industry tracks across venues** — top_conferences_research_icde_industry_practice_track, top_conferences_research_kdd_applied_data_science_track, top_conferences_research_naacl_industry_track, top_conferences_research_icse_seip_nier_tracks [INFERRED 0.75]
- **Systems flagship conferences** — top_conferences_research_osdi_osdi, top_conferences_research_sosp_sosp, top_conferences_research_sigcomm_sigcomm [INFERRED 0.75]
- **Database flagship conferences** — top_conferences_research_sigmod_sigmod, top_conferences_research_vldb_vldb, top_conferences_research_sigmod_pods [INFERRED 0.75]
- **Security flagship conferences** — top_conferences_research_sp_ieee_sp, top_conferences_research_usenix_security_usenix_security, top_conferences_research_sp_applied_cryptography [INFERRED 0.75]

## Communities (16 total, 0 thin omitted)

### Community 0 - "Computer Vision Venues"
Cohesion: 0.10
Nodes (23): 3D vision, CVPR conference, CVPR Best Student Paper, Generative vision models, Longuet-Higgins Prize, Seattle (venue), Video analysis, Vision-language (+15 more)

### Community 1 - "SE, Security & Crypto"
Cohesion: 0.12
Nodes (20): ASE conference, Automated reasoning, CI/CD automation, Munich (venue), Program analysis, Program synthesis, Atlanta (venue), CCS conference (+12 more)

### Community 2 - "ML & AI Flagships"
Cohesion: 0.13
Nodes (20): ICLR (Intl Conf on Learning Representations), ICLR Blog Post Track, OpenReview open review process, Representation Learning, ICLR submission growth 2022-2025, ICML (Intl Conf on Machine Learning), Big Three ML conferences, PMLR proceedings (+12 more)

### Community 3 - "NLP Conferences"
Cohesion: 0.14
Nodes (16): ACL conference, ACL Best Paper Awards, ACL Test of Time Awards, ACL Rolling Review (ARR), Computational linguistics, Kyoto (venue), Machine translation, Multilinguality (+8 more)

### Community 4 - "Systems, Arch & Tracks"
Cohesion: 0.17
Nodes (11): ICLR Tiny Papers Track, ICSE (IEEE/ACM Intl Conf on Software Engineering), ICSE multi-cycle submission, ICSE SEIP and NIER tracks, ISCA (Intl Symposium on Computer Architecture), Accelerators and memory systems, MICRO (IEEE/ACM Intl Symposium on Microarchitecture), Microarchitecture, compiler techniques, ILP (+3 more)

### Community 5 - "OS & ML Systems"
Cohesion: 0.20
Nodes (10): Distributed systems, ML systems, OSDI, USENIX ATC, SOSP Hall of Fame Award, Operating systems, ACM SIGOPS, Single-track format (+2 more)

### Community 6 - "AAAI & Symbolic AI"
Cohesion: 0.22
Nodes (9): AAAI conference, AI ethics, Classic Paper Awards, Knowledge Representation, Montreal (venue), Multi-agent systems, Outstanding Paper Awards, Robotics (+1 more)

### Community 7 - "Security Venues"
Cohesion: 0.22
Nodes (8): USENIX, Applied cryptography, IEEE Computer Society, IEEE S&P, Systematization of Knowledge (SoK), Internet Defense Prize, USENIX, USENIX Security

### Community 8 - "Database Venues"
Cohesion: 0.25
Nodes (8): Database systems, ML for databases, PODS, SIGMOD, ML in databases, PVLDB, VLDB, VLDB Endowment

### Community 9 - "HCI & CHI"
Cohesion: 0.29
Nodes (7): Accessibility, CHI conference, CHI Best Paper Award (top 1%), Interaction techniques, Pittsburgh (venue), Social computing, Visualization

### Community 10 - "Data Mining & ICDE"
Cohesion: 0.40
Nodes (6): ICDE (IEEE Intl Conf on Data Engineering), AI/ML for Data Systems, ICDE Industry and Practice Track, KDD (ACM SIGKDD Knowledge Discovery and Data Mining), KDD Applied Data Science (ADS) track, Graph mining and recommendation systems

### Community 11 - "IR & Web"
Cohesion: 0.33
Nodes (6): Information retrieval, Recommendation, SIGIR, Social networks, Web mining, The Web Conference (WWW)

### Community 12 - "FOCS & Theory"
Cohesion: 0.40
Nodes (5): Computational geometry, Data structures, FOCS conference, New York City (venue), Theoretical computer science

### Community 13 - "STOC & Algorithms"
Cohesion: 0.40
Nodes (5): Algorithmic game theory, Algorithms, Complexity theory, Quantum computing, STOC

### Community 14 - "Networking & SIGCOMM"
Cohesion: 0.50
Nodes (4): ACM, Networking, Software-Defined Networking, SIGCOMM

### Community 15 - "UIST & Interfaces"
Cohesion: 0.50
Nodes (4): AR/VR, Fabrication, Human-computer interaction, UIST

## Knowledge Gaps
- **102 isolated node(s):** `Montreal (venue)`, `Outstanding Paper Awards`, `Classic Paper Awards`, `Search and Planning`, `Knowledge Representation` (+97 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 104 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `Top Global Research Conferences Master Index` connect `SE, Security & Crypto` to `Computer Vision Venues`, `NLP Conferences`, `AAAI & Symbolic AI`, `HCI & CHI`, `FOCS & Theory`?**
  _High betweenness centrality (0.186) - this node is a cross-community bridge._
- **Are the 2 inferred relationships involving `CVPR conference` (e.g. with `ECCV conference` and `ICCV conference`) actually correct?**
  _`CVPR conference` has 2 INFERRED edges - model-reasoned connections that need verification._
- **What connects `Montreal (venue)`, `Outstanding Paper Awards`, `Classic Paper Awards` to the rest of the system?**
  _102 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `Computer Vision Venues` be split into smaller, more focused modules?**
  _Cohesion score 0.09881422924901186 - nodes in this community are weakly interconnected._
- **Why does `AAAI conference` connect `AAAI & Symbolic AI` to `SE, Security & Crypto`?**
  _High betweenness centrality (0.044) - this node is a cross-community bridge._
- **Are the 2 inferred relationships involving `ICCV conference` (e.g. with `CVPR conference` and `ECCV conference`) actually correct?**
  _`ICCV conference` has 2 INFERRED edges - model-reasoned connections that need verification._
- **Should `SE, Security & Crypto` be split into smaller, more focused modules?**
  _Cohesion score 0.11578947368421053 - nodes in this community are weakly interconnected._