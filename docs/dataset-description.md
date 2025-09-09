# MuseIT Cultural Heritage Knowledge Graph (MuseIT KG) - v2.0

**Overview**
The MuseIT KG  is a curated RDF dataset representing Cultural Heritage Assets (CHAs).  
It integrates metadata published by partners in Dataverse with a MuseIT domain ontology that reuses DCMI and FOAF while introducing MuseIT-specific classes and properties.

**Purpose & scope**
- Provide a semantic backbone for MuseIT assets across tangible and intangible domains.  
- Ensure interoperability via selective reuse of external vocabularies (DCMI, FOAF).  
- Support automated ingestion & synchronization from partner Dataverse instances.  
- Enable descriptive analytics, discovery, and downstream applications (e.g., MuseMeUp, recommendation systems, accessibility tooling).  

---

## Example Analytics (SPARQL query results)

### 1. Total Assets 
![Total assets](query-results/01_total_assets.png)

### 2. Tangible vs. intangible
![Tangible vs intangible assets](query-results/02_tangible_intangible.png)

### 3. Distribution by art form
![Art form distribution](query-results/03_artforms_distribution.png)

### 4. Distribution by modality
![Modality distribution](query-results/04_modalities_distribution.png)

### 5. Assets per publisher
![Publisher counts](query-results/05_publishers_counts.png)

---

## Example Asset Visualization
Below is a graph representation of one Cultural Heritage Asset and its linked metadata:

![Graph visualization of one asset](visuals/cha_triples_example.png)
