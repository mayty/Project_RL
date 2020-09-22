- [1. Introduction](#1-introduction)
  - [1.1. Purpose](#11-purpose)
  - [1.2. Scope](#12-scope)
  - [1.3. Definitions, Acronyms and Abbreviations](#13-definitions-acronyms-and-abbreviations)
  - [1.4. References](#14-references)
  - [1.5. Overview](#15-overview)
- [2. The Overall Description](#2-the-overall-description)
  - [2.1. Product Perspective](#21-product-perspective)
    - [2.1.1. Software Interfaces](#211-software-interfaces)
    - [2.1.2. User Interfaces](#212-user-interfaces)
    - [2.1.3. Communication Interfaces](#213-communication-interfaces)
    - [2.1.4. Memory Constraints](#214-memory-constraints)
  - [2.2. Product Functions](#22-product-functions)
  - [2.3. User Characteristics](#23-user-characteristics)
  - [2.4. Constraints](#24-constraints)
  - [2.5. Assumptions and Dependencies](#25-assumptions-and-dependencies)
  - [2.6. Apportioning of Requirements](#26-apportioning-of-requirements)
- [3. Specific Requirements](#3-specific-requirements)
  - [3.1. External Interfaces](#31-external-interfaces)
  - [3.2. Functions](#32-functions)
  - [3.3. Perfomance Requirements](#33-perfomance-requirements)
  - [3.4. Logical Data Requirements](#34-logical-data-requirements)
  - [3.5. Software System Attributes](#35-software-system-attributes)
    - [3.5.1. Reliability](#351-reliability)
    - [3.5.2. Avaliability](#352-avaliability)
    - [3.5.3. Security](#353-security)
    - [3.5.4. Maintainability](#354-maintainability)
    - [3.5.5. Portability](#355-portability)
    - [3.5.6. Other quality characteristics](#356-other-quality-characteristics)

# 1. Introduction
## 1.1. Purpose
The purpose of this product is to provide free and fun activity for users and place for advertising to companies. Intended audience is population with not enought free time to invest it into plot-based and long-term activities.
## 1.2. Scope
Project RL will provide rogue-like style gameplay with advertisement injections. This project is based on gameplay, and is not plot-driven.
## 1.3. Definitions, Acronyms and Abbreviations
Rogue-like -- subgenre of role-playing video games characterized by a dungeon crawl through procedurally generated levels, turn-based gameplay, tile-based graphics, and permanent death of the player character.
## 1.4. References
## 1.5. Overview
# 2. The Overall Description
## 2.1. Product Perspective
Project RL is a computer game intended for Windows OS but can be released on other platforms in the future. Main advantage over it's competitors is free distribution model. Project is going to earn money from integrating ads into gameplay. Most of it's competitors (Enter the gungeon, Binding of Isaac etc.) have license based revenue stream which can scare away popularity that can't afford buing it.
### 2.1.1. Software Interfaces
Project RL is going to be developed using Unity engine.
Project RL is developed for Windows 10 and support of earlier OS versions is not guaranteed.
### 2.1.2. User Interfaces
Project RL requires mouse and keyboard as input source and at least HD monitor as an output source.
### 2.1.3. Communication Interfaces
### 2.1.4. Memory Constraints
According to Steam survey vast majority of users have more than 8GB of RAM so target RAM usage will be under 8GB.
## 2.2. Product Functions
Product must have following gameplay features:
- Permadeath mechanic
- Health mechanic
- Melee attack mechanic
- Equipment mechanic
- Money mechanic 
- Merchants mechanic (buing and selling goods)
- Item drop mechanic (items are dropped based on player actions)
- World generation
## 2.3. User Characteristics
End user is assumed to have no vision and motorical disability so product is going to be designed with no regards for such users.
## 2.4. Constraints
Project RL must maintain framerate above 24fps on most popular system configuration (3.3GHz CPU, GTX 1060, 8GB RAM) at most scenarios.
## 2.5. Assumptions and Dependencies
Project RL is developed for Windows 10 so graphics are going to be based on DirectX.
## 2.6. Apportioning of Requirements
# 3. Specific Requirements
## 3.1. External Interfaces
## 3.2. Functions
Game loop must have following steps:
- Check user input and discard unused signals
- Update player entity based on input and enviroment
- Update enviroment based on its previous state
## 3.3. Perfomance Requirements
1% low framerate on most popular system configuration must be above 12fps.
## 3.4. Logical Data Requirements
## 3.5. Software System Attributes
### 3.5.1. Reliability
### 3.5.2. Avaliability
The system shall allow user to restart the application with the loss of at most 1 level of map.
### 3.5.3. Security
### 3.5.4. Maintainability
### 3.5.5. Portability
### 3.5.6. Other quality characteristics
