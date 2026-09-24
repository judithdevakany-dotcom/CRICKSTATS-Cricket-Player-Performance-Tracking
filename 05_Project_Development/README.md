# Phase 5 – Project Development

## 5.1 Development Overview

CRICKSTATS is developed as a Salesforce-based Cricket Player Performance Tracking Application.

The development process includes:

- Salesforce Developer Account Setup
- Custom Object Creation
- Object Tabs Creation
- Lightning App Creation
- Field Creation
- Relationships
- Roll-Up Summary Fields
- Flow Automation
- Reports and Dashboards

## 5.2 Salesforce Developer Setup

A Salesforce Developer environment is used to develop and configure the CRICKSTATS application.

The Salesforce environment provides the platform required to create custom objects, fields, relationships, automation, reports, and dashboards.

## 5.3 Custom Objects

Two main custom objects are created for the application:

### Player Object

The Player object stores information about cricket players.

It is used to manage player details and maintain centralized player records.

### Match Performance Object

The Match Performance object stores match-wise performance information of players.

It is used to record and analyze player performance for individual matches.

## 5.4 Object Relationships

A Master-Detail relationship is created between the Player and Match Performance objects.

This relationship connects player records with their corresponding match performance records.

## 5.5 Fields and Data Structure

Custom fields are created to store the required player and match performance information.

The fields support:

- Player Information
- Match Information
- Performance Statistics
- Performance Analysis

## 5.6 Roll-Up Summary

Roll-Up Summary fields are used to summarize related Match Performance records at the Player level.

This helps maintain player statistics based on match performance data.

## 5.7 Lightning App

A dedicated Salesforce Lightning App is created for CRICKSTATS.

The application provides access to the required objects, tabs, records, reports, and dashboards.

## 5.8 Flow Automation

Salesforce Flows are used to automate application processes.

The automated flows help update player statistics and maintain accurate performance information.

## 5.9 Reports and Dashboards

Reports are created to organize and analyze player performance data.

Dashboards provide a visual representation of performance information and help users analyze player statistics.

## 5.10 Development Outcome

The development phase produces a Salesforce-based cricket performance tracking application that provides:

- Centralized player data
- Match-wise performance tracking
- Automated statistics
- Reports
- Dashboards
- Performance analysis
