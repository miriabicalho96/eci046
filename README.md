# eci046<?xml version="1.0"?>
<rdf:RDF xmlns="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#"
     xml:base="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl"
     xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
     xmlns:owl="http://www.w3.org/2002/07/owl#"
     xmlns:xml="http://www.w3.org/XML/1998/namespace"
     xmlns:universidade="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#"
     xmlns:xsd="http://www.w3.org/2001/XMLSchema#"
     xmlns:rdfs="http://www.w3.org/2000/01/rdf-schema#">
    <owl:Ontology rdf:about="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl"/>
    


    <!-- 
    ///////////////////////////////////////////////////////////////////////////////////////
    //
    // Object Properties
    //
    ///////////////////////////////////////////////////////////////////////////////////////
     -->

    


    <!-- http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#ensina -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#ensina">
        <owl:inverseOf rdf:resource="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#ensinada_por"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#Professor"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#Disciplina"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#ensinada_por -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#ensinada_por">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#Disciplina"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#Professor"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#estuda -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#estuda">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#Estudante"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#Disciplina"/>
    </owl:ObjectProperty>
    


    <!-- http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#matriculado__em -->

    <owl:ObjectProperty rdf:about="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#matriculado__em">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#Estudante"/>
        <rdfs:range rdf:resource="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#Disciplina"/>
    </owl:ObjectProperty>
    


    <!-- 
    ///////////////////////////////////////////////////////////////////////////////////////
    //
    // Data properties
    //
    ///////////////////////////////////////////////////////////////////////////////////////
     -->

    


    <!-- http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#feminino -->

    <owl:DatatypeProperty rdf:about="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#feminino">
        <rdfs:subPropertyOf rdf:resource="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#sexo"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#Pessoa"/>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#hexBinary"/>
    </owl:DatatypeProperty>
    


    <!-- http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#idade -->

    <owl:DatatypeProperty rdf:about="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#idade">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#Pessoa"/>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#decimal"/>
    </owl:DatatypeProperty>
    


    <!-- http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#masculino -->

    <owl:DatatypeProperty rdf:about="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#masculino">
        <rdfs:subPropertyOf rdf:resource="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#sexo"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#Pessoa"/>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#hexBinary"/>
    </owl:DatatypeProperty>
    


    <!-- http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#matrícula -->

    <owl:DatatypeProperty rdf:about="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#matrícula">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#Estudante"/>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#integer"/>
    </owl:DatatypeProperty>
    


    <!-- http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#nome -->

    <owl:DatatypeProperty rdf:about="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#nome">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#Disciplina"/>
        <rdfs:domain rdf:resource="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#Pessoa"/>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#string"/>
    </owl:DatatypeProperty>
    


    <!-- http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#sexo -->

    <owl:DatatypeProperty rdf:about="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#sexo">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#Pessoa"/>
    </owl:DatatypeProperty>
    


    <!-- http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#sobrenome -->

    <owl:DatatypeProperty rdf:about="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#sobrenome">
        <rdfs:domain rdf:resource="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#Pessoa"/>
        <rdfs:range rdf:resource="http://www.w3.org/2001/XMLSchema#string"/>
    </owl:DatatypeProperty>
    


    <!-- 
    ///////////////////////////////////////////////////////////////////////////////////////
    //
    // Classes
    //
    ///////////////////////////////////////////////////////////////////////////////////////
     -->

    


    <!-- http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#Disciplina -->

    <owl:Class rdf:about="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#Disciplina"/>
    


    <!-- http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#Estudante -->

    <owl:Class rdf:about="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#Estudante">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#Pessoa"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#Gestao -->

    <owl:Class rdf:about="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#Gestao">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#Disciplina"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#Ontologia -->

    <owl:Class rdf:about="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#Ontologia">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#Disciplina"/>
    </owl:Class>
    


    <!-- http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#Pessoa -->

    <owl:Class rdf:about="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#Pessoa"/>
    


    <!-- http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#Professor -->

    <owl:Class rdf:about="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#Professor">
        <rdfs:subClassOf rdf:resource="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#Pessoa"/>
    </owl:Class>
    


    <!-- 
    ///////////////////////////////////////////////////////////////////////////////////////
    //
    // Individuals
    //
    ///////////////////////////////////////////////////////////////////////////////////////
     -->

    


    <!-- http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#0001 -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#0001">
        <rdf:type rdf:resource="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#Estudante"/>
    </owl:NamedIndividual>
    <rdf:Description>
        <rdf:type rdf:resource="http://www.w3.org/2002/07/owl#NegativePropertyAssertion"/>
        <owl:sourceIndividual rdf:resource="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#0001"/>
        <owl:assertionProperty rdf:resource="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#idade"/>
        <owl:targetValue rdf:datatype="http://www.w3.org/2001/XMLSchema#integer">20</owl:targetValue>
    </rdf:Description>
    <rdf:Description>
        <rdf:type rdf:resource="http://www.w3.org/2002/07/owl#NegativePropertyAssertion"/>
        <owl:sourceIndividual rdf:resource="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#0001"/>
        <owl:assertionProperty rdf:resource="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#masculino"/>
        <owl:targetValue></owl:targetValue>
    </rdf:Description>
    <rdf:Description>
        <rdf:type rdf:resource="http://www.w3.org/2002/07/owl#NegativePropertyAssertion"/>
        <owl:sourceIndividual rdf:resource="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#0001"/>
        <owl:assertionProperty rdf:resource="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#matrícula"/>
        <owl:targetValue rdf:datatype="http://www.w3.org/2001/XMLSchema#integer">20180003366</owl:targetValue>
    </rdf:Description>
    <rdf:Description>
        <rdf:type rdf:resource="http://www.w3.org/2002/07/owl#NegativePropertyAssertion"/>
        <owl:sourceIndividual rdf:resource="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#0001"/>
        <owl:assertionProperty rdf:resource="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#nome"/>
        <owl:targetValue>João</owl:targetValue>
    </rdf:Description>
    <rdf:Description>
        <rdf:type rdf:resource="http://www.w3.org/2002/07/owl#NegativePropertyAssertion"/>
        <owl:sourceIndividual rdf:resource="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#0001"/>
        <owl:assertionProperty rdf:resource="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#sobrenome"/>
        <owl:targetValue>Silva Pereira</owl:targetValue>
    </rdf:Description>
    


    <!-- http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#0002 -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#0002">
        <rdf:type rdf:resource="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#Professor"/>
        <feminino></feminino>
        <idade rdf:datatype="http://www.w3.org/2001/XMLSchema#integer">32</idade>
        <nome>Maria</nome>
        <sobrenome>Aparecida</sobrenome>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#003 -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#003">
        <rdf:type rdf:resource="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#Disciplina"/>
        <rdf:type rdf:resource="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#Gestao"/>
        <nome>Fontes de Informação</nome>
    </owl:NamedIndividual>
    


    <!-- http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#004 -->

    <owl:NamedIndividual rdf:about="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#004">
        <rdf:type rdf:resource="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#Ontologia"/>
        <nome>Introdução a Ontologias</nome>
    </owl:NamedIndividual>
    


    <!-- 
    ///////////////////////////////////////////////////////////////////////////////////////
    //
    // General axioms
    //
    ///////////////////////////////////////////////////////////////////////////////////////
     -->

    <rdf:Description>
        <rdf:type rdf:resource="http://www.w3.org/2002/07/owl#AllDisjointClasses"/>
        <owl:members rdf:parseType="Collection">
            <rdf:Description rdf:about="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#Estudante"/>
            <rdf:Description rdf:about="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#Gestao"/>
            <rdf:Description rdf:about="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#Ontologia"/>
            <rdf:Description rdf:about="http://www.semanticweb.org/miriabicalho/ontologies/2018/8/universidade.owl#Professor"/>
        </owl:members>
    </rdf:Description>
</rdf:RDF>



<!-- Generated by the OWL API (version 4.2.8.20170104-2310) https://github.com/owlcs/owlapi -->

