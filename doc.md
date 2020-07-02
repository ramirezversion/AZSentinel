# Schedueled Alert Rule: #displayName

Schedueled custom rules can search for specific criteria across your environment and generate incidents when the criteria are matched so that you can investigate them.

## General

### Description

#Description

### Tactics

In the tactics field, you can choose from among categories of attacks by which to classify the rule.

#Tactics

### Severity

#Severity

### Status

Current status is: #Status

## Logic

### Querry

The querys in Azure Sentinel are written in KQL Language. It's based on relational database management systems, and supports entities such as databases, tables, and columns. Complex analytical queries are made using the Kusto Query Language. Some query operators include:

* calculated columns
* searching and filtering on rows
* group by-aggregates
* join functions

```JSON
#Querry
```

### Map entities

| Entity Type | Column   |
| ----------- | -------- |
| Account     | #Account |
| Host        | #Host    |
| IP          | #Ip      |
| URL         | #URL     |

### Query scheduling

This Rule is schedueled to run every: #QueryFrequency
This Rule lookup data from the last: #QueryPeriod

### Alert threshold

This rule will generate alert when number of query results is #TriggerOperator with value #TriggerThreshold
