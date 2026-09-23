# Overview 

The goal of this assignment is to assess your understanding of UML class and use case diagrams.

# Instructions

## Class Diagram

Create a UML class diagram (save it as uml.wsd) that meets the following requirements:

* A flight is identified by an airline code ("UA", "Delta", "AA", etc.) and a flight number.
* An aircraft has a textual prefix, a registration number, a manufacturer, a model, and a capacity (the number of passengers it can safely carry).
* Your model should allow navigation from a flight object to the aircraft operating that flight.
* An airport is identified by its IATA code and includes information about its city, state, and country.
* A flight connects to different airports at different dates and times.
* Your model should allow navigation from a connection object to both the associated flight and airport objects.

Use the provided [class.wsd](class.wsd) file. 

## Use Case Diagram 

Create a UML use case diagram for the following scenario:

A system is designed to help companies hire employees to fill job vacancies. The system should support the following features:

* Create job descriptions and generate shareable links for posting on platforms such as LinkedIn.
* Candidates apply by completing an application form and uploading documents such as résumés (CVs) and letters of recommendation.
* A hiring committee evaluates all candidates.
* The system allows the committee to reject unqualified candidates and automatically sends rejection emails.
* Qualified candidates are interviewed, after which a hiring decision is made.
* The system can generate analytical reports for any completed hiring process.

Use the provided [use_case.wsd] file.
