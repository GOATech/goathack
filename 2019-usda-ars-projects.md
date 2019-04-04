# Projects for GOAT:Hack @ USDA ARS 2019

## Vision: The Reconfigurable Open-Ag Research Pipeline
The reconfigureable research pipeline is comprised of open source, community created technologies and processes that support sustainable agriculture research, both on working farms and research sites. The pipeline is comprised of technologies and processes that support the design of research objectives, the acquisition, processing, and storage of data for research findings, and visualization of research findings for dissemnination.

Each technology and process in the reconfigurable open-ag research pipeline serves a unique and focused purpose to one or several parts of the research data pipeline (e.g., data visualization). With a multiplicity of research pipeline technologies and processes in the Reconfigurable Open-Ag Research Pipeline, an open-ag researcher is able to select the technologies and processes that support their project-specific research objectives.

The goal of GOAT:Hack @ USDA ARS is to begin building the Reconfigurable Open-Ag Research Pipeline. Each project will contribute ideas, concept models, prototypes, and proofs of concepts that further the development of this pipeline.

## Projects
### Plant Data Service

Project Team: Ankita (facilitator), Juliet, Victoria, Mike, Leon, Peyton

Overview: People refer to plants using two types of names. Common names are fluid and vary by region, which easily creates miscommunication. Latin binomial nomenclature, in contrast, is fixed (see itis.gov) and follows a strict set of naming convention rules. Further, Latin or scientific names fit into the classification schema that starts with Kingdom (i.e. Plantae) and ends with a plant being identified down to the most specific level possible (sometimes genus, usually species, occasionally subspecies, occasionally cultivar). In the realm of cover crop informatics, it would be useful to explicitly map out and define this classification schema to improve communication and standardization among resources and reduce confusion. Take, for example, rye. Common names include rye, cereal rye, and winter rye. The classification from Kingdom down to species can be found here: https://plants.usda.gov/java/ClassificationServlet?source=display&classid=SECE. At the level of interest to most creators of cover crop resources, the Latin name of rye may be given as Secale cereale (effectively complete, but lacking the naming authority), Secale cereale L. (technically complete), or if the tool includes cultivars, Secale cereale L. ‘Aroostook’. 

Note that this approach follows the formal scientific classification system; it does not account for other methods of grouping cover crops (e.g., by life cycle, such as “winter annual”, or by use, such as “fixes nitrogen”, or by traits such as “survives the winter”). These other classification methods are often more useful to farmers than a formal scientific name. Note also, however, that scientific names can be crucial both for clarity in communicating information and when buying seed because some cover crops (e.g., oilseed/tillage radish, annual/Italian/perennial ryegrass) are notoriously problematic (i.e. misidentified in the seed trade due to confusion among common vs. Latin names, prone to interbreeding at the subspecies or species level, and/or subject to marketing tactics in which branding vs. cultivars becomes confusing).

Challenge Questions: 
  * Can agricultural plant data be effectively standardized across units, regions, and categorical groupings?
  * How can standardized data subsequently be grouped by use case?
   * E.g., a vegetable seed company will be interested in agronomic and/or culinary data while an ecosystem service planning tool will be interested in agronomic and/or cover crop data
  * How can regional differences in plant data be incorporated into use cases and made available?
   * Data will vary based on hardiness zone / microclimate
  * What is the top-level plant identifier (Latin name vs. common name)?
  * What is the baseline ("static") data that is useful regardless of use case?

  * How do we structure the existing plant classification system to meet the needs of the developers of cover crop resources?
  * Is there a structuring that is so logical and basic that it can be used as a standard for developers?

Datasets: Victoria Ackroyd has created a data dictionary for the Northeast region cover crop selector tool. It includes an overview of the name classification to be filled in for each cover crop in the tool, as well as the cover crops themselves and assorted classifications (e.g., likelihood of surviving the winter, life cycle).
  * [Link to data set]

Software Stack:
  * Word processor
  * Internet
  * Python
  * Flask
  * PostgreSQL
  
Description of Deliverables:
  * Presumably the output will be a hierarchical chart that can be used to generate standardized classifications for each cover crop that might be used in a tool.

References: [include any ancillary documentation (references, diagrams, background) you think would be useful.] 

Project repositories: [url]

Project website: [url]




## Template Project
 
### Project Name
* Project Team: [list team members]
* Overview: [2-3 sentence context of the problem]
* Challenge Questions: [Write up in the form of 1-3 questions or problem statements.]
* Datasets: [Describe your dataset, including a brief data dictionary. Also list any external datasets you’d like, be as specific as possible (e.g., climate variables)]
* Software Stack: [what would you use/need]
* Description of Deliverables: [provide a brief description (or even a screenshot or link) to any visual outputs you have created, OR provide a description of outputs you would like to create e.g., graphs, models, visualizations, connections to other things.]
* References: [include any ancillary documentation (references, diagrams, background) you think would be useful.] 
* Project repositories: [url]
* Project website: [url]
