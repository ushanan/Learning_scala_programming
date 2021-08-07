# Scala:
created by Martin Odersky and promoted by TypeSafe Company

## Benefits:
Scalable - OOP and functional programming
does not have boiler plate code(repetition of code)
Concurrency: octa cores will be efficiently used
Used in Bigdata along with hadoop and spark framework.

## What is unit type in scala?
This defines function which does not return data (similar to void in java)
` def main ( args : Array[String] ) : Unit ={} `

## Steps to be followed for setting up spark proj in Intellij using scala
- SBT or maven
- JAVA 8 jdk
- intellij
- scala plugin
- proxy for organization level / no proxy for local machine
- create new project and give versions for scala
- sbt build
- within SBT build file : dependency - maven repository for spark core - for spark and scala version (2.3.0,2.11.11)
- Build again

## What is SBT ? 
* scala build tool or simple build tool . 
* It is a build tool like maven .

## Use of SBT : 
* used to compile ,test,package

## Way to use SBT 
 through cmd prompt or intellij
