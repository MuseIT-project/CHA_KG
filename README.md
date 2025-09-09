# CHA_KG (Cultural Heritage Assets Knowledge Graph) 

**CHA_KG** s a knowledge graph that represents cultural heritage assets (CHAs) using semantic technologies. It integrates metadata harvested from two Dataverse instances maintained within the MuseIT project:  
- [MuseIT Dataverse](https://dataverse.museit.eu/)  
- [ShareMusic Dataverse](https://database.sharemusic.se/)  

These repositories are populated directly by MuseIT partners, providing curated cultural heritage assets across different modalities and domains.  
The dataset in this repository (`CulturalHeritageAssetsKG_v2.0.ttl`) reflects the latest synchronized download as of **09 September 2025**.



## Features
- **Ontology**: A well-structured semantic model for representing cultural heritage data.
- **Populated Knowledge Graph**:  RDF dataset of assets including art forms, modalities, publishers, periods, and creators.  
- **Query Support**: SPARQL queries for analytics and exploration.  
- **Interoperable & Extensible**: Designed for integration with external datasets and future ontology extensions.  
- **Automated synchronization**: On MuseIT premises, the Dataverse instances are interconnected and every change in Dataverses is automatically synchronized into a GraphDB instance, ensuring that the KG is always up to date.  



## Repository Structure
- `data/`  
  - `CulturalHeritageAssetsKG_v2.0.ttl` → latest populated graph (v2.0, D6.3)  
  - `older_versions/` → archived exports for reference  
- `queries/` → reusable SPARQL queries for analytics and exploration  
- `docs/`  
  - `dataset-description.md` → detailed dataset description with examples  
  - `query-results/` → PNG screenshots of SPARQL query results  
  - `visuals/` → visual graph examples of individual assets  





## Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/MuseIT-project/CHA_KG.git
   cd CHA_KG