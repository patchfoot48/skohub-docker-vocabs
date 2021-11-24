@prefix cat: <https://example.org/cat/> .
@prefix dct: <http://purl.org/dc/terms/> .
@prefix skos: <http://www.w3.org/2004/02/skos/core#> .
@prefix xsd: <http://www.w3.org/2001/XMLSchema#> .

cat: a skos:ConceptScheme ;
    dct:title "Cats"@en, "Katzen"@de ;
    dct:creator "Patch Foot"@de ;
    dct:created "2021-11-24"^^xsd:date ;
    dct:license <https://creativecommons.org/publicdomain/zero/1.0/> ;
    skos:hasTopConcept cat:black, cat:white, cat:ginger.

cat:black a skos:Concept ;
    skos:prefLabel "schwarze Katze"@de, "black cat"@en ;
    skos:altLabel ""@de, ""@en ;
    skos:topConceptOf cat: .

cat:white a skos:Concept ;
    skos:prefLabel "weiße Katze"@de, "white cat"@en ;
    skos:altLabel ""@de, ""@en ;
    skos:topConceptOf cat: .
    
    cat:ginger a skos:Concept ;
    skos:prefLabel "schildpatt Katze"@de, "ginger cat"@en ;
    skos:altLabel "rote Katze"@de, "orange cat"@en ;
    skos:topConceptOf cat: .
