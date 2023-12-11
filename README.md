# Africa Knowledge Graph Ontology
An Ontology for factual information about Africa

The preferred prefix is **akg**
The associated namespace of the ontology is <http://www.africaknowledgegraph.com#>

The ontology has been edited on [Protégé](https://protege.stanford.edu/) and available in the [Turtle format](https://www.w3.org/TR/turtle/)

The model uses new relationships, in order to represent the relevant information as a set of interconnected events. 
The ontology for facts and information about Africa and all the countries it contains over a knowledge graph.

A sample of a knowledge graph can be [queried here!](https://africakg.streamlit.app/)

## Citation
If you use this ontology, please cite:

Kakande, A. S. (2023). Africa Knowledge Graph Ontology. *Retrieved from https://github.com/ArthurKakande/AfricaKnowledgeGraphOntology*

Latex bib text

> @misc{Kakande2023,
  author = {Kakande, A. S.},
  title = {Africa Knowledge Graph Ontology},
  year = {2023},
  howpublished = {\url{https://github.com/ArthurKakande/AfricaKnowledgeGraphOntology
}}
}

This work is licensed under a Creative Commons Attribution 4.0 International License.

# Ontology for Africa Knowledge graph information

## Object Properties:
1. hasCapitalCity
Description: Represents the relationship between a country and its capital city.
Inverse Property: isCapitalCityOf

2. hasDesert
Description: Denotes the relationship between a geographical entity and the deserts found within it.
Equivalent Property: hasMountain
Inverse Property: isFoundIn

3. hasMountain
Description: Represents the relationship between a geographical entity and the mountains found within it.
Equivalent Property: Inverse of isFoundIn
Inverse Property: isFoundIn

4. hasOfficialLanguage
Description: Denotes the official language(s) associated with a particular country.
Inverse Property: isOfficialLanguageOf

5. hasRiver
Description: Represents the relationship between a geographical entity and the rivers found within it.
Inverse Property: isLocatedIn

6. isCapitalCityOf
Description: Represents the inverse relationship of hasCapitalCity.

7. isFoundIn
Description: Denotes the inverse relationship of both hasDesert and hasMountain.

8. isLocatedIn
Description: Represents the inverse relationship of hasRiver.

9. isOfficialLanguageOf
Description: Represents the inverse relationship of hasOfficialLanguage.

## Data Properties:
1. hasCoordinates
Description: Specifies the geographical coordinates associated with a location.
2. hasHeight
Description: Represents the height of a geographical feature, such as a mountain.
3. hasPopulation
Description: Denotes the population of a country or region.
4. hasProminence
Description: Specifies the prominence of a geographical feature.
5. ranksAt
Description: Denotes the ranking of a geographical feature

## Classes and sub classes
The list of classes and sub classes is available as a doc file
