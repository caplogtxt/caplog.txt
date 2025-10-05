# caplog.txt
A comprehensive guide on syntax and semantics of caplog.txt log file format

# Description

Caplog.txt is an open-source, plaintext syntax for formating and structuring log entries in a logbook. It is both machine-readable and human-readable. 
It is future-proof and designed to be interoperable with multiple independent implementations, including a paper-based logbook. It is inspired from Todo.txt. 


# Terminology

* Log Entry or Entry - Basic unit of information that describes an event. It consists of three parts:
    - DateTime - The time at which the event occured. 
    - Timestamp - The time at which the entry was updated. 
    - Description - The description of the event.
* Log Book - A collection of related log entries.  
* To log en entry means to add an entry to the log book. 


# Syntax

* Log entries are separated from each other by one or more blank lines. 
* The first line of the entry must be 'DateTime'
* The second line of the entry must be 'Timestamp'
* The Third line begins the 'Description' and it ends with a blank line. The only criteria of an entry description is that it cannot contain a blank line. 

## Structure

```text
DATE1
ENTRY TIMESTAMP1
ENTRY MESSAGE1

DATE2
ENTRY TIMESTAMP2
ENTRY MESSAGE2

DATE3
ENTRY TIMESTAMP3
ENTRY MESSAGE3

DATE4
ENTRY TIMESTAMP4
ENTRY MESSAGE4
```