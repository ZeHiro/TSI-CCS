# 1. INTRODUCTION

## 1.1. Technical scope

This TSI concerns the Control-Command and Signalling On-board Subsystem and the Control-Command and Signalling Track-side Subsystem.

## 1.2. Geographical scope

The geographical scope of this TSI is the trans-European rail system, i.e. the trans-European conventional and high-speed rail systems as set out in points 1 and 2 of Annex I to Directive 2008/57/EC (Railway Interoperability Directive).

## 1.3. Content of this TSI

In accordance with Article 5(3) of the Railway Interoperability Directive, this TSI:

1.  indicates its intended scope — Chapter 2 (Subsystem Definition and Scope);
2.  lays down essential requirements for the Control-Command and Signalling Subsystems and their interfaces vis-à-vis other subsystems — Chapter 3 (The Essential Requirements of the Control-Command and Signalling Subsystems);
3.  lays down the functional and technical specifications to be met by the Subsystems and their interfaces with other subsystems — Chapter 4 (Characterisation of the Subsystem);
4.  determines the interoperability constituents and interfaces which must be covered by European specifications, including European standards, and which are necessary to achieve interoperability within the trans-European rail system — Chapter 5 (Interoperability Constituents);
5.  states, in each case under consideration, which procedures are to be used to assess the conformity or the suitability for use of the interoperability constituents and for the ‘EC’ verification of the subsystems — Chapter 6 (Assessing the Conformity and/or Suitability For Use of the Constituents and Verifying the Subsystems);
6.  indicates the strategy for implementing this TSI — Chapter 7 (Implementing the Control-Command and Signalling Subsystems TSI);
7.  indicates the professional competences and health and safety conditions at work required for the staff operating and maintaining these subsystems and implementing the TSI — Chapter 4 (Characterisation of the Subsystem).

In accordance with Article 5(5) of the Railway Interoperability Directive, provisions for specific cases are indicated in Chapter 7 (Implementing the Control-Command and Signalling Subsystems TSI).

This TSI also sets out, in Chapter 4 (Characterisation of the Subsystems), the operating and maintenance rules which specifically apply to the scope indicated in paragraphs 1.1 and 1.2 above.

# 2. SUBSYSTEM DEFINITION AND SCOPE

## 2.1. Introduction

The Control-Command and Signalling Subsystems are defined in Annex II to the Railway Interoperability Directive as ‘all the equipment required to ensure safety and to command and control movements of trains authorised to travel on the network’.

The features of the Control-Command and Signalling Subsystems are:

1.  the functions that are essential for the safe control of railway traffic, and that are essential for its operation, including those required for degraded modes (1);
2.  the interfaces;
3.  the level of performance required to meet the essential requirements.

## 2.2. Scope

The Control-Command and Signalling Subsystems TSI specifies only those requirements which are necessary to assure the interoperability of the trans-European rail system and compliance with the essential requirements.
The Control-Command and Signalling Subsystems include the following parts:

1.  train protection;
2.  radio communication;
3.  train detection.

The Class A train protection system is ERTMS/ETCS whilst the Class A radio system is GSM-R.

For Class A train detection this TSI specifies only the requirements for the interface with other subsystems.

Class B systems are a limited set of train protection legacy control-command and signalling systems that were in use before 20 April 2001. The list of Class B systems is established in the European Railway Agency technical document ‘List of CCS Class B systems’, ERA/TD/2011-11, version 1.0.

The requirements for the Control-Command and Signalling On-board Subsystem are specified in relation to Class A radio mobiles and train protection.

The requirements for the Control-Command and Signalling Track-side Subsystem are specified in relation to:

1.  the Class A radio network;
2.  Class A train protection;
3.  the interface requirements for train detection systems, to ensure their compatibility with rolling stock.

## 2.3. Application levels (ERTMS/ETCS)

The interfaces specified by this TSI define the means of data transmission to, and (where appropriate) from trains. The ERTMS/ETCS specifications referenced by this TSI provide application levels from which a track-side implementation may choose the means of transmission that meet its requirements.

This TSI defines the requirements for all application levels.

A train equipped with Class A on-board train protection for a given application level must be able to operate on that level and any lower one. As a consequence:

-   a train equipped with Class A on-board train protection for level 2 must be able to operate on that level and on level 1 lines,
-   a train equipped with Class A on-board train protection for level 1 need not be equipped with a GSM-R data radio but must already implement all level 2 functions so as to ensure that the mere connection of a GSM-R data radio at a later stage will ensure it is equipped for level 2.

# 3. THE ESSENTIAL REQUIREMENTS FOR THE CONTROL-COMMAND AND SIGNALLING SUBSYSTEMS

## 3.1. General

The Railway Interoperability Directive requires that the subsystems and the interoperability constituents including interfaces meet the essential requirements set out in general terms in Annex III to the Directive.

The essential requirements are:

1.  Safety;
2.  Reliability and Availability;
3.  Health;
4.  Environmental Protection;
5.  Technical compatibility.

The essential requirements for Class A systems are described below.

The requirements for Class B systems are the responsibility of the relevant Member State.

## 3.2. Specific Aspects of the Control-Command and Signalling Subsystems

### 3.2.1. Safety

Every project to which this specification is applied shall take the measures necessary to ensure that the level of risk of an incident occurring within the scope of the Control-Command and Signalling Subsystems, is not higher than the objective for the service. For this purpose Commission Regulation (EC) No 352/2009 of 24 April 2009 on the adoption of a common safety method on risk evaluation and assessment as referred to in Article 6(3)(a) of Directive 2004/49/EC of the European Parliament and of the Council (2) (Common Safety Method) applies.

To ensure that the measures taken to achieve safety do not jeopardise interoperability, the requirements of the basic parameter defined in Section 4.2.1 (Control-Command and Signalling safety characteristics relevant to interoperability) shall be respected.

For the ERTMS/ETCS Class A system the safety objective is apportioned between the Control-Command and Signalling On-board and Track-side Subsystems. The detailed requirements are specified in the basic parameter defined in Section 4.2.1 (Control-Command and Signalling safety characteristics relevant to interoperability). This safety requirement must be met together with the availability requirements as defined in Section 3.2.2 (Reliability and Availability).

### 3.2.2. Reliability and Availability

For the Class A system, the reliability and availability objectives are apportioned between the Control-Command and Signalling On-board and Track-side Subsystems. The detailed requirements are specified in the basic parameter defined in Section 4.2.1 (Control-Command and Signalling safety characteristics relevant to interoperability).

The level of risk shall be monitored as constituents of the subsystem age and wear. The requirements for maintenance stated in Section 4.5 shall be respected.

### 3.2.3. Health

In accordance with EU regulations and with national regulations that are compatible with the European legislation, care shall be taken to ensure that the materials used in and the design of the Control-Command and Signalling Subsystems do not constitute a health hazard to persons having access to them.

### 3.2.4. Environmental Protection

In accordance with EU regulations and with national regulations that are compatible with European legislation:

1.  the Control-Command and Signalling equipment, if subjected to excessive heat or fire, shall not exceed limits for the emission of fumes or gases which are harmful to the environment;
2.  the Control-Command and Signalling equipment shall not contain substances which may abnormally contaminate the environment during their normal use;
3.  the Control-Command and Signalling equipment shall be subject to the European legislation in force controlling the limits to the emission of and the susceptibility to electromagnetic interference along the boundaries of railway property;
4.  the Control-Command and Signalling equipment shall comply with existing regulations on noise pollution;
5.  the Control-Command and Signalling equipment shall not give rise to any inadmissible level of vibration which could jeopardise the integrity of the infrastructure (when the infrastructure is in the correct state of maintenance).

### 3.2.5. Technical Compatibility

Technical compatibility includes the functions, interfaces and performances required to achieve interoperability.

The requirements of technical compatibility are subdivided in the following three categories:

1.  The first category sets out the general engineering requirements for interoperability namely environmental conditions, internal electromagnetic compatibility (EMC) within the railway boundaries, and installation. These compatibility requirements are defined in this chapter.
2.  The second category describes how the Control-Command and Signalling Subsystems have to be applied technically and what functions they have to perform to ensure interoperability. This category is defined in Chapter 4.
3.  The third category describes how the Control-Command and Signalling Subsystems have to be operated in order that interoperability is achieved. This category is defined in Chapter 4.

#### 3.2.5.1. Engineering Compatibility

##### 3.2.5.1.1. Physical environmental conditions

Control-Command and Signalling equipment shall be capable of operating under the climatic and physical conditions which characterise the area in which the relevant part of the trans-European rail system is located.

The requirements of basic parameter 4.2.16 (Environmental conditions) shall be respected.

##### 3.2.5.1.2. Railway Internal Electromagnetic Compatibility

In accordance with EU regulations and with national regulations that are compatible with the European legislation, the Control-Command and Signalling equipment shall neither interfere with nor be interfered with by other control-command and signalling equipment or other subsystems.

The basic parameter related for electromagnetic compatibility between rolling stock and control-command and signalling track-side equipment is described in Section 4.2.11 (Electromagnetic Compatibility).

#### 3.2.5.2. Control-Command and Signalling Compatibility

Chapter 4 defines the requirements for the interoperability of the Control-Command and Signalling Subsystems.

In addition, where the Control-Command and Signalling Subsystems are concerned, this TSI ensures technical interoperability between trans-European high-speed rail and conventional rail systems when both are fitted with Class A systems.

# 4. CHARACTERISATION OF THE SUBSYSTEMS

## 4.1. Introduction

In accordance with the relevant essential requirements, the Control-Command and Signalling Subsystems are characterised by the following basic parameters:

1.  Control-Command and Signalling safety characteristics relevant to interoperability (Section 4.2.1)
2.  On-board ERTMS/ETCS functionality (Section 4.2.2)
3.  Track-side ERTMS/ETCS functionality (Section 4.2.3)
4.  Mobile communication functions for railways – GSM-R (Section 4.2.4)
5.  ERTMS/ETCS and GSM-R air gap interfaces (Section 4.2.5)
6.  On-board interfaces Internal to Control-Command and Signalling (Section 4.2.6)
7.  Track-side interfaces Internal to Control-Command and Signalling (Section 4.2.7)
8.  Key management (Section 4.2.8)
9.  ETCS-ID management (Section 4.2.9)
10. Train detection systems (Section 4.2.10)
11. Electromagnetic compatibility between rolling stock and Control-Command and Signalling track-side equipment (Section 4.2.11)
12. ERTMS/ETCS DMI (driver machine interface) (Section 4.2.12)
13. GSM-R DMI (driver machine interface) (Section 4.2.13)
14. Interface to data recording for regulatory purposes (Section 4.2.14)
15. Visibility of track-side Control-Command and Signalling objects (Section 4.2.15)
16. Environmental conditions (Sections 4.2.16)

All requirements in Section 4.2 (Functional and technical specifications of the Subsystems) to meeting these basic parameters shall be applied to the Class A system.

Requirements for Class B systems and for STMs (which enable the Class A On-board system to operate on Class B infrastructure) are the responsibility of the appropriate Member State.

This TSI is based on the principles of enabling the Control-Command and Signalling Track-side Subsystem to be compatible with TSI compliant Control-Command and Signalling On-board Subsystems. To achieve this goal:

1.  functions, interfaces and performances of the Control-Command and Signalling On-board Subsystem are standardised, ensuring that every train will react in a predictable way to data received from track-side;
2.  for the Control-Command and Signalling Track-side Subsystem, track-to-train and train-to-track communication are fully standardised in this TSI. The specifications referenced in the sections below allow Control-Command and Signalling track-side functionality to be applied in a flexible way, so that it can be optimally integrated into the railway system. This flexibility shall be exploited without limiting the movement of TSI-compliant on-board subsystems.

The Control-Command and Signalling functions are classified in categories indicating whether they are optional (O) or mandatory (M). The categories are defined in Annex A 4.1a for ERTMS/ETCS and Annex A 4.1b for GSM-R and these texts also state how the functions are classified.

Annex A 4.1c provides the Glossary of ERTMS/ETCS terms and definitions, which are used in the specifications referred to in Annex A.
According to Section 2.2 (Scope) the Control-Command and Signalling Subsystems include three parts.

The following table indicates which basic parameters are relevant for each subsystem and for each part.

| Subsystem                                 | Part                | Basic parameters                                                 |
| ----------------------------------------- | ------------------- | ---------------------------------------------------------------- |
| Control-Command and Signalling On-board   | train protection    | 4.2.1, 4.2.2, 4.2.5, 4.2.6, 4.2.8, 4.2.9, 4.2.12, 4.2.14, 4.2.16 |
|                                           | radio communication | 4.2.4, 4.2.5, 4.2.6, 4.2.13, 4.2.14, 4.2.16                      |
| Control-Command and Signalling Track-side | train protection    | 4.2.3, 4.2.5, 4.2.7, 4.2.8, 4.2.9, 4.2.15, 4.2.16                |
|                                           | radio communication | 4.2.4, 4.2.5, 4.2.7, 4.2.16                                      |
|                                           | train detection     | 4.2.10, 4.2.11, 4.2.16                                           |

With respect to the essential requirements set out in Chapter 3, the functional and technical specifications of the Control-Command and Signalling Subsystems are as follows.

## 4.2. Functional and technical specifications of the Subsystems

### 4.2.1. Control-Command and Signalling safety characteristics relevant to interoperability

This basic parameter describes the requirements for the Control-Command and Signalling On-board Subsystem and Track-side subsystem with reference to Section 3.2.1 (Safety) and Section 3.2.2 (Availability and Reliability).

In order to achieve interoperability, when implementing Control-Command and Signalling On-board and Track-side subsystems the following provisions shall be respected:

1.  The design, implementation and use of a Control-Command and Signalling On-board or Track-side subsystem shall not export any requirements:

    <ol>
       <li type="a">across the interface between Control-Command and Signalling On-board and Track-side subsystems in addition to the requirements specified in this TSI;</li>
       <li type="a">to any other subsystem in addition to the requirements specified in the corresponding TSIs.</li>
    </ol>

2.  The requirements set out in Sections 4.2.1.1 and 4.2.1.2 below shall be respected.

#### 4.2.1.1. Safety

The Control-Command and Signalling On-board and Track-side subsystems shall respect the requirements for ERTMS/ETCS equipment and installations stated in this TSI.

For the hazard ‘exceeding speed and/or distance limits advised to ERTMS/ETCS’ the tolerable rate (THR) is 10– 9 h– 1 for random failures, for on-board ERTMS/ETCS and for track-side ERTMS/ETCS. See Annex A 4.2.1.a.

To achieve interoperability, the on-board ERTMS/ETCS shall fully respect all requirements specified in Annex A 4.2.1. Nevertheless, less stringent safety requirements are acceptable for track-side ERTMS/ETCS provided that, in combination with TSI-compliant Control-Command and Signalling On-board subsystems, the safety level for the service is met.

Requirements for hazards related to errors at the interface between driver and on-board ERTMS/ETCS are an open point.

#### 4.2.1.2. Availability/Reliability

The Control-Command and Signalling On-board and Track-side subsystems shall respect the requirements stated in this TSI. The availability/reliability requirements are defined in Annex A 4.2.1.b.

The level of risk shall be controlled during the life of the assemblies. The requirements for maintenance stated in Section 4.5 (Maintenance rules) shall be respected.

### 4.2.2. On-board ERTMS/ETCS functionality

The basic parameter for ERTMS/ETCS on-board functionality describes all of the functions needed to run a train in a safe way. The primary function is to provide automatic train protection and cab signalling:

1.  setting the train characteristics (e.g. maximum train speed, braking performance);
2.  selecting the supervision mode on the basis of information from track-side;
3.  performing odometry functions;
4.  locating the train in a coordinate system based on Eurobalise locations;
5.  calculating the dynamic speed profile for its mission on the basis of train characteristics and of information from track-side;
6.  supervising the dynamic speed profile during the mission;
7.  providing the intervention function.

These functions shall be implemented in accordance with Annex A 4.2.2.b and their performance shall conform to Annex A 4.2.2.a.

The requirements for tests are specified in Annex A 4.2.2.c.

The ETCS identities of equipment shall be managed in accordance with Section 4.2.9 (ETCS-ID management).

The main functionality is supported by other functions, to which Annex A 4.2.2.a and Annex A 4.2.2.b also apply, together with the additional specifications indicated below:

1.  Communication with the Control-Command and Signalling Track-side Subsystem.

    <ol>
       <li type="a">Eurobalise data transmission. See Section 4.2.5.2 (Eurobalise communication with the train);</li>
       <li type="a">Euroloop data transmission. See Section 4.2.5.3 (Euroloop communication with the train). This functionality is optional on-board unless Euroloop is installed track-side in ERTMS/ETCS Level 1 and the release speed is set to zero for safety reasons (e.g. protection of danger points);</li>
       <li type="a">Radio data transmission for radio in-fill. See Annex A 4.2.2.d, Section 4.2.5.1 (Radio communications with the train), Section 4.2.6.2 (Interface between GSM-R Radio Data Communication and ERTMS/ETCS) and Section 4.2.8 (Key Management). This functionality is optional on-board unless radio data transmission for radio in-fill is installed track-side in ERTMS/ETCS Level 1 and the release speed is set to zero for safety reasons (e.g. protection of danger points);</li>
       <li type="a">Radio data transmission. See Section 4.2.5.1 (Radio communications with the train), Section 4.2.6.2 (Interface between GSM-R Radio Data Communication and ERTMS/ETCS) and Section 4.2.8 (Key Management). Only mandatory on-board for ERTMS/ETCS Level 2 or ETCS Level 3 applications.</li>
    </ol>

2.  Communicating with the driver. See Annex A 4.2.2.e and Section 4.2.12 (ERTMS/ETCS DMI).
3.  Communicating with the STM. See Section 4.2.6.1 (Interface between ERTMS/ETCS and STM). This function includes:

    <ol>
       <li type="a">managing the STM output;</li>
       <li type="a">providing data to be used by the STM;</li>
       <li type="a">managing STM transitions.</li>
    </ol>

4.  Managing information about the completeness of the train (train integrity) — mandatory for level 3, not required for level 1 or 2.
5.  Equipment health monitoring and degraded mode support. This function includes:

    <ol>
       <li type="a">initialising the on-board ERTMS/ETCS functionality;</li>
       <li type="a">providing degraded mode support;</li>
       <li type="a">isolating the on-board ERTMS/ETCS functionality.</li>
    </ol>

6.  Support data recording for regulatory purposes. See Section 4.2.14 (Interface to Data Recording for Regulatory Purposes).
7.  Forwarding information/orders and receiving state information from rolling stock:

    <ol>
       <li type="a">to the DMI. See Section 4.2.12 (ERTMS/ETCS DMI);</li>
       <li type="a">to/from the train interface unit. See Annex A 4.2.2.f.</li>
    </ol>

### 4.2.3. Track-side ERTMS/ETCS functionality

This Basic parameter describes the ERTMS/ETCS track-side functionality. It contains all ERTMS/ETCS functionality to provide a safe path to a specific train.

The main functionality is:

1.  locating a specific train in a coordinate system based on Eurobalise locations (levels 2 and 3);
2.  translating the information from track-side signalling equipment into a standard format for the Control-Command and Signalling On-board Subsystem;
3.  sending movement authorities including track description and orders assigned to a specific train.

These functions shall be implemented in accordance with Annex A 4.2.3.b and their performance shall conform to Annex A 4.2.3.a.

The requirements for tests are specified in Annex A 4.2.3.c.

The ETCS identities of equipment shall be managed in accordance with Section 4.2.9 (ETCS-ID management).

The main functionality is supported by other functions, to which Annex A 4.2.3.a and Annex A 4.2.3.b also apply, together with the additional specifications indicated below:

1.  Communicating with the Control-Command and Signalling On-board Subsystem. This includes:

    <ol>
       <li type="a">Eurobalise data transmission. See Section 4.2.5.2 (Eurobalise communication with the train) and Section 4.2.7.4 (Eurobalise/Line-side Electronic Unit (LEU));</li>
       <li type="a">Euroloop data transmission. See Section 4.2.5.3 (Euroloop communication with the train) and Section 4.2.7.5 (Euroloop/LEU). Euroloop is only relevant in level 1, in which it is optional;</li>
       <li type="a">Radio data transmission for radio in-fill. See Annex A 4.2.3.d, Section 4.2.5.1 (Radio communications with the train), Section 4.2.7.3 (GSM-R/track-side ETCS functionality) and Section 4.2.8 (Key Management). Radio in-fill is only relevant in level 1, in which it is optional;</li>
       <li type="a">Radio data transmission. See Section 4.2.5.1 (Radio communications with the train), Section 4.2.7.3 (GSM-R/track-side ETCS functionality) and Section 4.2.8 (Key Management). Radio data transmission is only relevant to levels 2 and 3.</li>
    </ol>

2.  Generating information/orders to the on-board ERTMS/ETCS, e.g. information related to closing/opening the air flaps, lowering/raising the pantograph, opening/closing the main power switch, changing from traction system A to traction system B. Implementation of this functionality is optional for track-side.
3.  Managing the transitions between areas supervised by different Radio Block Centres (RBCs) (only relevant for levels 2 and 3). See Section 4.2.7.1 (Functional interface between RBCs) and Section 4.2.7.2 (Technical interface between RBCs).

### 4.2.4. Mobile communication functions for railways GSM-R

This basic parameter describes the radio communication functions. Such functions shall be implemented in the Control-Command and Signalling On-board and Track-side subsystems, according to the specifications indicated below.

#### 4.2.4.1. Basic communication function

The general requirements are specified in Annex A 4.2.4.a.

In addition, the following specifications shall be respected:

1.  ASCI features; Annex A 4.2.4.b;
2.  SIM card; Annex A 4.2.4.c;
3.  User-to-User Signalling; Annex A 4.2.4.d;
4.  location-dependent addressing; Annex A 4.2.4.e.

#### 4.2.4.2. Voice and operational communication applications

The general requirements are defined in Annex A 4.2.4.f.

The requirements for tests are specified in Annex A 4.2.4.g.

In addition, the following specifications shall be respected:

1.  confirmation of high-priority calls; Annex A 4.2.4.h;
2.  functional addressing; Annex A 4.2.4.j;
3.  presentation of functional numbers; Annex A 4.2.4.k.

#### 4.2.4.3. Data communication applications for ETCS

The general requirements are defined in Annex A 4.2.4.f.

The requirements for tests are specified in Annex A 4.2.4.g.

This functionality is mandatory only in the case of ETCS levels 2 and 3 and radio in-fill applications.

### 4.2.5. ERTMS/ETCS and GSM-R air gap interfaces

This basic parameter specifies the requirements for the air gap between Control-Command and Signalling Track-side and On-board subsystems and has to be taken into account in conjunction with the requirements for the interfaces between ERTMS/ETCS and GSM-R equipment, as specified in Section 4.2.6 (On-board Interfaces Internal to Control-Command and Signalling) and Section 4.2.7 (Track-side Interfaces Internal to Control-Command and Signalling).

This basic parameter includes:

1.  the physical, electrical and electromagnetic values to be respected to allow safe functioning;
2.  the communication protocol to be used;
3.  the availability of the communication channel.

The applicable specifications are listed below.

#### 4.2.5.1. Radio communications with the train

Class A radio communication interfaces shall operate in the GSM-R Band – see Annex A 4.2.5.a.

The protocols shall comply with Annex A 4.2.5.b.

Where radio in-fill is implemented, the requirements stated in Annex A 4.2.5.c shall be respected.

#### 4.2.5.2. Eurobalise communication with the train

Eurobalise communication interfaces shall comply with Annex A 4.2.5.d.

#### 4.2.5.3. Euroloop communication with the train

Euroloop communication interfaces shall comply with Annex A 4.2.5.e.

### 4.2.6. On-Board Interfaces Internal to Control-Command and Signalling

This Basic Parameter consists of three parts.

#### 4.2.6.1. ERTMS/ETCS and Class B train protection

Where ERTMS/ETCS and Class B train protection functions are installed on-board, the transitions between them can be managed with a standardised interface as specified in Annex A 4.2.6.a.

Annex A 4.2.6.b specifies the K-interface (to allow certain STMs to read information from Class B balises through the ERTMS/ETCS on-board antenna) and Annex A 4.2.6.c the G interface (air gap between ETCS on-board antenna and Class B balises).

Implementation of Interface ‘K’ is optional, but if done it must be in accordance with Annex A 4.2.6.b.

Furthermore, if Interface ‘K’ is implemented, the on-board transmission channel functionality must be able to handle the properties of Annex A 4.2.6.c.

If the transitions between ERTMS/ETCS and Class B train protection on-board are not managed using the standardised interface specified in Annex A 4.2.6.a, steps must be taken to ensure that the method used does not impose any additional requirements on the Control-Command and Signalling Track-side Subsystem.

#### 4.2.6.2. Interface between GSM-R Radio Data Communication and ERTMS/ETCS

The requirements for the interface between the Class A radio and the on-board ERTMS/ETCS functionality are specified in Annex A 4.2.6.d.

Where radio in-fill is implemented the requirements stated in Annex A 4.2.6.e shall be respected.

#### 4.2.6.3. Odometry

The interface between the odometry function and on-board ETCS shall meet the requirements of Annex A 4.2.6.f. This interface contributes to this Basic Parameter only when odometry equipment is supplied as a separate interoperability constituent (see Section 5.2.2, Grouping of interoperability constituents).

### 4.2.7. Track-side Interfaces Internal to Control-Command and Signalling

This Basic Parameter consists of five parts.

#### 4.2.7.1. Functional interface between RBCs

This interface defines the data to be exchanged between neighbouring RBCs to allow the safe movement of a train from one RBC area to the next:

1.  information from the ‘Handing Over’ RBC to the ‘Accepting’ RBC;
2.  information from the ‘Accepting’ RBC to the ‘Handing Over’ RBC.

The requirements are specified in Annex A 4.2.7.a.

#### 4.2.7.2. RBC/RBC

This is the technical interface between two RBCs. The requirements are specified in Annex A 4.2.7.b.

#### 4.2.7.3. GSM-R/track-side ETCS

This is the interface between the Class A radio system and the track-side ETCS functionality. The requirements are specified in Annex A 4.2.7.c.

#### 4.2.7.4. Eurobalise/LEU

This is the interface between Eurobalise and the LEU. The requirements are specified in Annex A 4.2.7.d.

This interface contributes to this basic parameter only when Eurobalise and LEU are supplied as separate interoperability constituents (see Section 5.2.2, Grouping of interoperability constituents).

#### 4.2.7.5. Euroloop/LEU

This is the interface between Euroloop and the LEU. The requirements are specified in Annex A 4.2.7.e.

This interface contributes to this Basic Parameter only when Euroloop and LEU are supplied as separate interoperability constituents (see Section 5.2.2, Grouping of interoperability constituents).

### 4.2.8. Key Management

This basic parameter specifies requirements for the management of cryptographic keys used for the protection of data transmitted via radio.

The requirements are specified in Annex A 4.2.8.a. Only requirements related to the interfaces of Control-Command and Signalling equipment fall within the scope of this TSI.

### 4.2.9. ETCS-ID Management

This basic parameter concerns the ETCS-identities (ETCS-IDs) for equipment in Control-Command and Signalling Track-side and On-board Subsystems.

The requirements are specified in Annex A 4.2.9.a.

### 4.2.10. Track-side Train Detection Systems

This basic parameter specifies the interface requirements between the track-side train detection systems and rolling stock.

The interface requirements to be respected by the train detection systems are specified in Annex A 4.2.10.a.

### 4.2.11. Electromagnetic Compatibility between Rolling Stock and Control-Command and Signalling track-side equipment

This basic parameter specifies the interface requirements for electromagnetic compatibility between rolling stock and track-side Control-Command and Signalling equipment.

The interface requirements to be respected by the train detection system are specified in Annex A 4.2.11.a

### 4.2.12. ERTMS/ETCS DMI (Driver Machine Interface)

This basic parameter describes the information provided from ERTMS/ETCS to the driver and entered into the on-board ERTMS/ETCS by the driver. See Annex A 4.2.12.a.

It includes:

1.  ergonomics (including visibility);
2.  ERTMS/ETCS functions to be displayed;
3.  ERTMS/ETCS functions triggered by driver input.

### 4.2.13. GSM-R DMI (Driver-Machine Interface)

This basic parameter describes the information provided from GSM-R to the driver and entered into the GSM-R on-board by the driver. See Annex A 4.2.13.a.

It includes:

1.  ergonomics (including visibility);
2.  GSM-R functions to be displayed;
3.  call-related information outgoing;
4.  call-related information incoming.

### 4.2.14. Interface to Data Recording for Regulatory Purposes

This basic parameter describes:

1.  data exchange between the on-board ERTMS/ETCS and the rolling stock recording device;
2.  communication protocols;
3.  physical interface.

See Annex A 4.2.14.a.

### 4.2.15. Visibility of track-side Control-Command and Signalling objects

This basic parameter describes:

1.  the characteristics of retro-reflecting signs to ensure correct visibility;
2.  the characteristics of interoperable marker boards.

See Annex A 4.2.15.a.

In addition, the installation of track-side Control-Command and Signalling objects shall be compatible with the driver’s field of view and the infrastructure requirements.

### 4.2.16. Environmental conditions

The environmental conditions mandated in the specifications referenced in this TSI shall be respected.

## 4.3. Functional and technical specifications of the interfaces to other Subsystems

### 4.3.1. Interface to the Traffic Operation and Management Subsystem

| Interface with Traffic Operation and Management TSI             |            |                                                    |            |
| --------------------------------------------------------------- | ---------- | -------------------------------------------------- | ---------- |
| **Reference CCS TSI**                                           |            | **Reference Traffic Operation and Management TSI** |            |
| **Parameter**                                                   | **Clause** | **Parameter**                                      | **Clause** |
| Operating rules (normal and degraded conditions)                | 4.4        | Rule book                                          | 4.2.1.2.1  |
| Visibility of track-side Control-Command and Signalling objects | 4.2.15     | Signal and line-side marker sighting               | 4.2.2.8    |
| Train braking performance and characteristics                   | 4.2.2      | Braking performance                                | 4.2.2.6    |
| Usage of sading equipement                                      |            |                                                    |            |
| On-board flange lubrication                                     | 4.2.10     | Rule book                                          | 4.2.1.2.1  |
| Use of composite brake blocks                                   |            |                                                    |            |
| Interface to Data Recording for Regulatory Purposes             | 4.2.14     | Data recording on-board                            | 4.2.3.5    |
| ETCS DMI                                                        | 4.2.12     | Train running number                               | 4.2.3.2.1  |
| GSM-R DMI                                                       | 4.2.13     | Train running number                               | 4.2.3.2.1  |

### 4.3.2. Interface to the Rolling Stock Subsystem

| Interface with Rolling Stock TSIs                                                                           |        |                                                                                                     |                                      |             |
| ----------------------------------------------------------------------------------------------------------- | ------ | --------------------------------------------------------------------------------------------------- | ------------------------------------ | ----------- |
| **Reference CCS TSI**                                                                                       |        | **Reference Rolling Stock TSIs**                                                                    |                                      |             |
| Parameter                                                                                                   | Clause | Parameter                                                                                           |                                      | Clause      |
| Compatibility with track-side train detection systems: vehicle design                                       | 4.2.10 | Rolling stock characteristics to be compatible with train detection systems based on track circuits | HR RS TSI                            |             |
|                                                                                                             |        |                                                                                                     | wheelset location                    | 4.2.7.9.2   |
|                                                                                                             |        |                                                                                                     | axle load                            | 4.2.3.3     |
|                                                                                                             |        |                                                                                                     | sanding                              | 4.2.3.2     |
|                                                                                                             |        |                                                                                                     | electrical resistance between wheels | 4.2.3.3.1   |
|                                                                                                             |        |                                                                                                     | LOC & PAS TSI                        | 4.2.3.3.1.1 |
|                                                                                                             |        |                                                                                                     | Wagon TSI                            |             |
|                                                                                                             |        | Rolling stock characteristics to be compatible with train detection systems based on axle counters  | HS RS TSI                            |             |
|                                                                                                             |        |                                                                                                     | wheelset geometry                    | 4.2.7.9.2   |
|                                                                                                             |        |                                                                                                     | wheels                               | 4.2.7.9.3   |
|                                                                                                             |        |                                                                                                     | LOC & PAS TSI                        | 4.2.3.3.1.2 |
|                                                                                                             |        |                                                                                                     | Wagon TSI                            | 4.2.3.3.1   |
|                                                                                                             |        | Rolling stock characteristics to be compatible with loop equipment                                  | HS RS TSI                            | None        |
|                                                                                                             |        |                                                                                                     | LOC & PAS TSI                        | 4.2.3.3.1.3 |
|                                                                                                             |        |                                                                                                     | Wagon TSI                            | None        |
| Electromagnetic compatibility between rolling stock and Control-Command and Signalling track-side equipment | 4.2.11 | Rolling stock characteristics to be compatible with train detection systems based on track circuits | HS RS TSI                            | 4.2.6.6.1   |
|                                                                                                             |        |                                                                                                     | LOC & PAS TSI                        | 4.2.3.3.1   |
|                                                                                                             |        |                                                                                                     | Wagon TSI                            | None        |
|                                                                                                             |        | Rolling stock characteristics to be compatible with train detection systems based on axle counters  | HS RS TSI                            | 4.2.6.6.1   |
|                                                                                                             |        |                                                                                                     | LOC & PAS TSI                        | 4.2.3.3.2   |
|                                                                                                             |        |                                                                                                     | Wagon TSI                            | None        |
| Train braking performance and characteristics                                                               | 4.2.2  | Emergency braking performance                                                                       | HS RS TSI                            |             |
|                                                                                                             |        |                                                                                                     | Emergency braking                    | 4.2.4.1     |
|                                                                                                             |        |                                                                                                     | Service braking                      | 4.2.4.4     |
|                                                                                                             |        |                                                                                                     | LOC & PAS TSI                        |             |
|                                                                                                             |        |                                                                                                     | Emergency braking                    | 4.2.4.5.2   |
|                                                                                                             |        |                                                                                                     | Service braking                      | 4.2.4.5.3   |
|                                                                                                             |        |                                                                                                     | Wagon TSI                            | 4.2.4.1.2   |
| Position of Control-Command and Signalling on-board antennas                                                | 4.2.2  | Kinematic gauge                                                                                     | HS RS TSI                            | 4.2.3.1     |
|                                                                                                             |        |                                                                                                     | LOC & PAS TSI                        | 4.2.3.1     |
|                                                                                                             |        |                                                                                                     | Wagon TSI                            | None        |
| Isolation of on-board ERTMS/ETCS functionality                                                              | 4.2.2  | Operating rules                                                                                     | HS RS TSI                            | 4.2.7.9.1   |
|                                                                                                             |        |                                                                                                     | LOC & PAS TSI                        | 4.2.12.3    |
|                                                                                                             |        |                                                                                                     | Wagon TSI                            | None        |
| Data interfaces                                                                                             | 4.2.2  | Monitoring and diagnostic concepts                                                                  | HS RS TSI                            | 4.2.7.10    |
|                                                                                                             |        |                                                                                                     | LOC & PAS TSI                        | 4.2.1.1     |
|                                                                                                             |        |                                                                                                     | Wagon TSI                            | None        |
| Visibility of track-side Control-Command and Signalling objects                                             | 4.2.15 | External visibility<br>Head lights                                                                  | HS RS TSI                            | 4.2.7.4.1.1 |
|                                                                                                             |        |                                                                                                     | LOC & PAS TSI                        | 4.2.7.1.1   |
|                                                                                                             |        |                                                                                                     | Wagon TSI                            | None        |
|                                                                                                             |        | Driver’s external field of view                                                                     | HS RS TSI                            |             |
|                                                                                                             |        |                                                                                                     | line of sight                        | 4.2.2.6 b   |
|                                                                                                             |        |                                                                                                     | windscreen                           | 4.2.2.7     |
|                                                                                                             |        |                                                                                                     | LOC & PAS TSI                        |             |
|                                                                                                             |        |                                                                                                     | line of sight                        | 4.2.9.1.3.1 |
|                                                                                                             |        |                                                                                                     | windscreen                           | 4.2.9.2     |
|                                                                                                             |        |                                                                                                     | Wagon TSI                            | None        |
| Interface to data recording for regulatory purposes                                                         | 4.2.14 | Recording device                                                                                    | HS RS TSI                            | 4.2.7.10    |
|                                                                                                             |        |                                                                                                     | LOC & PAS TSI                        | 4.2.9.6     |
|                                                                                                             |        |                                                                                                     | Wagon TSI                            | None        |
| Commands to rolling stock equipment                                                                         | 4.2.2  | Phase seperation                                                                                    | HS RS TSI                            | 4.2.8.3.6.7 |
|                                                                                                             | 4.2.3  |                                                                                                     | LOC & PAS TSI                        | 4.2.8.2.9.8 |
|                                                                                                             |        |                                                                                                     | Wagon TSI                            | None        |
| Emergency braking command                                                                                   | 4.2.2  | Emergency braking command                                                                           | HS RS TSI                            | None        |
|                                                                                                             |        |                                                                                                     | LOC & PAS TSI                        | 4.2.4.4.1   |
|                                                                                                             |        |                                                                                                     | Wagon TSI                            | None        |

### 4.3.3. Interfaces to Infrastructure Subsystem

| Interface with Infrastructure TSI                               |            |                                  |     |            |
| --------------------------------------------------------------- | ---------- | -------------------------------- | --- | ---------- |
| **Reference CCS TSI**                                           |            | **Reference Infrastructure TSI** |     |            |
| **Parameter**                                                   | **Clause** | **Parameter**                    |     | **Clause** |
| Train detection systems (space for installation)                | 4.2.10     | Minimum infrastructure gauge     | HS  | 4.2.3      |
|                                                                 |            | Structure gauge                  | CR  | 4.2.4.1    |
| Eurobalise communication (space for installation)               | 4.2.5.2    | Minimum infrastructure gauge     | HS  | 4.2.3      |
|                                                                 |            | Structure gauge                  | CR  | 4.2.4.1    |
| Euroloop communication (space for installation)                 | 4.2.5.3    | Minimum infrastructure gauge     | HS  | 4.2.3      |
|                                                                 |            | Structure gauge                  | CR  | 4.2.4.1    |
| Visibility of track-side Control-Command and Signalling objects | 4.2.15     | Minimum infrastructure gauge     | HS  | 4.2.3      |
|                                                                 |            | Structure gauge                  | CR  | 4.2.4.1    |

### 4.3.4. Interfaces to Energy Subsystem

| Interface with Energy TSI           |            |                            |            |            |
| ----------------------------------- | ---------- | -------------------------- | ---------- | ---------- |
| **Reference CCS TSI**               |            | **Reference Energy TSI**   |            |            |
| **Parameter**                       | **Clause** | **Parameter**              |            | **Clause** |
| Commands to rolling stock equipment | 4.2.2      | Phase separation sections  | HS ENE TSI | 4.2.21     |
|                                     | 4.2.3      | System separation sections |            | 4.2.22     |
|                                     |            | Phase separation sections  | CR ENE TSI | 4.2.19     |
|                                     |            | System separation sections |            | 4.2.20     |

## 4.4. Operating rules

The rules for operating a railway service with ERTMS/ETCS are specified in the Traffic Operation and Management TSI.

## 4.5. Maintenance rules

The maintenance rules of the subsystems covered by this TSI shall ensure that the values quoted in the basic parameters indicated in Chapter 4 are maintained within the required limits throughout the lifetime of the subsystems. However, during preventative or corrective maintenance, the subsystem may not be able to respect the values quoted in the basic parameters; the maintenance rules shall ensure that safety is not prejudiced during these activities.

The entity in charge of the Control-Command and Signalling Subsystems shall set up maintenance rules to achieve the above objectives. To assist with the preparation of these rules, the following requirements shall be respected.

### 4.5.1. Responsibility of the manufacturer of equipment

The manufacturer of equipment incorporated in the subsystem shall specify:

1.  all maintenance requirements and procedures (including health monitoring, diagnosis of events, test methods and tools and also the required professional competence) necessary for achieving essential requirements and values quoted in the mandatory requirements of this TSI throughout the equipment life-cycle (transport and storage before installation, normal operation, failures, repair work, checking and maintenance, decommissioning, etc.);
2.  the health and safety risks that may affect the public and the maintenance staff;
3.  the conditions for first line maintenance, i.e. the definition of Line Replaceable Units (LRUs), the definition of approved compatible versions of hardware and software, the procedures for replacing failed LRUs, and the conditions for storing LRUs and for repairing failed LRUs;
4.  the checks to be carried out if equipment is subject to exceptional stress (e.g. adverse environmental conditions or abnormal shocks);
5.  the checks to be carried out when maintaining equipment other than Control-Command and Signalling equipment and which influences the Control-Command and Signalling Subsystems (e.g. changing the wheel diameter).

### 4.5.2. Responsibility of the applicant for subsystem verification

The applicant shall:

1.  ensure that the maintenance requirements as described in Section 4.5.1 (Responsibility of the Manufacturer of Equipment) are defined for all components within the scope of this TSI regardless of whether or not they are interoperability constituents;
2.  complete the above requirements taking into account the risks arising from interactions between different components of the subsystem and interfaces to other subsystems.

## 4.6. Professional competences

The manufacturers of the equipment and of the subsystem shall provide information sufficient to define the professional competences required for the installation, final inspection and maintenance of the Control-Command and Signalling Subsystems. See Section 4.5 (Maintenance rules).

## 4.7. Health and safety conditions

Care shall be taken to ensure health and safety for maintenance and operations staff, in accordance with EU regulations and the national regulations that are compatible with the European legislation.

Manufacturers shall indicate the risks for health and safety that arise from using and maintaining their equipment and subsystems. See Section 4.4 (Operating rules) and Section 4.5 (Maintenance rules).

## 4.8. Registers

The data to be provided for the registers provided for in Articles 34 and 35 of Directive 2008/57/EC are those indicated in Commission Implementing Decision 2011/665/EU (3) and Commission Implementing Decision 2011/633/EU (4).

# 5. INTEROPERABILITY CONSTITUENTS

## 5.1. Definition

According to Article 2(f) of the Railway Interoperability Directive, interoperability constituents are ‘any elementary component, group of components, subassembly or complete assembly of equipment incorporated or intended to be incorporated into a subsystem, upon which the interoperability of the rail system depends either directly or indirectly. The concept of a constituent covers both tangible objects and intangible objects such as software.’

## 5.2. List of interoperability constituents

### 5.2.1. Basic interoperability constituents

The basic interoperability constituents in the Control-Command and Signalling Subsystems are defined in:

1.  Table 5.1.a for the Control-Command and Signalling On-board Subsystem;
2.  Table 5.2.a for the Control-Command and Signalling Track-side Subsystem.

### 5.2.2. Grouping of interoperability constituents

The functions of basic interoperability constituents may be combined to form a group. This group is then defined by those functions and by its remaining external interfaces. If a group is formed in this way, it shall be considered as an interoperability constituent.

1.  Table 5.1.b lists the groups of interoperability constituents of the Control-Command and Signalling On-board Subsystem.
2.  Table 5.2.b lists the groups of interoperability constituents of the Control-Command and Signalling Track-side Subsystem.

## 5.3. Constituents’ performance and specifications

For each basic interoperability constituent or group of interoperability constituents, the tables in Chapter 5 describe:

1.  in column 3, the functions and interfaces. Note that some interoperability constituents have functions and/or interfaces that are optional;
2.  in column 4, the mandatory specifications for the conformity assessment of each function or interface (where applicable) by reference to the relevant section of Chapter 4.

**_Table 5.1.a_**

 **Basic interoperability constituents in the Control-Command and Signalling On-board Subsystem**
 
| N | Interoperability constituent IC | Characteristics | Specific requirements to be assessed by reference to Chapter 4 |
\|---\|---\|---\|---\|
| 1 | ERTMS/ETCS on-board | Reliability, Availability, Maintainability, Safety (RAMS) | 4.2.1<br>4.5.1 |
| | | On-board ETCS functionality (excluding odometry) | 4.2.2 |
| | | ERTMS/ETCS and GSM-R air gap interfaces | 4.2.5 |
| | | - RBC (levels 2 and 3) | 4.2.5.1 |
| | | - Radio in-fill unit (optional level 1) | 4.2.5.1 |
| | | - Eurobalise air gap | 4.2.5.2 |
| | | - Euroloop air gap (optional level 1) | 4.2.5.3 |
| | | Interfaces |
| | | - STM (implementation of interface K optional) | 4.2.6.1 |
| | | - ERTMS/ETCS GSM-R on-board | 4.2.6.2 |
| | | - Odometry | 4.2.6.3 |
| | | - Key management system | 4.2.8 |
| | | - ETCS ID Management | 4.2.9 |
| | | - ERTMS/ETCS Driver-Machine Interface | 4.2.12 |
| | | - Train interface | 4.2.2 |
| | | - On-board recording device | 4.2.14 |
| | | Physical environmental conditions | 4.2.16 |
| 2 | Odometry equipment | Reliability, Availability, Maintainability, Safety (RAMS) | 4.2.1<br>4.5.1 |
| | | On-board ERTMS/ETCS functionality: only Odometry | 4.2.2 |
| | | Interfaces |
| | | - On-board ERTMS/ETCS | 4.2.6.3 |
| | | Environmental conditions | 4.2.16 |
| 3 | Interface of External STM | Interfaces | |
| | | -On-board ERTMS/ETCS | 4.2.6.1 |
| 4 | GSM-R voice cab radio<br>Note: SIM card, antenna, connecting cables and filters are not part of this interoperability constituent | Reliability, Availability, Maintainability, Safety (RAMS)<br>Note: no requirement for safety | 4.2.1<br>4.5.1 |
| | | Basic communication functions | 4.2.4.1 |
| | | Voice and operational communication applications | 4.2.4.2 |
| | | Interfaces |
| | | - GSM-R air gap | 4.2.5.1 |
| | | - GSM-R Driver-Machine Interface | 4.2.13 |
| | | Environmental conditions | 4.2.16 |
| 5 | GSM-R ETCS Data only Radio<br>Note: SIM card, antenna, connecting cables and filters are not part of this interoperability constituent | Reliability, Availability, Maintainability, Safety (RAMS)<br>Note: no requirement for safety | 4.2.1<br>4.5.1 |
| | | Basic communication functions | 4.2.4.1 |
| | | ETCS data communication applications | 4.2.4.3 |
| | | Interfaces |
| | | - On-board ERTMS/ETCS | 4.2.6.2 |
| | | - GSM-R air gap | 4.2.5.1 |
| | | Environmental conditions | 4.2.16 |
| 6 | GSM-R SIM card | Basic communication functions | 4.2.4.1 |
| | | Environmental conditions | 4.2.16 |

**_Table 5.1.b_**

**Groups of interoperability constituents in the Control-Command and Signalling On-board Subsystem**

This table is an example to show the structure. Other groups are allowed

| N   | Group of Interoperability constituents    | Characteristics                                           | Specific requirements to be assessed by reference to Chapter 4 |
| --- | ----------------------------------------- | --------------------------------------------------------- | -------------------------------------------------------------- |
| 1   | ERTMS/ETCS on-board<br>Odometry equipment | Reliability, Availability, Maintainability, Safety (RAMS) | 4.2.1<br>4.5.1                                                 |
|     |                                           | On-board ERTMS/ETCS functionality                         | 4.2.2                                                          |
|     |                                           | ERTMS/ETCS and GSM-R air gap interfaces                   | 4.2.5                                                          |
|     |                                           | - RBC (levels 2 and 3)                                    | 4.2.5.1                                                        |
|     |                                           | - Radio in-fill unit (optional level 1)                   | 4.2.5.1                                                        |
|     |                                           | - Eurobalise air gap                                      | 4.2.5.2                                                        |
|     |                                           | - Euroloop air gap (optional level 1)                     | 4.2.5.3                                                        |
|     |                                           | Interfaces                                                |                                                                |
|     |                                           | - STM (implementation of interface K optional)            | 4.2.6.1                                                        |
|     |                                           | - On-board ERTMS/ETCS – GSM-R                             | 4.2.6.2                                                        |
|     |                                           | - Key management system                                   | 4.2.8                                                          |
|     |                                           | - ETCS-ID Management                                      | 4.2.9                                                          |
|     |                                           | - ERTMS/ETCS Driver Machine Interface                     | 4.2.12                                                         |
|     |                                           | - Train interface                                         | 4.2.2                                                          |
|     |                                           | - On-board recording device                               | 4.2.14                                                         |
|     |                                           | Physical environmental conditions                         | 4.2.16                                                         |

**_Table 5.2.a_**
**Basic interoperability constituents in the Control-Command and Signalling Track-side Subsystem**

| N   | Interoperability constituent IC | Characteristics                                                                                                                   | Specific requirements to be assessed by reference to Chapter 4 |                          |        |
| --- | ------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------- | ------------------------ | ------ |
| 1   | RBC                             | Reliability, Availability, Maintainability, Safety (RAMS)                                                                         | 4.2.1<br>4.5.1                                                 |                          |        |
|     |                                 | Track-side ERTMS/ETCS functionality (excluding communication via Eurobalises, radio in-fill and Euroloop)                         | 4.2.3                                                          |                          |        |
|     |                                 | ERTMS/ETCS and GSM-R air gap interfaces: only radio communication with train                                                      | 4.2.5.1                                                        |                          |        |
|     |                                 | Interfaces                                                                                                                        |                                                                |                          |        |
|     |                                 | - Neighbouring RBC                                                                                                                | 4.2.7.1, 4.2.7.2                                               |                          |        |
|     |                                 | - ERTMS/ETCS GSM-R track-side                                                                                                     | 4.2.7.3                                                        |                          |        |
|     |                                 | - Key management system                                                                                                           | 4.2.8                                                          |                          |        |
|     |                                 | - ETCS-ID Management                                                                                                              | 4.2.9                                                          |                          |        |
|     |                                 | Environmental conditions                                                                                                          | 4.2.16                                                         |                          |        |
| 2   | Radio in-fill unit              | Reliability, Availability, Maintainability, Safety (RAMS)                                                                         | 4.2.1<br>4.5.1                                                 |                          |        |
|     |                                 | Track-side ERTMS/ETCS functionality (excluding communication via Eurobalises, Euroloop and level 2/3 functionality)               | 4.2.3                                                          |                          |        |
|     |                                 | ERTMS/ETCS and GSM-R air gap interfaces: only radio communication with train                                                      | 4.2.5.1                                                        |                          |        |
|     |                                 | Interfaces                                                                                                                        |                                                                |                          |        |
|     |                                 | - ERTMS/ETCS- GSM-R track-side                                                                                                    | 4.2.7.3                                                        |                          |        |
|     |                                 | - Key management system                                                                                                           | 4.2.8                                                          |                          |        |
|     |                                 | - ETCS-ID Management                                                                                                              | 4.2.9                                                          |                          |        |
|     |                                 | - Interlocking and LEU                                                                                                            | 4.2.3                                                          |                          |        |
|     |                                 | Environmental conditions                                                                                                          | 4.2.16                                                         |                          |        |
| 3   | Eurobalise                      | Reliability, Availability, Maintainability, Safety (RAMS)                                                                         | 4.2.1<br>4.5.1                                                 |                          |        |
|     |                                 | ERTMS/ETCS and GSM-R air gap interfaces: only Eurobalise communication with train                                                 | 4.2.5.2                                                        |                          |        |
|     |                                 | Interfaces                                                                                                                        |                                                                |                          |        |
|     |                                 | - LEU – Eurobalise                                                                                                                | 4.2.7.4                                                        | Environmental conditions | 4.2.16 |
| 4   | Euroloop                        | Reliability, Availability, Maintainability, Safety (RAMS)                                                                         | 4.2.1<br>4.5.1                                                 |                          |        |
|     |                                 | ERTMS/ETCS and GSM-R air gap interfaces: only Euroloop communication with train                                                   | 4.2.5.3                                                        |                          |        |
|     |                                 | Interfaces                                                                                                                        |                                                                |                          |        |
|     |                                 | - LEU – Euroloop                                                                                                                  | 4.2.7.5                                                        |                          |        |
|     |                                 | Environmental conditions                                                                                                          | 4.2.16                                                         |                          |        |
| 5   | LEU Eurobalise                  |                                                                                                                                   |                                                                |                          |        |
|     |                                 | Reliability, Availability, Maintainability, Safety (RAMS)                                                                         | 4.2.1<br>4.5.1                                                 |                          |        |
|     |                                 | Track-side ERTMS/ETCS functionality (excluding communication via radio in-fill, Euroloop and level 2 and level 3 functionality)   | 4.2.3                                                          |                          |        |
|     |                                 | Interfaces                                                                                                                        |                                                                |                          |        |
|     |                                 | - LEU – Eurobalise                                                                                                                | 4.2.7.4                                                        |                          |        |
|     |                                 | Environmental conditions                                                                                                          | 4.2.16                                                         |                          |        |
| 6   | LEU Euroloop                    | Reliability, Availability, Maintainability, Safety (RAMS)                                                                         | 4.2.1<br>4.5.1                                                 |                          |        |
|     |                                 | Track-side ERTMS/ETCS functionality (excluding communication via radio in-fill, Eurobalise and level 2 and level 3 functionality) | 4.2.3                                                          |                          |        |
|     |                                 | Interfaces                                                                                                                        |                                                                |                          |        |
|     |                                 | - LEU – Euroloop                                                                                                                  | 4.2.7.5                                                        |                          |        |
|     |                                 | Environmental conditions                                                                                                          | 4.2.16                                                         |                          |        |

**_Table 5.2.b_**

**Groups of interoperability constituents in the Control-Command and Signalling Track-side Subsystem**

This table is an example to show the structure. Other groups are allowed

| N   | Group of interoperability constituents | Characteristics                                                                                                     | Specific requirements to be assessed by reference to Chapter 4 |
| --- | -------------------------------------- | ------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------- |
| 1   | Eurobalise<br>LEU Eurobalise           | Reliability, Availability, Maintainability, Safety (RAMS)                                                           | 4.2.1<br>4.5.1                                                 |
|     |                                        | Track-side ERTMS/ETCS functionality (excluding communication via Euroloop and level 2 and level 3 functionality)    | 4.2.3                                                          |
|     |                                        | ERTMS/ETCS and GSM-R air gap interfaces: only Eurobalise communication with train                                   | 4.2.5.2                                                        |
|     |                                        | Environmental conditions                                                                                            | 4.2.16                                                         |
| 2   | Euroloop<br>LEU Euroloop               | Reliability, Availability, Maintainability, Safety (RAMS)                                                           | 4.2.1<br>4.5.1                                                 |
|     |                                        | Track-side ERTMS/ETCS functionality, (excluding communication via Eurobalise and level 2 and level 3 functionality) | 4.2.3                                                          |
|     |                                        | ERTMS/ETCS and GSM-R air gap interfaces: only Euroloop communication with train                                     | 4.2.5.3                                                        |
|     |                                        | Environmental conditions                                                                                            | 4.2.16                                                         |

# 6. ASSESSING THE CONFORMITY AND/OR SUITABILITY FOR USE OF THE CONSTITUENTS AND VERIFYING THE SUBSYSTEMS

## 6.1. Introduction

### 6.1.1. General principles

Fulfilment of the essential requirements set out in Chapter 3 of this TSI shall be ensured through compliance with the basic parameters specified in Chapter 4.

This compliance shall be demonstrated by:

1.  assessing the conformity of the interoperability constituents specified in Chapter 5 (see Section 6.2);
2.  verifying the subsystems (see Section 6.3).

In certain cases, however, some of the essential requirements may be met by national rules, because of:

1.  the use of Class B systems;
2.  open points in the TSI;
3.  derogations pursuant to Article 9 of the Railway Interoperability Directive;
4.  specific cases described in Section 7.2.9.

In such cases, assessment of conformity with those rules shall be carried out under the responsibility of the Member States concerned according to notified procedures.

### 6.1.2. Principles for testing ERTMS/ETCS and GSM-R

A Control-Command and Signalling On-board Subsystem covered by an ‘EC’ declaration of verification should be able to run on every Control-Command and Signalling Track-side Subsystem covered by an ‘EC’ Declaration of verification, under the conditions specified in this TSI, with no additional verifications.

Achievement of this goal is facilitated by:

1.  rules for the design and installation of the Control-Command and Signalling On-board and the Track-side subsystems;
2.  test specifications to prove that the Control-Command and Signalling On-board and Track-side Subsystems comply with the requirements of this TSI and are mutually compatible.

To make the conformity assessment of ERTMS/ETCS and GSM-R equipment more effective and to help achieve the goal mentioned above, each Member State shall make available to the Commission the operational test scenarios for checking the ERTMS/ETCS and GSM-R part of the Control-Command and Signalling Track-side Subsystem and its interaction with the corresponding part of the Control-Command and Signalling On-board Subsystem. The test scenarios in question:

1.  shall be consistent with the specifications referenced in this TSI and provide a technical description of functions and performances (e.g. reaction times) where these are relevant for the interaction between on-board and track-side subsystems;
2.  shall be submitted in a standard format. See Annex A 4.2.2.c;
3.  shall, unless otherwise specified in Annex A 4.2.2.c, cover at least the start of mission, the transition between levels, transition between modes that may be used on the line, the main identified degraded situations, the sending of emergency messages and any other relevant aspects specific to the line.

The European Railway Agency:

1.  shall make a preliminary publication of the operational test scenarios, allowing all interested parties to comment on the consistency of the test scenarios with the specifications referenced in this TSI and their impact on other implementations or developments. The period for comments shall be defined with each publication and shall not exceed 6 months;
2.  if the comments are negative, shall coordinate the efforts of the parties involved, in order to find an agreement, e.g. by changing the operational test scenarios;
3.  shall progressively build and make publicly available a database of test scenarios that have successfully passed the step described above and representing the situations which occur in different implementations;
4.  shall use the abovementioned data base to assess whether further mandatory test specifications are needed and whether it is necessary to draw up additional engineering rules for the Control-Command and Signalling On-board and Track-side subsystems.

## 6.2. Interoperability constituents

### 6.2.1. Assessment procedures for Control-Command and Signalling Interoperability Constituents

Before placing on the market an interoperability constituent and/or groups of interoperability constituents the manufacturer or his authorised representative established within the European Union shall draw up an ‘EC’ declaration of conformity in accordance with Article 13(1) and Annex IV to the Railway Interoperability Directive.

The assessment procedure shall be carried out using one of the modules specified in Section 6.2.2 (Modules for Control-Command and Signalling Interoperability Constituents).

An ‘EC’ declaration of suitability for use is not required for Control-Command and Signalling interoperability constituents, because they have to fully comply with all the relevant basic parameters. This compliance is demonstrated by the ‘EC’ Declaration of conformity and is sufficient for placing them on the market (5).

### 6.2.2. Modules for Control-Command and Signalling Interoperability Constituents

For assessing interoperability constituents within the Control-Command and Signalling Subsystems, the manufacturer or his authorised representative established within the European Union, may choose:

1.  either the type-examination procedure (Module CB) for the design and development phase in combination with the production quality management system procedure (Module CD) for the production phase; or
2.  the type-examination procedure (Module CB) for the design and development phase in combination with the product verification procedure (Module CF); or
3.  the full quality management system with design examination procedure (Module CH1).

In addition, for checking the SIM card Interoperability Constituent, the manufacturer or his representative may choose module CA.

The modules are described in detail in Commission Decision 2010/713/EU of 9 November 2010 on modules for the procedures for assessment of conformity, suitability for use and ‘EC’ verification to be used in the technical specifications for interoperability adopted under Directive 2008/57/EC of the European Parliament and of the Council (6).

The following clarifications apply to the use of some of the modules:

1.  with reference to Chapter 2 of the ‘Module CB’, ‘EC’-type examination must be carried out through a combination of production type and design type;
2.  with reference to Chapter 3 of the ‘Module CF’ (product verification) statistical verification is not allowed, i.e. all interoperability constituents must be individually examined.

### 6.2.3. Assessment requirements

Independently of the selected module:

1.  the requirements stated in Section 6.2.4.1 of this TSI shall be respected for the ‘On-board ERTMS/ETCS’ interoperability constituent;
2.  the activities shown in Table 6.1 shall be carried out when assessing the conformity of an interoperability constituent or a group of interoperability constituents as defined in Chapter 5 of this TSI. All verifications shall be carried out by reference to the applicable table in Chapter 5 and the basic parameters indicated there.

_Table 6.1_

| Aspect                                                    | What to assess                                                                                                                                                                                                                                                                                                  | supporting evidence                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| --------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Functions, interfaces and performances                    | Check that all mandatory functions, interfaces and performances as described in the basic parameters referenced in the relevant table of Chapter 5 are implemented and that they comply with the requirements of this TSI                                                                                       | Design documentation and running of test cases and test scenarios, as described in the basic parameters referenced in the relevant table of Chapter 5                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
|                                                           | Check which optional functions and interfaces as described in the basic parameters referenced in the relevant table of Chapter 5 are implemented and that they comply with the requirements of this TSI                                                                                                         | Design documentation and running of test cases and test scenarios, as described in the basic parameters referenced in the relevant table of Chapter 5                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
|                                                           | Check which additional functions and interfaces (not specified in this TSI) are implemented and that they do not lead to conflicts with implemented functions specified in this TSI                                                                                                                             | Impact analysis                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| Environment                                               | Check compliance with mandatory environmental conditions, where specified in the basic parameters referenced in the relevant table of Chapter 5                                                                                                                                                                 | Tests, to ensure that the requirements of the basic parameters referenced in the relevant table of Chapter 5 are satisfied                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
|                                                           | In addition, check that the interoperability constituent functions correctly in the environmental conditions for which it is designed                                                                                                                                                                           | Tests according to the applicant’s specifications                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| Reliability, Availability, Maintainability, Safety (RAMS) | Check compliance with the safety requirements described in the basic parameters referenced in the relevant table of Chapter 5, i.e.:<br>1. respect for quantitative Tolerable Hazard Rates (THRs) caused by random failures;<br>2. the development process is able to detect and eliminate systematic failures. | 1. Calculations for the THRs caused by random failures, based on supportable sources of reliability data.<br>2.1. The manufacturer’s quality and safety management throughout design, manufacturing and testing conforms to a recognised standard (see Note).<br>2.2. The software development life-cycle, the hardware development life-cycle and the integration of hardware and software have each been undertaken in accordance with a recognised standard (see Note).<br>2.3. The safety verification and validation process has been undertaken in accordance with a recognised standard (see Note) and respects the safety requirements described in the basic parameters referenced in the relevant table of Chapter 5.<br>2.4. The functional and technical safety requirements (correct operation under fault-free conditions, effects of faults and of external influences) are verified in accordance with a recognised standard (see Note).<br>Note: The standard shall satisfy at least the following requirements:<br>1. be widely acknowledged in the railway domain. If this is not the case, the standard will have to be justified and be acceptable to the notified body;<br>2. be relevant for the control of the considered hazards in the system under assessment;<br>3. be publicly available for all actors who want to use it.<br>See Annex A, Table A 3. |
|                                                           | Check that the quantitative reliability target indicated by the applicant is met                                                                                                                                                                                                                                | Calculations                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
|                                                           | Check compliance with maintenance requirements – Section 4.5.1                                                                                                                                                                                                                                                  | Document check                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |

### 6.2.4. Special issues

#### 6.2.4.1. The on-board ERTMS/ETCS

Particular attention shall be given to assessing the conformity of the on-board ERTMS/ETCS interoperability constituent, since it is complex and plays a key role in achieving interoperability.

Regardless of whether module CB or CH1 is chosen, the Notified Body shall check that a specimen of the interoperability constituent has passed the full set of mandatory test sequences referenced in Section 4.2.2 (on-board ERTMS/ETCS functionality) and that these tests were carried out in a laboratory accredited to carry out this type of tests in accordance with Regulation (EC) No 765/2008 of the European Parliament and of the Council of 9 July 2008 setting out the requirements for accreditation and market surveillance relating to the marketing of products and repealing Regulation (EEC) No 339/93 (7).

In addition, to increase confidence that the on-board ERTMS/ETCS can be correctly operated with different track-side applications, it is recommended that the on-board ERTMS/ETCS be tested using scenarios from the data base managed by the Agency and which are not part of the mandatory test specifications; see Section 6.1.2 (Principles for testing ERTMS/ETCS and GSM-R). The documentation accompanying the certificate shall indicate the database scenarios against which the interoperability constituent has been checked.

#### 6.2.4.2. The Specific Transmission Module (STM)

Each Member State shall be responsible for verifying that STMs conform to its national requirements.

Verification of the STM interface to the on-board ERTMS/ETCS requires a conformity assessment carried out by a Notified Body.

#### 6.2.4.3. Content of the ‘EC’ Declaration of conformity

The ‘EC’ Declaration of conformity specified in Annex IV to the Railway Interoperability Directive shall include the following details concerning the interoperability constituent:

1.  which optional and additional functions are implemented;
2.  the applicable environmental conditions.

## 6.3. Control-Command and Signalling Subsystems

### 6.3.1. Assessment procedures for Control-Command and Signalling Subsystems

This chapter deals with the ‘EC’ declaration of verification for the Control-Command and Signalling On-board Subsystem and the ‘EC’ declaration of verification for the Control-Command and Signalling Track-side Subsystem.

At the request of the applicant the Notified Body shall carry an ‘EC’ verification of a Control-Command and Signalling On-board or Track-side Subsystem in accordance with Annex VI to the Railway Interoperability Directive.

The applicant shall draw up the ‘EC’ declaration of verification for the Control-Command and Signalling On-board or Track-side Subsystem in accordance with Article 18(1) and Annex V to the Railway Interoperability Directive.
The content of the ‘EC’ declaration of verification shall conform to Annex V to the Railway Interoperability Directive.

The assessment procedure shall be carried out by using one of the modules as specified in Section 6.3.2 (Modules for Control-Command and Signalling Subsystems).

The ‘EC’ declarations of verification for a Control-Command and Signalling On-board Subsystem and of a Control-Command and Signalling Track-side Subsystem, together with the certificates of conformity, shall be deemed sufficient to ensure that the subsystems are compatible under the conditions specified in this TSI.

### 6.3.2. Modules for Control-Command and Signalling Subsystems

All modules indicated below are specified in the Decision 2010/713/EU.

#### 6.3.2.1. On-board Subsystem

For verifying the Control-Command and Signalling On-board Subsystem, the applicant may choose either:

1.  the type-examination procedure (Module SB) for the design and development phase in combination with the production quality management system procedure (Module SD) for the production phase; or
2.  the type-examination procedure (Module SB) for the design and development phase in combination with the product verification procedure (Module SF); or
3.  the full quality management system with design examination procedure (Module SH1).

#### 6.3.2.2. Track-side Subsystem

For verifying the Control-Command and Signalling Track-side Subsystem, the applicant may choose either:

1.  the unit verification procedure (Module SG); or
2.  the type-examination procedure (Module SB) for the design and development phase in combination with the production quality management system procedure (Module SD) for the production phase; or
3.  the type-examination procedure (Module SB) for the design and development phase in combination with the product verification procedure (Module SF); or
4.  the full quality management system with design examination procedure (Module SH1).

#### 6.3.2.3. Conditions for using modules for On-board and Track-side Subsystems

With reference to Section 4.2 of Module SB (type-examination), design review is requested.

With reference to Section 4.2 of Module SH1 (full quality management system with design examination), a type test is required.

### 6.3.3. Assessment requirements for an On-board Subsystem

Table 6.2 shows the checks that must be carried out when verifying a Control-Command and Signalling On-board Subsystem and the basic parameters that must be respected.

Independently of the module chosen:

1.  verification shall demonstrate that the Control-Command and Signalling On-board Subsystem complies with basic parameters when it is integrated into the vehicle;
2.  the functionality and performances of interoperability constituents already covered by their EC Declaration of conformity do not require additional verifications.

_Table 6.2_

| Aspect                                                                                                                            | What to assess                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | supporting evidence                                                                                                                                                                                                          |
| --------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Use of interoperability constituents                                                                                              | Check whether the interoperability constituents to be integrated into the subsystem are all covered by an ‘EC’ Declaration of conformity and a corresponding certificate.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | Existence and content of documents                                                                                                                                                                                           |
|                                                                                                                                   | Check restrictions on the use of Interoperability Constituents against the characteristics of the subsystem and of the environment                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | Analysis by document check                                                                                                                                                                                                   |
|                                                                                                                                   | For interoperability constituents that have been certified against older versions of the CCS TSI, check that the certificate still ensures compliance with the requirements of the TSI currently in force.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | Impact analysis by document checks                                                                                                                                                                                           |
| Integration of interoperability constituents in the subsystem                                                                     | Check the correct installation and functioning of the internal interfaces of the subsystem – Basic parameters 4.2.6                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | Checks according to specifications                                                                                                                                                                                           |
|                                                                                                                                   | Check that additional functions (not specified in this TSI) do not impact the mandatory ones                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | Impact analysis                                                                                                                                                                                                              |
|                                                                                                                                   | Check that the values of ETCS IDs are within the allowed range – Basic parameter 4.2.9                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | Check of design specifications                                                                                                                                                                                               |
| Integration with rolling stock                                                                                                    | Check the correct installation of equipment – Basic Parameters 4.2.2, 4.2.4, 4.2.14 and conditions for installation of equipment, as specified by the manufacturer                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | Results of checks (according to specifications referenced in the Basic Parameters and the manufacturer’s installation rules)                                                                                                 |
|                                                                                                                                   | Check that the Control-Command and Signalling On-board Subsystem is compatible with the rolling stock environment                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | Document check (certificates of interoperability constituents and possible integration methods checked against characteristics of rolling stock)                                                                             |
|                                                                                                                                   | Check that parameters (e.g. braking parameters) are correctly configured and that they are within the allowed range                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | Document check (values of parameters checked against characteristics of rolling stock)                                                                                                                                       |
| Integration with Class B                                                                                                          | Check that the external STM is connected to on-board ERTMS/ETCS with TSI-compliant interfaces                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | Nothing to test: there is a standard interface already tested at interoperability constituent level. Its functioning has already been tested when checking the integration of interoperability constituents in the subsystem |
|                                                                                                                                   | Check that Class B functions implemented in the on-board ERTMS/ETCS – Basic parameter 4.2.6.1 – create no additional requirements for the Control-Command and Signalling Track-side Subsystem due to transitions                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | Nothing to test: everything has already been tested at interoperability constituent level                                                                                                                                    |
|                                                                                                                                   | Check that separate Class B equipment which is not connected to the on-board ERTMS/ETCS – Basic Parameter 4.2.6.1 – creates no additional requirements for Control-Command and Signalling Track-side Subsystem due to transitions                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | Nothing to test: no interface (8)                                                                                                                                                                                            |
|                                                                                                                                   | Check that separate Class B equipment connected on-board ERTMS/ETCS using (partly) non-TSI compliant interfaces – basic parameter 4.2.6.1 – creates no additional requirements for the Control-Command and Signalling Track-side Subsystem due to transitions. Also check that ERTMS/ETCS functions are not affected                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | Impact analysis                                                                                                                                                                                                              |
| Integration with Control-Command and Signalling Track-side Subsystems                                                             | Check that Eurobalise telegrams can be read (scope of this test is limited to checking that the antenna has been appropriately installed. The tests already carried out at Interoperability Constituent level should not be repeated) – Basic Parameter 4.2.5                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | Test using a certified Eurobalise: the ability to read correctly the telegram is the supporting evidence.                                                                                                                    |
|                                                                                                                                   | Check that Euroloop telegrams (if applicable) can be read – Basic Parameter 4.2.5                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | Test using a certified Euroloop: the ability to read correctly the telegram is the supporting evidence.                                                                                                                      |
|                                                                                                                                   | Check that the equipment can handle a GSM-R call for voice and data (if applicable) – Basic Parameter 4.2.5                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | Test with a certified GSM-R network. The ability to set up, maintain and disconnect a connection is the supporting evidence.                                                                                                 |
| Reliability, Availability, Maintainability, Safety (RAMS)                                                                         | Check that the equipment complies with safety requirements – Basic Parameter 4.2.1                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | Application of procedures specified in the Common Safety Method                                                                                                                                                              |
|                                                                                                                                   | Check that the quantitative reliability target is met – Basic Parameter 4.2.1                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | Calculations                                                                                                                                                                                                                 |
|                                                                                                                                   | Check the compliance with requirements about maintenance – Section 4.5.2                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | Documents check                                                                                                                                                                                                              |
| Integration with Control-Command and Signalling Track-side Subsystems and other subsystems:<br>tests under operational conditions | Test the behaviour of the subsystem under as many different operational conditions as reasonably possible (e.g. line gradient, train speed, vibrations, traction power, weather conditions, design of Control-Command and Signalling track-side functionality). The test must be able to verify:<br>1. that odometry functions are correctly performed – basic parameter 4.2.2<br>2. that the on-board Control-Command and Signalling Subsystem is compatible with the rolling stock environment – basic parameter 4.2.16<br>These tests must also be such as to increase confidence that there will be no systematic failures. The scope of these tests excludes tests already carried out at earlier stages: tests performed on the interoperability constituents and tests performed on the subsystem in a simulated environment shall be taken into account. Tests under operational conditions are not necessary for on-board GSM-R voice equipment. | Reports of test runs.<br>Note: Indicate in the certificate which conditions have been tested, which standards have been applied and the criteria for considering the tests terminated                                        |

### 6.3.4. Assessment requirements for a Track-side Subsystem

The purpose of assessments carried out within the scope of this TSI is to verify that the equipment complies with the requirements stated in Chapter 4.

However, for the design of the ERTMS/ETCS part of the Control-Command and Signalling Track-side Subsystem, application-specific information is needed; This should include:

1.  line characteristics such as gradients, distances, positions of route elements and Eurobalises/Euroloops, locations to be protected, etc;
2.  the signalling data and rules to be handled by the ERTMS/ETCS system.

This TSI does not cover checks to assess whether the application-specific information is correct:

Regardless of the module chosen:

1.  Table 6.3 shows the checks that must be carried out to verify a Control-Command and Signalling Track-side Subsystem and the basic parameters that must be respected;
2.  functionality and performances that have already been checked at the level of the interoperability constituents do not require additional verification.

_Table 6.3_

| Aspect                                                                                                                       | What to assess                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | supporting evidence                                                                                                                                                                                                                                                                                                                                            |
| ---------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Use of interoperability constituents                                                                                         | Check that all interoperability constituents to be integrated into the subsystem are covered by an EC declaration of conformity and the corresponding certificate.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | Existence and content of documents                                                                                                                                                                                                                                                                                                                             |
|                                                                                                                              | Check restrictions on the use of interoperability constituents against the characteristics of the subsystem and of the environment                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | Impact analysis by documents check                                                                                                                                                                                                                                                                                                                             |
|                                                                                                                              | For interoperability constituents that have been certified against older versions of the Control-Command and Signalling TSI, check that the certificate still ensures compliance with the requirements of the TSI currently in force                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | Impact analysis by comparison of specifications referenced in the TSI and certificates of the interoperability constituents                                                                                                                                                                                                                                    |
| Use of train detection systems                                                                                               | Check that the selected types comply with Control-Command and Signalling TSI requirements – Basic parameters 4.2.10, 4.2.11                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | Document check                                                                                                                                                                                                                                                                                                                                                 |
| Integration of interoperability constituents in the subsystem                                                                | Check that the internal interfaces of the subsystem have been installed properly and function properly – Basic parameters 4.2.5, 4.2.7                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | Checks according to specifications                                                                                                                                                                                                                                                                                                                             |
|                                                                                                                              | Check that additional functions (not specified in this TSI) do not impact the mandatory ones                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | Impact analysis                                                                                                                                                                                                                                                                                                                                                |
|                                                                                                                              | Check that the values of ETCS IDs are within the allowed range – Basic Parameter 4.2.9                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | Check of design specifications                                                                                                                                                                                                                                                                                                                                 |
| Integration with infrastructure                                                                                              | Check that the equipment has been properly installed – Basic parameters 4.2.3, 4.2.4 and conditions for installation specified by the manufacturer                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | Results of checks (according to specifications referenced in the basic parameters and manufacturer’s installation rules)                                                                                                                                                                                                                                       |
|                                                                                                                              | Check that the Control-Command and Signalling Track-side subsystem equipment is compatible with the track-side environment                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | Document check (certificates of interoperability constituents and possible methods of integration checked against track-side characteristics)                                                                                                                                                                                                                  |
| Integration with track-side signalling                                                                                       | Check that all functions required by the application are implemented in accordance with specifications referenced in this TSI – Basic parameter 4.2.3                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | Document check (applicant’s design specification and certificates of interoperability constituents)                                                                                                                                                                                                                                                            |
|                                                                                                                              | Check the correct configuration of parameters (Eurobalise telegrams, RBC messages, marker boards positions, etc.)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | Document check (values of parameters checked against characteristics of track-side and of signalling)                                                                                                                                                                                                                                                          |
|                                                                                                                              | Check that the interfaces are correctly installed and function properly.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | Design verification and tests according to information supplied by the applicant                                                                                                                                                                                                                                                                               |
|                                                                                                                              | Check that the Control-Command and Signalling Track-side subsystem operates correctly according to information at the interfaces with track-side signalling (e.g. appropriate generation of Eurobalise telegrams by a LEU or of message by RBC)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | Design verification and tests according to the information supplied by the applicant                                                                                                                                                                                                                                                                           |
| Integration with Control-Command and Signalling On-board Subsystems and with rolling stock                                   | Check the GSM-R coverage – Basic Parameter 4.2.4                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | On-site measurements                                                                                                                                                                                                                                                                                                                                           |
|                                                                                                                              | Check the compliance of the train detection systems with the requirements of this TSI – Basic Parameter 4.2.10                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | On-site measurements                                                                                                                                                                                                                                                                                                                                           |
|                                                                                                                              | Check that the train detection systems comply with the requirements of this TSI – Basic parameters 4.2.10 and 4.2.11                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | Check evidence from existing installations (for systems already in use); perform tests according to standards for new types                                                                                                                                                                                                                                    |
|                                                                                                                              | Check that all functions required by the application are implemented in accordance with specifications referenced in this TSI – basic parameters 4.2.3, 4.2.4 and 4.2.5                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | Reports of tests of the operational scenarios specified in Section 6.1.2 with different certified Control-Command and Signalling On-board Subsystems. The report shall indicate which operational scenarios have been tested, which on-board equipment has been used and whether tests have been performed in laboratories, test lines or real implementation. |
| Reliability, Availability, Maintainability, Safety (RAMS)                                                                    | Check compliance with safety requirements – Basic Parameter 4.2.1                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | Application of procedures specified in the Common Safety Method                                                                                                                                                                                                                                                                                                |
|                                                                                                                              | Check that quantitative reliability targets are respected – Basic Parameter 4.2.1                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | Calculations                                                                                                                                                                                                                                                                                                                                                   |
|                                                                                                                              | Check the compliance with requirements about maintenance – Section 4.5.2                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | Document check                                                                                                                                                                                                                                                                                                                                                 |
| Integration with Control-Command and Signalling On-board Subsystems and rolling stock:<br>tests under operational conditions | Test the behaviour of the subsystem under such different operational conditions as reasonably feasible (e.g. train speed, number of trains on the line, weather conditions). The test must be able to verify:<br>1. the performance of train detection systems – Basic parameters 4.2.10, 4.2.11,<br>2. that the Control-Command and Signalling Track-side subsystem is compatible with track-side environment – Basic parameter 4.2.16<br>These tests will also increase confidence in the absence of systematic failures. <br>The scope of these tests excludes tests already done in previous steps: tests performed at the level of interoperability constituents and tests performed on the subsystem in a simulated environment shall be taken into account. | Reports of test runs.<br>Note: Indicate in the certificate which conditions have been tested, which standards have been applied and the criteria for considering the tests terminated.                                                                                                                                                                         |

## 6.4. Provisions for partial conformity

### 6.4.1. Introduction

Pursuant to Article 18(4) of the Railway Interoperability Directive, ‘the Notified Body may issue Intermediate Statement Verifications (ISVs) to cover certain stages of the verification procedure or certain parts of the subsystem’.

As pointed out in Section 2.2 (Scope) of this TSI, the Control-Command and Signalling Subsystems include three parts, which are specified in Section 4.1 (Introduction).

Section 6.4.2 deals with the verification of these parts of the Control-Command and Signalling Subsystems.

Section 6.4.3 deals with the verification of partial conformity of Control-Command and Signalling Subsystems when there are restricted conditions of use of its interoperability constituent(s).

### 6.4.2. Assessment of parts of Control-Command and Signalling Subsystems

Assessing whether a Control-Command and Signalling Track-side or On-board Subsystem complies with the requirements of this TSI is a process that may be performed in successive steps – one for each of the three parts. At each step, the assessor checks only whether that particular part complies with the TSI requirements.

Regardless of which module is chosen, the Notified Body shall verify that:

1.  the TSI requirements for the part in question have been respected;
2.  the TSI requirements already assessed are not prejudiced.

Functions already assessed and unchanged and which are not affected by this step do not need to be checked again.

### 6.4.3. Partial conformity of Control-Command and Signalling Subsystems due to restricted conditions of use of its interoperability constituent(s)

A partial certificate of conformity for an interoperability constituent can be issued even if some function, interface or performance has not been implemented, provided that:

1.  The non-implemented function, interface or performance is not required for integrating the interoperability constituent into a subsystem because of specific conditions of use, for example (9):

    <ol>
       <li type="a">the on-board ERTMS/ETCS interface to STM if the interoperability constituent is intended for installation on vehicles where no external STM is needed;</li>
       <li type="a">the RBC interface to other RBCs, if the RBC is intended for use in an application where no neighbouring RBCs are planned.</li>
    </ol>

2.  The certificate indicates which functions, interfaces or performance are not implemented and states the corresponding restrictions on the use of the interoperability constituent. This information will make it possible to identify the conditions under which the interoperability constituent can be used and the restrictions that will apply to the interoperability of a subsystem incorporating it.

In any event, the conditions for issuing such certificates with restrictions shall be coordinated between the Notified Bodies and the Agency in a working group set up pursuant to Article 21a(5) of Regulation (EC) No 881/2004 of the European Parliament and of the Council of 29 April 2004 establishing a European Railway Agency (Agency Regulation) (10).

When the interoperability constituent is integrated into a Control-Command and Signalling On-board or Track-side Subsystem, if the missing functions, interfaces, or performances do not allow to assess whether the subsystem fully complies with the requirements of this TSI, only an Intermediate Statement of Verification may be issued. It shall indicate which requirements have been assessed and shall state the corresponding restrictions on the use of the subsystem and its compatibility with other subsystems.

# 7. IMPLEMENTING THE TSI CONTROL-COMMAND AND SIGNALLING

## 7.1. Introduction

This chapter outlines the strategy and the associated technical measures for implementing the TSI, and in particular the conditions for migrating to Class A systems.

Account must be taken of the fact that the implementation of a TSI occasionally has to be coordinated with the implementation of other TSIs.

## 7.2. Generally applicable rules

### 7.2.1. Upgrading or renewing the Control-Command Track-side Subsystem or parts of it

Upgrading or renewing the Control-Command and Signalling Track-side Subsystem may concern any or all of the following:

1.  Train protection
2.  Radio communication
3.  Train detection

These different parts of the Control-Command and Signalling Track-side Subsystem may therefore be upgraded or renewed separately if interoperability is not jeopardised. The work involved will concern:

1.  GSM-R functions and interfaces
2.  ERTMS/ETCS functions and interfaces
3.  Train detection system compatibility with rolling stock

See Chapter 4.1 (Introduction) for the definition of the basic parameters for each part.

### 7.2.2. Legacy systems

Member States shall ensure that the functionality of the legacy systems and their interfaces remains unchanged, except where modifications are needed to mitigate safety-related flaws in these systems.

### 7.2.3. Availability of Specific Transmission Modules

If lines that fall within the scope of this TSI are not equipped with Class A train protection systems, the Member State shall make every effort to ensure the availability of an external Specific Transmission Module (STM) for its legacy Class B train protection system or systems.

In this context, due regard is to be given to ensuring an open market for STMs under fair commercial conditions. If, for technical or commercial reasons (11) the availability of an STM cannot be ensured, the Member State concerned shall inform the Committee of the underlying reasons for the problem and of the mitigation measures that it intends to put into place in order to allow operators — and in particular foreign operators — access to its infrastructure.

### 7.2.4. Additional Class B equipment on a line equipped with Class A

On a line equipped with ERTMS/ETCS and/or GSM-R, additional Class B equipment may be installed in order to allow the operation of rolling stock not compatible with Class A during the migration phase. Class B equipment may be used on-board as a fallback arrangement for a Class A system. However an infrastructure manager is not entitled to require the interoperable trains running on such a line to have Class B systems on board.

In addition, track-side shall support transitions between Class A and Class B without imposing on the Control-Command and Signalling On-board Subsystem requirements additional to those specified in this TSI.

### 7.2.5. Rolling stock with Class A and Class B equipment

Rolling stock may be equipped with both Class A and Class B systems to enable operation on several lines.

The Member State concerned may restrict the use of an on-board Class B system on lines where the corresponding system is not installed track-side.
When running on a line which is equipped with both Class A and Class B systems, a train that is also equipped with both Class A and Class B systems may use the Class B systems as a fallback arrangement. This cannot be a requirement for interoperability.

The Class B train protection systems may be implemented:

1.  using an STM operating via the standard interface (‘external STM’); or
2.  integrated within the ERTMS/ETCS equipment or connected via a non-standard interface; or
3.  independently from the ERTMS/ETCS equipment, for example via a system that enables switching between equipment. The Railway Undertaking must then ensure that the transitions between Class A and Class B train protection are carried out in conformity with the requirements of this TSI and with the national rules for the Class B system.

### 7.2.6. Conditions for mandatory and optional functions

Depending on the characteristics of the Control-Command and Signalling Track-side Sub-system and its interfaces with other sub-systems, some track-side functionalities not classified as mandatory may necessarily have to be implemented in certain applications to comply with the essential requirements.

The track-side implementation of national or optional-functions must not prevent the use of that infrastructure by a train that complies only with the mandatory requirements of the On-board Class A system except as required for the following on-board optional functions:

-   an ETCS Level 3 Track-side application requires train integrity supervision on board,
-   an ETCS Level 1 Track-side application with in-fill requires corresponding in-fill functionality on board if the release speed is set to zero for safety reasons (e.g. protection of danger points),
-   when ETCS requires data transmission by radio, the data transmission services of GSM-R must fulfil the ETCS data transmission requirements,
-   an on-board assembly, which incorporates a KER STM, may make it necessary to implement the K-interface.

### 7.2.7. GSM-R specific implementation rules

#### 7.2.7.1. Track-side installations

The fitting of GSM-R is mandatory when:

1.  installing for the first time the radio part of a Control-Command and Signalling Track-side Subsystem;
2.  upgrading the radio part of a Control-Command and Signalling Track-side Subsystem already in service in such a way that it changes the functions or the performance of the subsystem. This does not include the modifications deemed necessary to mitigate safety-related defects in the legacy installation.

#### 7.2.7.2. On-board installations

The fitting of GSM-R in rolling stock intended for use on a line including at least one section equipped with Class A interfaces (even if superimposed to a Class B system), is mandatory when:

1.  installing for the first time the radio part of a Control-Command and Signalling On-board Subsystem;
2.  upgrading the radio part of a Control-Command and Signalling On-board Subsystem already in service in such a way that it changes the functions or the performance of the subsystem. This does not apply to modifications deemed necessary to mitigate safety-related defects in the legacy installation.

### 7.2.8. Train detection systems specific implementation rules

In the context of this TSI, train detection system means the equipment installed track-side, which detects the presence or absence of vehicles either on an entire line of route or on a local section of it.

Track-side systems (e.g. interlocking or level crossing control systems) which use information from detection equipment are not considered parts of the train detection system.

This TSI specifies the requirements for the interface with rolling stock only to the extent necessary to ensure compatibility between TSI-compliant rolling stock and the infrastructure.

Implementing a train detection system that is compliant with the requirements of the Control-Command and Signalling Subsystems TSI can be done independently of the installation of ERTMS/ETCS or GSM-R, but can be dependent on the Class B signalling systems or on special requirements, e.g. for level crossing equipment.

The requirements of this TSI relating to train detection systems shall be respected when:

1.  upgrading the train detection system;
2.  renewing the train detection system, provided that respecting the requirements of this TSI does not imply unwanted modifications or upgrades of other track-side or on-board systems;
3.  renewing the train detection system, where this is required by the upgrade or renewal of track-side systems that use information from the train detection system;
4.  removing Class B train protection systems (where the train detection and train protection systems are integrated).

In the migration phase care shall be taken to ensure that installing a TSI compliant train detection system has a minimal negative impact on the existing non-TSI compliant rolling stock.

To achieve this, it is recommended that the Infrastructure Manager selects a TSI compliant train detection system that, at the same time, is compatible with the non-TSI compliant rolling stock already operating on that infrastructure.

### 7.2.9. Specific cases

#### 7.2.9.1. Introduction

The following special provisions are permitted in the specific cases below.

These specific cases belong to two categories: the provisions apply either permanently (case ‘P’) or temporarily (case ‘T’).

In this TSI, temporary case ‘T3’ is defined as temporary cases which will still exist after 2020.

The specific cases set out in Sections 7.2.9.2 to 7.2.9.7 should be read in conjunction with the relevant sections of Chapter 4 and/or specifications referenced there.

The specific cases replace the corresponding requirements set out in Chapter 4.

Where the requirements set out in the relevant section of Chapter 4 are not subject to a specific case, those requirements have not been duplicated in Sections 7.2.9.2 to 7.2.9.7 and continue to apply unmodified.

#### 7.2.9.2. Belgium

| Specific case                                                                                                                                                                                                                                                                                                                                 | Category | Notes                                                                               |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------- | ----------------------------------------------------------------------------------- |
| **4.2.10 Track-side Train Detection Systems** <br>Index 77, Section 3.1.2.4:<br>The distance between first and last axle L – (b1 + b2) (Figure 1) is at least 15 000 mm                                                                                                                                                                       | T3       | Applicable on HS L1<br>This Specific Case is linked with the use of TVM             |
| **4.2.10 Track-side Train Detection Systems**<br>Index 77, Section 3.1.8:<br>The weight of an isolated vehicle or a trainset is at least 40 t.<br>If the weight of an isolated vehicle or a trainset is inferior to 90 t, the vehicle should have a system ensuring the shunting which has an electrical basis superior or equal to 16 000 mm | T3       | Applicable on HS L1, L2, L3, L4<br>This Specific Case is linked with the use of TVM |

#### 7.2.9.3. United Kingdom

| Specific case                                                                                                                                                                                                                                                                                                                                                                                                                                | Category | Notes                                                                                                                                        |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------- | -------------------------------------------------------------------------------------------------------------------------------------------- |
| **4.2.10 Track-side Train Detection Systems** <br>Index 77, Section 3.1.2.4:<br>The distance between first and last axle L – (b1 + b2) (Figure 1) is at least 15 000 mm                                                                                                                                                                                                                                                                      | T3       | Applicable on High-Speed L 1<br>This Specific Case is linked with the use of TVM                                                             |
| **4.2.10 Track-side Train Detection Systems**<br>Index 77, Section 3.1.4.1:<br>In addition to the requirements in Section 3.1.4.1, sanding for traction purposes on multiple units:<br><ol> <li type="a">is not permitted ahead of the leading axle below 40 km/h; and</li> <li type="a">is only permitted where it can be demonstrated that at least a further six axles of the multiple unit are beyond the laying position. TVM</li></ol> | T3       |                                                                                                                                              |
| **4.2.12 ERTMS/ETCS DMI (Driver Machine Interface)** Index 51:<br>It is permissible for the ETCS DMI to display dynamic train speed information in miles per hour (and indicate ‘mph’) when operating on parts of the GB mainline network.                                                                                                                                                                                                   | T3       | This specific case is needed as soon as the open point related to the DMI specification is closed.<br>There is no impact on interoperability |

#### 7.2.9.4. France

| Specific case                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | Category | Notes                                                                                                                  |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------- | ---------------------------------------------------------------------------------------------------------------------- |
| **4.2.10 Track-side Train Detection Systems** <br>Index 77, Section 3.1.2.4:<br>The distance between first and last axle L – (b1 + b2) (Figure 1) is at least 15 000 mm                                                                                                                                                                                                                                                                                                                                                   | T3       | Applicable on HS L1<br>This Specific Case is linked with the use of TVM                                                |
| **4.2.10 Track-side Train Detection Systems**<br>Index 77, Section 3.1.9:<br>The electrical resistance between the running surfaces of the opposite wheels of a wheelset does not exceed 0,05 Ohm, measured by a voltage between 1,8 VDC and 2,0 VDC (open circuit).<br>In addition, the electrical reactance between the running surfaces of the opposite wheels of a wheelset does not exceed f/100 mOhm when f is between 500 Hz and 40 kHz, under a measuring current of at least 10 ARMS and open voltage of 2 VRMS. | T3       | This specific case may be revised when the open point related to the frequency management for track circuits is closed |
| **4.2.10 Track-side Train Detection Systems**<br>Index 77, Section 3.1.8:<br>The weight of an isolated vehicle or a trainset is at least 40 t.<br>If the weight of an isolated vehicle or a trainset is inferior to 90 t, the vehicle should have a system ensuring the shunting which has an electrical basis superior or equal to 16 000 mm.                                                                                                                                                                            | T3       | This Specific Case is linked with the use of TVM                                                                       |
| **4.2.10 Track-side Train Detection Systems**<br>Index 77, Section 3.1.3.2:<br>Dimension D (Figure 2) is not less than:<br>450 mm independently of the speed                                                                                                                                                                                                                                                                                                                                                              | 5 years  |                                                                                                                        |

#### 7.2.9.5. Poland

| Specific case                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | Category | Notes                                                                                                                  |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------- | ---------------------------------------------------------------------------------------------------------------------- |
| **4.2.10 Track-side Train Detection Systems**<br>Index 77, Section 3.1.9:<br>The electrical resistance between the running surfaces of the opposite wheels of a wheelset does not exceed 0,05 Ohm, measured by a voltage between 1,8 VDC and 2,0 VDC (open circuit).<br>In addition, the electrical reactance between the running surfaces of the opposite wheels of a wheelset does not exceed f/100 mOhm when f is between 500 Hz and 40 kHz, under a measuring current of at least 10 ARMS and open voltage of 2 VRMS. | T3       | This specific case may be revised when the open point related to the frequency management for track circuits is closed |

#### 7.2.9.6. Lithuania, Latvia

| Specific case                                                                                                                                         | Category | Notes                                                                                         |
| ----------------------------------------------------------------------------------------------------------------------------------------------------- | -------- | --------------------------------------------------------------------------------------------- |
| **4.2.10 Track-side Train Detection Systems**<br>Index 77, Section 3.1.3.4:<br>The range of the dimension Sh (Figure 2) is not less than 26,25 mm<br> | T3       | This specific case is needed as long as ČME locomotives operate on Lithuania 1 520 mm network |

#### 7.2.9.7. Sweden

| Specific case                                                                                                                                                                                                                                                                                                               | Category | Notes                         |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------- | ----------------------------- |
| **4.2.4 Mobile communication functions for railways – GSM-R**<br>Index 65, statement 4.2.3:<br>It is permissible to put in service on-board Control-Command and Signalling Subsystems including 2 Watt GSM-R voice cab radios and ETCS data only radios. The subsystems shall be able to operate in networks with - 82 dBm. | P        | No impact on interoperability |

#### 7.2.9.8. Luxembourg

| Specific case                                                                                                                                                                                                                                                                                                                                                                                        | Category | Notes |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------- | ----- |
| **4.2.10 Track-side Train Detection Systems** <br>Index 77, Section 3.1.2.4:<br>1. The output of the sanding devices fitted to the vehicle shall not exceed 0,3 l per minute per rail.<br>2. The sanding in the stations identified in the infrastructure register is prohibited.<br>3. The sanding in the area of switches is prohibited. <br>4. For emergency braking, no restrictions shall apply | T3       |       |

## 7.3. Rules for ERTMS

### 7.3.1. The ERTMS European Deployment Plan

This section outlines the strategy (ERTMS European Deployment Plan) for implementing the TSI. It specifies the stages to be completed in order to make a gradual transition from the existing situation to the final situation in which compliance with the TSIs shall be the norm.

The ERTMS European Deployment Plan does not apply to lines located in the territory of a Member State when its rail network is separated or isolated by the sea or separated as a result of special geographical conditions or of different track gauge from the rail network of the rest of the Community.

### 7.3.2. ERTMS Track-side Implementation

The aim of the ERTMS European Deployment Plan is to ensure that locomotives, railcars and other railway vehicles equipped with ERTMS can gradually have access to an increasing number of lines, ports, terminals and marshalling yards without needing national equipment in addition to ERTMS.

This does not mean that existing Class B systems have to be removed from the lines included in the plan. However, by the date specified in the implementation plan, locomotives, railcars and other railway vehicles equipped with ERTMS must be given access to lines included in the deployment plan without requiring those vehicles to be equipped with a Class B system.

Terminal areas such as ports, or specific lines in a port, which are not equipped with a Class B system fulfil the requirements set out in Section 7.3.2.2 provided railway vehicles are given access to these terminal areas without any requirement as regards equipment with an Automatic Train Protection system being imposed.

A line consisting of two or more tracks shall be considered equipped as soon as two of the tracks are equipped so as to allow traffic in both directions. When there is more than one line on a section of a corridor, at least one of the lines on this section must be equipped and the whole corridor shall be considered equipped as soon as at least one line is equipped over the whole length of the corridor.

#### 7.3.2.1. Corridors

The six corridors described in Section 7.3.4 shall be equipped with ERTMS according to the timetable indicated in that section (12).

#### 7.3.2.2. Connection to the main European ports, marshalling yards, freight terminals and freight transport areas

The ports, marshalling yards, freight terminals and freight transport areas listed in 7.3.5 shall be linked to at least one of the six corridors specified in 7.3.4 at the date and under the conditions specified in 7.3.5.

#### 7.3.2.3. High-speed network

It is mandatory to fit ERTMS/ETCS track-side when:

1.  installing for the first time the train protection part of a Control-Command and Signalling Track-side Subsystem (with or without a Class B system); or
2.  upgrading the existing train protection part of a Control-Command and Signalling Track-side Subsystem, where this would change the functions, performance and/or interoperability-relevant interfaces (air gaps) of the existing legacy system. This does not apply to modifications deemed necessary to mitigate safety-related defects in the legacy installation.

It is recommended that ERTMS/ETCS be installed whenever the infrastructure or energy sub-system of a section of line already in service is to be upgraded, renewed or maintained, provided the installation of ERTMS/ETCS on that section of line represents less than 10 % of the total upgrade/renewal/maintenance investment.

#### 7.3.2.4. EU-funded projects

Without prejudice to Sections 7.3.2.1, 7.3.2.2 and 7.3.2.3, in the case of railway infrastructure projects receiving financial support from European Regional Development Funds and/or Cohesion Funds (Council Regulation (EC) No 1083/2006 of 11 July 2006 laying down general provisions on the European Regional Development Fund, the European Social Fund and the Cohesion Fund (13)) and/or the TEN-T funds (Decision No 1692/96/EC of the European Parliament and of the Council (14)) the fitting of ERTMS/ETCS is mandatory when:

1.  installing for the first time the train protection part of a Control-Command and Signalling Subsystem; or
2.  upgrading the train protection part of a Control-Command and Signalling Subsystem already in service, where this changes the functions or the performance of the subsystem.

#### 7.3.2.5. Notification

For each corridor section described in 7.3.4, Member States shall either notify to the Commission a detailed timeline for equipping that corridor section with ERTMS or confirm that the corridor section is already equipped. The information shall be notified to the Commission no later than 3 years before the deadline for equipping that corridor section, as specified in 7.3.4.

For each port, marshalling yard, freight terminal or freight transport area listed in 7.3.5, Member States shall notify the specific lines to be used to connect it with one of the corridors listed in 7.3.4. This information shall be notified to the Commission no later than 3 years before the date specified in 7.3.5 and shall indicate the deadline for equipping this port, marshalling yard, freight terminal or freight transport area. If necessary, the Commission may request adjustments, in particular to ensure consistency between equipped lines at the borders. Member States shall either notify to the Commission a detailed timeline for equipping these specific lines with ERTMS or confirm that these specific lines are already equipped. This information shall be notified to the Commission no later than 3 years before the date specified in 7.3.5 and shall indicate the deadline for equipping this port, marshalling yard, freight terminal or freight transport area.

The detailed timelines shall in particular indicate the date by which the tender for equipping of the line will be concluded, the procedures put in place in order to ensure interoperability with the neighbouring countries on the corridor and the main milestones relating to the project. Every 12 months, Member States shall inform the Commission of the progress made in equipping these lines sending an updated timeline.

#### 7.3.2.6. Delays

When a Member State reasonably expects delays in fulfilling the deadlines laid down in this Decision, it shall immediately inform the Commission. It shall send the Commission a file containing a technical description of the project and an up-to-date implementation plan. The file shall also explain the reasons for the delay and shall indicate the corrective measures the Member State has taken.

A deadline extension of no more than 3 years can be granted to a Member State when the delay is due to causes beyond the Member State’s reasonable control such as failure of suppliers or problems regarding the authorisation process due to the absence of appropriate test vehicles. Such an extension can be advocated by a Member State only when the following conditions are fulfilled:

1.  the notifications, if needed, referred to in Section 7.3.2.5 were received in time and were comprehensive;
2.  the file referred to in Section 7.3.2.6, first paragraph, contains clear evidence that the causes for the delay were beyond the Member State’s control;
3.  a competent authority is responsible for coordinating on-board and track-side suppliers and for integrating and testing of products;
4.  appropriate use has been made of existing laboratories;
5.  evidence is given that appropriate measures have been taken to minimise the additional delay.

The Commission shall examine the file sent to it and the measures proposed by the Member State and shall notify the result of its examination to the committee referred to in Article 29 of Directive 2008/57/EC.

#### 7.3.3. ERTMS – On-board implementation

New locomotives, new railcars and other new railway vehicles able to run without traction equipped with a driving cab, ordered after 1 January 2012 or put into service after 1 January 2015, shall be equipped with ERTMS.

This requirement does not apply to new shunting locomotives or to other new locomotives, new railcars and other new railway vehicles equipped with a driving cab, if they are designed exclusively for national service or regional border crossing service. Member States may however introduce additional requirements at national level, in particular with a view to:

1.  allowing only ERTMS equipped locomotives to access ERTMS-equipped lines, so that existing national systems can be decommissioned;
2.  requesting that new shunting locomotives and/or other new railway vehicles equipped with a driving cab, even if designed exclusively for national service or regional border crossing service, be equipped with ERTMS.

#### 7.3.3.1. High-speed network

It is mandatory to fit ERTMS/ETCS on board when:

1.  installing any new train protection part of a Control-Command and Signalling On-board Subsystem; or
2.  upgrading any existing train protection part of a Control-Command and Signalling On-board Subsystem, where this would change the functions, performances and/or interoperability-relevant interfaces of the existing legacy system. This does not apply to modifications deemed necessary to mitigate safety related defects in the legacy system.

### 7.3.4. Specific lines constituting the corridors

**_Corridor A – to be equipped by 2015_**
**_Corridor B_**
**_Corridor C_**
**_Corridor D_**
**_Corridor E_**
**_Corridor F_**

### 7.3.5. Main European ports, marshalling yards, freight terminals and freight transport areas

| Country        | Freight transport area | Date       | Remark                                                                                                                                                              |
| -------------- | ---------------------- | ---------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Belgium        | Antwerpen              | 31.12.2015 | A link to Rotterdam shall also be provided by 2020.                                                                                                                 |
|                | Gent                   | 31.12.2020 |                                                                                                                                                                     |
|                | Zeebrugge              | 31.12.2020 |                                                                                                                                                                     |
| Bulgaria       | Burgas                 | 31.12.2020 | The connection to corridor E implies equipping the Burgas-Sofia section and the Sofia-Vidin-Calafat and Calafat-Curtici sections in Romania (PP22).                 |
| Czech Republic | Praha                  | 31.12.2015 |                                                                                                                                                                     |
|                | Lovosice               | 31.12.2020 |                                                                                                                                                                     |
| Denmark        | Taulov                 | 31.12.2020 | Connecting this terminal implies that the Flensburg-Padborg line is chosen to be an ERTMS equipped link – see corridor B footnote.                                  |
| Germany        | Dresden (18)           | 31.12.2020 | By 2020, a direct link between corridor E and corridor F (from Dresden to Hannover) shall also be ensured.                                                          |
|                | Lübeck                 | 31.12.2020 |                                                                                                                                                                     |
|                | Duisburg               | 31.12.2015 |                                                                                                                                                                     |
|                | Hamburg (19)           | 31.12.2020 |                                                                                                                                                                     |
|                | Köln                   | 31.12.2015 |                                                                                                                                                                     |
|                | München                | 31.12.2015 |                                                                                                                                                                     |
|                | Hannover               | 31.12.2015 |                                                                                                                                                                     |
|                | Rostock                | 31.12.2015 |                                                                                                                                                                     |
|                | Ludwigshafen/Mannheim  | 31.12.2015 |                                                                                                                                                                     |
|                | Nürnberg               | 31.12.2020 |                                                                                                                                                                     |
| Greece         | Pireás                 | 31.12.2020 | The connection to Corridor E implies equipping the Kulata-Sofia section in Bulgaria.                                                                                |
| Spain          | Algeciras              | 31.12.2020 |                                                                                                                                                                     |
|                | Madrid                 | 31.12.2020 |                                                                                                                                                                     |
|                | Pamplona               | 31.12.2020 | Three connections are requested. A connection to Paris via Hendaye, a connection from Pamplona to Madrid and a connection from Pamplona to corridor D via Zaragoza. |
|                | Zaragoza               | 31.12.2020 |                                                                                                                                                                     |
|                | Tarragona              | 31.12.2020 |                                                                                                                                                                     |
|                | Barcelona              | 31.12.2015 |                                                                                                                                                                     |
|                | Valencia               | 31.12.2020 |                                                                                                                                                                     |
| France         | Marseille              | 31.12.2020 |                                                                                                                                                                     |
|                | Perpignan              | 31.12.2015 |                                                                                                                                                                     |
|                | Avignon                | 31.12.2015 |                                                                                                                                                                     |
|                | Lyon                   | 31.12.2015 |                                                                                                                                                                     |
|                | Le Havre               | 31.12.2020 |                                                                                                                                                                     |
|                | Lille                  | 31.12.2020 |                                                                                                                                                                     |
|                | Dunkerque              | 31.12.2020 |                                                                                                                                                                     |
|                | Paris                  | 31.12.2020 | By 2020 the following connections will be provided: (i) Hendaye; (ii) Channel Tunnel; (iii) Dijon; and (iv) Metz via Epernay and Châlons-en-Champagne.              |
| Italy          | La Spezia              | 31.12.2020 |                                                                                                                                                                     |
|                | Genova                 | 31.12.2015 |                                                                                                                                                                     |
|                | Gioia Tauro            | 31.12.2020 |                                                                                                                                                                     |
|                | Verona                 | 31.12.2015 |                                                                                                                                                                     |
|                | Milano                 | 31.12.2015 |                                                                                                                                                                     |
|                | Taranto                | 31.12.2020 |                                                                                                                                                                     |
|                | Bari                   | 31.12.2020 |                                                                                                                                                                     |
|                | Padova                 | 31.12.2015 |                                                                                                                                                                     |
|                | Trieste                | 31.12.2015 |                                                                                                                                                                     |
|                | Novara                 | 31.12.2015 |                                                                                                                                                                     |
|                | Venezia                | 31.12.2020 |                                                                                                                                                                     |
|                | Bologna                | 31.12.2020 |                                                                                                                                                                     |
|                | Roma                   | 31.12.2020 |                                                                                                                                                                     |
| Luxembourg     | Bettembourg            | 31.12.2015 |                                                                                                                                                                     |
| Hungary        | Budapest               | 31.12.2015 |                                                                                                                                                                     |
| Netherlands    | Amsterdam              | 31.12.2020 |                                                                                                                                                                     |
|                | Rotterdam              | 31.12.2015 | A link to Antwerpen shall also be provided by 2020.                                                                                                                 |
| Austria        | Graz                   | 31.12.2020 |                                                                                                                                                                     |
|                | Wien                   | 31.12.2020 |                                                                                                                                                                     |
| Poland         | Gdynia                 | 31.12.2015 |                                                                                                                                                                     |
|                | Katowice               | 31.12.2020 |                                                                                                                                                                     |
|                | Wrocław                | 31.12.2015 | By 2020 the Wrocław-Legnica line, shall be equipped in order to ensure a direct link to the German border (Görlitz).                                                |
|                | Gliwice                | 31.12.2015 |                                                                                                                                                                     |
|                | Poznań                 | 31.12.2015 |                                                                                                                                                                     |
|                | Warszawa               | 31.12.2015 |                                                                                                                                                                     |
| Portugal       | Sines                  | 31.12.2020 |                                                                                                                                                                     |
|                | Lisboa                 | 31.12.2020 |                                                                                                                                                                     |
| Romania        | Constanța              | 31.12.2015 |                                                                                                                                                                     |
| Slovenia       | Koper                  | 31.12.2015 |                                                                                                                                                                     |
|                | Ljubljana              | 31.12.2015 |                                                                                                                                                                     |
| Slovakia       | Bratislava             | 31.12.2015 |                                                                                                                                                                     |
| United Kingdom | Bristol                |            | This terminal will be connected as corridor C is extended to the Channel Tunnel.                                                                                    |

# ANNEX A

## References

For each reference made in the basic parameters (Chapter 4 of this TSI) the following table indicates the corresponding mandatory specifications, via the index in table A-2.

**_Table A 1_**

| Reference in Chapter 4 | Index number (see Table A 2) |
| ---------------------- | ---------------------------- |
| **4.1**                |                              |
| 4.1 a                  | 1, 4                         |
| 4.1 b                  | 32                           |
| 4.1 c                  | 3                            |
| **4.2.1**              |                              |
| 4.2.1 a                | 27, 78                       |
| 4.2.1 b                | 28                           |
| **4.2.2**              |                              |
| 4.2.2.a                | 14                           |
| 4.2.2.b                | 1, 4, 13, 15, 60             |
| 4.2.2.c                | 31, 37b, c, d                |
| 4.2.2.d                | 18, 20                       |
| 4.2.2.e                | 6                            |
| 4.2.2.f                | 7                            |
| **4.2.3**              |                              |
| 4.2.3 a                | 14                           |
| 4.2.3 b                | 1, 4, 13, 15, 60             |
| 4.2.3 c                | 31, 37 b, c, d               |
| 4.2.3 d                | 18, 21                       |
| **4.2.4**              |                              |
| 4.2.4 a                | 64, 65                       |
| 4.2.4 b                | 66                           |
| 4.2.4 c                | 67                           |
| 4.2.4 d                | 68                           |
| 4.2.4 e                | 73, 74                       |
| 4.2.4 f                | 32, 33                       |
| 4.2.4 g                | 48                           |
| 4.2.4 h                | 69, 70                       |
| 4.2.4 j                | 71, 72                       |
| 4.2.4 k                | 75, 76                       |
| **4.2.5**              |                              |
| 4.2.5 a                | 64, 65                       |
| 4.2.5 b                | 10, 39, 40                   |
| 4.2.5 c                | 19, 20                       |
| 4.2.5 d                | 9, 43                        |
| 4.2.5 e                | 16, 50                       |
| **4.2.6**              |                              |
| 4.2.6 a                | 8, 25, 26, 36 c, 49, 52      |
| 4.2.6 b                | 29, 45                       |
| 4.2.6 c                | 46                           |
| 4.2.6 d                | 34                           |
| 4.2.6 e                | 20                           |
| 4.2.6 f                | 44                           |
| **4.2.7**              |                              |
| 4.2.7 a                | 12                           |
| 4.2.7 b                | 62, 63                       |
| 4.2.7 c                | 34                           |
| 4.2.7 d                | 9                            |
| 4.2.7 e                | 16                           |
| **4.2.8**              |                              |
| 4.2.8 a                | 11, 79                       |
| **4.2.9**              |                              |
| 4.2.9 a                | 23                           |
| **4.2.10**             |                              |
| 4.2.10 a               | 77 (section 3.1)             |
| **4.2.11**             |                              |
| 4.2.11 a               | 77 (section 3.2)             |
| **4.2.12**             |                              |
| 4.2.12 a               | 6, 51                        |
| **4.2.13**             |                              |
| 4.2.13 a               | 32, 33, 51, 80               |
| **4.2.14**             |                              |
| 4.2.14 a               | 5                            |
| **4.2.15**             |                              |
| 4.2.15 a               | 38                           |

## Specifications

One of the two sets of specifications listed in Table A-2 of this Annex shall be applied.

Documents referred to within a specification listed in Table A-2 shall be considered as being for information only, unless otherwise stated in Table A-2.

Note: specifications indicated as ‘Reserved’ in table A-2 are also listed as open points in Annex G when there is a need for notification of national rules to close the corresponding open points. Reserved documents not listed as open points are intended as improvements to the system.

**_Table A 2_**

**List of mandatory specifications**

Set of specifications # 1 (ETCS baseline 2 and GSM-R baseline 0)

| Index N | Reference              | Name of Specification                                                                       | Version | Notes  |
| ------- | ---------------------- | ------------------------------------------------------------------------------------------- | ------- | ------ |
| 1       | ERA/ERTMS/003204       | ERTMS/ETCS Functional requirement specification                                             | 5.0     |        |
| 2       | Intentionally deleted  |                                                                                             |         |        |
| 3       | UNISIG SUBSET-023      | Glossary of Terms and Abbreviations                                                         | 2.0.0   |        |
| 4       | UNISIG SUBSET-026      | System Requirements Specification                                                           | 2.3.0   |        |
| 5       | UNISIG SUBSET-027      | FFFIS Juridical recorder-downloading tool                                                   | 2.3.0   | Note 1 |
| 6       | UNISIG SUBSET-033      | FIS for man-machine interface                                                               | 2.0.0   |        |
| 7       | UNISIG SUBSET-034      | FIS for the train interface                                                                 | 2.0.0   |        |
| 8       | UNISIG SUBSET-035      | Specific Transmission Module FFFIS                                                          | 2.1.1   |        |
| 9       | UNISIG SUBSET-036      | FFFIS for Eurobalise                                                                        | 2.4.1   |        |
| 10      | UNISIG SUBSET-037      | EuroRadio FIS                                                                               | 2.3.0   |        |
| 11      | UNISIG SUBSET-038      | Offline key management FIS                                                                  | 2.3.0   |        |
| 12      | UNISIG SUBSET-039      | FIS for the RBC/RBC handover                                                                | 2.3.0   |        |
| 13      | UNISIG SUBSET-040      | Dimensioning and Engineering rules                                                          | 2.3.0   |        |
| 14      | UNISIG SUBSET-041      | Performance Requirements for Interoperability                                               | 2.1.0   |        |
| 15      | ERA SUBSET-108         | Interoperability related consolidation on TSI Annex A documents                             | 1.2.0   |        |
| 16      | UNISIG SUBSET-044      | FFFIS for Euroloop                                                                          | 2.3.0   |        |
| 17      | Intentionally deleted  |                                                                                             |         |        |
| 18      | UNISIG SUBSET-046      | Radio infill FFFS                                                                           | 2.0.0   |        |
| 19      | UNISIG SUBSET-047      | Trackside-Trainborne FIS for Radio infill                                                   | 2.0.0   |        |
| 20      | UNISIG SUBSET-048      | Trainborne FFFIS for Radio infill                                                           | 2.0.0   |        |
| 21      | UNISIG SUBSET-049      | Radio infill FIS with LEU/interlocking                                                      | 2.0.0   |        |
| 22      | Intentionally deleted  |                                                                                             |         |        |
| 23      | UNISIG SUBSET-054      | Responsibilities and rules for the assignment of values to ETCS variables                   | 2.1.0   |        |
| 24      | Intentionally deleted  |                                                                                             |         |        |
| 25      | UNISIG SUBSET-056      | STM FFFIS Safe time layer                                                                   | 2.2.0   |        |
| 26      | UNISIG SUBSET-057      | STM FFFIS Safe link layer                                                                   | 2.2.0   |        |
| 27      | UNISIG SUBSET-091      | Safety Requirements for the Technical Interoperability of ETCS in Levels 1 and 2            | 2.5.0   |        |
| 28      | Reserved               | Reliability — availability requirements                                                     |         |        |
| 29      | UNISIG SUBSET-102      | Test specification for interface ‘K’                                                        | 1.0.0   |        |
| 30      | Intentionally deleted  |                                                                                             |         |        |
| 31      | UNISIG SUBSET-094      | Functional requirements for an on-board reference test facility                             | 2.0.2   |        |
| 32      | EIRENE FRS             | GSM-R Functional requirements specification                                                 | 7.3.0   |        |
| 33      | EIRENE SRS             | GSM-R System requirements specification                                                     | 15.3.0  |        |
| 34      | A11T6001               | (MORANE) Radio Transmission FFFIS for EuroRadio                                             | 12.4    |        |
| 35      | Intentionally deleted  |                                                                                             |         |        |
| 36 a    | Intentionally deleted  |                                                                                             |         |        |
| 36 b    | Intentionally deleted  |                                                                                             |         |        |
| 36 c    | UNISIG SUBSET-074-2    | FFFIS STM Test cases document                                                               | 1.0.0   |        |
| 37 a    | Intentionally deleted  |                                                                                             |         |        |
| 37 b    | UNISIG SUBSET-076-5-2  | Test cases related to features                                                              | 2.3.3   |        |
| 37 c    | UNISIG SUBSET-076-6-3  | Test sequences                                                                              | 2.3.3   |        |
| 37 d    | UNISIG SUBSET-076-7    | Scope of the test specifications                                                            | 1.0.2   |        |
| 37 e    | Intentionally deleted  |                                                                                             |         |        |
| 38      | 06E068                 | ETCS Marker-board definition                                                                | 2.0     |        |
| 39      | UNISIG SUBSET-092-1    | ERTMS EuroRadio Conformance Requirements                                                    | 2.3.0   |        |
| 40      | UNISIG SUBSET-092-2    | ERTMS EuroRadio test cases safety layer                                                     | 2.3.0   |        |
| 41      | Intentionally deleted  |                                                                                             |         |        |
| 42      | Intentionally deleted  |                                                                                             |         |        |
| 43      | UNISIG SUBSET 085      | Test specification for Eurobalise FFFIS                                                     | 2.2.2   |        |
| 44      | Reserved               | Odometry FIS                                                                                |         |        |
| 45      | UNISIG SUBSET-101      | Interface ‘K’ Specification                                                                 | 1.0.0   |        |
| 46      | UNISIG SUBSET-100      | Interface ‘G’ Specification                                                                 | 1.0.1   |        |
| 47      | Intentionally deleted  |                                                                                             |         |        |
| 48      | Reserved               | Test specification for mobile equipment GSM-R                                               |         |        |
| 49      | UNISIG SUBSET-059      | Performance requirements for STM                                                            | 2.1.1   |        |
| 50      | UNISIG SUBSET-103      | Test specification for Euroloop                                                             | 1.0.0   |        |
| 51      | Reserved               | Ergonomic aspects of the DMI                                                                |         |        |
| 52      | UNISIG SUBSET-058      | FFFIS STM Application layer                                                                 | 2.1.1   |        |
| 53      | Intentionally deleted  |                                                                                             |         |        |
| 54      | Intentionally deleted  |                                                                                             |         |        |
| 55      | Intentionally deleted  |                                                                                             |         |        |
| 56      | Intentionally deleted  |                                                                                             |         |        |
| 57      | Intentionally deleted  |                                                                                             |         |        |
| 58      | Intentionally deleted  |                                                                                             |         |        |
| 59      | Intentionally deleted  |                                                                                             |         |        |
| 60      | Intentionally deleted  |                                                                                             |         |        |
| 61      | Intentionally deleted  |                                                                                             |         |        |
| 62      | Reserved               | RBC-RBC Test specification for safe communication interface                                 |         |        |
| 63      | UNISIG SUBSET-098      | RBC-RBC Safe Communication Interface                                                        | 1.0.0   |        |
| 64      | EN 301 515             | Global System for Mobile Communication (GSM);<br>Requirements for GSM operation on railways | 2.3.0   | Note 2 |
| 65      | TS 102 281             | Detailed requirements for GSM operation on railways                                         | 2.2.0   | Note 3 |
| 66      | (MORANE) A 01 T 0004 1 | ASCI Options for Interoperability                                                           | 1       |        |
| 67      | (MORANE) P 38 T 9001   | FFFIS for GSM-R SIM Cards                                                                   | 4.1     |        |
| 68      | ETSI TS 102 610        | Railway Telecommunication; GSM;<br>Usage of the UUIE for GSM operation on railways          | 1.1.0   |        |
| 69      | (MORANE) F 10 T 6002   | FFFS for Confirmation of High Priority Calls’                                               | 4       |        |
| 70      | (MORANE) F 12 T 6002   | FIS for Confirmation of High Priority Calls                                                 | 4       |        |
| 71      | (MORANE) E 10 T 6001   | FFFS for Functional Addressing                                                              | 4       |        |
| 72      | (MORANE) E 12 T 6001   | FIS for Functional Addressing                                                               | 5.1     |        |
| 73      | (MORANE) F 10 T6001    | FFFS for Location Dependent Addressing                                                      | 4       |        |
| 74      | (MORANE) F 12 T6001    | FIS for Location Dependent Addressing                                                       | 3       |        |
| 75      | (MORANE) F 10 T 6003   | FFFS for Presentation of Functional Numbers to Called and Calling Parties                   | 4       |        |
| 76      | (MORANE) F 12 T 6003   | FIS for Presentation of Functional Numbers to Called and Calling Parties                    | 4       |        |
| 77      | ERA/ERTMS/033281       | Interfaces between CCS track-side and other subsystems                                      | 1.0     |        |
| 78      | Reserved               | Safety requirements for ETCS DMI functions                                                  |         |        |
| 79      | Not applicable         | Not applicable                                                                              |         |        |
| 80      | Not applicable         | Not applicable                                                                              |         |        |

Set of specifications # 2 (ETCS baseline 3 and GSM-R baseline 0)

| Index N | Reference                         | Name of Specification                                                                       | Version | Notes  |
| ------- | --------------------------------- | ------------------------------------------------------------------------------------------- | ------- | ------ |
| 1       | Intentionally deleted             |                                                                                             |         |        |
| 2       | Intentionally deleted             |                                                                                             |         |        |
| 3       | UNISIG SUBSET-023                 | Glossary of Terms and Abbreviations                                                         | 3.0.0   |        |
| 4       | UNISIG SUBSET-026                 | System Requirements Specification                                                           | 3.3.0   |        |
| 5       | UNISIG SUBSET-027                 | FIS Juridical Recording                                                                     | 3.0.0   |        |
| 6       | ERA_ERTMS_015560                  | ETCS Driver Machine interface                                                               | 3.3.0   |        |
| 7       | UNISIG SUBSET-034                 | Train Interface FIS                                                                         | 3.0.0   |        |
| 8       | UNISIG SUBSET-035                 | Specific Transmission Module FFFIS                                                          | 3.0.0   |        |
| 9       | UNISIG SUBSET-036                 | FFFIS for Eurobalise                                                                        | 3.0.0   |        |
| 10      | UNISIG SUBSET-037                 | EuroRadio FIS                                                                               | 3.0.0   |        |
| 11      | UNISIG SUBSET-038                 | Offline key management FIS                                                                  | 3.0.0   |        |
| 12      | Reserved<br>UNISIG SUBSET-039     | FIS for the RBC/RBC handover                                                                |         |        |
| 13      | UNISIG SUBSET-040                 | Dimensioning and Engineering rules                                                          | 3.2.0   |        |
| 14      | UNISIG SUBSET-041                 | Performance Requirements for Interoperability                                               | 3.1.0   |        |
| 15      | Intentionally deleted             |                                                                                             |         |        |
| 16      | UNISIG SUBSET-044                 | FFFIS for Euroloop                                                                          | 2.4.0   |        |
| 17      | Intentionally deleted             |                                                                                             |         |        |
| 18      | Intentionally deleted             |                                                                                             |         |        |
| 19      | UNISIG SUBSET-047                 | Trackside-Trainborne FIS for Radio infill                                                   | 3.0.0   |        |
| 20      | UNISIG SUBSET-048                 | Trainborne FFFIS for Radio infill                                                           | 3.0.0   |        |
| 21      | Intentionally deleted             |                                                                                             |         |        |
| 22      | Intentionally deleted             |                                                                                             |         |        |
| 23      | UNISIG SUBSET-054                 | Responsibilities and rules for the assignment of values to ETCS variables                   | 3.0.0   |        |
| 24      | Intentionally deleted             |                                                                                             |         |        |
| 25      | UNISIG SUBSET-056                 | STM FFFIS Safe time layer                                                                   | 3.0.0   |        |
| 26      | UNISIG SUBSET-057                 | STM FFFIS Safe link layer                                                                   | 3.0.0   |        |
| 27      | UNISIG SUBSET-091                 | Safety Requirements for the Technical Interoperability of ETCS in Levels 1 and 2            | 3.2.0   |        |
| 28      | Reserved                          | Reliability — availability requirements                                                     |         |        |
| 29      | UNISIG SUBSET-102                 | Test specification for interface ‘K’                                                        | 2.0.0   |        |
| 30      | Intentionally deleted             |                                                                                             |         |        |
| 31      | Reserved<br>UNISIG SUBSET-094     | Functional requirements for an on-board reference test facility                             |         |        |
| 32      | EIRENE FRS                        | GSM-R Functional requirements specification                                                 | 7.3.0   |        |
| 33      | EIRENE SRS                        | GSM-R System requirements specification                                                     | 15.3.0  |        |
| 34      | A11T6001                          | (MORANE) Radio Transmission FFFIS for EuroRadio                                             | 12.4    |        |
| 35      | Intentionally deleted             |                                                                                             |         |        |
| 36 a    | Intentionally deleted             |                                                                                             |         |        |
| 36 b    | Intentionally deleted             |                                                                                             |         |        |
| 36 c    | Reserved<br>UNISIG SUBSET-074-2   | FFFIS STM Test cases document                                                               |         |        |
| 37 a    | Intentionally deleted             |                                                                                             |         |        |
| 37 b    | Reserved<br>UNISIG SUBSET-076-5-2 | Test cases related to features                                                              |         |        |
| 37 c    | Reserved<br>UNISIG SUBSET-076-6-3 | Test sequences                                                                              |         |        |
| 37 d    | Reserved<br>UNISIG SUBSET-076-7   | Scope of the test specifications                                                            |         |        |
| 37 e    | Intentionally deleted             |                                                                                             |         |        |
| 38      | 06E068                            | ETCS Marker-board definition                                                                | 2.0     |        |
| 39      | UNISIG SUBSET-092-1               | ERTMS EuroRadio Conformance Requirements                                                    | 3.0.0   |        |
| 40      | UNISIG SUBSET-092-2               | ERTMS EuroRadio test cases safety layer                                                     | 3.0.0   |        |
| 41      | Intentionally deleted             |                                                                                             |         |        |
| 42      | Intentionally deleted             |                                                                                             |         |        |
| 43      | UNISIG SUBSET 085                 | Test specification for Eurobalise FFFIS                                                     | 3.0.0   |        |
| 44      | Reserved                          | Odometry FIS                                                                                |         |        |
| 45      | UNISIG SUBSET-101                 | Interface ‘K’ Specification                                                                 | 2.0.0   |        |
| 46      | UNISIG SUBSET-100                 | Interface ‘G’ Specification                                                                 | 2.0.0   |        |
| 47      | Intentionally deleted             |                                                                                             |         |        |
| 48      | Reserved                          | Test specification for mobile equipment GSM-R                                               |         |        |
| 49      | UNISIG SUBSET-059                 | Performance requirements for STM                                                            | 3.0.0.  |        |
| 50      | UNISIG SUBSET-103                 | Test specification for Euroloop                                                             | 1.1.0   |        |
| 51      | Intentionally deleted             |                                                                                             |         |        |
| 52      | UNISIG SUBSET-058                 | FFFIS STM Application layer                                                                 | 3.0.0   |        |
| 53      | Intentionally deleted             |                                                                                             |         |        |
| 54      | Intentionally deleted             |                                                                                             |         |        |
| 55      | Intentionally deleted             |                                                                                             |         |        |
| 56      | Intentionally deleted             |                                                                                             |         |        |
| 57      | Intentionally deleted             |                                                                                             |         |        |
| 58      | Intentionally deleted             |                                                                                             |         |        |
| 59      | Intentionally deleted             |                                                                                             |         |        |
| 60      | UNISIG SUBSET-104                 | ETCS System Version Management                                                              | 3.1.0   |        |
| 61      | Intentionally deleted             |                                                                                             |         |        |
| 62      | Intentionally deleted             |                                                                                             |         |        |
| 63      | UNISIG SUBSET-098                 | RBC-RBC Safe Communication Interface                                                        | 3.0.0   |        |
| 64      | EN 301 515                        | Global System for Mobile Communication (GSM);<br>Requirements for GSM operation on railways | 2.3.0   | Note 2 |
| 65      | TS 102 281                        | Detailed requirements for GSM operation on railways                                         | 2.2.0   | Note 3 |
| 66      | (MORANE) A 01 T 0004 1            | ASCI Options for Interoperability                                                           | 1       |        |
| 67      | (MORANE) P 38 T 9001              | FFFIS for GSM-R SIM Cards                                                                   | 4.1     |        |
| 68      | ETSI TS 102 610                   | Railway Telecommunication; GSM;<br>Usage of the UUIE for GSM operation on railways          | 1.1.0   |        |
| 69      | (MORANE) F 10 T 6002              | FFFS for Confirmation of High Priority Calls’                                               | 4       |        |
| 70      | (MORANE) F 12 T 6002              | FIS for Confirmation of High Priority Calls                                                 | 4       |        |
| 71      | (MORANE) E 10 T 6001              | FFFS for Functional Addressing                                                              | 4       |        |
| 72      | (MORANE) E 12 T 6001              | FIS for Functional Addressing                                                               | 5.1     |        |
| 73      | (MORANE) F 10 T6001               | FFFS for Location Dependent Addressing                                                      | 4       |        |
| 74      | (MORANE) F 12 T6001               | FIS for Location Dependent Addressing                                                       | 3       |        |
| 75      | (MORANE) F 10 T 6003              | FFFS for Presentation of Functional Numbers to Called and Calling Parties                   | 4       |        |
| 76      | (MORANE) F 12 T 6003              | FIS for Presentation of Functional Numbers to Called and Calling Parties                    | 4       |        |
| 77      | ERA/ERTMS/033281                  | Interfaces between CCS track-side and other subsystems                                      | 1.0     |        |
| 78      | Reserved                          | Safety requirements for ETCS DMI functions                                                  |         |        |
| 79      | UNISIG SUBSET-114                 | KMC-ETCS Entity Off-line KM FIS                                                             | 1.0.0   |        |
| 80      | Reserved                          | GSM-R Driver Machine Interface                                                              |         |        |

Note 1: only the functional description of information to be recorded is mandatory, not the technical characteristics of the interface.

Note 2: the specifications listed in section 2.1 of EN 301 515 are mandatory.

Note 3: the change requests (CRs) listed in table 1 and 2 of TR 102 281 are mandatory.

**_Table A 3_**

**List of mandatory standards**

The standards listed in this table shall be applied in the certification process, without prejudice to chapter 4 and chapter 6 of this TSI.

| No  | Reference  | Document name and comments                                                                                                                    | Version |
| --- | ---------- | --------------------------------------------------------------------------------------------------------------------------------------------- | ------- |
| A1  | EN 50126   | Railway applications — The specification and demonstration of reliability, availability, maintainability and safety (RAMS)                    | 1999    |
| A2  | EN 50128   | Railway applications — Communication, signalling and processing systems — Software for railway control and protection systems                 | 2001    |
| A3  | EN 50129   | Railway applications — Communication, signalling and processing systems — Safety related electronic systems for signalling                    | 2003    |
| A4  | EN 50159-1 | Railway applications — Communication, signalling and processing systems — Part 1: Safety related communication in closed transmission systems | 2001    |
| A5  | EN 50159-2 | Railway applications — Communication, signalling and processing systems — Part 2: Safety related communication in open transmission systems   | 2001    |

# ANNEX B

Intentionally deleted

# ANNEX C

Intentionally deleted

# ANNEX D

Intentionally deleted

# ANNEX E

Intentionally deleted

# ANNEX F

Intentionally deleted

# ANNEX G

**OPEN POINTS**

| Open Point                                                                  | Notes                                                                                                                                                         |
| --------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Braking aspects                                                             | It only applies to ERTMS/ETCS Baseline 2 (see Annex A, Table A2, Index 15).<br>Resolved for ERTMS/ETCS Baseline 3 (see Annex A, Table A 2, Indexes 4 and 13). |
| Index 28 – Reliability/availability requirements                            | Frequent occurrences of degraded situations caused by failures of control-command and signalling equipment will decrease the system safety.                   |
| Minimum wheel diameter for speed greater than 350 km/h                      | See Annex A, Table A 2, Index 77                                                                                                                              |
| Minimum axle distance for speed greater than 350 km/h                       | See Annex A, Table A 2, Index 77                                                                                                                              |
| Metal and inductive components free space between wheels                    | See Annex A, Table A 2, Index 77<br>This is not an open point for freight wagons                                                                              |
| Characteristics of sand applied to tracks                                   | See Annex A, Table A 2, Index 77                                                                                                                              |
| Vehicle metal mass                                                          | See Annex A, Table A 2, Index 77                                                                                                                              |
| Combination of rolling stock characteristics influencing shunting impedance | See Annex A, Table A 2, Index 77                                                                                                                              |
| Electromagnetic interferences (traction current)                            | See Annex A, Table A 2, Index 77                                                                                                                              |
| Electromagnetic interferences (electromagnetic fields)                      | See Annex A, Table A 2, Index 77<br>This is not an open point for power systems other than DC                                                                 |
| Vehicle Impedance                                                           | See Annex A, Table A 2, Index 77                                                                                                                              |
| DC and low frequency components of traction current                         | See Annex A, Table A 2, Index 77                                                                                                                              |
| Use of magnetic/eddy current brakes                                         | See Annex A, Table A 2, Index 77                                                                                                                              |
| Index 78 — Safety requirements for ETCS DMI functions                       | This open point is related to the interface between ETCS on-board and the driver, i.e. errors in displaying information and in entering data and commands.    |
