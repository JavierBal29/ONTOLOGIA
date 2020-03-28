# PEQUE-A-ONTOLOG-A
<?xml version="1.0"?>
<rdf:RDF xmlns="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-14#"
     xml:base="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-14"
     xmlns:owl="http://www.w3.org/2002/07/owl#"
     xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
     xmlns:xml="http://www.w3.org/XML/1998/namespace"
     xmlns:xsd="http://www.w3.org/2001/XMLSchema#"
     xmlns:rdfs="http://www.w3.org/2000/01/rdf-schema#">
    <owl:Ontology rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-14"/>
    


    <!-- 
    ///////////////////////////////////////////////////////////////////////////////////////
    //
    // Classes
    //
    ///////////////////////////////////////////////////////////////////////////////////////
     -->

    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-14#Acuaticos -->

    <owl:Class rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-14#Acuaticos">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-14#Habitat"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-14#Alimento -->

    <owl:Class rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-14#Alimento">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-14#Clasificación"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-14#Carnivoros -->

    <owl:Class rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-14#Carnivoros">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-14#Alimento"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-14#Clasificación -->

    <owl:Class rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-14#Clasificación">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-14#Mamiferos"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-14#Habitat -->

    <owl:Class rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-14#Habitat">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-14#Clasificación"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-14#Herbivoros -->

    <owl:Class rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-14#Herbivoros">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-14#Alimento"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-14#Mamiferos -->

    <owl:Class rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-14#Mamiferos"/>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-14#Reproducción -->

    <owl:Class rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-14#Reproducción">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-14#Clasificación"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-14#Terrestres -->

    <owl:Class rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-14#Terrestres">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-14#Habitat"/>
    </owl:Class>
    


    <!-- 
    ///////////////////////////////////////////////////////////////////////////////////////
    //
    // Individuals
    //
    ///////////////////////////////////////////////////////////////////////////////////////
     -->

    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-14#Orca -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-14#Orca">
        <rdf:type rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-14#Acuaticos"/>
        <rdf:type rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-14#Carnivoros"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-14#Tigre -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-14#Tigre">
        <rdf:type rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-14#Carnivoros"/>
        <rdf:type rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-14#Terrestres"/>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-14#Vaca -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-14#Vaca">
        <rdf:type rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-14#Herbivoros"/>
        <rdf:type rdf:resource="http://www.semanticweb.org/javierbalbuena/ontologies/2020/2/untitled-ontology-14#Terrestres"/>
    </owl:NamedIndividual>
     </rdf:RDF>



<!-- Generated by the OWL API (version 4.5.9.2019-02-01T07:24:44Z) https://github.com/owlcs/owlapi -->


