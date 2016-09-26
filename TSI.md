# 1.   INTRODUCTION

## 1.1.   Technical scope

This TSI concerns the control-command and signalling subsystem, shown in the list in point 1 of Annex II to Directive 2001/16/EC. It is referred to in this document as ‘control-command subsystem’.

Further information about the control-command subsystem is provided in Chapter 2 (Subsystem definition and scope).

## 1.2.   Geographical scope

The geographical scope of this TSI is the trans-European conventional rail system as described in Annex I to Directive 2001/16/EC.

## 1.3.   Content of this TSI

In accordance with Article 5(3) of Directive 2001/16/EC, this TSI:

<ol type="a">
<li>indicates its intended scope (part of the network or rolling stock referred to in Annex I to the Directive; subsystem or part of subsystem referred to in Annex II to the Directive) — Chapter 2 (Subsystem definition and scope);</li>
<li>lays down essential requirements for the control-command subsystem concerned and its interfaces vis-à-vis other subsystems — Chapter 3 (The Essential Requirements Of The control-command subsystem);</li>
<li>establishes the functional and technical specifications to be met by the subsystem and its interfaces vis-à-vis other subsystems. If necessary, these specifications may vary according to the use of the subsystem, for example according to the categories of line, hub and/or rolling stock provided for in Annex I to the Directive — Chapter 4 (Characterisation of the subsystem);</li>
<li>determines the interoperability constituents and interfaces covered by European specifications, including European standards, which are necessary to achieve interoperability within the trans-European conventional rail system — Chapter 5 (Interoperability constituents);</li>
<li>states, in each case under consideration, the procedures for the assessment of conformity or suitability for use. This includes in particular the modules defined in Decision 93/465/EEC or, where appropriate, the specific procedures to be used to assess either the conformity or the suitability for use of interoperability constituents and EC verification of subsystems — Chapter 6 (Assessment of conformity and/or suitability for use of the constituents and verification of the subsystem);</li>
<li>indicates the strategy for implementing the TSI. In particular, it is necessary to specify the stages to be completed in order to make a gradual transition from the existing situation to the final situation in which compliance with the TSI shall be the norm — Chapter 7 (Implementation of the TSI control-command);</li>
<li>indicates, for the staff concerned, the professional qualifications and health and safety conditions at work required for the operation and maintenance of the subsystem concerned, as well as for the implementation of the TSI — Chapter 4 (Characterisation of the subsystem).</li>
</ol>

Moreover, in accordance with Article 5(5) of Directive 2001/16/EC, provision may be made for specific cases for each TSI; these are indicated in Chapter 7 (Implementation of the TSI control-command).

Lastly, this TSI also comprises, in Chapter 4 (Characterisation of the subsystem), the operating and maintenance rules specific to the scope indicated in sections 1.1 (Technical scope) and section 1.2 (Geographical scope).

# 2.   SUBSYSTEM DEFINITION AND SCOPE

## 2.1.   General

The control-command subsystem is defined as that set of functions and their implementation, which allow the safe movement of trains.

The TSI control-command defines the essential requirements for those parts of the Control-command subsystem that have relevance to interoperability, and therefore are subject to EC declaration of verification.

The features of the Control-command subsystem that are related to the interoperability of the trans-European conventional rail system are determined by:

1.  The FUNCTIONS that are essential for the safe control of the railway traffic, and that are essential for the operation, including those required under degraded conditions.
2.  INTERFACES.
3.  The level of PERFORMANCE required to meet the essential requirements.

The specification of these functions, interfaces and performance requirements are provided in Chapter 4 (Characterisation of the Subsystem) where supporting standards are referenced.

## 2.2.   Overview

The interoperability of the trans-European conventional rail network depends in part on the ability of the on-board control-command equipment to work with various track-side equipment.

Because of the mobility of the onboard part, the control-command subsystem is divided in two parts: onboard assembly and track-side assembly (see Figure 8 in Annex D).

### 2.2.1.   Interoperability

This TSI defines the functions, interfaces and performance requirements to ensure the achievement of technical interoperability. Technical interoperability is the prerequisite for operational interoperability, in which the driving is based on consistent information displayed in the cabs and is in accordance with unified operational requirements defined for the conventional network. This TSI also contains functions that are needed to achieve operational interoperability (see section 4.3.1 Interface to the subsystem traffic operation and management).

### 2.2.2.   Classes of control-command systems

Within the Control-command subsystem two classes of train protection and radio communication systems are defined:

Class A: The unified Control-command system.
Class B: Control-command systems and applications existing before entry into force of the Directive 2001/16/EC, limited to those described in Annex B.

In order to achieve interoperability, the trains’ on-board control-command assembly will provide:

-   the Class A radio and data communication interfaces to the infrastructure, in case of operation with Class A infrastructure,
-   the Class B radio and data communication interfaces to the infrastructure, in case of operation with Class B infrastructure. For signalling data, this can be achieved with the use of a specific transmission module (STM) that allows a Class A On-board system to operate on lines fitted with Class B track-side system using the Class B data. The interface between the Class A on-board system and STM’s is defined in this TSI.

Member States have the responsibility to ensure that Class B systems are managed during their lifetime; in particular any changes to these specifications must not prejudice interoperability.

### 2.2.3.   Levels of application

The interfaces specified by this TSI define the means of data transmission to, and sometimes from, trains. The Class A specifications referenced by this TSI provide options from which a project may choose the means of transmission that meet its requirements. Three levels of application are defined:

Level 1: Data transmission is achieved by spot transmission (Eurobalise) and in some cases by semi-continuous transmission (Euroloop or radio in-fill). The detection of trains is achieved by track-based equipment, usually track-circuits or axle counters. Signalling information is communicated to the driver by equipment in the driving cab and, optionally, lineside signals.
Level 2: Data transmission is achieved by continuous radio transmission (GSM-R). For some functions, the radio transmission requires complementing by spot transmission (Eurobalise). The detection of trains is achieved by track-based equipment, usually track-circuits or axle counters. Signalling information is communicated to the driver by equipment in the driving cab and, optionally, lineside signals.
Level 3: Data transmission is achieved by continuous radio transmission (GSM-R). For some functions, the radio transmission requires complementing by spot transmission (Eurobalise). The detection of trains is achieved by equipment on-board, reporting to the control-command track-side assembly. Signalling information is communicated to the driver by equipment in the driving cab.

The requirements of this TSI apply to all levels of application. Implementation is addressed in Chapter 7 (Implementation of the TSI control-command). A train equipped with a Class A On-board system for a given level of application shall be able to operate on that level and any lower one.

### 2.2.4.   Infrastructure network borders

The local technical interfaces between the Track-side control-command Assemblies of neighbouring infrastructures shall not restrict the uninterrupted passage of trains when crossing borders between them.

Any high-speed or conventional train fitted with Class A On-board system in accordance with the corresponding TSI shall not, on grounds concerning anyone of both TSIs, be restricted in operating on any high-speed or conventional route with infrastructure fitted with Class A track-side system in accordance with the corresponding TSI, as soon as the register of rolling stock of that train and the register of Infrastructure of that route have been cross-checked for interoperability.

# 3.   THE ESSENTIAL REQUIREMENTS OF THE CONTROL-COMMANDCONTROL-COMMAND SUBSYSTEM

## 3.1.   General

The interoperability Directive 2001/16/EC Article 4(1) requires that the trans-European conventional rail system, subsystems and the interoperability constituents including interfaces meet the essential requirements set out in general terms in Annex III to the Directive. The eEssential requirements are:

-   safety,
-   reliability and availability,
-   health,
-   environmental protection,
-   technical compatibility.

The Directive allows that the essential requirements may be applied to the whole trans-European conventional rail system or be specific to each subsystem and its interoperability constituents.

The Essential Requirements are taken in turn, below. Requirements on Class B systems are the responsibility of the relevant Member State.

## 3.2.   Specific Aspects for the control-command subsystem

### 3.2.1.   Safety

Every project to which this specification is applied shall put into effect the measures necessary to demonstrate that the level of risk of an incident occurring that is within the scope of the Control-command subsystem, is not higher than the objective for the service. To ensure that the solutions to achieve safety do not jeopardise interoperability the requirements of the basic parameter defined in section  4.2.1 (Control-command safety characteristics relevant to interoperability) shall be respected.

For Class A system, the global safety objective for the subsystem is apportioned between the on-board and Track-side Assemblies. The detailed requirements are specified in the basic parameter defined in section 4.2.1 (Control-command safety characteristics relevant to interoperability). This safety requirement must be met together with the availability requirements as defined in Section 3.2.2 (Reliability and Availability).

For Class B systems used for conventional rail operation, it is the responsibility of the appropriate Member State (defined in Annex B) to:

-   ensure that the Class B system design meets national safety targets,
-   ensure that the application of the Class B system meets national safety targets,
-   define the safe operating parameters and conditions of use of the Class B system (including, but not limited to, maintenance and degraded modes).

### 3.2.2.   Reliability and Availability

<ol type="a">
<li>For Class A system, the global reliability and availability objectives for the subsystem are apportioned between the On-board and Track-side Assemblies. The detailed requirements are specified inthe Basic Parameter defined in section 4.2.1 (control-command safety characteristics relevant to interoperability).</li>
<li>The quality of the maintenance organisation for all systems comprising the control-command subsystem shall ensure that the level of risk is controlled as constituents age and wear. The quality of the maintenance shall ensure that safety is not prejudiced because of these activities. See section 4.5 (Maintenance rules).</li>
</ol>

### 3.2.3.   Health

According to the European regulations and to the national regulations which are compatible with the European legislation, precautions shall be taken to ensure that the materials used in and the design of Control-command subsystems do not constitute a health hazard to persons having access to them.

### 3.2.4.   Environmental protection

According to the European regulations and to the national regulations which are compatible with the European legislation:

-   the control-command equipment, if subjected to excessive heat or fire, shall not exceed limits for the emission of fumes or gases which are harmful to the environment,
-   the control-command equipment shall not contain substances which may during their normal use abnormally contaminate the environment,
-   the control-command equipment shall be subject to the European legislation in force controlling the limits to the emission of and the susceptibility to electromagnetic interference along the boundaries of railway property,
-   the control-command equipment shall comply with existing regulations on noise pollution,
-   the control-command equipment shall not give rise to any inadmissible level of vibration which could jeopardise the integrity of the infrastructure (when the infrastructure is in the correct state of maintenance).

### 3.2.5.   Technical compatibility

Technical compatibility includes the functions, interfaces and performances required to achieve interoperability.

The requirements of technical compatibility are subdivided in the following three categories:

-   the first category sets out the general engineering requirements for interoperability, that is environmental conditions, internal electromagnetic compatibility (EMC) within the railway boundaries, and installation. These compatibility requirements are defined in this Chapter,
-   the second category describes how the control-command subsystem has to be applied and what functions it has to perform in order that interoperability is achieved. This category is defined in Chapter 4,
-   the third category describes how the control-command subsystem has to be operated in order that interoperability is achieved. This category is defined in Chapter 4.

#### 3.2.5.1.   Engineering compatibility

##### 3.2.5.1.1.   Physical environmental conditions

Systems complying with the Class A system requirements shall be capable of operating under the climatic and physical conditions which exist along the relevant part of the trans-European conventional network. For the interfaces to rolling stock see section 4.3.2.5 (Physical environmental conditions) and for the interfaces to infrastructure see section 4.3.3.3 (Physical environmental conditions).

Systems complying with the Class B system requirements shall conform at least to the physical environmental specifications applying to the corresponding Class B system, in order to be capable of operating under the climatic and physical conditions which exist along the conventional lines concerned.

##### 3.2.5.1.2.   Railway internal electromagnetic compatibility

The Basic Parameter is described in section 4.2.12 (Electromagnetic compatibility). For the interfaces to rolling stock see section 4.3.2.6 (Electromagnetic compatibility), for the interfaces to infrastructure see section 4.3.3.4 (Electromagnetic compatibility) and for the interfaces to Energy see section 4.3.4.1 (Electromagnetic compatibility).

##### 3.2.5.2.   Control-command compatibility.

Chapter 4, supported by Annexes A and B, defines the requirements for the interoperability of the control-command subsystem.

In addition, this TSI together with the control-command TSI for the trans-European high-speed rail system ensures, as far as the control-command subsystem is concerned, the technical interoperability between trans-European high- speed rail and conventional rail systems when both are fitted with Class A system.

# 4.   CHARACTERISATION OF THE SUBSYSTEM

## 4.1.   Introduction

The trans-European conventional rail system, to which the Directive 2001/16/EC applies and of which the control-command subsystem is a part, is an integrated system whose consistency must be verified. This consistency must be checked in particular with regard to the specifications of the subsystem, its interfaces vis-à-vis the system in which it is integrated, as well as the operating and maintenance rules.

Taking account of all the relevant essential requirements, the control-command subsystem is characterised by the following basic parameters:

-   control-command safety characteristics relevant to interoperability (section 4.2.1),
-   on-board ETCS functionality (section 4.2.2),
-   track-side ETCS functionality (section 4.2.3),
-   EIRENE functions (section 4.2.4),
-   ETCS and EIRENE air gap interfaces (section 4.2.5),
-   on-board Interfaces Internal to Control Command (section 4.2.6),
-   track-side Interfaces Internal to Control Command (section 4.2.7),
-   key management (section 4.2.8),
-   ETCS-ID management (section 4.2.9),
-   HABD (hot axle box detector) (section 4.2.10),
-   compatibility with track-side Train Detection Systems (section 4.2.11),
-   Electromagnetic compatibility (section 4.2.12),
-   ETCS DMI (driver machine interface) (section 4.2.13)
-   EIRENE DMI (driver machine interface) (section 4.2.14)
-   interface to data recording for regulatory purposes (section 4.2.15)
-   Visibility of track-side control-command objects (section 4.2.16)

The requirements of sections

-   4.2.10 (HABD (Hot axle box detector)),
-   4.2.11 (Compatibility with track-side train detection systems),
-   4.2.12 (Electromagnetic compatibility),
-   4.2.16 (Visibility of track-side Control-command objects)

shall always be applied, independently of the class of system.

All other requirements in section 4.2 (Functional and technical specifications of the subsystem) shall always be applied to the Class A system only. Requirements of Class B systems are the responsibility of the appropriate Member State. Annex B deals with the characteristics of the Class B system and defines the responsible Member States.

The STMs, which enable the Class A on-board system to operate over Class B infrastructure, are subject to the Class B requirements.

To achieve interoperability it is not necessary to standardise all the functions within the whole control-command subsystem. The functionality for automatic train protection and automatic train control considered in chapter 4 is:

-   on-board standard functions, ensuring that every train will react to data received from track-side in a predictable way,
-   track-side standard functions, able to process data from national interlocking and signalling systems and to translate such data into standard messages for the trains,
-   standard interfaces for track-to-train and train-to-track communication.

The control-command functions are classified in categories indicating, for example, whether they are optional or mandatory. The categories are defined in Annex A, Index 1 and Annex A, Index 32 and the classification of the functions are indicated within their text.

Annex A, Index 3 provides the Glossary of ETCS terms and definitions which are used in the specifications referred in Annex A.

In light of the essential requirements in Chapter 3, the functional and technical specifications of the control-command subsystem are as follows:

## 4.2.   Functional and technical specifications of the subsystem

### 4.2.1   Control-command safety characteristics relevant to interoperability

This basic parameter describes the safety requirements on On-board assemblies and the safety requirements on Track-side assemblies.

With reference to the essential requirement ‘safety’ (see section 3.2.1, Safety), this basic parameter establishes the mandatory requirements for interoperability:

-   to ensure that the solutions to achieve safety do not jeopardise interoperability the requirements of Annex A, Index 47 shall be respected,
-   for the safety related part of one on-board assembly as well as for one track-side assembly, the safety requirement for ETCS level 1 or level 2 (1) is: tolerable hazard rate (THR) of 10-9/hour (for random failures) corresponding to Safety Integrity Level 4. The detailed requirements for Class A equipment are specified in Annex A, Index 27. Less restrictive safety requirements on THR values for track-side equipment may be adopted, provided that the safety objective for the service is met.
-   The reliability and availability requirements of Annex A, Index 28 shall be respected.

### 4.2.2.   On-board ETCS functionality

This basic parameter describes the ETCS on-board functionality. It contains all functions to run a train in a safe way. The performance of the functions shall conform to Annex A, Index 14. These functions shall be implemented in accordance with Annex A, Index 1, 2, 4, 13, 23, 24, 53 and the technical specifications indicated below:

-   Communicating with the control-command track-side assembly. The in-fill data transmission function in ETCS Level 1 applications is only mandatory on-board under the conditions defined in Chapter 7. Data radio functionality for ETCS is only mandatory for ETCS Level 2 or ETCS Level 3 applications.
-   Eurobalise reception. See Annex A, Index 9, 36, 43
-   Euroloop reception. See Annex A, Index 15, 16, 50
-   Radio transmission and radio messages protocol management. See Annex A, Index 10, 11, 12, 18, 19, 22, 39, 40.
-   Communicating with the driver
-   Supporting driving. See Annex A, Index 51
-   Providing odometry information. See Annex A, Index 51.
-   Communicating with the STM’s. See Annex A, Index 8, 25, 26, 36, 52. This function includes:
-   Managing the STM’s output
-   Providing data to be used by the STM
-   Managing STM transitions.
-   Providing the automatic train protection function and cab-signalling. See Annex A, Index 6, 7, 31, 37. This function includes:
-   Locating the train in a Eurobalise co-ordination system, which is the basis for supervising the dynamic speed profile
-   Calculating the dynamic speed profile for its mission
-   Supervising the dynamic speed profile during its mission
-   Selecting the speed supervision mode
-   Supervising the train according national values
-   Defining and providing the intervention function
-   Setting the train characteristics.
-   Demonstrating the completeness of the train (train integrity) — mandatory for level 3, not required for level 1 or 2.
-   Equipment health monitoring and failure mode support. This function includes:
-   Initialising the on-board ETCS functionality
-   Providing failure mode support.
-   Isolation of the on-board ETCS functionality.
-   Support data recording for regulatory purposes. See Annex A, Index 5, 41, 55.
-   The vigilance function. See Annex A, Index 42. Implementation may be:
-   Outside the ERTMS/ETCS On-board, interoperability constituent (see Chapter 5), with an optional interface to the ERTMS/ETCS On-board, or
-   Inside the ERTMS/ETCS On-board.

### 4.2.3.   Track-side ETCS functionality

This basic parameter describes the ETCS track-side functionality. It contains all ETCS functionality to provide a safe path to a specific train. The performance of the functions shall conform to Annex A, Index 14. These functions shall be implemented in accordance with Annex A, Index 1, 2, 4, 13, 23, 24, 31, 37, 53 and the technical specifications indicated below:

-   Communication with track-side signalling equipment (interlocking, signal)
-   Locating a specific train in a Eurobalise co-ordination system (levels 2 and 3)
-   Translating the information from track-side signalling equipment into a standard format for the control-command On-board Assembly.
-   Generating movement authorities including track description and orders assigned to a specific train.
-   Communicating with the Control-command On-board Assembly. This includes:
-   Eurobalise transmission. See Annex A, Index 9, 43
-   Radio in-fill. See Annex A, Index 18, 19, 21. Radio in-fill is only relevant in level 1 in which it is optional. (see also section 7.2.6)
-   Euroloop. See Annex A, Index 16, 50. Euroloop is only relevant in level 1 in which it is optional (see also section 7.2.6)
-   RBC radio communication. See Annex A, Index 10, 11, 12, 39, 40. RBC radio communication is only relevant to level 2 and level 3.
-   Providing track clearance information to the interlocking. This function is only required for level 3.

### 4.2.4.   EIRENE functions

This basic parameter describes the EIRENE voice and data communication functions:

-   Driver call related functions
-   Operational radio functions
-   Data communication.

These functions shall be implemented in accordance with the technical specifications indicated in Annex A, Index 32, 33 and 48 and their performance shall conform to Annex A Index 54.

### 4.2.5.   ETCS and EIRENE air gap interfaces

The complete specification of these interfaces consists of two parts:

-   specification of the protocols for the transport of information from/to ERTMS functions and for ensuring safety in the communication.
-   specification of the interfaces between pieces of equipment. The interfaces between the equipment are described in:
-   Section 4.2.6 (on-board interfaces internal to control-command) for on-board
-   Section 4.2.7 (trackside interfaces internal to control-command) for track-side

This basic parameter describes the air gap between track-side and onboard control-command assemblies. It includes:

-   the physical, electrical and electromagnetic values to be respected to allow a safe functioning,
-   the communication protocol to be used,
-   the availability of the communication channel.

The following specifications apply:

-   radio communications with the train.

Class A radio communication interfaces shall operate in the R-GSM Band. See Annex A, Index 35. The protocols shall comply with Annex A Index 10, 18, 19, 39, 40

-   Eurobalise and Euroloop communication with the train.

Eurobalise communication interfaces shall comply with Annex A Index 9, 43. Euroloop communication interfaces shall comply with Annex A Index 16, 50.

### 4.2.6.   On-board interfaces internal to control-command

This basic parameter consists of three parts.

\####4.2.6.1.   Interface between ETCS and STM
The specific transmission module (STM) allows ETCS on-board to operate on lines fitted with Class B systems.

The interface between the on-board ETCS functionality and the STMs for Class B systems is defined in Annex A, Index 4, 8, 25, 26. Annex A, Index 45 specifies the K interface. Implementation of the K interface is optional but if done, must be in accordance with Annex A, Index 45.

#### 4.2.6.1.   GSM-R/ETCS

The interface between the Class A radio and the on-board ETCS functionality. These requirements are specified in Annex A Index 4, 7, 20, 22, 34.

#### 4.2.6.2.   Odometry

The interface between the odometry function and ERTMS/ETCS on-board shall meet the requirements of Annex A, Index 44. This interface only contributes to this basic parameter when odometry equipment is supplied as a separate interoperability constituent (see section 5.2.2, Grouping of interoperability constituents).

### 4.2.7.   Trackside interfaces internal to control-command

This basic parameter consists of six parts.

#### 4.2.7.1.   Functional interface between RBCs

This interface is used to define the data to be exchanged between neighbouring radio block centres (RBC) to be able to move in a safe way a train from one RBC area to another. It describes:

-   information from the ‘handing over’ RBC to the ‘accepting’ RBC,
-   information from the ‘accepting’ RBC to the ‘handing over’ RBC

These requirements are specified in Annex A, Index 12.

#### 4.2.7.2.   Technical interface between RBCs

This is the technical interface between two RBC's. These requirements are specified in Annex A, Index 58.

#### 4.2.7.3.   GSM-R/RBC

This is the interface between the Class A radio system and the track-side ETCS functionality. These requirements are specified in Annex A, Index 4, 20, 22, 34.

#### 4.2.7.4.   Eurobalise/LEU

This is the interface between Eurobalise and the lineside electronic unit (LEU). These requirements are specified in Annex A, Index 9. This interface only contributes to this basic parameter when Eurobalise and LEUs are supplied as separate interoperability constituents (see section 5.2.2, Grouping of interoperability constituents).

#### 4.2.7.5.   Euroloop/LEU

This is the interface between Euroloop and the LEU. These requirements are specified in Annex A, Index 16. This interface only contributes to this basic parameter when Euroloop and LEUs are supplied as separate interoperability constituents (see section 5.2.2, Grouping of interoperability constituents).

#### 4.2.7.6.   Requirements on pre-fitting of ERTMS track side equipment

This is the interface between track-side Class A equipment and track-side control-command infrastructure. These requirements are specified in Annex A Index 59. This Index describes means for track-side pre-fitting of Class A equipment.

### 4.2.8.   Key management

This basic parameter concerns the safety related data transmitted via radio that is protected by mechanisms that need cryptographic keys. The infrastructure managers and railway undertakings shall provide a management system that controls and manages the keys. A key management interface is required:

-   between the key management systems of different infrastructure managers,
-   between the key management systems of railway undertakings and the infrastructure managers,
-   between the key management system and the on-board and track-side ETCS equipment.

The requirements to the key management between key management systems of interoperable regions are specified in Annex A, Index 11.

### 4.2.9.   ETCS-ID management

This basic parameter concerns the unique ETCS-identities for equipment in track-side and on-board assemblies. The requirements are specified in Annex A, Index 23. The allocation of variables is defined in Annex A, Index 53.

Suppliers of on-board control-command equipment are responsible for the management of unique identities within the allocated range as defined in Annex A, Index 53. Rolling stock keepers shall provide a management system that controls and manages the identities during the life-cycle of the assembly.

In Annex A, Index 53 Member States are allocated ranges of identities. Member States are responsible for the management of allocation of these ranges to the contracting entities in their State.

Contracting entities of track-side assemblies are responsible for the management of unique identities within their allocated range. The infrastructure manager shall provide a management system that controls and manages the identities during the life-cycle of the assembly.

### 4.2.10.   HABD (Hot axle box detector)

This basic parameter specifies the requirements for the track-side equipment, used to check if the temperature of passing rolling stock axle bearings has exceeded a certain value and to transmit this information to a control centre. The requirements are defined in Annex A, Appendix 2.

The treatment of rolling stock equipped with on-board detection is also described in TSI RS HS section 4.2.11.

### 4.2.11.   Compatibility with track-side train detection systems

This basic parameter describes the characteristics of track-side train detection systems that are necessary to be activated by rolling stock which conforms to the rolling stock TSI.

Rolling stock shall have the characteristics necessary for the operation of track-side train detection systems. In Annex A, Appendix 1 the requirements related to the characteristics of a vehicle are specified. These characteristics are defined in TSI rolling stock HS and TSI rolling stock freight wagons in the sections given in the table, and will be included in future rolling stock TSI’s.

| Parameter                                  | Appendix 1 TSI control-command | TSI rolling stock HS | TSI rolling stock freight wagons | TSI rolling stock traction units –locos, EMUs, DMUs- and coaches | TSI operations and traffic management (HS) | TSI operations and traffic management (CR) |     |
| ------------------------------------------ | ------------------------------ | -------------------- | -------------------------------- | ---------------------------------------------------------------- | ------------------------------------------ | ------------------------------------------ | --- |
| Axle distances                             | 2.1 incl. Figure 6             | Not yet specified    | 4.2.3.2                          | ?                                                                |                                            | —                                          |     |
| Wheel geometry                             | 2.2 incl. Figure 7             | 4.2.10               | 5.4.2.3                          | ?                                                                |                                            | —                                          |     |
| Vehicle mass (minimum axle load)           | 3.1                            | 4.1.2                | 4.2.3.2                          | ?                                                                |                                            | —                                          |     |
| Metal-free space around wheels             | 3.2                            | Not yet specified    | Chapter 6 (2)                    | ?                                                                |                                            | —                                          |     |
| Metal-mass of vehicle                      | 3.3                            | Not yet specified    | Open point                       | ?                                                                |                                            | —                                          |     |
| Wheel material                             | 3.4                            | Not yet specified    | 5.4.2.3                          | ?                                                                |                                            | —                                          |     |
| Impedance between wheels                   | 3.5                            | 4.2.10e              | 4.2.3.3.1                        | ?                                                                |                                            | —                                          |     |
| Vehicle impedance                          | 3.6                            | Not yet specified    | None                             | ?                                                                |                                            | —                                          |     |
| Use of sanding equipment                   | 4.1                            | Not yet specified    | None                             | ?                                                                |                                            | Not yet addressed                          |     |
| Use of composite brake blocks              | 4.2                            | Not yet specified    | Open point                       | ?                                                                |                                            | —                                          |     |
| Traction current                           | 5.1                            | Not yet specified    | None                             | ?                                                                |                                            |                                            | —   |
| Use of electric/magnetic brakes            | 5.2                            | 4.1.5, 4.2.15, 4.3.6 | None                             | ?                                                                |                                            | (3)                                        |     |
| Electric, magnetic, electromagnetic fields | 5.3                            | 4.1.9                | None                             | ?                                                                |                                            | —                                          |     |

### 4.2.12.   Electromagnetic compatibility

This basic parameter is split into two parts.

#### 4.2.12.1.   Internal control-command electromagnetic compatibility

Control-command equipment shall not interfere with other control-command equipment.

#### 4.2.12.2.   Electromagnetic compatibility between rolling stock and control-command track-side equipment

This includes the range of electromagnetic compatibility (EMC) emissions (conducted and induced traction current and other train originated currents, electromagnetic field characteristics as well as static fields) to be respected by rolling stock in order to ensure the correct functioning of the track-side control-command equipment. It includes the description for measuring the values.

Track-side train detection systems shall have the characteristics necessary to be compatible with rolling stock that conforms to the rolling stock TSI.

Annex A, Appendix 1 specifies the train detection systems characteristics necessary to be compatible with rolling stock. These characteristics will be included in the rolling stock TSI’s.

### 4.2.13.   ETCS DMI (driver machine interface)

This basic parameter describes the information provided from the ETCS On-board system to the driver and entered to the ERTMS/ETCS On-board by the driver. See Annex A, Index 51.

It includes:

-   ergonomics (including visibility),
-   ETCS functions to be displayed,
-   ETCS functions triggered by driver input.

### 4.2.14.   EIRENE DMI (driver machine interface)

This basic parameter describes the information provided from the EIRENE on-board system to the driver and entered to the EIRENE on-board system by the driver. See Annex A, Index 32, 33, 51.

It includes:

-   ergonomics (including visibility),
-   EIRENE functions to be displayed,
-   call related information outgoing,
-   call related information incoming.

### 4.2.15.   Interface to data recording for regulatory purposes

This basic parameter describes:

-   data exchange between the juridical recorder and the downloading tool,
-   communication protocols,
-   physical interface,
-   functional requirements for, and use of, data-recording.

It shall be possible for investigatory authorities in each Member State to have access to the recorded data that meets obligatory data-recording requirements for official and investigative purposes.

See Annex A Index 4, 5, 41, 55.

### 4.2.16.   Visibility of track-side Control-command objects

This Basic parameter describes:

-   the characteristics of retro-reflecting signs,
-   driver’s external field of view. Track-side control-command objects that need to be observed by the driver must be sited taking into account the driver’s external field of view as defined in the TSI Traffic Operations and Management.

## 4.3.   Functional and technical specifications of the interfaces to other subsystems

### 4.3.1.   Interface to the subsystem traffic operation and management

All references to the TSI OPE CR are open points and remain to be confirmed, when this TSI will be approved.

#### 4.3.1.1.   Operating rules

The European conventional network will be subject to some unified operational requirements, which will be described in the CR TSI ‘Traffic operation and management’ (section 4.4 Operating rules of CCS TSI).

TSI OPE CR: section 4.4 (to be confirmed)

#### 4.3.1.2.   ETCS driver machine interface

This interface describes the information provided from the ERTMS ETCS On-board to the driver and entered to the ERTMS ETCS On-board by the driver. The control-command basic parameter is described in section 4.2.13 (ETCS DMI (driver machine interface)).

This interface is relevant to Class A system. Requirements for Class B systems are defined by the appropriate Member State (see Annex B).

TSI OPE CR: section 4.4 (to be confirmed)

#### 4.3.1.3.   EIRENE driver machine interface

This interface describes the information provided from the EIRENE on-board system to the driver and entered to the EIRENE on-board system by the driver. The control-command basic parameter is described in section 4.2.14 (EIRENE DMI (Driver Machine Interface))

This interface is relevant to Class A systems. Equivalent requirements for Class B systems are defined by the appropriate Member State (see Annex B).

TSI OPE CR: section 4.4 (to be confirmed)

#### 4.3.1.4.   Interface to data recording for regulatory purposes

This interface refers to the functional requirements for, and use of, data-recording. The control-command basic parameter is described in section section 4.2.15 (Interface to data recording for regulatory purposes).

This interface is relevant to Class A systems. Equivalent requirements for Class B systems are defined by the appropriate Member State (see Annex B).

TSI OPE CR: section 4.2.3.5 (to be confirmed)

#### 4.3.1.5.   Guaranteed train braking performance and characteristics

The control-command subsystem requires provision of the guaranteed train braking performance. The TSI traffic operation and management will define the rules to determine the guaranteed braking performance of a train. The rolling stock TSI’s shall define the method of determining the braking performance of vehicles.

This interface is relevant to Class A system. Equivalent requirements for Class B systems are defined by the appropriate Member State (see Annex B).

TSI OPE CR: section 4.2.2.4 (to be confirmed)

#### 4.3.1.6.   Isolation of on-board ETCS functionality

This interface refers to the operational requirements for the isolation of the On-board ETCS functionality in case of failure. The control-command requirements are in section 4.2.2 (On-board ETCS functionality).

This interface is relevant to Class A system. Equivalent requirements for Class B systems are defined by the appropriate Member State (see Annex B).

TSI OPE CR: section 4.4 (to be confirmed)

#### 4.3.1.7.   Key management

This interface refers to the operational requirements for Key Management. The control-command basic parameter is described in section 4.2.8 (Key Management).

This interface is relevant to Class A system.

TSI OPE CR: To be confirmed

#### 4.3.1.8.   Hot Axle Box Detectors

This interface refers to the operational requirements for hot axle box detectors. The control-command basic parameter is described in section 4.2.10 (HABD (Hot axle box detector)).

TSI OPE CR: section 4.2.3.5.1 (to be confirmed)

#### 4.3.1.9.   Driver Vigilance

This interface refers to the operational requirements for driver vigilance. The control-command basic parameter is described in section 4.2.2 (On-board ETCS functionality).

TSI OPE CR: section 4.3.3.7 (to be confirmed)

#### 4.3.1.10.   Use of sanding

This interface refers to the operational requirements for drivers so that sand does not adversely affect the performance of track-side train detection equipment. The control-command basic parameter is described in section 4.2.11 (Compatibility with track-side train detection systems).

TSI OPE CR: Presently not addressed in OPE TSI because level of detail is different: to be confirmed

#### 4.3.1.11.   Driver’s external field of view

This interface refers to the driver’s field of view through the cab windscreen. The requirements on Control-command are described in section 4.2.16 (Visibility of track-side Control-command objects).

TSI OPE CR: section 4.3.2.2 (to be confirmed)

### 4.3.2.   Interface to the subsystem rolling stock

All references to interfaces with the CR TSI rolling stock traction units and coaches remain open points. Traction units mean locomotives, electric multiple units and diesel multiple units.

#### 4.3.2.1.   Compatibility with track-side train detection systems

Track-side train detection systems shall have the characteristics necessary to be activated by rolling stock which conforms to the rolling stock TSI. The control-command basic parameter and the references to the relevant rolling stock TSI’s are described in section 4.2.11 (Compatibility with track-side train detection systems).

#### 4.3.2.2.   Electromagnetic compatibility between rolling stock and control-command track-side equipment.

This interface is the range of electromagnetic compatibility (EMC) emissions (conducted and induced traction current and other train originated currents, electromagnetic field characteristics as well as static fields) to be respected by rolling stock in order to ensure the correct functioning of the track-side control-command equipment. The control-command basic parameter is described in section 4.2.12.2 (Electromagnetic compatibility between rolling stock and control-command track-side equipment).

TSI Rolling stock freight wagons: not concerned.

TSI Rolling stock HS: Section 4.1.9

TSI Rolling stock traction units and coaches

#### 4.3.2.3.   Guaranteed train braking performance and characteristics

The control-commandsubsystem requires provision of the guaranteed train braking performance. The rolling stock TSI’s shall define the method of determining the braking performance of vehicles. The TSI traffic operation and management will define the rules to determine the guaranteed braking performance of a train.

This interface is relevant to Class A system. Equivalent requirements for Class B systems are defined by the appropriate Member State (see Annex B).

TSI Rolling stock freight wagons: Section 4.2.4.1.2

TSI Rolling stock HS: Section 4.1.5, 4.3.7, 4.3.9

TSI Rolling stock traction units and coaches

#### 4.3.2.4.   Position of control-command on-board antennae

The position of the Eurobalise and Euroloop antennae on the rolling stock shall be such that reliable data communication is assured at the extremes of the track geometry capable of being traversed by the rolling stock. The movement and behaviour of the rolling stock shall be taken into account. The control-command basic parameter is described in section 4.2.2 (On-board ETCS functionality).

This interface is relevant to Class A system. Requirements for Class B systems are defined by the appropriate Member State (see Annex B).

The position of the GSM-R antenna on the roof of vehicles is mainly dependent on measurements that have to be carried out for any type of vehicle taking into account also the position of other (new or existing) antennas. Under test conditions the output of the antenna has to comply with the requirements described in section 4.2.5 (ETCS and EIRENE air gap interfaces). The test conditions are also described in section 4.2.5 (ETCS and EIRENE air gap interfaces).

TSI Rolling stock freight wagons not concerned.

TSI Rolling stock HS: Annex 0, 0.5, section 4.2.4

TSI Rolling stock traction units and coaches

#### 4.3.2.5.   Physical environmental conditions

The climatic and physical environmental conditions of control-command equipment expected on the train shall be defined by reference to the Infrastructure Registers of the lines where the train is intended to operate and by reference to Annex A, Index A4.

TSI Rolling stock HS: Section 4.3.12

TSI Rolling stock freight wagons not concerned

TSI Rolling stock traction units and coaches

#### 4.3.2.6.   Electromagnetic compatibility

To facilitate the universal use of the equipment for the control-command on-board Assembly on new rolling stock accepted for operation upon the trans-European conventional network, the electromagnetic conditions expected on the train shall be defined in accordance with Annex A, Index A6. For Eurobalise communication system specific provisions in Annex A, Index 9 apply.

Requirements for Class B systems are defined by the appropriate Member State (see Annex B).

TSI Rolling stock HS:

TSI Rolling stock freight wagons not concerned.

TSI Rolling Stock traction units and coaches

#### 4.3.2.7.   Isolation of on-board ETCS functionality

This interface refers to the isolation of the on-board ETCS functionality. The control-command requirements are in 4.2.2 (On-board ETCS functionality).

This interface is relevant to Class A system. Equivalent requirements for Class B subsystems are defined by the responsible Member States (see Annex B).

TSI Rolling stock HS: Section 4.2.4 (to be added in)

TSI Rolling stock freight wagons not concerned.

TSI Rolling stock traction units and coaches

#### 4.3.2.8.   Data interfaces

The data interface between the train and control-command on-board assembly is defined in Annex A, Index 7.

This interface is relevant to Class A system. Equivalent requirements for Class B systems are defined by the appropriate Member State (see Annex B).

TSI Rolling stock HS: Section 4.2.4, 4.3.13

TSI Rolling stock freight wagons are not concerned for ETCS level 1 and level 2.

TSI Rolling stock traction units and coaches

The interface requirements between the radio communications and the rolling stock subsystem are specified in Annex A, Index 33.

This interface is relevant to Class A system. Equivalent requirements for Class B systems are defined by the appropriate Member State (see Annex B).

The respective corresponding specification is laid down in

-   TSI Rolling stock freight wagons: not concerned.
-   TSI Rolling stock HS: Section
-   TSI Rolling stock traction units and coaches

#### 4.3.2.9.   Hot axle box detectors

This interface refers to the technical requirements for hot axle box detectors. The control-command basic parameter is described in section 4.2.10 (HABD (Hot axle box detector)).

The respective corresponding specification is laid down in

-   TSI Rolling stock freight wagons: Section 4.2.3.3.2
-   TSI Rolling stock HS: Section 4.2.11, 4.3.13
-   TSI Rolling stock traction units and coaches

#### 4.3.2.10.   Vehicle headlights

This interface refers to the technical requirements for the chromaticity and luminosity of vehicle headlights to ensure the correct visibility of reflective lineside signage and reflective clothing. The control-command requirements are described in section 4.2.16 (Visibility of track-side control-command objects).

TSI Rolling stock freight wagons not concerned.

TSI Rolling stock HS: Section: 4.2.20

TSI Rolling stock traction units and coaches

#### 4.3.2.11.   Driver vigilance

This interface refers to the technical requirements for driver vigilance. The control-command basic parameter is described in section 4.2.2 (On-board ETCS functionality).

TSI Rolling stock freight wagons not concerned.

TSI Rolling stock HS: Section 4.2.2

TSI Rolling stock traction units and coaches

#### 4.3.2.12.   Odometry

This is the interface between the odometry device and the odometry functionality required for ETCS on-board functions.

This interface to rolling stock TSI’s is only relevant to the basic parameter described in section 4.2.6.3 (Odometry) when odometry equipment is supplied as a separate interoperability constituent (see section 5.2.2 Grouping of interoperability constituents).

This interface is relevant to Class A system. Equivalent requirements for Class B systems are defined by the appropriate Member State (see Annex B).TSI Rolling stock HS: Section 4.2.4

TSI Rolling stock freight wagons not concerned.

TSI Rolling stock traction units and coaches

#### 4.3.2.13.   Interface to data recording for regulatory purposes

This interface refers to the technical requirements for data recording. The control-command basic parameter is described in section 4.2.15 (Interface to data recording for regulatory purposes).

This interface is relevant to Class A system. Requirements for Class B systems are defined by the appropriate Member State (see Annex B).

TSI Rolling stock freight wagons not concerned.

TSI Rolling stock HS: section 4.3.13

TSI Rolling stock traction units and coaches

#### 4.3.2.14.   Onboard pre-fitting

This interface refers to the extend of pre-fitting on a rolling stock with Class A equipment as described in Annex A, Index 57.

This interface is relevant to Class A systems.

TSI Rolling stock HS: section 4.2.4

### 4.3.3.   Interfaces to subsystem infrastructure

#### 4.3.3.1.   Train detection systems

The infrastructure installation shall ensure that the train detection system respects the requirements quoted in section 4.2.11 (Compatibility with track-side train detection systems).

TSI Infrastructure: a reference to CCS TSI will be included in future TSI so that CCS requirements can be respected by Infrastructure.

#### 4.3.3.2.   Track-side antennae

Track-side subsystems antennae must be positioned so that reliable data communication is assured at the extremes of the track geometry capable of being traversed by the rolling stock. The movement and behaviour of the rolling stock shall be taken into account. See section 4.2.5 (ETCS and EIRENE air gap interfaces).

This interface is relevant to Class A system. Equivalent requirements for Class B systems are defined by the appropriate Member State (see Annex B).

TSI Infrastructure: tbd relative to the gauge

#### 4.3.3.3.   Physical environmental conditions

The climatic and physical environmental conditions expected in the infrastructure shall be indicated in the Infrastructure Register, by reference to Annex A, Index A5.

#### 4.3.3.4.   Electromagnetic compatibility

The electromagnetic conditions expected in the infrastructure shall be defined by reference to Annex A, Index A7. For the Eurobalise communication system the specific provisions in Annex A, Index 9 apply. A control-command on-board assembly complying with Annex A, Index A6 and the specific requirements for Eurobalise in Annex A, Index 9 shall be considered compliant with the relevant essential requirements.

### 4.3.4.   Interfaces to subsystem energy

#### 4.3.4.1.   Electromagnetic compatibility

The electromagnetic conditions expected from the fixed installations shall be defined by reference to Annex A, Index A7. For the Eurobalise communication system the specific provisions in Annex A, Index 9 apply. A control-command on-board assembly complying with Annex A, Index A6 and the specific requirements for Eurobalise in Annex A, Index 9 shall be considered compliant with the relevant essential requirements.

## 4.4.   Operating rules

The operating rules specific to the control-command subsystem are detailed in the TSI Traffic operation and management.

## 4.5.   Maintenance rules

The maintenance rules of the subsystem covered by this TSI shall ensure that the values quoted in the basic parameters indicated in Chapter 4 are maintained within the required limits throughout the lifetime of the assemblies. However, during preventative or corrective maintenance, the subsystem may not be able to achieve the values quoted in the basic parameters; the maintenance rules shall ensure that safety is not prejudiced during these activities.

To achieve these results, the following shall be respected.

### 4.5.1.   Responsibility of manufacturer of equipment

The manufacturer of equipment incorporated in the subsystem shall specify:

-   all maintenance requirements and procedures (including supervision of well functioning, diagnosis and test methods and tools) necessary for the achievement of essential requirements and values quoted in the mandatory requirements of this TSI during the whole equipment life-cycle (transport and storage before installation, normal operation, failures, repair actions, verifications and maintenance interventions, de-commissioning etc.),
-   all the risk for health and safety that may affect the public and the maintenance staff,
-   the conditions for first line maintenance (i.e. the definition of line replaceable units (LRUs), the definition of approved compatible versions of hardware and software, the substitution of failed LRUs, and e.g. the conditions for storage of LRUs and for repair of failed LRUs,
-   the technical conditions for running a train with failed equipment to the end of its mission or to the workshop (degraded mode from a technical point of view, e.g. functions partially or fully switched off, isolation from other functions etc.).
-   the verifications to be performed in case equipment is subject to exceptional stress (e.g. exceedance of environmental conditions or abnormal shocks)

### 4.5.2.   Responsibility of contracting entities

The contracting entities shall:

-   ensure that, for all components within the scope of this TSI (regardless if interoperability constituents or not), the maintenance requirements as described in section 4.5.1 (Responsibility of manufacturer of equipment) are defined.
-   set up the necessary maintenance rules relevant for all components within the scope of this TSI taking account of risks due to interactions of different equipment inside the subsystem and interfaces to other subsystems.

### 4.5.3.   Responsibility of infrastructure manager or railway undertaking

The infrastructure manager or railway undertaking responsible for operating the on-board or track-side assembly:

-   Shall set up a maintenance plan as specified in section 4.5.4 (Maintenance plan).

### 4.5.4.   Maintenance plan

The maintenance plan shall be based on the provisions specified in section 4.5.1 (Responsibility of manufacturer of equipment), section 4.5.2 (Responsibility of contracting entities) and section 4.5.3 (Responsibility of infrastructure manager or railway undertaking) and cover, at least:

-   conditions for the use of equipment, according to the requirements indicated by the manufacturers,
-   specification of the maintenance programs (e.g. definition of preventive and corrective maintenance categories, maximum time between preventive maintenance actions and corresponding precautions to be taken for the safety of the subsystem and the maintenance staff, considering interference of maintenance actions with the operation of the Control-command subsystem),
-   requirements for the storage of spare parts,
-   definition of first line maintenance,
-   rules for the management of failed equipment,
-   requirements related to the minimum competence of maintenance staff, with reference to the risks for health and safety,
-   definition of responsibilities and authorisation of maintenance staff (e.g. for access to equipment, management of limitations and/or interruptions of system operation, replacement of LRUs, repair of failed LRUs, restore of normal system operation),
-   procedures for the management of ETCS-identities. See section 4.2.9 (ETCS-ID Management),
-   methods for reporting to the manufacturer of equipment information on safety-critical defects and frequent system failures.

## 4.6.   Professional qualifications

The professional qualifications required for the operation of the control-command subsystem are covered by the TSI Traffic Operation and Management.

The competence requirements for the maintenance of the Control-command subsystem shall be detailed in the maintenance plan (see section 4.5.4 Maintenance plan).)

## 4.7.   Health and safety conditions

In addition to the requirements specified in the maintenance plans, see section 4.5 (Maintenance rules), precautions shall be taken to ensure health and safety for maintenance and operations staff, in accordance with the European regulations and the national regulations that are compatible with the European legislation.

## 4.8.   Infrastructure and Rolling stock registers

The control-command subsystem is treated as two assemblies:

-   the on-board assembly,
-   the track-side assembly.

The requirements for the conventional rail infrastructure and rolling stock register content with regard to the control-command assemblies are specified in Annex C (line specific and train specific characteristics).

# 5.   INTEROPERABILITY CONSTITUENTS

## 5.1.   Definitions

According to Article 2(d) of Directive 2001/16/EC:

Interoperability constituents are ‘any elementary component, group of components, subassembly or complete assembly of equipment incorporated or intended to be incorporated into a subsystem upon which the interoperability of the trans-European conventional rail system depends directly or indirectly. The concept of a constituent covers both tangible objects and intangible objects such as software.’

As described in Chapter 2, the control-command subsystem is divided into two assemblies therefore the general definition of the Directive may therefore be adapted as follows:

Control-command interoperability constituents are any elementary component, group of components or subassembly of equipment incorporated or intended to be incorporated into the track-side assembly or into the on-board assembly, and upon which the interoperability of the trans-European conventional rail system depends directly or indirectly. The concept of a constituent covers both tangible objects and intangible objects such as software.

## 5.2.   List of interoperability constituents

### 5.2.1.   Basic interoperability constituents

The interoperability constituents in the control-command subsystem are listed in:

-   Table 5.1.a for the on-board assembly,
-   Table 5.2.a for the track-side assembly.

The interoperability constituent ‘safety platform’ is defined as a building block (generic product, independent of the application) made of hardware and base software (firmware and/or operating system and/or support tools), which can be used for building more complex systems (generic applications, i.e. classes of applications).

### 5.2.2.   Grouping of interoperability constituents

The control-command basic interoperability constituents defined in Tables 5.1.a and 5.2.a may be combined to form a larger unit. The group is then defined by the functions of the integrated interoperability constituents and the remaining interfaces to the outside of the group. If a group is formed this way, it shall be considered as an interoperability constituent.

-   Table 5.1.b lists the groups of interoperability constituents of the on-board assembly
-   Table 5.2.b lists the groups of interoperability constituents of the track-side assembly

When the mandatory specifications indicated in this TSI are not available to support an interface, a declaration of conformity may be possible by grouping interoperability constituents.

## 5.3.   Constituents performances and specifications

For each basic interoperability constituent or group of interoperability constituents, the tables in chapter 5 describe:

-   in column 3, the functions and interfaces. Note that some interoperability constituents have functions and/or interfaces that are optional,
-   in column 4, the mandatory specifications for the conformity assessment of each function or interface, as far as relevant, by reference to the relevant section of chapter 4,
-   in column 5, the modules to be applied for conformity assessment, which are described in chapter 6 of this TSI.

Note that the requirements of section 4.5.1 (Responsibility of manufacturer of equipment) apply to each basic interoperability constituent or group of interoperability constituents.

Table 5.1.a

Basic interoperability constituents in the on-board control-command assembly

| 1 No | 2 Interoperability constituent IC | 3 Characteristics                                                                          | 4 Specific requirements to be assessed by reference to Annex A Index n | 5 Module                   |
| ---- | --------------------------------- | ------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------- | -------------------------- |
| 1.   | ERTMS ETCS on-board               | Safety                                                                                     | 4.2.1                                                                  |                            |
|      |                                   | On-board ETCS functionality                                                                | 4.2.2                                                                  | H2 or B with D or B with F |
|      |                                   | Excluding:<ul><li>Odometry</li><li>Data recording for regulatory purposes</li></ul>        |                                                                        |                            |
|      |                                   | ETCS and EIRENE air gap interfaces                                                         | 4.2.5                                                                  |                            |
|      |                                   | RBC (level 2 and 3)                                                                        |                                                                        |                            |
|      |                                   | Radio in-fill unit (optional level 1)                                                      |                                                                        |                            |
|      |                                   | Eurobalise airgap                                                                          |                                                                        |                            |
|      |                                   | Euroloop airgap (optional level 1)                                                         |                                                                        |                            |
|      |                                   | Interfaces                                                                                 |                                                                        |                            |
|      |                                   | STM (implementation of interface K optional)                                               | 4.2.6.1                                                                |                            |
|      |                                   | ERTMS GSM-R on-board                                                                       | 4.2.6.2                                                                |                            |
|      |                                   | Odometry                                                                                   | 4.2.6.3                                                                |                            |
|      |                                   | Key management system                                                                      | 4.2.8                                                                  |                            |
|      |                                   | ETCS ID Management                                                                         | 4.2.9                                                                  |                            |
|      |                                   | ETCS Driver Machine Interface                                                              | 4.2.13                                                                 |                            |
|      |                                   | Key Management                                                                             | 4.3.1.7                                                                |                            |
|      |                                   | Physical environmental conditions                                                          | 4.3.2.5                                                                |                            |
|      |                                   | EMC                                                                                        | 4.3.2.6                                                                |                            |
|      |                                   | Data interface. This also includes vigilance (optional) and train integrity (only level 3) | 4.3.2.8                                                                |                            |
|      |                                   | Safety Information recorder                                                                | none                                                                   |                            |
| 2.   | Safety platform on-board          | Safety                                                                                     | 4.2.1                                                                  | H2 or B with D or B with F |
| 3.   | Safety information recorder       | On-board ETCS functionality                                                                | 4.2.2                                                                  | H2 or B with D or B with F |
|      |                                   | Only Data recording for regulatory purposes                                                |                                                                        |                            |
|      |                                   | Interfaces                                                                                 |                                                                        |                            |
|      |                                   | JRU downloading tool                                                                       | 4.2.15                                                                 |                            |
|      |                                   | ERTMS/ETCS on-board                                                                        | none                                                                   |                            |
|      |                                   | Environmental conditions                                                                   | 4.3.2.5                                                                |                            |
|      |                                   | EMC                                                                                        | 4.3.2.6                                                                |                            |
| 4.   | Odometry                          | Safety                                                                                     | 4.2.1                                                                  | H2 or B with D or B with F |
|      |                                   | On-board ETCS functionality                                                                | 4.2.2                                                                  |                            |
|      |                                   | Only odometry                                                                              |                                                                        |                            |
|      |                                   | Interfaces                                                                                 |                                                                        |                            |
|      |                                   | ERTMS ETCS on-board                                                                        | 4.2.6.3                                                                |                            |
|      |                                   | Environmental conditions                                                                   | 4.3.2.5                                                                |                            |
|      |                                   | EMC                                                                                        | 4.3.2.6                                                                |                            |
| 5.   | External STM                      | Functions and safety                                                                       | none                                                                   | H2 or B with D or B with F |
|      |                                   | According to national specifications                                                       |                                                                        |                            |
|      |                                   | Interfaces                                                                                 |                                                                        |                            |
|      |                                   | ERTMS ETCS on-board                                                                        | 4.2.6.1                                                                |                            |
|      |                                   | Class B system air gap According to national specifications                                | none                                                                   |                            |
|      |                                   | Environmental conditions According to national specifications                              | none                                                                   |                            |
|      |                                   | EMC According to national specifications                                                   | none                                                                   |                            |
| 6.   | ERTMS/GSM-R on-board              | EIRENE functions                                                                           | 4.2.4                                                                  | H2 or B with D or B with F |
|      |                                   | Data communication only in level 2 or 3 or level 1 with radio in-fill                      |                                                                        |                            |
|      |                                   | Interfaces                                                                                 |                                                                        |                            |
|      |                                   | ERTMS ETCS on-board Only in level 2 or 3 or level 1 with radio in-fill                     | 4.2.6.2                                                                |                            |
|      |                                   | GSM-R                                                                                      | 4.2.5                                                                  |                            |
|      |                                   | EIRENE Driver Machine Interface                                                            | 4.2.14                                                                 |                            |
|      |                                   | Environmental conditions                                                                   | 4.3.2.5                                                                |                            |
|      |                                   | EMC                                                                                        | 4.3.2.6                                                                |                            |

Table 5.1.b

Groups of interoperability constituents in the On-board control-command assembly

This table is an example to show the structure. Other groups may be proposed

| 1 No | 2 Interoperability constituent IC                                                             | 3 Characteristics                                                                          | 4 Specific requirements to be assessed by reference to Annex A Index n | 5 Module                   |
| ---- | --------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------- | -------------------------- |
| 1.   | Safety platform on-board<br/>ERTMS ETCS on-board<br/>safety information recorder<br/>Odometry | Safety                                                                                     | 4.2.1                                                                  |                            |
|      |                                                                                               | On-board ETCS functionality                                                                | 4.2.2                                                                  | H2 or B with D or B with F |
|      |                                                                                               | ETCS and EIRENE air gap interfaces                                                         | 4.2.5                                                                  |                            |
|      |                                                                                               | RBC (level 2 and 3)                                                                        |                                                                        |                            |
|      |                                                                                               | Radio in-fill unit (optional level 1)                                                      |                                                                        |                            |
|      |                                                                                               | Eurobalise airgap                                                                          |                                                                        |                            |
|      |                                                                                               | Euroloop airgap (optional level 1)                                                         |                                                                        |                            |
|      |                                                                                               | Interfaces                                                                                 |                                                                        |                            |
|      |                                                                                               | STM (implementation of interface K optional)                                               | 4.2.6.1                                                                |                            |
|      |                                                                                               | ERTMS GSM-R on-board                                                                       | 4.2.6.2                                                                |                            |
|      |                                                                                               | Key management system                                                                      | 4.2.8                                                                  |                            |
|      |                                                                                               | ETCS ID Management                                                                         | 4.2.9                                                                  |                            |
|      |                                                                                               | ETCS Driver machine Interface                                                              | 4.2.13                                                                 |                            |
|      |                                                                                               | Physical environmental conditions                                                          | 4.3.2.5                                                                |                            |
|      |                                                                                               | EMC                                                                                        | 4.3.2.6                                                                |                            |
|      |                                                                                               | JRU downloading tool                                                                       | 4.2.15                                                                 |                            |
|      |                                                                                               | Data interface. This also includes vigilance (optional) and train integrity (only level 3) | 4.3.2.8                                                                |                            |

Table 5.2.a

Basic interoperability constituents in the Track-side control-command assembly

| 1 No | 2 Interoperability constituent IC | 3 Characteristics                                                                          | 4 Specific requirements to be assessed by reference to Annex A Index n | 5 Module                   |
| ---- | --------------------------------- | ------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------- | -------------------------- |
| 1.   | RBC                               | Safety                                                                                     | 4.2.1                                                                  |                            |
|      |                                   | Track-side ETCS functionality                                                              | 4.2.3                                                                  | H2 or B with D or B with F |
|      |                                   | Excluded communication via Eurobalises, radio in-fill and Euroloop                         |                                                                        |                            |
|      |                                   | ETCS and EIRENE air gap interfaces                                                         | 4.2.5                                                                  |                            |
|      |                                   | Only radio communication with train                                                        |                                                                        |                            |
|      |                                   | Interfaces                                                                                 |                                                                        |                            |
|      |                                   | Neighbouring RBC                                                                           | 4.2.7.1, 4.2.7.2                                                       |                            |
|      |                                   | ERTMS GSM-R track-side                                                                     | 4.2.7.3                                                                |                            |
|      |                                   | Key management system                                                                      | 4.2.8                                                                  |                            |
|      |                                   | ETCS-ID Management                                                                         | 4.2.9                                                                  |                            |
|      |                                   | Interlocking                                                                               | none                                                                   |                            |
|      |                                   | Environmental conditions                                                                   | 4.3.3.3                                                                |                            |
|      |                                   | EMC                                                                                        | 4.3.3.4                                                                |                            |
| 2.   | Radio in-fill unit                | Safety                                                                                     | 4.2.1                                                                  |                            |
|      |                                   | Track-side ETCS functionality                                                              | 4.2.3                                                                  | H2 or B with D or B with F |
|      |                                   | Excluded communication via Eurobalises, Euroloop and level 2/3 functionality               |                                                                        |                            |
|      |                                   | ETCS and EIRENE air gap interfaces                                                         | 4.2.5                                                                  |                            |
|      |                                   | Only radio communication with train                                                        |                                                                        |                            |
|      |                                   | Interfaces                                                                                 |                                                                        |                            |
|      |                                   | ERTMS GSM-R track-side                                                                     | 4.2.7.3                                                                |                            |
|      |                                   | Key management system                                                                      | 4.2.8                                                                  |                            |
|      |                                   | ETCS-ID Management                                                                         | 4.2.9                                                                  |                            |
|      |                                   | Interlocking and LEU                                                                       | 4.2.3                                                                  |                            |
|      |                                   | Environmental conditions                                                                   | 4.3.3.3                                                                |                            |
|      |                                   | EMC                                                                                        | 4.3.3.4                                                                |                            |
| 3.   | Eurobalise                        | Safety                                                                                     | 4.2.1                                                                  |                            |
|      |                                   | ETCS and EIRENE air gap interfaces                                                         | 4.2.5                                                                  | H2 or B with D or B with F |
|      |                                   | Only Eurobalise communication with train                                                   |                                                                        |                            |
|      |                                   | Interfaces                                                                                 |                                                                        |                            |
|      |                                   | LEU Eurobalise                                                                             | 4.2.7.4                                                                |                            |
|      |                                   | ETCS-ID Management                                                                         | 4.2.9                                                                  |                            |
|      |                                   | Environmental conditions                                                                   | 4.3.3.3                                                                |                            |
|      |                                   | EMC                                                                                        | 4.3.3.4                                                                |                            |
| 4.   | Euroloop                          | Safety                                                                                     | 4.2.1                                                                  |                            |
|      |                                   | ETCS and EIRENE air gap interfaces                                                         | 4.2.5                                                                  | H2 or B with D or B with F |
|      |                                   | Only Euroloop communication with train                                                     |                                                                        |                            |
|      |                                   | Interfaces                                                                                 |                                                                        |                            |
|      |                                   | LEU Euroloop                                                                               | 4.2.7.5                                                                |                            |
|      |                                   | ETCS-ID Management                                                                         | 4.2.9                                                                  |                            |
|      |                                   | Environmental conditions                                                                   | 4.3.3.3                                                                |                            |
|      |                                   | EMC                                                                                        | 4.3.3.4                                                                |                            |
| 5.   | LEU Eurobalise                    | Safety                                                                                     | 4.2.1                                                                  |                            |
|      |                                   | Track-side ETCS functionality                                                              | 4.2.3                                                                  | H2 or B with D or B with F |
|      |                                   | Excluded communication via radio in-fill, Euroloop and level 2 and level 3 functionality   |                                                                        |                            |
|      |                                   | Interfaces                                                                                 |                                                                        |                            |
|      |                                   | Track-side signalling                                                                      | None                                                                   |                            |
|      |                                   | Eurobalise                                                                                 | 4.2.7.4                                                                |                            |
|      |                                   | ETCS-ID Management                                                                         | 4.2.9                                                                  |                            |
|      |                                   | Environmental conditions                                                                   | 4.3.3.3                                                                |                            |
|      |                                   | EMC                                                                                        | 4.3.3.4                                                                |                            |
| 6.   | LEU Euroloop                      | Safety                                                                                     | 4.2.1                                                                  |                            |
|      |                                   | Track-side ETCS functionality                                                              | 4.2.3                                                                  | H2 or B with D or B with F |
|      |                                   | Excluded communication via radio in-fill, Eurobalise and level 2 and level 3 functionality |                                                                        |                            |
|      |                                   | Interfaces                                                                                 |                                                                        |                            |
|      |                                   | Track-side signalling                                                                      | None                                                                   |                            |
|      |                                   | Euroloop                                                                                   | 4.2.7.5                                                                |                            |
|      |                                   | ETCS-ID Management                                                                         | 4.2.9                                                                  |                            |
|      |                                   | Environmental conditions                                                                   | 4.3.3.3                                                                |                            |
|      |                                   | EMC                                                                                        | 4.3.3.4                                                                |                            |
| 7.   | Safety platform track-side        | Safety                                                                                     | 4.2.1                                                                  | H2 or B with D or B with F |

Table 5.2.b

Groups of interoperability constituents in the track-side control-command assembly

| 1 No | 2 Interoperability constituent IC                            | 3 Characteristics                                                           | 4 Specific requirements to be assessed by reference to Annex A Index n | 5 Module                   |
| ---- | ------------------------------------------------------------ | --------------------------------------------------------------------------- | ---------------------------------------------------------------------- | -------------------------- |
| 1.   | Safety platform track-side<br/>Eurobalise<br/>LEU Eurobalise | Safety                                                                      | 4.2.1                                                                  |                            |
|      |                                                              | Track-side ETCS functionality                                               | 4.2.3                                                                  | H2 or B with D or B with F |
|      |                                                              | Excluded communication via Euroloop and level 2 and level 3 functionality   |                                                                        |                            |
|      |                                                              | ETCS and EIRENE air gap interfaces                                          | 4.2.5                                                                  |                            |
|      |                                                              | Only Eurobalise communication with train                                    |                                                                        |                            |
|      |                                                              | Interfaces                                                                  |                                                                        |                            |
|      |                                                              | Track-side signalling                                                       | None                                                                   |                            |
|      |                                                              | ETCS-ID Management                                                          | 4.2.9                                                                  |                            |
|      |                                                              | Environmental conditions                                                    | 4.3.3.3                                                                |                            |
|      |                                                              | EMC                                                                         | 4.3.3.4                                                                |                            |
| 2.   | Safety platform track-side<br/>Euroloop<br/>LEU Euroloop     | Safety                                                                      | 4.2.1                                                                  |                            |
|      |                                                              | Track-side ETCS functionality                                               | 4.2.3                                                                  | H2 or B with D or B with F |
|      |                                                              | Excluded communication via Eurobalise and level 2 and level 3 functionality |                                                                        |                            |
|      |                                                              | ETCS and EIRENE air gap interfaces                                          | 4.2.5                                                                  |                            |
|      |                                                              | Only Euroloop communication with train                                      |                                                                        |                            |
|      |                                                              | Interfaces                                                                  |                                                                        |                            |
|      |                                                              | Track-side signalling                                                       | None                                                                   |                            |
|      |                                                              | ETCS-ID Management                                                          | 4.2.9                                                                  |                            |
|      |                                                              | Environmental conditions                                                    | 4.3.3.3                                                                |                            |
|      |                                                              | EMC                                                                         | 4.3.3.4                                                                |                            |

# 6.   ASSESSMENT OF CONFORMITY AND/OR SUITABILITY FOR USE OF THE CONSTITUENTS AND VERIFICATION OF THE SUBSYSTEM

## 6.0.   Introduction

In the scope of the present TSI, fulfilment of relevant essential requirements quoted in chapter 3 of this TSI will be ensured by the compliance with the specification referenced in Chapter 4 and, as a follow up, in chapter 5 for the interoperability constituents, as demonstrated by a positive result of the assessment of conformity and/or suitability of use of the interoperability constituent and verification of the subsystem as described in Chapter 6.

Nevertheless, where part of the essential requirements are satisfied by national rules, because of:

<ul>
<li>use of Class B systems (including national functions in STMs);</li>
<li>open points in the TSI;</li>
<li>derogation’s under Article 7 of Directive 2001/16/EC;</li>
<li>specific cases described in Section 7.3.</li>
</ul>

then the conformity assessment shall be carried out under the responsibility of the Member States concerned according to notified procedures.

## 6.1.   Interoperability constituents

### 6.1.1.   Assessment procedures

The manufacturer of an interoperability Constituent (IC) (and/or groups of interoperability constituents) or his authorised representative established within the Community shall draw up an EC declaration of conformity in accordance with Article 13.1 and Annex IV of Directive 2001/16/EC before placing them on the market.

The assessment procedure for conformity of interoperability constituents and/or groups of interoperability constituents as defined in Chapter 5 of this TSI shall be carried out by application of modules as specified in section 6.1.2 (Modules).

Some of the specifications in this TSI contain mandatory and/or optional functions. The notified body shall:

-   verify that all mandatory functions relevant to the interoperability constituent are implemented;
-   verify which optional functions are implemented,

and carry out the assessment of conformity.

The supplier shall indicate in the EC declaration which optional functions are implemented.

The notified body shall verify, that no additional functions, implemented in the constituent, lead to conflicts with implemented mandatory or optional functions.

#### 6.1.1.1.   The specific transmission module (STM)

The STM has to meet national requirements, and its approval is a responsibility of the appropriate Member State as stated in Annex B.

The verification of the STM interface to the ERTMS/ETCS on-board requires a conformity assessment carried out by a notified body. The notified body shall verify that the Member State has approved the national part of the STM.

#### 6.1.1.2.   EC declaration of suitability for use

An EC declaration of suitability for use is not required for interoperability constituents of the control-command subsystem.

### 6.1.2.   Modules

For the assessment of interoperability constituents within the control-command subsystem, the manufacturer, or his authorised representative established within the Community, may choose the modules according to tables 5.1A, 5.1B, 5.2A and 5.2B:

-   either the type-examination procedure (Module B) for the design and development phase in combination with the production quality management system procedure (Module D) for the production phase, or
-   the type-examination procedure (Module B) for the design and development phase in combination with the product verification procedure (Module F), or
-   the full quality management system with design examination procedure (Module H2).

The description of the modules is in Annex E of this TSI.

The Module D (production quality management system) may only be chosen where the manufacturer operates a quality system for production, final product inspection and testing, approved and surveyed by a notified body.

The Module H2 (full quality management system with design examination) may only be chosen where the manufacturer operates a quality system for design, production, final product inspection and testing, approved and surveyed by a notified body.

The following additional clarifications apply to the use of some of the modules:

-   with reference to Chapter 4 of the Module B (type examination) description in Annex E:

    <ol>
    <li type="a">design review is requested;</li>
    <li type="a">review of manufacturing process is not requested if Module B (type examination) is used together with Module D (production quality management system);</li>
    <li type="a">review of manufacturing process is requested if Module B (type examination) is used together with Module F (product verification),</li>
    </ol>

-   With reference to chapter 3 of the Module F (product verification) description in Annex E, statistical verification is not allowed, i.e., all interoperability constituents shall be individually examined,
-   With reference to section 6.3 of the Module H2 (full quality management system with design examination), a type test is required.

Independently of the selected module, provisions of Annex A Index 47, Index A1, Index A2 and Index A3 shall be applied for the certification of interoperability constituents, for which requirements of the basic parameter safety (section 4.2.1 Control-command safety characteristics relevant to interoperability) apply.

Independently of the selected module, it shall be checked that the indications of the supplier for the maintenance of the interoperability constituent are compliant with the requirements of section 4.5 (Maintenance rules) of this TSI.

If Module B (type examination) is used, this shall be made on the basis of the examination of the technical documentation (see section 3 and 4.1 of the description of Module B (type examination)).

If Module H2 (full quality management system with design examination) is used, the application for design examination shall include all elements supporting evidence that the requirements of section 4.5 (Maintenance rules) of this TSI are fulfilled.

## 6.2.   Control-command subsystem

### 6.2.1.   Assessment procedures

This Chapter deals with EC declaration of verification of control-command subsystem. As stated in Chapter 2 the application of the control-command subsystem is treated as two assemblies:

-   the on-board assembly,
-   the track-side assembly.

For each assembly, an EC declaration of verification is required.

At the request of the contracting entity or its representative established in the Community the notified body carries out EC verification of an on-board or track-side assembly in accordance with Annex VI to Directive 2001/16/EC.

The contracting entity shall draw up the EC declaration of verification for the control-command assembly in accordance with Article 18(1) and Annex V of Directive 2001/16/EC.

The content of the EC declaration of verification shall conform to Annex V to Directive 2001/16/EC. This includes the verification of the integration of the interoperability constituents that are part of the assembly; the tables 6.1 and 6.2 define the characteristics to be verified and reference the mandatory specifications to be applied.

Some of the specifications in this TSI contain mandatory and/or optional functions. The notified body shall:

-   verify that all mandatory functions required to the Assembly are implemented,
-   verify that all optional functions required by the track-side or on-board specific implementation are implemented.

The notified body shall verify, that no additional functions, implemented in the assembly, lead to conflicts with implemented mandatory or optional functions.

Information on the specific implementation of the track-side assembly and on-board assembly shall be provided in the Register of Infrastructure and in the Register of Rolling Stock in accordance with Annex C.

The EC declaration of verification of track-side assembly or on-board assembly shall provide all the information required for inclusion in the abovementioned registers. The Registers shall be managed in accordance with Article 24 of Directive 2001/16/EC.

The EC declaration of verification of on-board and track-side assemblies, together with the certificates of conformity, is sufficient to ensure that an track-side assembly will operate with a on-board assembly equipped with corresponding characteristics as defined in the Register of Rolling Stock and in the Register of Infrastructure without an additional subsystem EC declaration of verification.

#### 6.2.1.1.   Functional integration verification of on-board assembly

The verification is to be made for a control-command on-board assembly installed on a vehicle. For the control-command equipment that is not defined as Class A only the verification requirements associated with interoperability (for example STM/ERTMS ETCS on-board interface) are included in this TSI.

Before any on-board functional verification can take place, the interoperability constituents included in the assembly shall have been assessed in accordance with section 6.1 above resulting in an EC declaration of conformity. The notified body shall assess that they are suitable for the application (e.g. optional functions implemented).

Class A functionality already verified at interoperability constituent level does not require additional verification.

The integration verification tests shall be performed to demonstrate that the components of the assembly have been correctly interconnected and interfaced to the train to ensure that the required functionality and performance required for that application of the assembly is achieved. When identical control-command on-board assemblies are installed on identical items of rolling stock, the integration verification has to be done only once on one item of rolling stock.

The following shall be verified:

-   correctness of installation of the control-command on-board assembly (e.g. compliance with engineering rules, co-operation of interconnected equipment, absence of unsafe interactions and, where required, storage of application specific data),
-   correctness of operations at the interfaces with rolling stock (e.g. train brakes, vigilance, train integrity),
-   ability to interface with control-command track-side assembly with corresponding characteristics (e.g. ETCS application level, optional functions installed),
-   ability of reading and storing in the safety data recorder all required information (also provided by non-ETCS systems, if required).

This verification may be made in a depot.

The verification of the ability of the on-board assembly to interface with a track-side assembly consists of the verification of the ability to read a certified Eurobalise and (if the functionality is installed on-board) Euroloop and the ability to establish GSM-R connections for voice and (if the functionality is installed) for data.

If class B equipment is also included, the notified body shall verify that the integration test requirements issued by the appropriate Member State have been met.

#### 6.2.1.2.   Functional integration verification of track-side assembly

The verification is to be made for a control-command track-side assembly installed on an infrastructure. For the control-command equipment that is not defined as Class A only the verification requirements associated with interoperability (for example EMC) are included in this TSI.

Before track-side functional verification can take place the interoperability constituents included in the assembly shall have been assessed in accordance with section 6.1 (interoperability constituants) above and have an EC declaration of conformity. The notified body shall verify that they are suitable for the application (e.g. optional functions implemented).

Class A functionality already verified at interoperability constituent level does not require additional verification.

For the design of the ERTMS/ETCS part of the control-command track-side assembly, TSI requirements must be complemented by national specifications covering e.g.:

-   the description of the line, characteristics such as gradients, distances, positions of route elements and Eurobalises/Euroloops, locations to be protected, etc.
-   the signalling data and rules required to be handled by the ERTMS/ETCS system.

The integration verification tests shall be performed to demonstrate that the components of the assembly have been correctly interconnected and interfaced to national track-side equipment to ensure that the required functionality and performance of the assembly necessary for that application is achieved.

The following track-side interfaces shall be considered:

-   between the Class A radio system and the ERTMS/ETCS (RBC or radio in-fill unit, if relevant),
-   between Eurobalise and the LEU,
-   between Euroloop and the LEU,
-   between neighbouring RBCs,
-   between the ERTMS/ETCS (RBC, LEU, radio in-fill unit) and interlocking or national signalling, as relevant.

The following shall be verified:

-   correctness of installation of the ERTMS/ETCS part of the control-command track-side assembly (e.g. compliance with engineering rules, co-operation of interconnected pieces of equipment, absence of unsafe interactions and, where required, storage of application specific data according to the above mentioned national specifications),
-   correctness of operations at the interfaces with national track-side equipment,
-   ability to interface with an on-board assembly with corresponding characteristics (e.g. ETCS application level).

#### 6.2.1.3.   Assessment in migration phases

Upgrading an existing track-side or on-board control-command assembly may be performed in successive steps in accordance with section  and section 7.2.3 and section 7.2.4. In each step only compliance with the TSI requirements relevant for the step is achieved, while other requirements of the remaining steps are not fulfilled.

The contracting entity may lodge an application for the assessment of the assembly at this step from a notified body.

Independently of the modules chosen by the contracting entity the notified body shall verify that:

-   the TSI requirements relevant for this step are respected,
-   the TSI requirements already assessed are not prejudiced.

Functions already assessed and unchanged and not affected by this step do not need to be checked again.

The certificate(s) issued by the notified body after the positive assessment of the assembly is accompanied by reservations indicating the limits of the certificate(s), which TSI requirements are fulfilled and which are not fulfilled.

The reservations shall be indicated in the Rolling Stock Register and/or Infrastructure Register as appropriate.

### 6.2.2.   Modules

All modules indicated below are specified in Annex E of this TSI.

#### 6.2.2.1.   On-board assembly

For the verification procedure of the On-board assembly, the contracting entity or its authorised representative established within the Community may choose either:

-   the type-examination procedure (Module SB) for the design and development phase in combination with the production quality management system procedure (Module SD) for the production phase, or
-   the type-examination procedure (Module SB) for the design and development phase in combination with the product verification procedure (Module SF), or
-   the full quality management system with design examination procedure (Module SH2).

#### 6.2.2.2.   Track-side assembly

For the verification procedure of the track-side assembly, the contracting entity or its authorised representative established within the Community may choose either:

-   the unit verification procedure (Module SG), or
-   the type-examination procedure (Module SB) for the design and development phase in combination with the production quality management system procedure (Module SD)) for the production phase, or
-   the type-examination procedure (Module SB) for the design and development phase in combination with the product verification procedure (Module SF), or
-   the full quality management system with design examination procedure (Module SH2).

#### 6.2.2.3.   Conditions for use of modules for on-board and track-side assemblies

The Module SD (production quality management system) may only be chosen where the contracting entity contracts only with manufacturers, that operate a quality system for production, final product inspection and testing, approved and surveyed by a notified body.

The Module SH2 (full quality management system with design examination) may only be chosen where all activities contributing to the Subsystem project to be verified (design, manufacturing, assembling, installation) are subject to a quality system for design, production, final product inspection and testing, approved and surveyed by a notified body.

Independently of the selected module, the design review includes the verification that the requirements of section 4.5 (Maintenance rules) of this TSI have been respected.

Independently of the selected module, the provisions of Annex A Index 47, Index A1, and where relevant Index A2 and Index A3 shall be applied.

With reference to Chapter 4 of Module SB (type-examination), design review is requested.

With reference to section 4.3 of Module SH2 (full quality management system with design examination), a type test is required.

With reference to:

-   Section 5.2 of Module SD (production quality management system),
-   Chapter 7 of Module SF (product verification),
-   Chapter 4 of Module SG (unit verification),
-   Section 5.2 of Module SH2 (full quality management system with design examination), validation under full operational conditions is defined in section 0 (on-board assembly validation) and section 0 (track-side assembly validation).

On-board assembly validation

For an on-board assembly the validation under full operational conditions shall be a type test. It is acceptable to be performed on a single instance of the assembly, and shall be performed by means of test runs with the scope to verify:

-   performances of the odometry functions,
-   compatibility of the control-command assembly with rolling stock equipment and environment (e.g. EMC) in order to be able to multiply the implementation of the On-board assembly on other locomotives of the same type,
-   compatibility of the rolling stock with control-command Track-side assembly (e.g. EMC aspects, operation of track circuits and axle counters).

Such test runs shall be performed on an infrastructure allowing for verifications in conditions representative of the characteristics that may be found in the European conventional rail network (e.g. gradients, train speed, vibrations, traction power, temperature).

If the tests show that the specifications are not achieved in all cases (e.g. TSI compliance only up to a certain speed), the consequences with regard to compliance with the TSI shall be recorded on the certificate of conformity and in the rolling stock register.

Track-side assembly validation

For a Track-side assembly the validation under full operational conditions shall be performed by means of test runs of a rolling stock of known characteristics and shall have the scope to verify compatibility between rolling stock and control-command Track-side assembly (e.g. EMC aspects, operation of track circuits and axle counters). Such test runs shall be performed with suitable rolling stock of known characteristics allowing for verifications in conditions that may occur during service (e.g. train speed, traction power).

Test runs shall also validate the compatibility of the information provided to the train driver by the Track-side assembly with the physical route (e.g. speed limits, etc.).

If specifications that are foreseen by, but not yet available in, this TSI for the verification of a Track-side assembly, the Track-side assembly shall be validated by appropriate field tests (to be defined by the contracting entity of this track-side assembly).

#### 6.2.2.4.   Assessment of maintenance

The conformity assessment of the maintenance is in the responsibility of a body authorised by the Member State. The Annex F describes the procedure by which this body ascertains that maintenance arrangements meet the provisions of this TSI and ensure the respect of the basic parameters and essential requirements during the subsystem lifetime.

Table 6.1

Verification requirements for on-board control-command assembly

| 1 No | 2 Description                                       | 2a Remarks                                                                                                                                                                                 | 3 CC interfaces                                                                                                                   | 4 Interfacing TSI subsystems | 5 Characteristics to be assessed by reference to Chapter 4 of this TSI |         |
| ---- | --------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------- | ---------------------------- | ---------------------------------------------------------------------- | ------- |
| 1.   | Safety                                              | The notified body shall ensure the completeness of the safety approval process, including safety case                                                                                      |                                                                                                                                   |                              | 4.2.1                                                                  |         |
| 2.   | On-board ETCS functionality                         | This functionality is performed by ERTMS/ETCS on-board IC                                                                                                                                  |                                                                                                                                   |                              | 4.2.2                                                                  |         |
|      |                                                     | Notes:                                                                                                                                                                                     |                                                                                                                                   |                              |                                                                        |         |
|      |                                                     | Vigilance supervision                                                                                                                                                                      | If the vigilance supervision is external, an interface between vigilance device and ERTMS/ETCS on-board for suppressing may exist | OPE                          | 4.3.1.9                                                                |         |
|      |                                                     |                                                                                                                                                                                            |                                                                                                                                   | RST                          | 4.3.2.11                                                               |         |
|      |                                                     | Train integrity supervision: In the case, where the train is configured for Level 3, the train integrity supervision function must be supported via detection equipment rolling stock-side | Interface between ERTMS/ETCS on-board and detection equipment                                                                     | RST                          | 4.3.2.8                                                                |         |
| 3.   | EIRENE functions                                    | This functionality is performed by ERTMS/GSM-R on-board IC                                                                                                                                 |                                                                                                                                   |                              | 4.2.4                                                                  |         |
|      |                                                     | Data communication only for level 1 with radio in-fill (optional) or level 2 and level 3                                                                                                   |                                                                                                                                   |                              |                                                                        |         |
| 4.   | ETCS and EIRENE air gap interfaces                  | This functionality is performed by ERTMS/ETCS on-board and ERTMS/GSM-R on-board IC’s                                                                                                       | CC trackside assembly                                                                                                             |                              | 4.2.5                                                                  |         |
|      |                                                     | Radio communication with the train only for level 1 with radio in-fill (optional) or level 2 and level 3                                                                                   |                                                                                                                                   |                              |                                                                        |         |
|      |                                                     | Euroloop communication is optional                                                                                                                                                         |                                                                                                                                   |                              |                                                                        |         |
| 5.   | Key management                                      | Security policy for key management                                                                                                                                                         |                                                                                                                                   | OPE                          | 4.2.8                                                                  |         |
|      |                                                     |                                                                                                                                                                                            |                                                                                                                                   |                              | 4.3.1.7                                                                |         |
| 6.   | ETCS-ID management                                  | Policy for ETCS-ID management                                                                                                                                                              |                                                                                                                                   | OPE                          | 4.2.9                                                                  |         |
| 7.   | Interfaces                                          |                                                                                                                                                                                            |                                                                                                                                   |                              |                                                                        |         |
|      | STM                                                 | The notified body shall verify that the integration test requirements issued by the appropriate Member State have been met                                                                 | ERTMS/ETCS on-board and external STM IC’s                                                                                         |                              | 4.2.6.1                                                                |         |
|      | ERTMS/GSM-R on-board                                |                                                                                                                                                                                            | ERTMS/ETCS on-board and ERTMS/GSM-R on-board IC’s                                                                                 |                              | 4.2.6.2                                                                |         |
|      | Odometry                                            | This interface is not relevant if equipment is delivered as grouping of constituents                                                                                                       | ERTMS/ETCS on-board and odometry IC’s                                                                                             | MR                           | 4.2.6.3                                                                |         |
|      |                                                     |                                                                                                                                                                                            |                                                                                                                                   |                              | 4.3.2.12                                                               |         |
|      | ETCS DMI                                            | Part of ERTMS/ETCS on-board IC                                                                                                                                                             |                                                                                                                                   | OPE                          | 4.2.13                                                                 |         |
|      | EIRENE DMI                                          | Part of ERTMS/GSM-R on-board IC                                                                                                                                                            |                                                                                                                                   |                              | 4.3.1.2                                                                |         |
|      |                                                     |                                                                                                                                                                                            |                                                                                                                                   |                              | 4.2.14                                                                 |         |
|      |                                                     |                                                                                                                                                                                            |                                                                                                                                   | OPE                          | 4.3.1.3                                                                |         |
|      | Interface to data recording for regulatory purposes | Part of safety information recorder IC                                                                                                                                                     |                                                                                                                                   |                              | 4.2.15                                                                 |         |
|      |                                                     |                                                                                                                                                                                            |                                                                                                                                   | OPE                          | 4.3.1.4                                                                |         |
|      |                                                     |                                                                                                                                                                                            |                                                                                                                                   | RST                          | 4.3.2.13                                                               |         |
|      | Train braking performances                          | Verification of adaptation to the concerned rolling stock                                                                                                                                  |                                                                                                                                   | OPE                          | 4.3.1.5                                                                |         |
|      |                                                     |                                                                                                                                                                                            |                                                                                                                                   | RST                          | 4.3.2.3                                                                |         |
|      | isolation                                           |                                                                                                                                                                                            |                                                                                                                                   | OPE                          | 4.3.1.6                                                                |         |
|      |                                                     |                                                                                                                                                                                            |                                                                                                                                   | RST                          | 4.3.2.7                                                                |         |
|      | Antennae installation                               |                                                                                                                                                                                            |                                                                                                                                   | RST                          | 4.3.2.4                                                                |         |
|      | Environmental conditions                            | Verification of correct operation off control-command assembly in the environmental conditions.                                                                                            | This check has to be done in the validation under full operational conditions.                                                    |                              | RST                                                                    | 4.3.2.5 |
|      | EMC                                                 | Verification of correct operation off control-command assembly in the environmental conditions                                                                                             | This check has to be done in the validation under full operational conditions.                                                    | RST                          | 4.3.2.6                                                                |         |
|      | data interfaces                                     | Part of ERTMS/ETCS on-board IC.                                                                                                                                                            |                                                                                                                                   | RST                          | 4.3.2.8; 4.3.2.11                                                      |         |
|      |                                                     | Correct operation of the interface to the train<br/>This interface includes vigilance (optional) and train integrity (only level 3)                                                        |                                                                                                                                   | OPE                          | 4.3.1.9                                                                |         |

Table 6.2

Verification requirements for track-side control-command assembly

| 1 No | 2 Description                                                      | 2a Remarks                                                                                                                                                                       | 3 CC interfaces                                          | 4 Interfacing TSI subsystems | 5 Characteristics to be assessed by reference to Chapter 4 of this TSI |
| ---- | ------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------- | ---------------------------- | ---------------------------------------------------------------------- |
| 1.   | Safety                                                             | The notified body shall ensure the completeness of the safety approval process, including safety case                                                                            |                                                          |                              | 4.2.1                                                                  |
| 2.   | Track side ETCS functionality                                      | This functionality is performed by RBC’s, LEU’s and radio in-fill units IC’s, according to the implementation                                                                    |                                                          |                              | 4.2.3                                                                  |
| 3.   | EIRENE functions                                                   | Data communication only for level 1 with radio in-fill or level 2/3                                                                                                              |                                                          |                              | 4.2.4                                                                  |
| 4.   | ETCS and EIRENE air gap interfaces                                 | This functionality is performed by RBC’s, radio in-fill units, Eurobalises, Euroloop’s and GSM-R trackside equipment, according to the implementation.                           | CC on-board assembly                                     |                              | 4.2.5                                                                  |
|      |                                                                    | Radio communication with the train only for level 1 with radio in-fill (optional) or level 2/3                                                                                   |                                                          |                              |                                                                        |
|      |                                                                    | Euroloop communication is optional                                                                                                                                               |                                                          |                              |                                                                        |
| 5.   | Key management                                                     | Security policy for key management                                                                                                                                               |                                                          | OPE                          | 4.2.8                                                                  |
|      |                                                                    |                                                                                                                                                                                  |                                                          |                              | 4.3.1.7                                                                |
| 6.   | ETCS ID management                                                 | Policy for ETCS-ID management                                                                                                                                                    |                                                          | OPE                          | 4.2.9                                                                  |
| 7.   | HABD                                                               |                                                                                                                                                                                  |                                                          | OPE                          | 4.2.10                                                                 |
|      |                                                                    |                                                                                                                                                                                  |                                                          | RST                          | 4.3.1.8                                                                |
|      |                                                                    |                                                                                                                                                                                  |                                                          |                              | 4.3.2.9                                                                |
| 8.   | Interfaces                                                         |                                                                                                                                                                                  |                                                          |                              |                                                                        |
|      | RBC/RBC                                                            | Only for level 2/3                                                                                                                                                               | Between neighbouring RBC’s                               |                              | 4.2.7.1                                                                |
|      | GSM-R track-side                                                   | Only for level 2/3 or level 1 with radio in-fill (optional)                                                                                                                      | Between RBC’s or radio In-fill units and GSM-R trackside |                              | 4.2.7.3                                                                |
|      | Eurobalise/LEU                                                     | This interface is not relevant if equipment is delivered as grouping of constituents                                                                                             | Between Control-command IC’s                             |                              | 4.2.7.4                                                                |
|      | Euroloop/LEU                                                       | Euroloop is optional                                                                                                                                                             | Between control-command IC’s                             |                              | 4.2.7.5                                                                |
|      |                                                                    | This interface is not relevant if equipment is delivered as grouping of constituents                                                                                             |                                                          |                              |                                                                        |
|      | Antennae installation                                              |                                                                                                                                                                                  |                                                          | IN                           | 4.3.3.2                                                                |
|      | Environmental conditions                                           | Verification of correct operation off control-command assembly in the environmental conditions<br/>This check has to be done in the validation under full operational conditions |                                                          | IN                           | 4.3.3.3                                                                |
|      | EMC                                                                | Verification of correct operation off control-command assembly in the environmental conditions<br/>This check has to be done in the validation under full operational conditions | IN                                                       | 4.3.3.4                      |                                                                        |
|      |                                                                    |                                                                                                                                                                                  |                                                          | ENE                          | 4.3.4.1                                                                |
| 9.   | Compatibility of train detection systems                           | Characteristics to be activated by rolling stock                                                                                                                                 |                                                          | RST                          | 4.2.11                                                                 |
|      |                                                                    |                                                                                                                                                                                  |                                                          |                              | 4.3.1.10                                                               |
|      |                                                                    |                                                                                                                                                                                  | IN                                                       | 4.3.2.1                      |                                                                        |
|      |                                                                    |                                                                                                                                                                                  |                                                          |                              | 4.3.3.1                                                                |
| 10.  | EM compatibility between rolling stock and train detection systems |                                                                                                                                                                                  |                                                          | RST                          | 4.2.12.2                                                               |
|      |                                                                    |                                                                                                                                                                                  |                                                          |                              | 4.3.2.2                                                                |
|      | Compatibility with train headlights                                | Characteristics of retro reflecting line-side signals and clothing                                                                                                               |                                                          | RST                          | 4.2.16                                                                 |
|      |                                                                    |                                                                                                                                                                                  |                                                          |                              | 4.3.2.10                                                               |
|      | Compatibility with driver’s external field of view                 | Installation of trackside equipment that must be seen by the driver                                                                                                              |                                                          | OPE                          | 4.2.16                                                                 |
|      |                                                                    |                                                                                                                                                                                  |                                                          |                              | 4.3.1.11                                                               |

# 7.   IMPLEMENTATION OF THE TSI CONTROL-COMMAND

## 7.1.   General

This chapter outlines the strategy and the associated technical solutions for implementation of the TSI, notably the conditions underpinning the migration to Class A systems. Account must be taken of the fact that the implementation of a TSI occasionally has to be co-ordinated with the implementation of other TSIs.

Chapters 2 to 6 and any specific provisions in paragraph 7.3 below apply in full to control-command subsystem as defined by Directive 2001/16/EC.

## 7.2.   Specific issues of implementation of the TSI control-command

### 7.2.1.   General migration criteria

Within the control-command subsystem two classes (A and B) of train protection and radio communication systems are defined.

It is recognised that Class A cannot be installed on all existing conventional routes instantly for reasons which include economic considerations and installation capacity aspects. In the migration-period between the current (pre-unified) situation (Class B) and the application of Class A, there will be a number of possible interoperability solutions that might be implemented in the framework of this TSI. These solutions apply to both the European conventional rail infrastructure, including connecting lines, and to the European conventional rail trains. A number of illustrative examples are given below:

-   within ERTMS/ETCS provision is made for modules known as STMs (Specific Transmission Modules) to be added to ETCS to enable a train fitted with appropriate STMs to operate over existing pre-unified infrastructure. Another solution is that an infrastructure may be equipped with both Class A and Class B systems,
-   the implementation of GSM-R systems on a nation-wide basis has already started in a significant number of countries of the former EU15. The first inter-connections of these national networks are due in 2004. Other networks will follow shortly. Some railways have chosen a solution where mobile equipment is designed in such a way that it can work in both systems (dual-mode = GSM-R and >=1 analogue radio), others have taken the solution to have a double coverage on network-side but only single equipment on the trains. GSM-R does not have ‘STMs’. Cab radios that have additional interface-units for Class B radio systems (Dual-mode) are able to work also on lines in a Class B network if specially designed. This solution is only an interim solution to allow early exchange of international trains.

#### 7.2.1.1.   Migration paths

The existing systems as well as the future unified system have system components infrastructure-side and on-board. Therefore migration strategies have to be defined for both assemblies. This paragraph deals with migration paths from Class B to Class A by giving examples.

Migration strategies must pay special attention to the following distinction:

-   train radio (from Class B to Class A),
-   train protection (from Class B to Class A),
-   the train detection system,
-   the hot axle-box detection system,
-   EMC.

Each of the above can follow a different migration path.

Possible migration paths from Class B to Class A are explained by means of the following examples for the train protection system.

Figure 1

Image

Figure 1 depicts the starting state, where only non compatible systems exist (denominated START) to the final state (denominated TARGET).

The following two figures describe the two possible extreme migration paths from the present to the future state.

Figure 2

Image

Figure 2 shows a migration process, where all the initial investment is made on-board only. A possible technical solution is the so-called STM, which can be linked to the kernel of the ETCS on-board and which translates information from existing systems to a form that can be processed by the ETCS kernel. After the equipment of all vehicles of a railway fleet under consideration with the combination of ETCS kernel and respective Class B systems, the wayside equipment can be altered to ETCS or newly equipped lines can be built based on the ETCS system. The existing class B system on these lines can be removed.

Figure 3

Image

Figure 3 shows the other extreme migration process. In this case, the respective railway would double equip existing lines with the ETCS system. After all lines have ETCS in addition to the national system, the on-board equipment of the rolling stock can be changed to ETCS. When all vehicles under consideration are equipped with ETCS, the wayside equipment for the national system can then be removed.

Figure 4

Image

Figure 4 shows the combination of both extremes described above. The possible migration paths have to be between these two limits. In practical terms, there should to be a mixture of both ways.

Figure 5

Image

Figure 5 depicts an example, where ETCS on-board equipment in vehicles and ETCS wayside equipment on parts of the lines is installed alternatively. This method minimises the inception investment necessary to take advantage of the system as a whole (i.e. the on-board and trackside equipment in the sections where these are fitted). On the other hand, it implies a certain restriction in usage of rolling stock on the network.

The selection of the appropriate migration strategy depends largely on the mix between lines equipped, rolling stock equipped and planned purchase of new rolling stock and additional equipment of lines.

Also international corridors and international use of rolling stock should be considered. In case a line is not foreseen for migration and is only equipped with Class B the interoperable operation can be ensured by a STM for the Class B system concerned.

The migration steps, however, have to enable access of other railway undertakings to the network at any time. A vehicle equipped with the appropriate ETCS on-board equipment and the existing system as described in annexes B and C must always be able to run on the line under consideration.

### 7.2.2.   Timing criteria

#### 7.2.2.1.   Introduction

ETCS and GSM-R are computer-based systems with a faster technology evolution and potentially a lower life expectancy than current traditional railway signalling and telecommunication facilities. As such, they call for a pro-active rather than reactive deployment strategy to avoid potential system obsolescence prior to system deployment reaching maturity.

Notwithstanding this fact, the adoption of a too fragmented deployment throughout the European rail network, mainly along the trans-European rail corridors, would give rise to major cost and operational overheads resulting from the needs to ensure backward compatibility and interconnection with a diversity of legacy facilities. Moreover, synergies in terms of time, cost and risk reduction might be reached by the reconciliation of common elements of different national implementation strategies — e.g. through joint procurement initiatives, collaboration in system validation and certification activities.

Whereas such pro-active implementation strategy does appears a must to underpin the whole of the migration process, the specific modalities to be adopted for the conventional rail network have to account for the current level and planned rate of deployment of these technologies as well as the relevant economic, operational, technical and financial factors that influence such an implementation.

Within this context, it is evident that a clear distinction is to be made between ETCS and GSM-R in view of the current status of migration throughout Europe and the magnitude and extent of the barriers underlying such a migration, a fact that commands a different rationale for the implementation of GSM-R and of ETCS on the conventional network. Such a distinct rationale will be delineated in fuller detail within the next paragraphs:

#### 7.2.2.2.   GSM-R — Rationale for Deployment

The current magnitude of the GSM-R deployment activity throughout the whole of the European rail network (approximately 100 000 km nowadays in 11 out of the 15 States of the former EU15) and the four- to five-year time horizon that generally underpins the conclusion of such deployment works indicates that any deployment rationale will have to confront three main concerns:

-   to ensure the continuity of GSM-R service across borders avoiding the establishment of ‘black spots’ within some regions of the Community,
-   to reconcile the migration timings throughout Europe in order to significantly reduce the cost and time overheads associated with the potential needs to sustain double analogue/digital telecommunication infrastructures and on-board facilities,
-   to avoid a ‘two speed’ Europe between the former EU15 and the new Member States. Convergence needs to be achieved a target that is facilitated by the on-going programmes for major upgrading of the railway networks of the new Member States.

#### 7.2.2.3.   GSM-R — Implementation rules

Set against this background, and taking into account that a GSM-R infrastructure is a telecommunication bearer for both high-speed and conventional rail applications, the implementation criteria now in force for the former applications should equally apply for conventional rail, e.g.

Trackside installations:The fitting of GSM-R is mandatory in the case of:

-   new installations of radio part of a CCS assembly,
-   an upgrade of radio part of a CCS assembly already in service that changes the functions or the performance of the subsystem.

On-board installations:The fitting of GSM-R in Rolling Stock intended for use on a line including at least a section equipped with Class A interfaces (even if superimposed to a Class B system), is mandatory in the case of:

-   new installations of the radio part of a CCS assembly,
-   an upgrade of the radio part of a CCS assembly already in service that changes the functions or the performance of the subsystem.

Legacy systems:Member States shall ensure that the functionality of the legacy systems referred to in Annex B to the TSI as well as their interfaces is to remain as currently specified, excluding those modifications that might be deemed necessary in order to mitigate safety-related flaws of these systems. Member States shall make available the necessary information regarding their legacy systems that is required for purposes of development and certification of apparatus allowing interoperability of Class A equipment with their legacy Class B facilities.

In order to enable a pro-active implementation, Member States are also encouraged to promote and support the fitting of GSM-R in any renewal or maintenance-related work affecting the whole of an infrastructure already in service entailing an investment at least one order of magnitude higher than those associated with the installation of GSM-R facilities.

#### 7.2.2.4.   ERTMS/ETCS — rationale for deployment

##### 7.2.2.4.1.   Introduction

As it stands nowadays, the case of ERTMS/ETCS on conventional applications has to be underlined by a different deployment rationale that accounts for the manifold complexity associated to a migration of signalling systems, to its associated costs and to the expected longer lifetime of the assets when compared to those of GSM-R. However, in no way such barriers should detract from the generic deployment principles exposed in paragraph 7.2.2.1, in particular, the necessity to keep the implementation momentum within acceptable levels notably on the major corridors and trunk lines of the trans-European rail network (TEN).

##### 7.2.2.4.2.   The ETCS-Net corridor concept

In order to reconcile the apparent conflicting objectives of avoidance of fragmented approach with the perceived constraints on investment it is deemed necessary to define a start-up core of rail projects where ERTMS/ETCS deployment can be indeed justified on an ‘end-to-end’ business/service perspective whereas not commanding unacceptable barriers in terms of implementation costs. In view of such over-ridding objectives, and after consultation of the sector, it was recognized that such core should be built upon a coherent set of priority corridors of the trans-European rail network. The objectives to be achieved with such an approach are three-fold:

<ol type="i">
<li>to enable the creation of an interoperable rail backbone across Europe (coined hereafter as ETCS-Net) enabling the development of new and improved quality rail services that can ultimately heighten the competitive profile of rail transport notably in those market segments of major growth potential — e.g. international freight transport;</li>
<li>to constitute a focus for trans-national co-ordination efforts and for concentration of financing instruments in view of an accelerated and wider-ranging deployment of ERTMS/ETCS across the main routes of the trans-European rail network;</li>
<li>to move towards the conditions of ‘critical mass’ for ERTMS/ETCS to emerge as the natural market selection solution for new and upgrade signalling projects of the conventional rail network across Europe.</li>
</ol>

An outline of the ETCS-Net is depicted below. A detailed listing of the corridors encompassed therein is attached in annex H.

Image

In order to ensure the development of a coherent network providing a backbone for the development of enhanced end-to-end services the ETCS-Net as presented above builds upon both high-speed (4) and conventional lines. The deployment of ERTMS/ETCS on the former is governed by Decision 2002/731/EC whereas the implementation principles outlined below apply to the latter.

In view for such a backbone to contribute to a major re-engineering of international rail transport services in a credible time horizon from the perspective of the customer it is necessary to attach a relatively ambitious timeframe for its full realisation. Taking into account the range of parameters that impact on the latter (e.g. level of investment resources, engineering/project management capability of the railways and supply industry, needs for cross-border co-ordination of activities) a period of 10 to 12 years can be earmarked as an indicative timeframe for such a purpose.

##### 7.2.2.4.3.   The inception kernel

To enable the accomplishment of the implementation of the whole ETCS-Net within such a time horizon it is deemed necessary to kick-start the deployment process by earmarking a sub-set of projects (hereafter referred to as the inception kernel) where deployment of ETCS will be mandatory. The adoption of such an approach basically reverts to the deployment of a three-tiered perspective as depicted below:

Image

In order to minimise the financial impact of such a mandatory step the selection criteria for inclusion of projects within such Inception Kernel should notably account for the availability of Community funding to a level well above the amounts that can be normally earmarked for signalling works. The set of conventional rail priority projects established within the Trans-European Network guidelines (Decision No 884/2004/EC of the European Parliament and of the Council (5) as well as all those major rail construction/upgrading works funded under the framework of the Structural Funds (Council Regulation (EC) No 1260/1999 (6) and/or Cohesion Funds (Council Regulation (EC) No 1264/1999 (7) are to be considered as forming such an inception kernel.

The Inception Kernel is to constitute a steppingstone for the achievement of the full ETCS-Net deployment scenario as described above. However, the fulfilment of this latter objective requires the visibility of the deployment strategy (timing and planning of the works) that will underpin those national sections of the different corridors not encompassed by the ‘Inception Kernel’ criteria. In order to provide for such visibility, Member States will be required to elaborate national ERTMS implementation plans addressing a range of deployment issues which are outlined in paragraph 7.2.2.6.

The scope of the current ETCS-Net backbone might be revised in a subsequent phase (potentially during a future revision of this TSI) to account for the real progress of its implementation and for the ever evolving needs of the transportation markets.

The rationale in what regards rolling-stock has to account for the fact that ERTMS/ETCS is a system concept composed of infrastructure and on-board elements. As such it is crucial that any emergent deployment rationale considers these two system elements in a coherent manner as they both concur to enable system operation. Moreover, as in the case for infrastructure, appropriate consideration must be given to the minimisation of the financial impact of any mandatory step that might be imposed.

A ‘marginal cost’ approach, linking the fitment of on-board ERTMS/ETCS with major investment decisions, does constitute the best available route to ensure such a goal. This applies notably to the procurement of new rolling-stock or major retrofitting operations for which the value of the signalling equipment and of its installation represent only a limited percentage of the whole investment to be put in place. The adoption of such a policy will push in the longer-term for the scenario of ETCS on-board equipment as a commodity asset in what regards new rolling-stock.

##### 7.2.2.4.4.   A pre-fitment strategy

Pre-fitment covers the installation of any on-board or trackside ERTMS/ETCS and GSM-R equipment or other enabling equipment for ETCS and GSM-R (e.g. installation of cabling and wiring, ducts, mechanical fixtures, interfaces, power supply or other specific signalling or telecommunication facilities) aimed at reaching a certain stage of ERTMS readiness without fully implementing the Class A requirements.

The aim of such an approach is to ensure such ERTMS readiness by piggybacking such pre-fitment activities on major construction or upgrading operations of infrastructure assets or on factory-fit (8) of rolling-stock assets. This shall allow for the reduction of the implementation cost of full-fledged ERTMS/ETCS or GSM-R facilities complying Class A requirements at a later stage. However, the scope of ERTMS readiness has to set against the specificities of each project from a technical, operational and economic viewpoint as well as to the time horizon for the installation of the Class A compliant facilities.

It is therefore deemed necessary to establish a hierarchical approach to pre-fitment based on the concept of pre-fitment stages. It is expected these should range from the simple reservation of space, ducting, and fitment of mechanical fixtures (Stage 1) upwards to the installation of all components that are not affected by obsolescence within the nominal lifetime of the installation (Stage 3). The details of pre-fitment are to be defined by subset 57 (on-board) and subset 59 (trackside equipment) to be appended to Annex A.

#### 7.2.2.5.   ERTMS/ETCS — Implementation Rules

All the implications enumerated in the previous paragraph are to be eventually qualified as follows:

Trackside installations:The fitting of ERTMS/ETCS is mandatory in the case of:

-   new installations of train protection as part of a CCS assembly,
-   an upgrade of train protection as part of a CCS assembly already in service that changes the functions or the performance of the subsystem.

for the set of railway infrastructure projects falling within one of the following criteria:

-   being part of the set of conventional rail priority projects established under the Trans-European Network guidelines included in Annex II of the Decision No 884/2004/EC,
-   commanding a financial support from Structural Funds (Regulation (EC) No 1260/1999) and/or Cohesion Funds (Regulation (EC) No 1264/1999) in excess of 30 % of the total project costs.

For any other new or upgrade projects not encompassed under these latter criteria and that are part of the Trans-European conventional rail network, as defined by the Corrigendum of 7 June 2004 to Decision No 884/2004/EC, the pre-fitting of equipment to pre-fitment stage 1 as defined under Paragraphs 7.2.2.4.4 and 7.2.3.2 shall be performed. Those lines included in the ETCS-Net backbone which are outside of the Inception Kernel shall comply with a Pre-fitment Stage 3 in what regards such a pre-fitting.In order to enable a pro-active implementation, Member States are also encouraged to promote and support the fitting of ERTMS/ETCS in any renewal or maintenance-related work of the infrastructure that entails investments at least one order of magnitude higher than those associated with the installation of ERTMS/ETCS facilities.On-board installations:The fitment of rolling stock intended for operation on the conventional rail infrastructures where the fitting of ERTMS/ETCS is mandatory shall be in accordance with the national migration strategy once this is reconciled with the EU master plan as described in paragraph 7.2.2.6 with the exception referred to underneath.The fitting of ERTMS/ETCS, complemented where necessary by the relevant Specific Transmission Modules (STM) to enable operation on Class B systems, is mandatory on.

-   new installations of the train protection part of a CCS assembly,
-   an upgrade of the train protection part of a CCS assembly already in service that changes the functions or the performance of the subsystem,
-   any ‘major retrofitting’ of rolling stock already in service (9);

for rolling-stock for cross-border operations within the inception kernel.A pre-fitting ERTMS/ETCS to Pre-fitment Stage 1 as defined under Paragraphs 7.2.2.4.4 and 7.2.4.4 on

-   New installations of the train protection part of a CCS assembly;
-   An upgrade of the train protection part of a CCS assembly already in service that changes the functions or the performance of the subsystem.

for those rolling stock assets earmarked for operation in the trans-European transport conventional rail network as defined by the corrigendum of 7 June 2004 to Decision No 884/2004/EC. Pre-fitment stage 3 shall apply for those assets earmarked for operation on the ETCS-Net backbone.Legacy systems:Member States shall ensure that the functionality of the legacy systems referred to in Annex B to the TSI as well as their interfaces is to remain as currently specified, excluding those modifications that might be deemed necessary in order to mitigate safety-related flaws of these systems. Member States shall make available the necessary information regarding their legacy systems that is required for purposes of development and safety-certification of apparatus allowing interoperability of Class A equipment with their legacy Class B facilities.

#### 7.2.2.6.   National ERTMS implementation plans and EU master plan

Set against the deployment rationale exposé above and the mandatory rules specified in sections 7.2.2.3 and 7.2.2.4.4 Member States are deemed to prepare a formal national ERTMS implementation plan for the conventional rail network addressing the deployment of both ERTMS/ETCS and GSM-R.

Regarding ERTMS/ETCS the realisation of the ETCS-Net backbone as described in paragraph 7.2.2.4 shall constitute the reference baseline for the elaboration of such a national plan. The ultimate goal for the latter is to define a tailor-made set of obligations regarding ERTMS/ETCS deployment in lieu of the generic prescriptions now embodied in the inception kernel. However, such built-in flexibility cannot detract from the level of obligation (10) already embodied in the inception kernel.

The national plans shall provide, in particular, the following elements:

-   target lines: a clear identification of the national lines or sections which are earmarked for implementation. This applies notably to the national sections of the trans-national corridors earmarked in the ETCS-net blueprint (11). Appropriate consideration is to be given in this context to the national ERTMS/ETCS implementation plans notified under Decision 2002/731/EC in what refers to the high-speed sections covered by the ETCS-Net backbone,
-   technical requirements: the essential technical characteristics of the different implementations (e.g. voice or data-quality network for GSM-R implementations, functional level of ERTMS/ETCS, ERTMS/ETCS-only or overlaid installations),
-   deployment strategy and planning: an outline of the implementation plan (including sequencing and timing of the works),
-   migration strategy: the strategy envisaged for the migration of both the infrastructure and rolling-stock subsystems of the earmarked national lines or sections (e.g. superposition of Class A and Class B systems, switch from Class B to Class A facilities at a planned date, migration based on the implementation of ETCS-based gap-filling solutions such as SCMT (12) or limited supervision),
-   potential constraints: an overview of potential elements that might impact on fulfilment of the implementation plan (e.g. signalling works integrating larger scope infrastructure works, assurance of continuity of service across borders).

These national plans are to be finally aggregated within an EU master plan within six months of their notification. Such a master plan should aim at providing an appropriate knowledge base for decision support to the different stakeholders — in particular, to the Commission in the allocation of its financial support to railway projects — and, where appropriate, at reconciling the different national implementations in terms of time or implementation strategies where this is deemed necessary for the achievement of a coherent whole. This overall process can be represented as depicted below:

Image

In addition, the EU master plan shall include the outline of a rolling-programme to underpin the range of foreseen implementation activities from planning-through-to-realisation.

The EU master plan will be appended to this TSI through a revision procedure replacing the field of mandatory implementations now defined in the inception kernel. Subsequently,

-   all activities related to installation of control-command subsystems have to be justified by the awarding entities against this EU Master Plan in addition to all other applicable legislative requirements that are in force,
-   Member States will be requested to punctually adapt their national ERTMS implementation plans where this is deemed necessary to ensure reconciliation with the EU Master Plan. In particular, such a revision shall ensure that the migration strategy adopted by a Member State — notably for rolling stock — does not hamper the fulfilment of the ETCS-Net strategic goal and the access of new entrants in accordance with the timing and requirements called for by the EU master plan,
-   whenever the reconciliation of a national plan and the EU master plan is not feasible the mandatory prescriptions of the Inception Kernel shall remain of application for that particular Member State.

Necessarily, the EU master plan and the national ERTMS implementation plans will be evolving documents that will have to be updated in order to reflect the real evolution of the deployment in each Member State and throughout the European rail network.

### 7.2.3.   Implementation: infrastructure (stationary equipment)

The following requirements apply to the categories of lines defined in Directive 2001/16/EC:

-   lines intended for passenger services,
-   lines intended for mixed traffic (passengers and freight),
-   lines specially designed or upgraded for freight services,
-   passenger hubs,
-   freight hubs including intermodal terminals,
-   lines connecting the above mentioned components.

The control-command subsystem concerns two classes (A and B) of train protection and radio communication systems. The lines mentioned above presently not equipped with Class A shall be equipped either:

-   with Class A functions and interfaces according to the specifications referenced in Annex A, or
-   with Class A functions and interfaces according to the specifications referenced in Annex A and with Class B functions and interfaces according to Annex B, or
-   with Class B functions and interfaces according to Annex B and pre-fitting for Class A, or
-   only with Class B functions and interfaces according to Annex B.

In case lines under the scope of the present TSI will not be equipped with Class A systems, the Member State shall make every effort for the availability of an external specific transmission module (STM) for its legacy Class B system or systems. In this context, due regard is to be given to the assurance of an open market for STM at fair commercial conditions. In those cases that due to technical or commercial reasons (13) the availability of an STM cannot be ensured within the appropriate time frame (14) the relevant Member State is deemed to inform the Committee of the reasons underpinning such a problem and the mitigation measures that it intends to put into place in order to allow access — notably of foreign operators — to its infrastructure.

#### 7.2.3.1.   Additional Class-B equipment on a Class A — equipped line

On a line equipped with ETCS and/or GSM-R, additional Class B equipment is possible in order to allow the operation of rolling stock not compatible with Class A during the migration phase. It is allowed to use existing Class B equipment on-board as a fallback arrangement to Class A system: this does not allow an infrastructure manager to require Class B systems onboard the interoperable trains for running on such a line.

Where dual fitment and operation of Class A and B systems occurs, then both systems may be active simultaneously onboard, provided that national technical requirements and operating rules support this manner and that interoperability is not compromised. The national technical requirements and operating rules will be provided by the Member State.

#### 7.2.3.2.   Pre-fitting for Class A

The track side pre-fitting is defined as the installation of any ETCS and GSM-R equipment or other enabling equipment for ETCS and GSM-R (e.g. installation of cabling and wiring, interlocking interfaces, LEU or fibre optic backbones) which is fitted but not necessarily put in service aimed at reducing the implementation cost of full-fledged ERTMS/ETCS or GSM-R facilities complying with Class A requirements at a later stage. For ETCS the scope of the pre-fitting for the three-tiered structure of pre-fitment stages defined in paragraph 7.2.2.4.4 should adhere with the requirements set out in Index 59 of Annex A (pending).

The extent of the pre-fitting to be performed should be established during the implementation planning of the signalling or telecommunication facilities that are to be deployed. In particular, the network planning for GSM-R has to take into account at the earliest stage the inclusion of all services that have to be foreseen also in the future (voice, non safety critical data, ETCS).

#### 7.2.3.3.   Upgrading or renewal of the control-command track-side assembly or parts of it

Upgrading or renewal of the track-side assembly may concern separately:

-   radio-system (for class B, only renewal is possible) ,
-   train protection system,
-   train detection system interface,
-   hot axle box detection system,
-   EMC characteristics.

Therefore different parts of the control-command track-side assembly may be upgraded or renewed separately (if interoperability is not prejudiced) and concern:

-   EIRENE functions and interfaces (see sections 4.2.4 and 4.2.5),
-   ETCS/ERTMS functions and interfaces (see sections 4.2.1, 4.2.3, 4.2.5, 4.2.7, 4.2.8),
-   train detection system (see section 4.2.11),
-   hot axle-box detector (see section 4.2.10),
-   EMC characteristics (see section 4.2.12).

After the upgrade to Class A system, the existing Class B equipment may remain in use simultaneously with Class A.

#### 7.2.3.4.   Registers of Infrastructure

The Infrastructure Register shall provide railway undertakings with Class A and Class B information, following Annex C requirements. The Infrastructure Register indicates if mandatory or optional (15) functions are concerned; the constraints on onboard configuration have to be identified.

In case European specifications for some interface(s) between control-command and signalling and other subsystems are not available at the moment of installation (e.g. electromagnetic compatibility between train detection and rolling stock), the corresponding characteristics and the standards applied shall be indicated in the Registers of Infrastructure. This shall be possible, in any case, only for the items listed in Annex C.

### 7.2.4.   Implementation: rolling stock (on-board equipment)

According to Directive 2001/16/EC each of the categories of rolling stock which are likely to travel on all or part of the trans-European conventional rail network must be subdivided into:

-   rolling stock for international use,
-   rolling stock for national use,

taking due account of the local, regional or long-distance use of the stock.

Rolling stock mentioned above shall be equipped either:

-   with Class A functions and interfaces according to the specifications referenced in Annex A, or
-   with Class A functions and interfaces according to the specifications referenced in Annex A and with Class B functions and interfaces according to Annex B, or
-   with Class B functions and interfaces according to Annex B and pre-fitment for Class A, or
-   only with Class B functions and interfaces according to Annex B, or
-   as in section 7.2.5.2.

such as to allow it to travel on any line on which it is expected to operate.

#### 7.2.4.1.   Rolling stock with Class A equipment only

The Class A assembly shall ensure that the onboard functions, interfaces and minimum performance required by this TSI are matched to the lines concerned as described in Annex C. Installation of Class A equipment may take advantage from additional interface specifications between rolling stock and control-command.

#### 7.2.4.2.   Rolling stock with Class B equipment only

The Class B equipment shall ensure that the onboard functions, interfaces and minimum performance required by this TSI are matched to the lines concerned as described in Annex C.

#### 7.2.4.3.   Rolling stock with Class A and Class B equipment

Rolling stock may be equipped with both Class A and Class B systems to enable operations on several lines. The Class B systems may be implemented

-   using an STM that may be plugged into the Class A assembly (external STM), or
-   built into the Class A assembly.

Also, the Class B system could be implemented independently (or, in case of upgrade or renewal, be left as it is), in case of Class B systems for which an STM is not an economically viable alternative, from the rolling stock owner's point of view. However, if a STM is not used, the Railway Undertaking must ensure that the absence of a ‘handshake’ (= handling, by ETCS, of transitions between Class A and Class B on track-side) nevertheless is properly managed. The Member State may put requirements on this in the Infrastructure Register.

When running on a line which is equipped with both Class A and Class B systems, the Class B systems may act as fallback arrangement for the Class A system if the train is equipped with both Class A and Class B systems. This cannot be a requirement for interoperability and is not valid for GSM-R.

#### 7.2.4.4.   Pre-fitting for Class A

The on-board pre-fitting is defined as the installation of any ETCS and GSM-R equipment or other enabling equipment for ETCS and GSM-R (e.g. installation of cabling and wiring, antennas, sensors, power supply or installation fixtures) which is fitted but not necessarily put in service aimed at reducing the implementation cost of full-fledged ERTMS/ETCS or GSM-R facilities complying with the Class A requirements at a later stage. For ETCS the scope of the pre-fitting for the three-tiered structure of pre-fitment stages defined in paragraph 7.2.2.4.4 should adhere with the requirements set out in Index 57 of Annex A (pending).

The extent of the pre-fitting to be performed should be established during the engineering phase of the on-board signalling or telecommunication facilities. Pre-fitting may take advantage from additional interface specifications between the subsystems rolling stock and control-command.

#### 7.2.4.5.   Reverse STM

See section 7.2.5.2.

#### 7.2.4.6.   Upgrading or renewal the control-command on-board assembly or parts of it

Upgrading or renewal of the on-board assembly may concern separately:

-   radio-system (Class B to Class A),
-   train protection system (Class B to Class A).

Therefore different parts of the control-command on-board assembly may be performed or upgraded separately (if interoperability is not prejudiced) and concern:

-   EIRENE functions and interfaces (see sections 4.2.4 and 4.2.5),
-   ETCS/ERTMS functions and interfaces (see sections 4.2.1, 4.2.3, 4.2.5, 4.2.7, 4.2.8).

After the upgrade to Class A system, the existing Class B equipment may remain in use simultaneously with Class A.

#### 7.2.4.7.   Registers of rolling stock

The Rolling Stock Register shall provide information following Annex C requirements.

In case TSI requirements for some interface(s) between control-command and signalling and other subsystems are not available at the moment of installation (e.g. electromagnetic compatibility between train detection and Rolling Stock, climatic conditions and physical conditions in which the train can work, geometric parameters of the train like length, maximal distance of axles in the train, length of the nose of the first and of the last car of the train, braking parameters), the corresponding characteristics and the standards applied shall be indicated in the Registers of Rolling Stock. This shall be possible, only for the items listed in Annex C.

Remark: for every implementation of control-command subsystem on a given line, Annex C gives the list of the requirements for the onboard, to be addressed in the Registers of Infrastructure, indicating if these requirements concern mandatory or optional (16) functions and identifying constraints on train configuration.

### 7.2.5.   Particular migration paths

#### 7.2.5.1.   Specific solution for partial additional use of Class A system

In a migration phase when only part of the fleet is equipped with an onboard system able to handle Class A, it may be necessary to have both systems fully or partially installed on a line.

For ETCS there is no functional link between the two onboard systems except to manage transitions during train operation (and with exception to satisfy the needs of the STMs for Class B systems when STMs are used).

For ETCS from a purely functional point, a system may also be built combining components from the unified and a pre-unified system. An example is the combination of an ETCS Level 1 using Eurobalise as a spot transmission means and an infill function not based on a unified solution, but on a national system. This solution requires an on-board data link between the unified and the pre-unified system. Therefore, the solution is not in accordance with either Class A or Class B and is not interoperable.

There is, however, the possibility to use the combination as a national enhancement of an interoperable line. This is only permitted if trains not equipped with the data link between both systems can operate either on the unified or on the pre-unified system without information from the other system. If this is not possible, the line cannot be declared interoperable for the control-command subsystem.

#### 7.2.5.2.   Specific solution for partial alternative use of ETCS Class A airgap

An infrastructure may also be used for the movement of trains not compliant with the requirements of this TSI, according to Article 5(6) of Directive 2001/16/EC, provided this does not create prejudice to the fulfilment of essential requirements.

Such trains receive information from a Class B signalling infrastructure via Class A track-to-train communication.

#### 7.2.5.3.   Competition criteria

Any action to allow the movement of interoperable trains on other infrastructures or the movement of not interoperable trains on interoperable infrastructures shall ensure that free competition between suppliers is not prejudiced.

Specially, knowledge about relevant interfaces between already installed equipment and new equipment to be purchased shall be put at the disposal of all the interested suppliers.

### 7.2.6.   Conditions under which optional functions are required

According to the characteristics of the track-side control-command track-side assembly and its interfaces with other subsystems, some track-side functionality not classified as mandatory, may have necessarily to be implemented in certain applications to comply with the essential requirements.

The track-side implementation of national or optional-functions must not prevent the entry onto that infrastructure for a train that complies only with the mandatory requirements of Onboard Class A system except as required for the following on-board optional functions:

-   an ETCS Level 3 Track-side application requires train integrity supervision onboard,
-   an ETCS Level 1 Track-side application with infill requires corresponding in-fill functionality onboard if the release speed is set to zero for safety reasons (e.g. protection of danger points),
-   when ETCS requires data transmission by radio, the data transmission services of GSM-R must fulfil the ETCS data transmission requirements,
-   an onboard assembly, which incorporates a KER STM, may require to implement the K-interface.

## 7.3.   Management of change

### 7.3.1.   Introduction

Change is a facet inherent to any kind of computer-based systems used in real-world environments. It is prompted by the emergence of new requirements or by changes to existing requirements either due to errors reported in operation or the need of improvements in performance or other non-functional characteristics.

But change has to be managed as it is underpinned by safety-critical considerations and by backward compatibility objectives so as to provoke minimal time and cost overheads to the operation of already deployed ERTMS (17) equipment (i.e. legacy ERTMS facilities). It is therefore crucial to define a clear strategy of how to implement and manage change to legacy ERTMS equipment to avoid disruption to railway operations without undermining the underlying objectives of guaranteeing safety and interoperability. Two main issues underpin the definition of such a strategy:

-   the establishment of a Configuration Management framework defining the standards and procedures for managing system evolution. This should include how to record and process proposed system changes, how to relate these changes to system components and how to track system releases,
-   a policy for release of system baselines.

### 7.3.2.   Baselining

System stability is essential so that actual implementation and deployment can be realistic. This need for stability is akin to all parties:

-   the infrastructure managers and the railway operators that will have to handle various versions of ERTMS/ETCS or GSM-R,
-   the industry that needs time to specify, develop and prove continued interoperability.

A baseline in essence embodies the concept of a stable kernel in terms of system functionality, performance and other non-functional characteristics (e.g. RAMS) (18). However, past experience with this type of systems has shown that a number of version releases (19) are needed to achieve a stable and implementation-suitable baseline. This can be illustrated as a cascade process as follows:

Image

Through its feedback loops such a process is highly intertwined. This precludes putting several of those processes in parallel an approach that would lead to unstable and confusing and operationally hampering situations. Baselines have then to be processed in a series rather than in a parallel manner as illustrated below for the specific case of ERTMS/ETCS (20):

Image

### 7.3.3.   The ERTMS consolidation phase

The first baseline of the ERTMS specifications (both ETCS and GSM-R) was appended to the TSI Command/Control and Signalling for high-speed (reference Decision 2002/731/EC). A new version release of these specifications was issued recently (Decision 2004/447/EC). It included minor functional and system changes whereas laying down the foundation of a structured approach for conformity assessment of the on-board command/control equipment.

The current on-going consolidation process for ERTMS (both ETCS and GSM-R) is clearly focused on two main issues:

-   the consolidation of the current baseline in order it becomes a more robust reference for interoperability, and
-   the closure of a number of still standing operational and technical open points.

This work relies on the feedback from current pilots, early commercial applications as well as on structured program of cross-tests with products from different suppliers. It should eventually lead to the release of a new baseline to be put under configuration management during the first half of 2005.

During this phase it may be necessary to make special, mutual agreements between infrastructure managers and railway undertakings for using Class A systems.

### 7.3.4.   Baseline release

Based on current experience the timing between different baselines can be estimated to be approximately four to five years for ETCS and approximately two years for GSM-R.

A new baseline should in principle be linked with significant modifications of the system functionality or system performance. This could include aspects such as:

-   the incorporation of a set of today's national functions, where these can be generalised, within the interoperable kernel,
-   the set-up of additional interoperability constituents on the ETCS on-board and trackside,
-   GSM-R-based value-added services.

Each baseline should also embrace the functionality of the previous baseline. Debugging versions to repair system faults or safety shortcomings should be handled as a version release of a particular baseline. Unless prevented by safety implications such version releases within the same baseline are to be backward compatible.

The added functionality that might be embodied in different baselines necessarily implies that different baselines are not backward compatible. However, in order to facilitate migration and in the extent possible from a technical view point, different baselines should encompass a common core of functionality for which backward compatibility should be ensured. Such a common core should provide a minimum kernel to enable interoperable operation under acceptable performance.

### 7.3.5.   Deployment of new baselines

Infrastructure managers and railway operators will never be in a position to switch from one baseline to the next over night. Henceforth, each baseline has to developed hand-in-hand with an appropriate migration strategy. This is to address problems such as co-existence of ETCS and GSM-R facilities compliant with different versions of the ETCS or GSM-R specifications, preferred paths of migration (e.g. trackside priority, rolling-stock priority or simultaneous) as well as the indicative timeframes and the priorities for the migration.

### 7.3.6.   Change management process — the requirements

As discussed earlier change is a fact of life for large software based systems. Henceforth, change management procedures should be designed to ensure that the costs and benefits of change are properly analysed and that changes are implemented in a controlled way. This requires the defined change management process and associated tools to ensure that changes are recorded and applied to the specifications in a cost-effective manner. Whatever the specific details of such a process might eventually be the latter should be broadly mapped on a structured approach as follows:

Image

A configuration management plan embodying the set of standards and procedures for change management should underpin the whole of the change management process as described above. The generic requirements for such a plan are described in paragraph 7.3.7 below. The implementation strategy for the approved changes should be formalised (on the basis of due process and due documentation) into a change management plan that includes notably

-   the identification of the technical constraints underpinning the change,
-   a statement of who takes responsibility for the change implementation procedures,
-   the validation procedure for the changes to be implemented,
-   the policy for change management, release, migration and roll-out.

### 7.3.7.   Configuration management plan — the requirements

The configuration management plan should describe the set of standards and procedures for change management encompassing notably:

-   the definition of what entities are to be managed and a formal scheme for identifying these entities,
-   a statement of who takes responsibility for the configuration management procedures and for submitting controlled entities to the configuration management decision structure,
-   the configuration management policies that are to be used for change control and version management,
-   a description of the records of the configuration management process which should be maintained,
-   a description of the tools to be used for configuration management and the process to be applied when using these tools,
-   a definition of the configuration database which will be used to record configuration information.

The specific details of the configuration management processes for ETCS and GSM-R are to be formalised through specifications to be incorporated in the list included under Annex A to this TSI, respectively, under Index 60 (for ETCS) and Index 61 (for GSM-R).

### 7.3.8.   Governance

The management of change of the ERTMS/ETCS and GSM-R specifications is to be placed under the aegis of the European Railway Agency (ERA) established by Regulation (EC) No 881/2004. The ERA will be responsible for mastering the change management process, including the delivery of the specifications, its quality assurance and configuration management.

This way the ERA will play the centre role of system authority centralising and ensuring the overall coherence of a process that is nowadays fragmented through a number of different parties as evidenced in the table below:

| Responsibility             | ERTMS/ETCS                         | GSM-R                                       |
| -------------------------- | ---------------------------------- | ------------------------------------------- |
| Delivery of specifications | ERTMS users’ group, UIC and UNISIG | EIRENE group, ERIG and GSM-R industry group |
| Quality assurance          | ERTMS users’ group                 | EIRENE group, ERIG and ERTMS users’ group   |
| Configuration management   | AEIF                               |                                             |

In its role of system authority the ERA will ensure the cooperation of a representative cross-section of the stakeholders in the process — e.g. infrastructure managers, railway undertakings, supply industry, notified bodies and safety authorities — for the performance of its duties. These parties should notably:

<ol type="i">
<li>Provide input for the process in terms of:

-   specification of functional and operational interoperability requirements. This will be primarily the role to be played by the railway undertakings and infrastructure managers,
-   definition of technical standards including those assuring technical interoperability for ERTMS/ETCS and GSM-R emerging from representative industrial groupings such as UNISIG and the GSM-R industry group.

      </li>
    <li>Be part of the change control board (CCB) to be established for the management of change requests as referred to in paragraph 7.3.6. The CCB should ensure a system perspective on the changes that are to be made and a global assessment of their implications.</li>
    </ol>

A coordinated handover needs to be ensured between the current AEIF-led and the ERA-led change management structures. For this handover to happen in a smooth manner it is deemed essential:

-   to formalise and document the current change management process within the set of documentation referred to in Annex A in order this is taken as baseline for ensuring the continuity and the quality of the change management work,
-   to foresee a period of transition of approximately 12 months where the two structures will operate in parallel following a modus operandi to be agreed between the two parties.

The ERA will start-up its formal change management activity from the 2005 baseline emerging from the consolidation phase as referred to in paragraph 7.3.3.

## 7.4.   Specific cases

### 7.4.1.   Introduction

The following special provisions are permitted in the specific cases below.

These specific cases belong to two categories: the provisions apply either permanently (case P), or temporarily (case T). In temporary cases, it is recommended that the Member States concerned should conform with the relevant subsystem either by 2010 (case T1), an objective set out in Decision No 1692/96/EC of the European Parliament and of the Council of 23 July 1996 on Community guidelines for the development of the trans-European transport network (21), or by 2020 (case T2) (22).

In this TSI temporary case T3 is defined as temporary cases which will still exists after 2020.

### 7.4.2.   List of specific cases

#### 7.4.2.1.   Category of each specific case is given in Annex A, Appendix 1.

| No  | Specific case                                                                                                                                                                                               | Justification                                                                                                                                                                                                                                                                                                                                         | Duration                 |
| --- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------ |
| 1   | Interdependence between axle distance and wheel diameter of vehicles operating in Germany is given in Annex A, Appendix 1 paragraph 2.1.5                                                                   | Existing axle counter equipment, identified in the infrastructure register.                                                                                                                                                                                                                                                                           | P                        |
| 2   | Maximum length of vehicle overhang (nose) operating in Poland is given in Annex A, Appendix 1 paragraph 2.1.6                                                                                               | Existing geometry of track circuit equipment                                                                                                                                                                                                                                                                                                          | T3                       |
| 3   | Minimum distances between first 5 axles of trains operating in Germany is given in Annex A, Appendix 1 paragraph 2.1.7                                                                                      | Relevant on lines with level crossing according to infrastructure register.                                                                                                                                                                                                                                                                           | T3                       |
| 4   | Minimum distance between the first and last axle of a lone vehicle or trainset operating on high speed lines in France and on high speed line L1 in Belgium is given in Annex A, Appendix 1 paragraph 2.1.8 | Existing track circuit equipment, identified in the infrastructure register.                                                                                                                                                                                                                                                                          | France T3<br/>Belgium T3 |
| 5.  | Minimum distance between the first and last axle of a lone vehicle or trainset operating in Belgium is given in TSI CCS CR Annex A, Appendix 1 paragraph 2.1.9                                              | Existing track circuit equipment, identified in the infrastructure register.                                                                                                                                                                                                                                                                          | T3                       |
| 6.  | Minimum diameter of wheels of vehicles operating in France is given Annex A, Appendix 1 paragraph 2.2.2                                                                                                     | Existing axle counter equipment, identified in the infrastructure register.                                                                                                                                                                                                                                                                           | T3                       |
| 7.  | Minimum axle load for vehicles operating in Germany, Austria, Sweden is given in Annex A, Appendix 1 paragraph 3.1.3                                                                                        | Minimum axle load necessary to shunt certain track circuits is determined in a requirement of EBA (Eisenbahn-Bundesamt), relevant on some main lines in Germany in the area of former DR (Deutsche Reichsbahn) with 42 Hz and 100 Hz track circuits according to the infrastructure register. No renewal. <br/>To be completed for Austria and Sweden | T3                       |
| 8.  | Minimum mass of a lone vehicle or trainset operating on high speed lines in France and on high speed line L1 in Belgium is given in Annex A, Appendix 1 paragraph 3.1.4.                                    | Existing track circuit equipment                                                                                                                                                                                                                                                                                                                      | France T3<br/>Belgium T3 |
| 9.  | Minimum mass of a lone vehicle or train-set operating on high speed lines in Belgium (except high speed line L1) is given in TSI CCS CR Annex A, Appendix 1 paragraph 3.1.5                                 | The rolling stock is more homogeneous on the high-speed lines. The running surface on the rail is more limited than on the conventional network. The detection of the presence of any type of circulation when running or at standstill is granted anytime if the mass of a lone vehicle or train-set is greater than 90 tons.                        | T3                       |
| 10. | Minimum dimension of metal mass and approval conditions of vehicles operating in Germany and Poland are given in Annex A, Appendix paragraph 3.3.1                                                          | Relevant on lines with level crossing with detection loops according to infrastructure register.                                                                                                                                                                                                                                                      | Germany P<br/>Poland P   |
| 11. | Maximum reactance between running surfaces of a wheelset of vehicles operating in Poland is given in Annex A, Appendix 1 paragraph 3.5.3                                                                    | Existing track circuit equipment                                                                                                                                                                                                                                                                                                                      | T3                       |
| 12. | Maximum reactance between running surfaces of a wheelset of vehicles operating in France is given in Annex A, Appendix 1 paragraph 3.5.4                                                                    | Existing track circuit equipment                                                                                                                                                                                                                                                                                                                      | T3                       |
| 13. | Additional requirements on shunting parameters of a vehicle operating in Netherlands are given in Annex A, Appendix 1 paragraph 3.5.5                                                                       | Existing low voltage track circuit equipment, identified in the infrastructure register.                                                                                                                                                                                                                                                              | T3                       |
| 14. | Minimum impedance between pantograph and wheels of vehicles operating in Belgium is given in Annex A, Appendix 1 paragraph 3.6.1                                                                            | Existing Class B equipment                                                                                                                                                                                                                                                                                                                            | T3                       |
| 15. | The magnetic brake and eddy current brake is not permitted at the first bogie of a leading vehicle operating in Germany, defined in Annex A, Appendix 1 paragraph 5.2.3                                     | Relevant on lines with level crossing according to infrastructure register.                                                                                                                                                                                                                                                                           | T3                       |
| 16. | Sanding for traction purposes on multiple units is not permitted ahead of the leading axle below 40km/h in the United Kingdom, as defined in Annex A, Appendix 1 paragraph 4.1.4                            | Track circuits cannot be relied upon to operate safely when sanding ahead of a leading axle on a multiple unit                                                                                                                                                                                                                                        | T3                       |

#### 7.4.2.2.   Specific case for Greece

Category T1- temporary: rolling stock for track gauge 1 000 mm or less, and lines with track gauge 1 000 mm or less. National rules shall apply on these lines.

#### 7.4.2.3.   Specific case for the Baltic States (Latvia, Lithuania, Estonia)

Category T open — the functional and technical upgrading of the current class B facilities deployed on the 1 520 mm track gauge corridors is allowed if this is deemed necessary to enable the operation of the locomotives of the railway undertakings of both the Russian Federation and Belarus. The on-board equipment of the latter is excluded from compliance with the requirements of paragraph 7.2.2.5. Such corridors are to be mentioned in the infrastructure register.

## 7.5.   Transitional provisions

The open points indicated in this TSI will be managed in the revision process.

(1)  The safety requirements for ERTMS/ETCS Level 3 still have to be established.

(2)  This requirement shall be respected as RS design parameter and for RS subsystem assessment.

(3)  Different level of specification: shall be part of driver training and route knowledge.

(4)  The high-speed lines are identified by a dotted pattern.

(5)  OJ L 167, 30.4.2004, p. 1, corrected by OJ L 201, 7.6.2004, p. 1.

(6)  OJ L 161, 26.6.1999, p. 1. Regulation as amended by Regulation (EC) No 173 (OJ L 29, 2.2.2005, p. 3).

(7)  OJ L 161, 26.6.1999, p. 57).

(8)  This includes the factory-fit like operations associated to major maintenance exercises.

(9)  For purposes of fitment of ETCS equipment ‘major retrofitting’ is defined as those maintenance operations that entail an investment at least 10 times higher than the value of fitting the ETCS equipment on that specific type of rolling-stock.

(10)  The level of obligation is to be defined in terms of the following criteria: (i) market relevance of the corridors targeted for ERTMS/ETCS implementation; (ii) line coverage by ERTMS/ETCS.

(11)  It is expected this will be the result of a corridor-by-corridor analysis to be jointly performed by the relevant stakeholders — namely Member States, infrastructure managers, railway undertakings and potentially the supply industry.

(12)  Sistema Controllo Marcia Treno. An Italian Class B system built upon ETCS components.

(13)  E.g. the feasibility of the external STM concept cannot be technically guaranteed or potential issues relating to the ownership of the intellectual property rights of the Class B systems prevent a timely development of an STM product.

(14)  31 December 2007.

(15)  Function classification: see section 4.

(16)  Function classification: see section 4.

(17)  Both ERTMS/ETCS and GSM-R.

(18)  A baseline acts as a reference starting point for a controlled management of the system evolution.

(19)  A version release is a version of the system that is distributed to railway customers. Versions of the system may have different functionality, performance or may repair system faults or safety or security shortcomings.

(20)  Additional elements regarding this issue are included in the following paragraphs.

(21)  OJ L 228, 9.9.1996, p. 1. Decision as last amended by Decision No 884/2004/EC (OJ L 167, 30.4.2004, p. 1, corrected by OJ L 201, 7.6.2004, p. 1).

(22)  Other dates (Tx) may be specified depending on the TSI and the specific case.

# ANNEX A

LIST OF MANDATORY SPECIFICATIONS (1)

| Index No | Reference                               | Document name                                                                                                                                 | Version   |
| -------- | --------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------- | --------- |
| 1        | UIC ETCS FRS                            | ERTMS/ETCS Functional Requirement Specification                                                                                               | 4.29 (3)  |
| 2        | 99E 5362                                | ERTMS/ETCS Functional Statements                                                                                                              | 2.0.0     |
| 3        | UNISIG SUBSET-023                       | Glossary of Terms and Abbreviations                                                                                                           | 2.0.0     |
| 4        | UNISIG SUBSET-026                       | System Requirement Specification                                                                                                              | 2.2.2     |
| 5        | UNISIG SUBSET-027                       | FFFIS Juridical Recorder-Downloading Tool                                                                                                     | 2.2.9     |
| 6        | UNISIG SUBSET-033                       | FIS for Man-Machine Interface                                                                                                                 | 2.0.0 (2) |
| 7        | UNISIG SUBSET-034                       | FIS for the Train Interface                                                                                                                   | 2.0.0     |
| 8        | UNISIG SUBSET-035                       | Specific Transmission Module FFFIS                                                                                                            | 2.1.1     |
| 9        | UNISIG SUBSET-036                       | FFFIS for Eurobalise                                                                                                                          | 2.3.0     |
| 10       | UNISIG SUBSET-037                       | Euroradio FIS                                                                                                                                 | 2.3.0     |
| 11       | Reserved 05E537                         | Off line key management FIS                                                                                                                   |           |
| 12       | UNISIG SUBSET-039                       | FIS for the RBC/RBC Handover                                                                                                                  | 2.1.2     |
| 13       | UNISIG SUBSET-040                       | Dimensioning and Engineering rules                                                                                                            | 2.1.0     |
| 14       | UNISIG SUBSET-041                       | Performance Requirements for Interoperability                                                                                                 | 2.1.0     |
| 15       | UNISIG SUBSET-108                       | Interoperability-related consolidation on TSI Annex A documents (mainly SUBSET-026 v2.2.2)                                                    | 1.0.0     |
| 16       | UNISIG SUBSET-044                       | FFFIS for Euroloop subsystem                                                                                                                  | 2.2.0 (4) |
| 17       | Intentionally Deleted                   |                                                                                                                                               |           |
| 18       | UNISIG SUBSET-046                       | Radio In-fill FFFS                                                                                                                            | 2.0.0     |
| 19       | UNISIG SUBSET-047                       | Track-side-Train-borne FIS for Radio In-Fill                                                                                                  | 2.0.0     |
| 20       | UNISIG SUBSET-048                       | Train-borne FFFIS for Radio In-Fill                                                                                                           | 2.0.0     |
| 21       | UNISIG SUBSET-049                       | Radio In-fill FIS with LEU/Interlocking                                                                                                       | 2.0.0     |
| 22       | Intentionally deleted                   |                                                                                                                                               |           |
| 23       | UNISIG SUBSET-054                       | Assignment of Values to ETCS variables                                                                                                        | 2.0.0     |
| 24       | Intentionally deleted                   |                                                                                                                                               |           |
| 25       | UNISIG SUBSET-056                       | STM FFFIS Safe Time Layer                                                                                                                     | 2.2.0     |
| 26       | UNISIG SUBSET-057                       | STM FFFIS Safe Link Layer                                                                                                                     | 2.2.0     |
| 27       | UNISIG SUBSET-091                       | Safety Requirements for the Technical Interoperability of ETCS in Levels 1 and 2                                                              | 2.2.11    |
| 28       | Reserved                                | Reliability — Availability Requirements                                                                                                       |           |
| 29       | UNISIG SUBSET-102                       | Test specification for Interface K                                                                                                            | 1.0.0     |
| 30       | Intentionally deleted                   |                                                                                                                                               |           |
| 31       | UNISIG SUBSET-094                       | Functional Requirements for an On-board Reference Test Facility                                                                               | 2.0.0     |
| 32       | EIRENE FRS                              | GSM-R Functional Requirements Specification                                                                                                   | 7         |
| 33       | EIRENE SRS                              | GSM-R System Requirements Specification                                                                                                       | 15        |
| 34       | A11T6001 12                             | (MORANE) Radio Transmission FFFIS for EuroRadio                                                                                               | 12        |
| 35       | ECC/DC(02)05                            | ECC Decision of 5 July 2002 on the designation and availability of frequency bands for railway purposes in the 876-880 and 921-925 MHz bands. |           |
| 36a      | Intentionally deleted                   |                                                                                                                                               |           |
| 36b      | Intentionally deleted                   |                                                                                                                                               |           |
| 36c      | UNISIG SUBSET-074-2                     | FFFIS STM Test cases document                                                                                                                 | 1.0.0     |
| 37a      | Intentionally deleted                   |                                                                                                                                               |           |
| 37b      | UNISIG SUBSET-076-5-2                   | Test cases related to features                                                                                                                | 2.2.2     |
| 37c      | UNISIG SUBSET-076-6-3                   | Test sequences                                                                                                                                | 2.0.0     |
| 37d      | UNISIG SUBSET-076-7                     | Scope of the test specifications                                                                                                              | 1.0.0     |
| 37e      | Intentionally deleted                   |                                                                                                                                               |           |
| 38       | Reserved                                | Marker boards                                                                                                                                 |           |
| 39       | UNISIG SUBSET-092-1                     | ERTMS EuroRadio Conformance Requirements                                                                                                      | 2.2.5     |
| 40       | UNISIG SUBSET-092-2                     | ERTMS EuroRadio Test cases Safety Layer                                                                                                       | 2.2.5     |
| 41       | Reserved<br/>UNISIG SUBSET 028          | JRU Test Specification                                                                                                                        |           |
| 42       | Intentionally deleted                   |                                                                                                                                               |           |
| 43       | UNISIG SUBSET 085                       | Test Specification for Eurobalise FFFIS                                                                                                       | 2.1.2     |
| 44       | Reserved                                | Odometry FIS                                                                                                                                  |           |
| 45       | UNISIG SUBSET-101                       | Interface K Specification                                                                                                                     | 1.0.0     |
| 46       | UNISIG SUBSET-100                       | Interface G” specification                                                                                                                    | 1.0.1     |
| 47       | Intentionally deleted                   |                                                                                                                                               |           |
| 48       | Reserved                                | Test specification for mobile equipment GSM-R                                                                                                 |           |
| 49       | UNISIG SUBSET-059                       | Performance requirements for STM                                                                                                              | 2.1.1     |
| 50       | Reserved                                | Test specification for EUROLOOP                                                                                                               |           |
| 51       | Reserved<br/>UNISIG                     | Ergonomic aspects of the DMI                                                                                                                  |           |
| 52       | UNISIG SUBSET-058                       | FFFIS STM Application Layer                                                                                                                   | 2.1.1     |
| 53       | Reserved<br/>AEIF-ETCS-Variables-Manual | AEIF-ETCS-Variables-Manual                                                                                                                    |           |
| 54       | Intentionally deleted                   |                                                                                                                                               |           |
| 55       | Reserved                                | Juridical recorder baseline requirements                                                                                                      |           |
| 56       | Reserved<br/>05E538                     | ERTMS Key Management Conformance Requirements                                                                                                 |           |
| 57       | Reserved<br/>UNISIG SUBSET-107          | Requirements on pre-fitting of ERTMS on-board equipment                                                                                       |           |
| 58       | Reserved<br/>UNISIG SUBSET-097          | Requirements for RBC-RBC Safe Communication Interface                                                                                         |           |
| 59       | Reserved<br/>UNISIG SUBSET-105          | Requirements on pre-fitting of ERTMS track side equipment                                                                                     |           |
| 60       | Reserved<br/>UNISIG SUBSET-104          | ETCS version management                                                                                                                       |           |
| 61       | Reserved                                | GSM-R version management                                                                                                                      |           |
| 62       | Reserved<br/>UNISIG SUBSET-099          | RBC-RBC Test specification for Safe Communication Interface                                                                                   |           |
| 63       | Reserved<br/>UNISIG SUBSET-098          | RBC-RBC Safe Communication Interface                                                                                                          |           |

LIST OF MANDATORY EN STANDARDS

| Index No | Reference    | Document name and comments                                                                                                              | Version |
| -------- | ------------ | --------------------------------------------------------------------------------------------------------------------------------------- | ------- |
| A1       | EN 50126     | Railway applications — The specification and demonstration of reliability, availability, maintainability and safety (RAMS)              | 1999    |
| A2       | EN 50128     | Railway applications — Communication, signalling and processing systems — Software for railway control and protection systems           | 2001    |
| A3       | EN 50129     | Railway applications — Communication, signalling and processing systems — Safety related electronic systems for signalling              | 2003    |
| A4       | EN 50125-1   | Railway applications — Environmental conditions for equipment — Part 1: equipment on board rolling stock                                | 1999    |
| A5       | EN 50125-3   | Railway applications — Environmental conditions for equipment — Part 3: equipment for signalling and telecommunications                 | 2003 -  |
| A6       | EN 50121-3-2 | Railway applications — Electromagnetic compatibility — Part 3-2: Rolling stock — Apparatus                                              | 2000    |
| A7       | EN 50121-4   | Railway applications — Electromagnetic compatibility — Part 4: Emission and immunity of the signalling and telecommunications apparatus | 2000    |
| A8       | EN 50238     | Railway applications — Compatibility between rolling stock and train detection systems                                                  | 2003    |

LIST OF INFORMATIVE SPECIFICATIONS

Note:
Type 1 specifications represent the current state of the work for the preparation of a mandatory specification still reserved

Type 2 specifications give additional information, justifying the requirements in mandatory specifications and providing help for their application

Index B32 is intended to ensure unique references in the Annex A documents. As this is used for editorial purposes and to support future changes of documents referred only, it is not classified as a Type and not linked to a mandatory Annex A document.

| Index No | Reference                        | Document name                                                                                                                                                                                           | Version     | Type             |
| -------- | -------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------- | ---------------- |
| B1       | EEIG 02S126                      | RAM requirements (chapter 2 only)                                                                                                                                                                       | 6           | 2 (Index 28)     |
| B2       | EEIG 97S066                      | Environmental conditions                                                                                                                                                                                | 5           | 2 (Index A5)     |
| B3       | UNISIG SUBSET-074-1              | Methodology for testing FFFIS STM                                                                                                                                                                       | 1.0.0       | 2 (Index 36)     |
| B4       | EEIG 97E267                      | ODOMETER FFFIS                                                                                                                                                                                          | 5           | 1 (Index 44)     |
| B5       | O_2475                           | ERTMS GSM-R QoS Test Specification                                                                                                                                                                      | 1.0.0       | 2                |
| B6       | UNISIG SUBSET-038                | Off-line Key Management FIS                                                                                                                                                                             | 1 (Index11) | 1.               |
| B7       | Reserved<br/>UNISIG SUBSET-074-3 | FFFIS STM test specification traceability of test cases with Specific Transmission Module FFFIS                                                                                                         | 1.0.0       | 2 (Index 36)     |
| B8       | UNISIG SUBSET-074-4              | FFFIS STM Test Specification Traceability of testing the packets specified in the FFFIS STM Application Layer                                                                                           | 1.0.0       | 2 (Index 36)     |
| B9       | UNISIG SUBSET 076_0              | ERTMS/ETCS Class 1, Test plan                                                                                                                                                                           | 2.2.3       | 2 (Index 37)     |
| B10      | UNISIG SUBSET 076_2              | Methodology to prepare features                                                                                                                                                                         | 2.2.1       | 2 (Index 37)     |
| B11      | UNISIG SUBSET 076_3              | Methodology of testing                                                                                                                                                                                  | 2.2.1       | 2 (Index 37)     |
| B12      | UNISIG SUBSET 076_4_1            | Test sequence generation: Methodology and Rules                                                                                                                                                         | 1.0.0       | 2 (Index 37)     |
| B13      | UNISIG SUBSET 076_4_2            | ERTMS ETCS Class 1 States for Test Sequences                                                                                                                                                            | 1.0.0       | 2 (Index 37)     |
| B14      | UNISIG SUBSET 076_5_3            | On-Board Data Dictionary                                                                                                                                                                                | 2.2.0       | 2 (Index 37)     |
| B15      | UNISIG SUBSET 076_5_4            | SRS v.2.2.2 Traceability                                                                                                                                                                                | 2.2.2       | 2 (Index 37)     |
| B16      | UNISIG SUBSET 076_6_1            | UNISIG test data base                                                                                                                                                                                   | 2.2.2.      | 2 (Index 37)     |
| B17      | UNISIG SUBSET 076_6_4            | Test Cases Coverage                                                                                                                                                                                     | 2.0.0       | 2 (Index 37)     |
| B18      |                                  |                                                                                                                                                                                                         |             |                  |
| B19      | UNISIG SUBSET 077                | UNISIG Causal Analysis Process                                                                                                                                                                          | 2.2.2       | 2 (Index 27)     |
| B20      | UNISIG SUBSET 078                | RBC interface: Failure modes and effects analysis                                                                                                                                                       | 2.2.2       | 2 (Index 27)     |
| B21      | UNISIG SUBSET 079                | MMI: Failure Modes and Effects Analysis                                                                                                                                                                 | 2.2.2       | 2 (Index 27)     |
| B22      | UNISIG SUBSET 080                | TIU: Failure Modes and Effects Analysis                                                                                                                                                                 | 2.2.2       | 2 (Index 27)     |
| B23      | UNISIG SUBSET 081                | Transmission system: Failure Modes and Effects Analysis                                                                                                                                                 | 2.2.2       | 2 (Index 27)     |
| B24      | UNISIG SUBSET 088                | ETCS Application Levels 1&2 -Safety Analysis                                                                                                                                                            | 2.2.10      | 2 (Index 27)     |
| B25      | TS50459-1                        | Railway applications — European Rail Traffic Management System — Driver Machine Interface" part 1 — Ergonomic principles of ERTMS/ETCS/GSM-R Information                                                | 2005        | 2 (Index 51)     |
| B26      | TS50459-2                        | Railway applications — Communication, signalling and processing systems — European Rail Traffic Management System — Driver Machine Interface" part 2 — Ergonomic arrangements of ERTMS/ETCS Information | 2005        | 2 (Index 51)     |
| B27      | TS50459-3                        | Railway applications — Communication, signalling and processing systems -European Rail Traffic Management System — Driver Machine Interface" part 3 — Ergonomic arrangements of ERTMS/GSM-R Information | 2005        | 2 (Index 51)     |
| B28      | TS50459-4                        | Railway applications — Communication, signalling and processing systems -European Rail Traffic Management System — Driver Machine Interface" part 4 — Data entry for the ERTMS/ETCS/GSM-R systems       | 2005        | 2 (Index 51)     |
| B29      | TS50459-5                        | Railway applications — Communication, signalling and processing systems -European Rail Traffic Management System — Driver Machine Interface" part 5 — Symbols                                           | 2005        | 2 (Index 51)     |
| B30      | TS50459-6                        | Railway applications — Communication, signalling and processing systems -European Rail Traffic Management System — Driver Machine Interface" part 6 — Audible Information                               | 2005        | 2 (Index 51)     |
| B31      | EN50xxx                          | Railway applications — European Rail Traffic Management System — Driver Machine Interface" part 7 — Specific Transmission Modules                                                                       |             | 2 (Index 51)     |
| B32      | Reserved                         | Guideline for references                                                                                                                                                                                |             | Non              |
| B33      | EN 310515                        | Global System for Mobile communication (GSM); Requirements for GSM operation in railways.                                                                                                               | 2.1.0       |                  |
| B34      | 05E466                           | Operational DMI information                                                                                                                                                                             | 1           | 1 (Index 51)     |
| B35      | Reserved<br/>UNISIG SUBSET-069   | ERTMS Key Management Conformance Requirements                                                                                                                                                           |             | 1 (Index 56)     |
| B36      | 04E117                           | ETCS/GSM-R Quality of Service user requirements — Operational Analysis                                                                                                                                  |             | 2 (Index 22)     |
| B37      | UNISIG SUBSET-093                | GSM-R Interfaces — Class 1 requirements                                                                                                                                                                 | 2..3.0      | 1 (Index 32, 33) |
| B38      | UNISIG SUBSET-107A               | Requirements on pre-fitting of ERTMS on-board equipment                                                                                                                                                 | 1.0.0       | 2 (Index 57)     |
| B39      | UNISIG SUBSET-076-5-1            | ERTMS ETCS Class 1 Feature List                                                                                                                                                                         | 2.2.2       | 2 (Index 37)     |
| B40      | UNISIG SUBSET-076-6-7            | Test Sequences Evaluation and Validation                                                                                                                                                                | 1.0.0       | 2 (Index 37)     |
| B41      | UNISIG SUBSET-076-6-8            | Generic train data for test Sequences                                                                                                                                                                   | 1.0.0       | 2 (Index 37)     |
| B42      | UNISIG SUBSET-076-6-10           | Test Sequence Viewer (TSV)                                                                                                                                                                              | 2.10        | 2 (Index 37)     |
| B43      | 04E083                           | Safety Requirements and Requirements to Safety Analysis for Interoperability for the control-command and signalling subsystem                                                                           | 1.0         | 1                |
| B44      | 04E084                           | Justification Report for the Safety Requirements and Requirements to Safety Analysis for Interoperability for the control-command and signalling subsystem.                                             | 1.0         | 2(Index B43)     |

(1)  ERTMS references are to be reviewed after the consolidation phase.

(2)  The content if this document is only valid for the part where there is no contradiction to Index 51

(3)  Version to be updated (TSI control-command CR change requests on FRS forwarded to CCM).

(4)  Conditioned to CEPT approval of the frequency.

# Appendix 1

## TRAIN DETECTION SYSTEMS CHARACTERISTICS NECESSARY TO BE COMPATIBLE WITH ROLLING STOCK

### 1.   GENERAL

#### 1.1. Train detection systems shall be designed in such a way that they are able to detect in a safe and reliable way a vehicle with the limit values specified in this Appendix. Section 4.3 (Functional and technical specifications of the interfaces to other subsystems) of TSI CCS ensures the conformity of TSI-compliant vehicles with the requirements of this Appendix.

#### 1.2. The longitudinal vehicle dimensions are defined as:

ai = distance between following axles, where i = 1, 2, 3, …, n-1, where n is total number of axles of the vehicle

bx = longitudinal distance from first axle (b 1 ) or last axle (b 2 ) to the nearest end of the vehicle, i.e. nearest buffer/nose

L = total length of the vehicle

Figure 6 shows an example for a three-axle twin-bogie vehicle (n=6).

Figure 6

Image

#### 1.3. The term wheelset shall apply to any pair of opposite wheels, even without common axle. Any references to wheelsets concern centre of wheels.

#### 1.4. For definition of wheel dimensions the Figure 7 applies, where:

D = wheel diameter

BR = width of the rim

Sd = thickness of the flange

Sh = height of the flange

Other dimensions in Figure 7 are not relevant in this TSI

#### 1.5. The values quoted are absolute limit values including any measurement tolerances.

#### 1.6. Infrastructure manager may permit less restrictive limits, which shall be stated in the Infrastructure register.

Figure 7

Image

Image

### 2.   VEHICLE GEOMETRY

#### 2.1.   Axle distances

##### 2.1.1. The distance a i (Figure 6) shall not exceed 17 500 mm for existing lines, 20 000 mm for use on new lines.

##### 2.1.2. The distance b x (Figure 6) shall not exceed 4 200 mm.

##### 2.1.3. The distance a i (Figure 6) shall not be less than:

ai = v x7,2

where v is vehicle maximum speed in km/h and distance ai is in mm

if the vehicle maximum speed does not exceed 350 km/h; for higher speeds the limits will have to be defined when necessary.

##### 2.1.4. The distance L — (b1 + b2) (Figure 6) shall not be less than 3 000 mm.

##### 2.1.5.   Specific case Germany

Limitations on the relationship between axle distance (ai, Fig 1) and wheel diameter are still to be defined.

– Open point –

##### 2.1.6.   Specific case Poland and Belgium

The distance bx (Figure 6) shall not exceed 3 500 mm.

##### 2.1.7.   Specific case Germany

The distance ai (Figure 6) between each of the first five axles of a train (or all axles if the train has less than five) shall not be less than 1 000 mm if speed does not exceed 140 km/h; for higher speeds the Article 2.1.3. applies.

##### 2.1.8.   Specific case France high Speed TEN and Belgium high speed TEN ‘L1’ only

The distance between first and last axle of a lone vehicle or trainset shall not be less than 15 000 mm.

##### 2.1.9.   Specific case Belgium

The distance L — (b1 + b2) (Figure 6) shall not be less than 6 000 mm

#### 2.2.   Wheel geometry

##### 2.2.1. The dimension B R (Figure 7) shall not be less than 133 mm

##### 2.2.2. The dimension D (Figure 7) shall not be less than:

-   330 mm if the vehicle maximum speed does not exceed 100 km/h
-   D = 150 + 1,8x v [mm]

where v is vehicle maximum speed in km/h: 100 &lt; v ≤ 250 km/h

-   D = 50 + 2,2x v [mm]

where v is vehicle maximum speed in km/h: 250 &lt; v ≤ 350 km/h for higher speeds the limits will have to be defined when necessary.

-   600 mm in the case of spoke wheels (spoke wheels of the design existing when the TSI enters in force only) if the vehicle maximum speed does not exceed 250 km/h.
-   Specific case France:

450 mm independently of a speed.

##### 2.2.3. The dimension S d (Figure 7) shall not be less than 20 mm.

##### 2.2.4. The range of the dimension S h (Figure 7) shall be 27,5 — 36 mm.

-   Specific case Lithuania

The dimension Sh (Figure 7) shall not be less than 26,25 mm

### 3.   VEHICLE DESIGN

#### 3.1.   Vehicle mass

##### 3.1.1. The axle load shall be at least 5 tonnes unless the braking force of the vehicle is provided by brake blocks, in which case the axle load shall be at least 3,5 tonnes for use on existing lines.

##### 3.1.2. The axle load shall be at least 3,5 tonnes for use on new or upgraded lines.

##### 3.1.3.   Specific case Austria, Germany, Sweden and Belgium

The axle load shall be at least 5 tones on certain lines specified in the infrastructure register.

##### 3.1.4.   Specific case France high speed TEN and Belgium high speed TEN L1 only

If the distance between first and last axle of a lone vehicle or trainset is greater or equal to 16 000 mm, a lone vehicle or trainset mass shall be greater than 90 tonnes. When this distance is less than 16 000 mm, and greater or equal to 15 000 mm, the mass shall be less than 90 tonnes and greater or equal to 40 tonnes, the vehicle must be equipped with two pairs of rail friction-shoe whose electrical base is greater or equal to 16 000 mm.

##### 3.1.5.   Specific case Belgium high speed TEN (except L1)

A lone vehicle or trainset mass shall be at least 90 tonnes.

#### 3.2.   Metal-free space around wheels

##### 3.2.1. The space where only wheels and their parts (gearboxes, brake parts, sanding tube) or non-ferromagnetic components can be mounted are to be defined.

– Open point –

#### 3.3.   Metal-mass of vehicle

##### 3.3.1.   Specific case Germany, Poland

Vehicle needs either to fulfil requirement of a well-specified track-side test loop when passing the loop or shall have a minimum metal mass between wheels with a certain shape, height above rail head and conductance.

– Open point –

#### 3.4.   Wheel material

##### 3.4.1. The wheels shall have ferromagnetic characteristics.

#### 3.5.   Impedance between wheels

##### 3.5.1. Electrical resistance between the running surfaces of the opposite wheels of a wheelset shall not exceed:

-   0,01 Ohm for new or reassembled wheelsets,
-   0,05 Ohm after overhaul of wheel sets.

##### 3.5.2. The resistance is measured by a measuring voltage that is between 1,8 VDC and 2,0 VDC (open voltage)

##### 3.5.3.   Specific case Poland

The reactance between running surfaces of a wheelset shall be less than f/100 in milliohms when f is between 500 Hz and 40 kHz, under a measuring current of at least 10 ARMS and open voltage of 2 VRMS.

##### 3.5.4.   Specific case France

The reactance between running surfaces of a wheelset shall be less than f/100 in milliohms when f is between 500 Hz and 10 kHz, under a measuring voltage of 2 VRMS (Open voltage)

##### 3.5.5.   Specific case Netherlands

In addition to the general requirements in Annex A, Appendix 1, additional requirements may apply to locomotives and multiple units on track circuits. The Infrastructure Register identifies the lines to which these requirements apply.

– Open point –

#### 3.6.   Vehicle impedance

##### 3.6.1. The minimum impedance between pantograph and wheels of the rolling stock has to be :

-   more than 0,45 Ohm inductive at 75 Hz for 1 500 VDC traction systems,

-   Specific case Belgium

more than 1,0 Ohm inductive at 50 Hz for 3 kVDC traction systems.

### 4.   ISOLATING EMISSIONS

#### 4.1.   Use of sanding equipment

##### 4.1.1. For improving braking and traction performances, it is permissible to apply sand on the tracks. The allowed amount of sand per sanding device within 30 seconds is

-   for speeds of V &lt; 140 km/h: 400 g + 100 g
-   for speeds of V ≥ 140 km/h: 650 g + 150 g

##### 4.1.2. The number of active sanding devices shall not exceed the following:

-   For multiple units with distributed sanding devices: first and last car and intermediate cars with a minimum of seven intermediate axles, between two sanding devices that are not sanded. It is permissible to couple such multiple units and to operate all sanding devices at the coupled ends.
-   For loco-hauled trains
-   For emergency and full service braking: all available sanding devices
-   In all other cases: a maximum of four sanding devices per rail
-   The sand shall have the following characteristics:

– Open point –

##### 4.1.3.   Specific case United Kingdom

Sanding for traction purposes on multiple units is not permitted ahead of the leading axle below 40 km/h.

– Open point –

#### 4.2.   Use of composite brake blocks

##### 4.2.1. Conditions for use of composite brake blocks will have to be defined by a survey group by end 2005.

– Open point –

### 5.   ELECTROMAGNETIC INTERFERENCES

#### 5.1.   Traction current

##### 5.1.1. Limits and accompanying explanation in a separate document that is under preparation.

– Open point –

#### 5.2.   Use of electric/magnetic brakes

##### 5.2.1. The use of magnetic brakes and eddy current brakes is only allowed for an emergency brake application or at standstill. The Infrastructure Register may forbid the use of magnetic brakes and eddy current brakes for an emergency brake application.

##### 5.2.2. If stated in the Infrastructure Register eddy current brakes and magnetic brakes may be used for service braking.

##### 5.2.3.   Specific case Germany

The magnetic brake and eddy current brake is not permitted at the first bogie of a leading vehicle unless defined in the Infrastructure Register.

#### 5.3.   Electric, magnetic, electromagnetic fields

##### 5.3.1. – Open point –

### 6.   SPECIFIC CHARACTERISTICS ON THE LINES WITH A GAUGE 1 520/1 524 MM

1.  Train detection systems installed on the lines with a gauge 1 520/1 524 mm have to have characteristics listed above except of those listed in this Chapter.
2.  The distance ai shall not exceed 19 000 mm.
3.  The dimension BR shall not be less than 130 mm.
4.  Electrical resistance between the running surfaces of the opposite wheels of a wheel-set shall not exceed 0,06 Ohm.
5.  The number of active sanding devices in loco-hauled trains shall not exceed six sanding devices per rail.

# Appendix 2

## Requirements on hot-axle box detection

– Open point –

# ANNEX B

# CLASS B

## CONTENTS

-   Use of Annex B
-   Part 1: Signalling
-   Part 2: Radio
-   Part 3: Transition matrix

## USE OF ANNEX B

This Annex presents the train protection, control and warning systems and radio systems that pre-date the introduction of the Class A train control systems and radio systems and that are authorised for use on the European high speed and conventional network up to speed limits defined by the appropriate Member State. These Class B systems were not developed under unified European specifications, and therefore there may be proprietary specification rights with their suppliers. The provision and maintenance of these specifications shall not conflict with national regulations — especially those concerning patents.

During the migration phase in which these systems will be gradually replaced by the unified system, there will be a need to manage the engineering specifications in the interests of interoperability. This is the responsibility of the Member State concerned or its representative in co-operation with the respective system supplier in accordance with both control-command TSIs for the trans-European high-speed and conventional rail systems.

Railway undertakings needing to install one or more of these systems on their trains shall refer to the appropriate Member State. Annex C manages the corresponding geographical distribution of each system, requiring for each line a Register of Infrastructure describing the equipment type and the associated operational arrangements. By means of the Register of Infrastructure the infrastructure manager ensures the coherence between the control-command track-side assembly and the rule book under his authority.

The Member State shall provide to the railway undertaking the advice necessary to obtain a safe installation compatible with the requirements of both TSIs and Annex C.

The Class B installations shall include the fallback arrangements, as required by Annex C.

For the Class B systems, this Annex provides basic information. For each system listed, the Member State identified shall guarantee that its interoperability is maintained and shall provide the information required for the purposes of its application, in particular the information relevant to its approval.

## Part 1: Signalling

INDEX:

1.  ALSN
2.  ASFA
3.  ATB
4.  ATP-VR/RHK
5.  BACC
6.  CAWS and ATP
7.  Crocodile
8.  Ebicab
9.  EVM
10. GW ATP
11. Indusi/PZB
12. KVB
13. LS
14. LZB
15. MEMOR II+
16. RETB
17. RSDD/SCMT
18. SELCAB
19. SHP
20. TBL
21. TPWS
22. TVM
23. ZUB 123

For information only, systems not used in Member States:

23.ZUB 121

**ALSN**

**Automatic locomotive signalling of continuous operation**

Автоматическая Локомотивная Сигнализация Непрерывного действия (original Russian name),

**Description:**

ALSN is a system of in-cab signalling and train auto-stop equipment. It is installed on major lines of Latvian Railway and neighbouring countries: Lithuania and Estonia. (For information only: it is installed as well as on railways of Russian Federation and Belarus).

The system consists of coded track circuits (TC) and on-board equipment.

The track circuits are of rather conventional design with receivers based on relay technique.

Open lines are equipped with:

-   coded TC's of alternating current (AC) with frequency of 50 (1), 75 or 25 Hz; or
-   continuous TC's, which ensure switching-on coding mode towards an approaching train depending on the train direction:
    -   TC's with frequency of 50, 75 or 25 Hz of AC for continuous mode and with frequency of 50, 75 or 25 Hz for coding mode;
    -   DC TC's.

Stations are equipped with:

-   continuous TC's which ensure switching-on coding mode towards an approaching train depending on the train direction:
    -   TC's with frequency of 50, 75, 25 Hz or audio-frequency of AC for continuous mode and with frequency of 50, 75 and 25 Hz for coding mode; or
    -   DC TC's.

The on-board equipment consists of an electronic amplifier; a relay-based decoder; an electro-pneumatic valve for switching on/off braking system; a light signal, representing aspects of field-side signals, and a vigilance handle for confirmation of received information by a driver.

The system is safety-related, not fail-safe since it is a supplement to field-side signals, but safe enough to supervise the driver.

The data transmission between coded track circuits and on-board equipment is via inductively coupled air coil pickup antennae above the rails.

The system is intended to operate with train movement speed up to 160 km/h.

**Main characteristics:**

-   Data transmission to train:
    -   50, 25 or 75 Hz Carrier frequency
    -   Numerical code
    -   Minimal coding current in rails for ALSN operation is 1,2 A
    -   four on-board signal aspects (three codes and code absence)
-   Information available on-board (outside the ALSN): actual speed, length of passed route.
-   Display to driver:
    -   Aspect of on-board signal, corresponding to receive code,
    -   Sound announcement in case of code change to more restrictive one.
-   Supervision:
    -   Acknowledgement of a more restrictive by driver within 15 seconds,
    -   Continuous speed supervision after passing the STOP field-side signal,
    -   Acknowledgement of code absence each 40 to 90 seconds.
-   Reaction:
    The emergency brake is called in the case of:
    -   Passing the field-side signal with STOP aspect,
    -   Over-speeding the value, allowed for actual signal aspect,
    -   Warning (sound announcement) is not acknowledged by the driver.

Responsible Member States: Latvia, Estonia, Lithuania

**ASFA**

**Description:**

ASFA is a cab signalling and ATP system installed on most lines of RENFE (1 676 mm), on metre gauge lines of FEVE, and on the new European gauge NAFA line.

ASFA is found on all lines being considered for Interoperability.

Track-to-train communication is based on magnetically coupled resonant circuits in such a way that nine different data can be transmitted. A resonant circuit track-side is tuned to a frequency representing the signal aspect. The magnetically coupled on-board PLL is locked to the track-side frequency. The system is safety related, not fail safe, but safe enough to supervise the driver. It reminds the driver of the signalling conditions and obliges him to acknowledge restrictive aspects.

The track-side and on-board units are of conventional design.

**Main Characteristics:**

-   Nine frequencies  
    Range: 55 kHz to 115 kHz
-   Three different train categories can be selected on-board
-   Supervision:
    -   Acknowledgement of restrictive signal by driver within three seconds
    -   Continuous speed supervision (160 km/h or 180 km/h) after passing restrictive signal
    -   Speed check (60 km/hr, 50 km/hr or 35 km/hr depending on train type) after passing a transponder 300 m in rear of signal
    -   Train trip at signal at danger
    -   Line speed.
-   Reaction:
    The emergency brake is called if any supervision is violated. The emergency brake can be released at standstill.

Responsible Member State: Spain

**ATB**

ATB exists in two basic versions: ATB first generation and ATB new generation.

**Description of ATB first generation:**

ATB first generation is installed on the vast majority of lines of NS.

The system consists of coded track circuits of rather conventional design and a computerised (ACEC) or conventional electronic (GRS) on-board equipment.

The data transmission between coded track circuits and on-board equipment is via inductively coupled air coil pickup antennae above the rails.

**Main characteristics:**

-   Data transmission to trains:
    -   75 Hz Carrier frequency
    -   AM modulated speed codes
    -   Six speed codes (40,60,80,130,140) km/hr
    -   One exit code
-   No train characteristics on board (Speed code from wayside)
-   Display to driver:
    -   Speed corresponding to speed code
    -   Gong in case of code change
    -   Bell in case the system requests brake application
-   Supervision:
    -   Speed (continuous)
-   Reaction: The emergency brake is called in the case of overspeed and the driver does not react to an acoustic warning.

Responsible Member State: Netherlands

**Description of ATB new generation:**

ATC System partially installed on lines of NS.

The system consists of track-side balises and on-board equipment. An infill function based on a cable loop is also available.

The data transmission is between the active balise and an antenna on-board. The system is direction sensitive, the balises are mounted between the rails with a small offset from the centre.

ATBNG on-board equipment is fully interoperable with ATB first generation track-side equipment.

**Main characteristics:**

-   Data transmission to trains:
    -   100 kHz +/- 10 kHz (FSK)
    -   25 kbit/sec
    -   119 useful bits per Telegram
-   Train characteristics as input by the driver
    -   Train length
    -   Maximum train speed
    -   Train braking characteristics
-   Displays to the driver:
    -   Maximum line speed
    -   Target speed
    -   Target distance
    -   Braking curve
-   Supervision:
    -   Line speed
    -   Speed restrictions
    -   Stopping point
    -   Dynamic brake profile
-   Reaction:
    -   Optical pre warning
    -   Acoustic warning
        The emergency brake is called in the case of movement supervision is violated or the driver does not react to an acoustic warning.

Responsible Member State: Netherlands

**ATP-VR/RHK**

**Automatic train protection (ATP), Junakulunvalvonta (JKV)**

Commonly called Junakulunvalvonta (JKV) (Finnish meaning Automatic train protection (ATP)).

**Description:**

ATP-VR/RHK system in Finland is a fail safe standard ATP system, which is based either on technology of Ebicab 900 with JGA balises or on technology of ATSS with Mini-transponder balises. The system consists of track-side balises and signal encoders or computers, and on-board computerised equipment.

The data transmission is between passive track side balises (two per balise point) and on-board antenna underneath vehicle which also supplies the balise with energy when passing. The coupling between balise and on-board is inductive.

**Main characteristics:**

-   Energising balises:
    -   27,115 MHz
    -   Amplitude modulation for clock pulses
    -   50 kHz pulse frequency
-   Data transmission to trains:
    -   4,5 MHz
    -   50 kb/s
    -   180 useful for total 256 bits
-   Linking:
    -   All permanent balises are linked
    -   Temporary balises may not be linked
-   Train characteristics are input by the driver:
    -   Maximum train speed
    -   Train braking characteristics
    -   Train length
    -   Train weight
    -   Possibility to use higher speeds in curves
    -   Train specific properties (e.g. retardation because of heavy axle load)
    -   Surface conditions
-   Displays to the driver:
    -   By speedometer:
        -   permitted speed
        -   target speed
    -   By numeric display:
        -   distance to target point
    -   By alphanumeric display with audible warning :
        -   over speed — alarm
        -   brake — alarm
        -   brake more — alarm
        -   ATP breaking
        -   brake release permitted
        -   passing signal with stop — aspect
        -   next signal ‘expect danger’ and supervision speed to the signal
        -   target point beyond two or three blocks
        -   switch as target point
        -   speed restriction as target point
        -   reserved track
        -   faults in way side or vehicle equipment
        -   can be checked from system: e.g. retardation, brake-pipe pressure, speed, information received from last balises
-   Supervisions:  
    General: All information about signals, switches and speed limitations is transferred to 2 400 or 3 600 m (depends on maximum line speed) distance from target point. System calculates brake curves to every target point and indicates the most restrictive information to driver:
    -   Maximum line speed or maximum train speed
    -   ‘Expect danger’ beyond two to three blocks
    -   Supervision speed at signal with stop aspect
    -   Speed restriction
    -   Speed restriction in curves for traditional train and train with tilting body
    -   Train specific restrictions
    -   Speed restrictions in switches
    -   Speed after switch
    -   Authorised passing of signal at stop, 50 km/h supervised until next main signal
    -   Speed after balise fault
-   Other functions:
    -   Shunting
    -   Roll away protection
    -   Slip compensation
-   Reaction:
    -   Supervision of speed limit: audible warning at 3 km/h over-speed (higher speeds: at 5 km/h over-speed), service brake 5 km/h after warning.
    -   Supervision of target point: System calculates brake curves which functions are audible prompt to apply brake, continuous audible prompt to apply more brake and service brake by system. Driver can release the service brake when speed is within limits. System will brake sufficiently regardless of driver action.
    -   Emergency brake applied by system if permitted speed exceeded by 15 km/h, by passing emergency brake curve or service brake is out of order. Emergency brake can be released after train has stopped.

Responsible Member State: Finland

**BACC**

**Description:**

BACC is installed on all lines exceeding 200 km/h on the network of FS and other lines, which are most of the lines under consideration for interoperability.

The system consists of conventional coded track circuits which operate at two carrier frequencies to deal with two train classes. The on-board equipment is computerised.

The data transmission between coded track circuits and on-board equipment is via inductively coupled air coil pickup antennae above the rails.

**Main characteristics:**

-   Data transmission to trains:
    -   50 Hz carrier frequency
        -   AM modulated speed codes
        -   five speed codes
    -   78 Hz carrier frequency
        -   AM modulated speed codes
        -   four additional speed codes
-   Two possible train categories on board (Speed code from wayside)
-   Display to driver:
    -   Speed corresponding to speed code
    -   Signal aspect (one out of 10)
-   Supervision:
    -   Speed (continuous)
    -   Stopping point
-   Reaction:  
    Emergency brake in case of overspeed

Responsible Member State: Italy

**CAWS AND ATP**

(installed on Iarnród Éireann)

The system consists of coded track circuits and on-board equipment. Transmission of code is via pick up coils mounted on front of train over each rail.

Coded track circuits are installed on all high density Dublin suburban routes and on Intercity routes to Cork, Limerick, Athlone and as far as border with UK towards Belfast.

The diesel powered fleet is fitted with continuous automatic warning system equipment. Included are trains from UK operating into Ireland on a daily basis. This translates the received coded signal into a signal colour indication which is displayed to the driver.

The electric powered fleet is fitted with automatic train protection equipment. This translates the received coded signal into a maximum speed which is displayed to the driver. The electric fleet operates only in Dublin suburban electrified area.

**Main characteristics: (Dublin suburban electrified area)**

-   83 1/3 Hz carrier frequency.
-   pulsed square wave codes 50, 75, 120, 180, 270 and 420 CPM. Translated by ATP as 29 km/h, 30 km/h, 50 km/h, 50 km/h, 75 km/h, 100 km/h. Translated by CAWS as yellow, green, yellow, green, double yellow, green.
-   Permitted speeds are also based on signal aspect being displayed. Speeds limit is reduced to zero in steps approaching a red signal

**Main characteristics: (outside Dublin suburban electrified area)**

-   50 Hz carrier frequency
-   Three pulsed square wave codes 50, 120 and 180 CPM. Translated by CAWS as yellow, double yellow, green

**Automatic train protection**

-   Display to driver:
    -   Current permitted speed. Continuously updated to reflect changes in signal aspects ahead.
    -   Continuous audible tone to indicated overspeed
    -   Momentary tone to indicate increase in permitted speed
    -   Intermittent tone to indicate running release selected
    -   test function when stationary.
-   Characteristics input by driver:
    -   Running release to permit movement in sidings and up to Red signals.
-   Supervision:
    -   Continuous speed monitoring.
-   Reaction:
    -   If the permitted speed is exceeded or a lower speed code is received, a service brake application occurs until the permitted speed is achieved and the driver has acknowledged the overspeed by moving the power controller into coast or brake. Failure to do so maintains the brake application.

**Continuous automatic warning system**

-   Display to driver:
    -   Aspect in lineside signal last passed until about 350 metres from signal ahead then aspect of signal ahead. Continuously updated to reflect changes in signal aspects ahead.
    -   Continuous audible tone to indicate more restrictive aspect indication received until acknowledged.
    -   Momentary audible ‘warble’ to indicate less restrictive aspect received.
    -   Test function when stationary.
    -   Carrier selected.
-   Characteristics input by driver:
    -   Carrier frequency.
    -   Disable red aspect display when outside coded track circuit areas.
-   Supervision:
    -   Acknowledgement of change to more restrictive aspect. Once acknowledged — no supervision of train until another change to more restrictive aspect.
-   Reaction:
    -   The driver must acknowledge a change to a more restrictive signal aspect within seven seconds otherwise an emergency brake application occurs for one minute. This is not recoverable until the time has expired. Train should be at a stand within one minute.

Responsible Member State: Ireland

**Crocodile**

**Description:**

Crocodile is installed on all major lines of SNCF, SNCB and CFL. On all lines under consideration for Interoperability crocodile is found.

The system is based on an iron bar in the track which is physically contacted by a brush on-board the train. The bar carries a tension of +/- 20  V from a battery depending on the signal aspect. There is an indication to the driver and the driver has to acknowledge the warning. If not acknowledged, an automatic brake action is triggered. Crocodile does not supervise any speed or distance. It only acts as a vigilance system.

The track-side and on-board units are of conventional design.

**Main characteristics:**

-   DC-powered bar (± 20 V)
-   No train characteristics on-board
-   Supervision:  
    Acknowledgement by driver
-   Reaction:  
    The emergency brake is called if the warning is not acknowledged. The emergency brake can be released after standstill.

Responsible Member States: Belgium, France, Luxembourg

**Ebicab**

Ebicab exists in two versions: Ebicab 700 and Ebicab 900.

**Description of Ebicab 700:**

Fail safe standard ATP system in Sweden, Norway, Portugal and Bulgaria. Identical software in Sweden and Norway enables cross-border trains without changing drivers or locomotives despite different signal systems and rules. Different software in Portugal and Bulgaria.

The system consists of track side, balises and signal encoders or serial communication with electronic interlocking, and on-board computerised equipment.

The data transmission is between passive track side balises (two to five per signal) and an on-board antenna underneath the vehicle which also supplies the balise with energy when passing. The coupling between balise and on-board is inductive.

**Main characteristics:**

-   Energising Balises:
    -   27,115 MHz
    -   Amplitude modulation for clock pulses
    -   50 kHz pulse frequency
-   Data transmission to trains:
    -   4,5 MHz
    -   50 kb/s
    -   12 useful bits of total 32 bits
-   Linking
    -   Signals are linked
    -   Boards, e.g. warning and speed boards are not necessarily linked, 50 % unlinked balises are acceptable for fail safety
-   Train characteristics can be input by the driver:
    -   Maximum train speed
    -   Train length
    -   Train braking characteristics
    -   Specific properties of train for either allowing over-speeding or enforcing slow driving on specific sections
    -   Surface conditions
-   Displays to the driver:
    -   Maximum line speed
    -   Target speed
    -   Advanced information on secondary targets for distance-to-go signalling or speed step signalling, five blocks may be supervised
    -   Speed restrictions beyond first signal.
    -   Time to service brake intervention, three warnings
    -   Faults in way side or vehicle equipment
    -   Value of last retardation
    -   Brake pipe pressure and current speed
    -   Information in last passed balise
    -   Auxiliary information
-   Supervision:
    -   Line speed, depending on over-speeding track capability and vehicle performance or enforcement of low speed for specific trains
    -   Multiple targets including signal information without optical signals
    -   Permanent, temporary and emergency speed restrictions may be implemented with unlinked balises
    -   Stopping point
    -   Dynamic brake profile
    -   Level crossing and land slide detector status
    -   Shunting
    -   Roll away protection
    -   Slip compensation
    -   Authorised passing signal at stop, 40 km/h is supervised until the next main signal
-   Reaction:  
    Audible warning when >5 km/h, service brake when >10 km/h over-speed. The service brake can be released by the driver when speed is within limits. Ebicab will brake sufficiently regardless of driver action. The emergency brake is only used in a real emergency e.g. where service braking is not sufficient. Release of emergency brake can occur when train is stationary.
-   Implemented options
    -   Radio block system with ‘ETCS Level 3 like’ functionality
    -   Train to track communication

Responsible Member States: Portugal, Sweden

**Description of Ebicab 900:**

The system consists of track side, balises and signal encoders or serial communication with electronic interlocking, and on-board computerised equipment.

The data transmission is between passive track side balises (two to four per signal) and an on-board antenna underneath the vehicle which also supplies the balise with energy when passing. The coupling between balise and on-board is inductive.

**Main characteristics:**

-   Energising balises:
-   27 MHz
-   Amplitude modulation for clock pulses
-   50 kHz pulse frequency
-   Data transmission to trains:
    -   4,5 MHz
    -   50 kb/s
    -   255 bits
-   Linking:
    -   Signals are linked
    -   Boards, e.g. warning and speed boards are not necessarily linked, 50 % unlinked balises are acceptable for fail safety
-   Train characteristics can be input by the driver:
    -   Train identification
    -   Maximum train speed
    -   Train length
    -   Train braking characteristics
    -   Train speed type (only if the train speed is in 140-300)
    -   Train pressurisation
-   Displays to the driver:
    -   Limit speed
    -   Target speed
    -   Overspeed
    -   Efficacy
    -   ASFA Alarm
    -   Brake rearmament
    -   Running past allowed
    -   END
    -   Audible warning
    -   Braking pre-warning
    -   Red Indicator
    -   Alphanumeric display
-   Supervision:
    -   Line speed, depending on over-speeding track capability and vehicle performance or enforcement of low speed for specific trains
    -   Multiple targets including signal information without optical signals
    -   Permanent, temporary and emergency speed restrictions may be implemented with unlinked balises
    -   Stopping point
    -   Dynamic brake profile
    -   Level crossing and land slide detector status
    -   Shunting
    -   Roll away protection
    -   Slip compensation
    -   Authorised passing signal at stop, 40 km/h is supervised until the next main signal
-   Reaction:
    Audible warning when >3 km/h, service brake when >5 km/h over-speed. The service brake can be released by the driver when speed is within limits. Ebicab will brake sufficiently regardless of driver action.

Responsible Member State: Spain

**EVM**

**Description:**

EVM is installed on all main lines on the network of Hungarian State Railways (MÁV). These lines are under consideration for interoperability. The major part of locomotive fleet is equipped.

The track-side part of the system consists of coded track circuits which operate one carrier frequency for information transmission. The carrier frequency is coded by 100 % amplitude modulation m using electronic encoder.

The data transmission between coded track circuits and on-board equipment is via inductively coupled air coil pickup antennae above the rails.

**Main characteristics:**

-   Data transmission track to trains:
    -   75 Hz carrier frequency
    -   Amplitude modulated codes (100 %)
    -   Seven codes (six speed codes)
-   Display to driver:
    -   Cab signal
    -   Signal aspects: Stop, permitted speed at the next signal (15, 40, 80, 120, MAX), no transmission/failure, shunting mode
-   Supervision:
    -   Speed limit
    -   vigilance check every 1 550 m in case of vactual &lt; vtarget,
    -   vigilance check every 200 m in case of vactual > vtarget
    -   Stop aspect
    -   shunting mode speed limitation
-   Reaction:
    -   The emergency brake is triggered:
        -   in the case of driver reaction missing
        -   if the speed limit is still exceeded after vigilance signal or
        -   in case a stop signal being passed with a speed exceeding 15 km/h
        -   in shunting mode immediately after exceeding 40 km/h (the brake is activated in this case without any acoustic signal)
-   Additional functions:
    -   Roll away protection
    -   Comfort function (indication that the signal has been cleared when train is stationary)

Responsible Member State: Hungary

**GW ATP SCHEME**

**Description:**

The GW ATP is an automatic train protection (ATP) system used in the UK on the Great Western (GW) lines between London (Paddington), Bristol Temple Meads, Bristol Parkway and Newbury. The system is based on similar hardware to the TBL system used in Belgium, although there are some differences both technically and in operation.

The system is only relevant for trains which run with a speed higher than 160 km/h.

The system provides the following core functions:

-   Full automatic train protection where the train is fitted and operating over fitted infrastructure
-   Vehicle maximum speed supervision and roll-away protection where the train is fitted and operating over unfitted infrastructure

Data is transmitted from the track-side by beacons located adjacent to signals. Infill loops are provided where necessary to improve operational performance.

**Main characteristics**

-   Data transmission to the trains:
    -   100 kHz ± 10 kHz (FSK)
    -   25 kbit/sec
    -   99 useful bits per telegram
-   Train characteristics as input by the driver:
    -   Train characteristics in terms of e.g. basic braking rates, maximum speed are set by a pre-programmed parameter plug fitted to the train hardware. Variations in train make-up and brake availability can be set by the driver at start-up.
-   Driver interface:
    -   Visual indications:
        -   The maximum safe speed
        -   The target speed
        -   The expected status of the next approaching signal
        -   Presence of Emergency Speed Restrictions
        -   Fault indications
        -   Roll away
        -   Intervention activation
        -   Shunting operation mode
        -   Pass stop signal mode
        -   Signal passed at danger
        -   Subsidiary signal passed (authorised movement onto an occupied line)
    -   Audible indications:
        -   Short advisory tone whenever the displayed information changes
        -   Continuous warning tone when the safe speed is being exceeded, or an emergency speed restriction has been encountered, or when a signal is passed at danger, or roll away is detected or a system fault is detected
    -   Driver controls:
        -   On button/indicator
        -   Acknowledge button to regain control following system intervention
        -   Shunting mode activation button
        -   Pass Stop Signal button for passing a signal at danger under authority
        -   Isolation controls
-   Supervision:
    -   The system supervises train movements using following parameters:
        -   Maximum safe speed (line speed and permanent speed restrictions)
        -   Temporary speed restrictions
        -   Stopping point
        -   Dynamic braking profile
        -   Direction of movement (including roll-away supervision)
    -   The system initiates a full service brake application if:
        -   The indicated safe maximum speed is exceeded by a set margin and the driver fails to respond to the audible warning
        -   An emergency speed restriction is encountered
        -   A recoverable system fault occurs, e.g. failure to receive data from a track-side beacon when expected
    -   The ATP system initiates an emergency brake application if:
        -   The train passes a signal at danger (the train is brought to a stand, and the driver can then proceed in partial supervision, but is limited to 20 mph for 3 minutes or until the next beacon is passed)
        -   Roll away occurs (i.e. a movement of more than 10 metres or at more than 5 mph in a direction not corresponding to the position of the master controller)
        -   A non-recoverable system failure occurs

Responsible Member State: United Kingdom

**INDUSI/PZB**

(Induktive Zugsicherung/Punktförmige Zugbeeinflussung)

**Description:**

ATP system which is installed on lines in Austria and Germany under consideration for Interoperability.

Magnetically coupled resonant circuits track-side and on-board transmit 1 out of 3 information to the train. The system is not considered fail safe, but safe enough to supervise the driver. It acts completely in background mode, that means that is does not give the driver any indications about signal aspects, it only indicates that the train is supervised.

**Main Characteristics:**

-   Three frequencies
    -   500 Hz
    -   1 000 Hz
    -   2 000 Hz
-   Train characteristics can be input by the driver:  
    Braking characteristics (braking percentage and braking regime for three supervision categories)
-   Supervision:
    -   Hardware version (not for Germany):
        -   500 Hz: Immediate speed supervision
        -   1 000 Hz: Acknowledgement of restrictive signal aspect, speed supervision depends on type of train
        -   2 000 Hz: Immediate stop
    -   Microprocessor version:
        -   500 Hz: Immediate speed supervision and following braking curve supervision
        -   1 000 Hz: Acknowledgement of restrictive signal aspect, speed supervision depends on program with different braking curves, supervision by means of time and speed values for a limited distance; braking curves (over time and distance) triggered by 1 000 Hz, additionally over distance triggered by 500 Hz
        -   2 000 Hz: Immediate stop
-   Reaction:  
    The emergency brake is called if supervision is violated. The emergency brake can be released under special conditions.

Responsible Member States: Austria, Germany

**KVB**

**Description:**

Standard ATP system in France on the network of SNCF. All electrified conventional lines are sprinkled with, for speed supervision, protection of dangerous points, and temporary speed restrictions. Implemented as 99 % on conventional lines. Partially installed on high speed lines for spot transmission and for supervision of temporary speed restrictions when speed levels are not provided by the TVM codes.

The system consists of track-side balises including signal encoders and on-board computerised equipment. The system is an overlay system to conventional signalling equipment.

The data transmission is between passive track-side balises (two to nine per signal) and an on-board antenna underneath the vehicle which also supplies the balise with energy when passing. The coupling between balise and on-board is inductive. This data transmission is also used for spot information not related to ATP (e.g. doors, radio channels).

Moreover, the kVB can be completed by a continuous transmission, to allow in-fill functionality (like Euroloop):

The in-fill is realised with a continuous transmission. This is done by a shift frequency modulation (FSK) with two carriers Fp at 20 kHz and 25 kHz (one for each track). The data to transmit are of binary type, in groups of 80 bits (64 are useful). An in-fill message needs three elements of 80 bits, successively transmitted. This is a so-called ‘long’ message.

The transmission of a bit set to ‘1’ is made b the emission of the frequency Fp + 692 Hz, the transmission of one bit set to ‘0’ is made by the emission of the frequency Fp — 750 Hz.

**Characteristics:**

-   Energising balises:
    -   27,115 MHz
    -   Amplitude modulation for clock pulses
    -   50 kHz pulse frequency
-   Data transmission to trains:
    -   4,5 MHz
    -   50 kbit/sec
    -   12 useful bits (total 4x8 bits) type analogue
    -   172 useful bits (total 256 bits) type digital
-   Except for trainsets, train characteristics must be input by the driver:
    -   Train category
    -   Maximum train speed
    -   Train length
    -   Train braking characteristics
-   Displays to the driver:
    -   State of speed supervision
    -   Release speed

In the last version of the kVB, only are provided indications for approaching a danger signal with a short overlap (000), the ‘b’ and ‘p’ for the preannounce. The speed indications are in no way provided.

-   Supervision:
    -   Line speed, including permanent and temporary speed restrictions
    -   Stopping point
    -   Dynamic brake profile
    -   Speed restrictions  
        The kVB controls the shunting and the transitions to some other systems (TVM), takes actions on the radio channels switching, on the opening of the circuit breaker, the lowering of the pantographs, the side selection for doors opening, the selection for the height of the steps, the command of air tightness through tunnels or across areas with chemical risk. Moreover, the kVB can be completed by a continuous transmission to allow infill functions (like Euroloop).
-   Reaction:  
    Warning of the driver. The emergency brake is called if movement supervision is violated. Release of the emergency brake is possible only when the train is stationary.

Responsible Member State: France

**LS**

**Description:**

LS is installed on all main lines on the network of Czech Railways (CD) and Railways of Slovak Republic (ZSR) and on other lines with a speed exceeding 100 km/h. These lines are under consideration for interoperability.

The track-side part of the system consists of coded track circuits which operate one carrier frequency. The carrier frequency is coded by 100 % amplitude modulation. Almost entire fleet of locomotives is equipped by the on-board equipment. The on-board part of the system has been upgraded and so the equipment is partly computerised.

The data transmission between coded track circuits and on-board equipment is via inductively coupled air coil pickup antennae above the rails.

**Main characteristics:**

-   Data transmission to trains:
    -   75 Hz carrier frequency
        -   AM modulated codes
        -   four speed codes (including stop aspect)
-   Display to driver:
    -   Cab signal
    -   Signal aspects: stop, limited speed, caution (speed limit 100 km/h), full speed
-   Supervision:
    -   Speed limit/may be overridden by vigilance control
    -   no distance supervision
-   Reaction:  
    Emergency brake in case of missing driver reaction if speed limit is received

Responsible Member States: Czech Republic, Slovak Republic

**LZB**

**(Linienförmige Zugbeeinflussung)**

**Description:**

ATC system which is installed on all lines in Germany exceeding 160 km/hr, which are significant parts of the lines under consideration for Interoperability. LZB is also installed on lines in Austria and Spain.

The system consists of a track-side part, which again has the building parts:

-   Adaptation to interlocking systems and respective data transmission
-   Data processing and MMI in LZB-centre
-   Data transmission to and from other LZB-centres
-   Data transmission system to and from trains

The on-board equipment normally has an integrated Indusi function.

The data transmission between track-side and on-board is via track-side inductive cable loop and on-board ferrite antennae.

**Main characteristics:**

-   Data transmission to trains:
    -   36 kHz ± 0,4 kHz (FSK)
    -   1 200 bit/sec
    -   83,5 steps per telegram
-   Data transmission from trains:
    -   56 kHz ± 0,2 kHz (FSK)
    -   600 bit/sec
    -   41 Steps per telegram
-   Train characteristics can be input by the driver:
    -   Train length
    -   Maximum train speed
    -   Train braking characteristics (braking percentage and braking regime)
-   Displays to the driver:
    -   Valid operating mode, status of data transmission
    -   Maximum permitted speed/actual speed on a two pointer speedometer
    -   Target speed
    -   Distance to target
    -   Auxiliary indications
-   Supervision:
    -   Line speed (maximum speed, temporary and permanent speed limitations)
    -   Maximum train speed
    -   Stopping point
    -   Direction of movement
    -   Dynamic speed profile
    -   Auxiliary functions, e.g. lowering of pantograph (see Annex C).
-   Reaction:  
    The emergency brake is called if the movement supervision is violated. The emergency brake can be released in case of over-speed when speed is within limits.
-   LZB operating rules:  
    DB uses the system as fully safety-relevant Automatic Train Control, wayside signals are not required; in the case when wayside signals exist because of non-equipped trains, these signals are not valid for LZB-guided trains. LZB is typically connected with automatic motor and brake control.

Responsible Member States: Austria, Germany, Spain

**MEMOR II+**

**Description:**

The ATP system, which is installed on all lines of the Luxembourg railway network, is used for the protection of dangerous points and temporary speed restrictions. The MEMOR II+ is complementary to the Crocodile system.

The system is based on respectively two iron bars in the track, which are physically contacted by brushes installed on board of the trains. The bars carry a tension of +/- 12 to +/- 20V depending on the signal aspect. The system is not considered fail safe, but safe enough to supervise the driver. It acts completely in background mode, that means that it doesn't give any indications to the driver about signal aspects, it only indicates that the train is supervised.

**Main characteristics:**

-   Trackside DC powered bars (± 12 to ± 20 V)
-   On board, no input of train characteristics by the driver, only one predefined speed curve stored on board.
-   Supervision:
    -   In case of caution signals or signals indicating speed restrictions, one positive trigger starts speed supervision, supervision of time and speed values for a certain distance compared to the stored speed curve.
    -   In case of absolute stop signals, two positive triggers within a distance of 11 metres act an emergency brake.
-   Reaction:
    -   The emergency brake is called if supervision is violated (no valid reaction from the driver).
    -   The emergency brake can be released after standstill.
-   Displays to the driver:
    -   State of supervision.
    -   State of emergency brake.

**Outlook:**

The Luxembourg railway infrastructure network is being equipped with ECTS level I. The stepwise putting into service of ECTS will replace the MEMOR II and the crocodile system. This requests a transition period to adapt the engine side systems to ETCS. Finally the ECTS level I system will be the only valid system in use on the Luxembourg railway infrastructure network.

Responsible Member State: Luxembourg

**RETB**

**Description:**

Radio electronic token block (RETB) is a signalling system used on a small number of lightly used lines in the UK within the scope of the conventional interoperability directive (three lines in Scotland and one in Wales).

The system provides the following core functions:

-   Issuing of movement authorities from the signalling control centre to trains by means of electronic tokens, sent by radio to the train-borne equipment
-   Display of the movement authority to the driver
-   Surrendering the movement authority token when the train has completed the authorised movement

The RETB system is operated in conjunction with procedures for the driver-signaller communications protocol, which are applied when requesting, issuing and surrendering the movement authority tokens.

RETB does not include train protection functionality (therefore there is no interface between the train's RETB equipment and the braking system). However, train protection against overruns is provided by standard TPWS equipment, described elsewhere in Annex B. The train-borne TPWS equipment includes AWS functionality (also described in Annex B), which provides audible and visual indications to the driver on the approach to the limit of a movement authority and on the approach to speed restrictions.

**Train-borne equipment**

The train-borne equipment comprises the radio equipment and the RETB cab display unit (CDU).

**Radio equipment**

The radio system used for transmission of the movement authority tokens is a variant of the NRN system that is used in the UK (described elsewhere in Annex B). The radio equipment is used for both voice and data purposes.

**Cab display unit (CDU)**

The CDU comprises:

-   a key switch for switching the train-borne equipment into operational mode
-   a ‘receive’ button for receiving movement authority tokens from the control centre in order that a train movement can be made
-   an alphanumeric display, which displays the name of the section of line for which a movement authority token has been issued
-   a ‘send’ button for returning the movement authority token to the control centre when the train has completed its movement

The train must also be fitted with TPWS equipment (also including AWS functionality), for the purposes described above, but there is no interface between the TPWS and RETB equipment on the train.

Responsible Member State: United Kingdom

**RSDD/SCMT**

**(Ripetizione segnali discontinua digitale/sistema controllo marcia del treno)**

**Description:**

RSDD/SCMT is an ATP system; it can be used alone or superimposed on the BACC infrastructure.

The on-board equipment is able to manage in a coordinated way information coming from the different sources.

The system consists of track-side balises and encoders, and an on-board antenna which also supplies the balise with energy when passing. The coupling is inductive.

From the logical point of view, two kinds of balises exist: system balises containing information on the line ahead, and signalling balises containing information on the signals aspect.

Three types of balises are foreseen, all using the same frequencies for up- and downlink, but with different capacity:

-   Energising frequency:
    -   27,115 MHz
-   Data transmission to trains:
    -   4,5 MHz
    -   12/180 bit ASK Modulation
    -   1 023 bit FSK Modulation
-   Train characteristics:  
    Fixed train characteristics are loaded in maintenance facilities, while data depending on train composition are inserted by the driver. Special balises are used to calibrate the on board odometer system, before it can be used for train supervision purpose.
-   Displays to the driver:
    -   Maximum permitted speed
    -   Target speed
    -   Actual train speed
    -   Advanced information on secondary targets
    -   Warnings before emergency brake intervention
    -   Auxiliary information
-   Supervision:  
    In normal condition (full supervision) the train controls the following characteristics:
    -   Line speed, depending on over-speeding track capability and vehicle performances
    -   Permanent and temporary speed restriction
    -   Level Crossing
    -   Stopping point
    -   Dynamic brake profile
    -   Shunting  
        If one or more characteristics of line cannot be sent to the on board system (e.g. fault) it is possible to use the system in partial supervision. In this case the MMI is switched off and the driver has to drive according to line side signals.
-   Reactions:
    -   Service brake
    -   Emergency brake

Responsible Member State: Italy

**SELCAB**

**Description:**

ATC system which is installed on the high speed line Madrid-Seville as an extension of LZB in station areas. The on-board equipment LZB 80 (Spain) can also process SELCAB information.

The data transmission between track-side and on-board is via semi-continuous track-side inductive loop and on-board ferrite antennae.

**Main characteristics:**

-   Data transmission to trains:
    -   36 kHz ± 0,4 kHz (FSK)
    -   1 200 bit/sec
    -   83,5 steps per telegram
-   Train characteristics can be input by the driver:
    -   Train length
    -   Maximum train speed
    -   Train braking characteristics
-   Displays to the driver:
    -   Maximum permitted speed/actual speed as two pointer speedometer
    -   Target speed
    -   Distance to target
    -   Auxiliary indications
-   Supervision:
    -   Line speed
    -   Stopping point
    -   Direction of movement
    -   Dynamic brake profile
    -   Speed restrictions
-   Reaction:  
    The emergency brake is called if the movement supervision is violated. The emergency brake in the case of over-speed can be released when the speed is within limits.

Responsible Member States: Spain

**SHP**

Samoczynne Hamowanie Pociągu

**Description:**

AWS system, which is installed in Poland on lines under consideration for Interoperability.

Magnetically coupled resonant circuits track-side and on-board transmit information to the train. The system is considered fail safe. It is integrated with on-board active vigilance system. The vigilance system is also protecting against uncontrolled vehicle movement (sliding) with speed above 10 % of the vehicle maximal allowed speed. It acts completely in background mode, that means that it does not give the driver any indications about signal aspects, it only indicates that the train is supervised.

**Main characteristics:**

-   Frequency:
    -   1 000 Hz
-   Supervision:
    -   1 000 Hz: Acknowledgement of a signal
-   Resonant circuit location:
    -   200 m before line signals and station entrance signals
    -   0 m before (at) station exit signals

**Reaction:**

On-board signal lamp is activated, when train is passing resonant circuit (mounted track-side), requesting driver confirmation. If confirmation is not received within 3 seconds, an acoustic signal is activated. If confirmation is not received within 2 seconds after acoustic signal activation, system initiates emergency brake. The emergency brake can be released under special conditions.

The active vigilance system is activated when vehicle speed exceeds 10 % of vehicle maximal allowed speed. After 16 seconds signal lamp is activated and driver confirmation is required with the same timing as in SHP function. Then confirmation is required after each 60 seconds. The SHP supervision is retriggering 60 second vigilance check period.

Responsible Member State: Poland

**TBL 1/2/3**

**Description:**

TBL is an ATC system partially installed on lines of NMBS/SNCB (presently: 1 200 beacons and 120 train-borne equipment TBL1, 200 beacons and 300 train-borne equipment TBL2, all lines for speeds higher than 160 km/h equipped with TBL2)

The system consists of a track-side balise at each signal and an on-board equipment. The TBL1 is a warning system, TBL2/3 is a cab signal system. For TBL2/3, there are in-fill balises, and an infill cable loop is also available.

The track-side part is designated TBL2 in case of interface to relay interlockings, and TBL3 in case of serial interface to electronic interlocking.

The train-borne equipment is called TBL2. It includes the TBL2, the TBL1 and the crocodile functions.

The data transmission is between the active balise and a set of air coil antennae on-board. The system is direction sensitive, the balises are mounted between the rails with a small offset from the centre.

**Main characteristics:**

-   Data transmission to trains:
    -   100 kHz ± 10 kHz (FSK)
    -   25 kbit/sec
    -   119 useful bits per telegram for TBL2/3
    -   Five useful decimal data on 40 bits per telegram for TBL1
-   Train characteristics as input by the driver (TBL2):
    -   Train length
    -   Maximum train speed
    -   Train braking characteristics (brake weight, type of train, isolations, other specific parameters)
    -   Language selection, identification parameters
-   Displays to the driver:
    -   Maximum speed (braking curve)
    -   Target speed
    -   Target distance
    -   Train speed
    -   Operating mode
    -   Auxiliary indications
-   Supervision:
    -   Line speed
    -   Speed restrictions (permanent and temporary)
    -   Specific restrictions for freight and other trains
    -   Stopping point
    -   Dynamic braking profile
    -   Direction of movement
    -   Vigilance of the driver
    -   Auxiliary functions (pantograph, radio commutation)
-   Reaction:
    -   Acoustic and optical warnings
    -   The emergency brake is called when the movement supervision is violated or the driver does not acknowledge the warning.

Responsible Member States: Belgium

**TPWS**

**Description:**

TPWS is to improve safety, principally at junctions. It includes the functionality of AWS, shown in italics. TPWS applies to all lines considered to be interoperable.

The system assures the following functions:

-   Warning to the driver at standard braking distance of the following restrictive conditions:
    -   Signals not at clear
    -   Permanent speed restrictions
    -   Temporary speed restrictions
-   Train protection (pre-determined train characteristics) under the following circumstances:
    -   Train exceeding permitted line speed at specified speed restrictions (speed trap)
    -   Train approaching a stop signal at excess speed (one or more speed traps)
    -   Train passing a signal at danger (train stop).

The system is based on permanent magnets and coils generating fields in the track. The system is not considered failsafe, but incorporates measures and principles to reduce the probability of misleading the driver as low as reasonably practicable.

The TPWS indicates visually to the driver:

-   The state of the last magnet, clear or restrictive (the ‘sunflower’ indicator).
-   That it is the cause of a brake application.
-   Its fault/isolation status.

The TPWS controls are:

-   An acknowledgement button for the warning of a restrictive condition.
-   A button to pass a signal at danger valid only for a limited time after operation.
-   Isolation controls.

The TPWS audio indications are:

-   A bell tone — signal at clear.
-   A horn tone — restrictive condition, that must be acknowledged.

The TPWS system interfaces to the train brake system and provides a full emergency brake application if:

-   the horn tone is not acknowledged within 2,5 seconds.
-   Immediately the train passes the speed trap at excess speed.
-   Immediately if the train passes a signal at danger.

The technology is not processor based, but this is not excluded.

**Other characteristics:**

-   Sequence of magnetic fields (north pole, south pole) to provide details of signal clear or not clear.
-   One of a selection of sinusoidal electromagnetic fields in the region of 60 kHz for the speed trap and train stop functions (up to eight frequencies used).
-   Train characteristics in terms of braking capacity are set by train wiring and give different maximum speeds at speed traps. No train characteristics input presently in service, but can be envisaged.
-   Driver acknowledgement of a restrictive condition required within 2,5 seconds, otherwise the emergency brakes are called.
-   The emergency brake is releasable one minute after the brake has been applied provided the brake demand has also been acknowledged.

Responsible Member State: United Kingdom

**TVM**

**Description:**

TVM is a cab signalling control-command system. It is especially dedicated to the high speed lines of SNCF. The older version TVM 300 is installed on the line Paris-Lyon (LGV SE) and Paris-Tours/Le Mans (LGV A) lines. The later version TVM 430 on the line Paris-Lille-Calais (LGV N), on the SNCB part towards Brussels, on the line Lyon-Marseilles/Nimes (LGV Mediterranée), through the Eurotunnel and on the Channel Tunnel Rail Link in the UK. TVM 430 is compatible with TVM 300.

TVM 300 and TVM 430 are based on coded track circuits as continuous transmission means and inductive loops or balises (KVB or TBL type) as spot transmission means.

The data transmission between coded track circuits and on-board equipment is via inductively coupled air coil pickup antennae above the rails.

**Main characteristics:**

-   Data transmission to trains via track circuits:
    -   various carrier frequencies (1,7; 2,0; 2,3; 2.6) kHz
    -   FSK modulated speed codes
    -   18 speed codes (TVM 300)
    -   27 bits (TVM 430)
-   Data transmission to trains via inductive loops:
    -   TVM 300: 14 frequencies (1,3 to 3,8 kHz)
    -   TVM 430: PSK modulated signal, 125 kHz, 170 bits
-   Train characteristics on board introduced on locomotives for hauled trains in Eurotunnel (not on TGV, where fixed values are used)
-   Display to driver:  
    Speed orders associated to colour light aspects
-   Supervision:
    -   Speed (continuous)
    -   Braking triggering based on
        -   stepping curve for TVM 300
        -   parabolic curve for TVM 430
    -   Stopping point
-   Reaction:  
    The emergency brake is called in the case of overspeed.

Responsible Member States: Belgium, France, United Kingdom

**ZUB 123**

**Description:**

ATC system which is installed extensively on lines in Denmark under consideration for Interoperability.

The system consists of the following parts:

-   Track-side equipment:
    -   A track coupling coil (transponder), which is mounted outside the rails
    -   In certain locations loops are used for in-fill purpose
    -   A signal interface board which scans and derives the information to be transmitted
-   On-board equipment:
    -   The on-board unit with processing logic and receiving/transmitting equipment. It acts through a brake interface unit on the brakes
    -   The vehicle coupling coil, mounted on the bogie, which receives data from the line
    -   The axle mounted odometer pulse generator which supplies information for the distance covered and the actual speed
    -   The cab display and operating panel

The ZUB 123 on-board equipment is considered fail safe.

**Main characteristics:**

-   Three frequencies:
    -   50 kHz checking channel
    -   100 kHz energy channel
    -   850 kHz data channel
-   Data transmission modes:
    -   Time-division multiplex for serial transmission of telegrams with up to 96 useful bits.
-   On-board data processing:
    -   Vital computer processing (enhanced performance level)
-   Display to the driver:
    -   Maximum authorised speed
    -   Actual speed
    -   Target speed
    -   Target distance
    -   Auxiliary indicators and buttons
-   Train data input:
    -   Encoder panel, or
    -   Directly into the on-board unit
-   Supervision:
    -   Line speed
    -   Stopping point
    -   Speed restrictions
    -   Dynamic brake profile
-   Reaction:
    -   The emergency brake is called if the movement supervision is violated.
    -   The emergency brake in the case of over-speed can be released when the speed is within a defined value limit

Responsible Member State: Denmark

**ZUB 121**

**(For information only)**

**Description:**

ATC system which is installed extensively in Switzerland on lines by SBB and BLS under consideration for Interoperability.

The system consists of the following parts:

-   Line equipment:
    -   determine travel direction to be influenced
    -   A track coupling coil (transponder), which is mounted inside the rails, lying off centre to coupling loop, which is mounted inside the rails, laying off centre. A previous coupling coil determines travel direction to be influenced by the following loop.
    -   A signal interface board which scans and derives the information to be transmitted. (Not fail-safe)
-   On-board equipment:
    -   The on-board unit with processing logic and receiving/transmitting equipment. It acts through a brake interface unit on the brakes
    -   The vehicle coupling coil, mounted on the bogie, which receives data from the line. (With our equipment only transmission track to train possible)
    -   The axle mounted odometer pulse generator, which supplies information for the distance covered, actual speed and driving direction
    -   The cab display and operating panel
    -   An input/output interface to the train-borne radio unit or the integrated train-borne information system (IBIS) to exchange vehicle data entered by the train driver

**Characteristics:**

-   Three frequencies:
    -   50 kHz checking channel
    -   100 kHz energy channel
    -   850 kHz data channel
-   Data transmission modes:
    -   Time-division multiplex for serial transmission of telegrams with up to 104 usable data bits.
    -   On-board data processing: (Not fail-safe)
    -   Single computer processing (supplementary performance level)
-   Display to the driver:
    -   One four-digit LCD showing:
        -   ‘8 — — 8’; no monitoring or
        -   ‘8 8 8 8’; monitoring the maximum train speed or
        -   ‘— — — —’; monitoring the maximum authorised line speed or
        -   ‘ 6 0’; target speed or
        -   ‘ / / / / ’; information ‘proceed’ received by a loop
-   Lamps and horn:
    -   Emergency brake applied
    -   Equipment failure
-   Buttons:
    -   Testing button
    -   Emergency stop reset
    -   Release button (together with ‘Signum’ release button)
-   Train data input:  
    Train-borne radio operating panel is used
-   Supervision/Commands:
    -   Line speed
    -   Stopping point
    -   Speed restrictions
    -   Dynamic brake profile
    -   Control of radio channels
-   Reaction:
    -   The emergency brake is called if the threshold speed is reached
    -   Abort speed monitoring if movement supervision is violated

Responsible State: Switzerland

## Part 2: Radio

INDEX:

1.  UIC Radio Chapter 1-41. UIC Radio Chapter 1-4+6
2.  UIC Radio Chapter 1- 4 + 6 (Irish system)
3.  UIC Radio Chapter 1-4+6+7  
    Introduction to UK systems
4.  BR 1845
5.  BR 1609
6.  FS ETACS and GSM
7.  UIC Radio Chapter 1-4 (TTT radio system installed at Cascais line)
8.  TTT radio system CP_N
9.  PKP radio system
10. VR trainr
11. TRS — The Czech Railways radio system
12. LDZ radio system
13. CH — Greek Railways radio system
14. The Estonian radio system
15. The Lithuanian radio system

These systems are currently in use in Member States. For detailed information reference has to be made to the Register of Infrastructure as defined in Annex C.

For information only, systems not used in Member States:

15. UIC Radio Chapter Bulgaria

**UIC Radio Chapter 1-4**

**Description:**

This ground-to-train radio follows the technical regulations described in UIC code 751-3, Third Edition, 1 July 1984. It is a minimum subset necessary for international railway traffic.

The UIC radio is an analogue radio, which consists of lineside and mobile (train-borne) equipment.

Radio systems following this basic subset allow for simplex and duplex voice communication and use of operating signals (tones), but not for selective calls and for data transmission:

**Main characteristics:**

-   Frequencies:
    -   Train to ground:..
        457,450 MHz ..458,450 MHz
    -   Ground to train:
        -   Band A: 467,400 MHz ..468,450 MHz
        -   Band B: 447,400 MHz ..448,450 MHz (only to be used when band A is not available)
    -   Frequency spacing 25 kHz
    -   Duplex frequency couples 10 MHz apart
    -   Grouping of four channels, preferred 62 ... 65 for international traffic
    -   Agreement on frequencies used bilateral or multilateral
-   Sensitivity:
    -   > 1 μV at > 20 dB signal to noise ratio (mobile)
    -   > 2 μV (lineside)
-   Radiating power:
    -   6 W mobile
    -   6 W lineside
-   Antenna characteristics:
    -   λ/4 omnidirectional (mobile)
    -   4 m above rail (mobile)
    -   omnidirectional or directional (lineside)
    -   In tunnels leaky cables or very directional aerials (lineside)
    -   Terminating resistor 50 Ohms
-   Polarisation:
    -   Vertical
    -   In tunnels, any polarisation
-   Frequency deviation:
    -   &lt; 1,75 kHz for operating tone
    -   &lt; 2,25 kHz for voice
-   Modes of operation:
    -   Mode 1, duplex mode
    -   Mode 2, semiduplex mode
-   Switchover of channels on-board:
    -   manually by input of channel number
    -   automatic, depending on receiver voltage
-   Operating tones:

|                 |          |
| --------------- | -------- |
| - Channel free: | 2 280 Hz |
| - Listening:    | 1 960 Hz |
| - Pilot:        | 2 800 Hz |
| - Warning:      | 1 520 Hz |

Responsible Member States: France, Germany, Hungary, Luxembourg

**UIC Radio Chapter 1- 4 + 6**

**Description:**

This ground-to-train radio follows the technical regulations described in UIC code 751-3, Third Edition, 1 July 1984.

The UIC radio is an analogue radio, which consists of lineside and mobile (train-borne) equipment.

Radio systems following this basic subset allow for simplex and duplex voice communication and use of operating signals (tones), and for selective calls and for data transmission:

**Main characteristics:**

-   Frequencies:
    -   Train to ground:  
        457,450 MHz ..458,450 MHz.
    -   Ground to train:
        -   Band A: 467,400 MHz ..468,450 MHz.
        -   Band B: 447,400 MHz ..448,450 MHz (only to be used when band A is not available).
    -   Frequency spacing 25 kHz
    -   Duplex frequency couples 10 MHz apart
    -   Grouping of four channels, preferred 62 ... 65 for international traffic
    -   Agreement on frequencies used bilateral or multilateral
-   Sensitivity:
    -   > 1 μV at > 20 dB signal to noise ratio (mobile)
    -   > 2 μV (lineside)
-   Radiating power:
    -   6 W mobile
    -   6 W lineside
-   Antenna characteristics:
    -   λ/4 omnidirectional (mobile)
    -   4 m above rail (mobile)
    -   Omnidirectional or directional (lineside)
    -   In tunnels leaky cables or very directional aerials (lineside)
    -   Terminating resistor 50 Ohms
-   Polarisation:
    -   Vertical
    -   In tunnels, any polarisation
-   Frequency deviation:
    -   &lt; 1,75 kHz for operating tone
    -   &lt; 2,25 kHz for voice
-   Modes of operation:
    -   Mode 1, duplex mode
    -   Mode 2, semiduplex mode
-   Switchover of channels on-board
    -   manually by input of channel number
    -   automatic, depending on receiver voltage
-   Operating tones:

|                 |          |
| --------------- | -------- |
| - Channel free: | 2 280 Hz |
| - Listening:    | 1 960 Hz |
| - Pilot:        | 2 800 Hz |
| - Warning:      | 1 520 Hz |

-   Telegram structure:
    -   Sync. header: 1111 1111 0010 
    -   Six decimal train number BCD coded
    -   Two positions of information four bits each
    -   Seven bit redundancy code, polynomial: 1110 000 1 (H=4)
-   Telegram transmission:
    -   600 bits/sec
    -   FSK, ‘0’ = 1 700 Hz, ‘1’ = 1 300 Hz
-   Messages (coding given in hexadecimal representation)

    -   Lineside to train:

|                               |     |
| ----------------------------- | --- |
| - Speech                      | 08  |
| - Emergency stop              | 09  |
| - Test                        | 00  |
| - Run faster                  | 04  |
| - Run slower                  | 02  |
| - Announcement by loudspeaker | 0C  |
| - Written order               | 06  |
| - Extension of telegram       | 03  |

-   Train to lineside:

|                                   |     |
| --------------------------------- | --- |
| - Communication desired           | 08  |
| - Acknowledgement of order        | 0A  |
| - Advice                          | 06  |
| - Test                            | 00  |
| - Train staff wish to communicate | 09  |
| - Telephone link desired          | 0C  |
| - Extension of telegram           | 03  |

Responsible Member States: Austria, Belgium, Denmark, Germany, Netherlands, Spain

**UIC Radio Chapter 1- 4 + 6 (Irish system)**

**Description:**

This ground-to-train radio follows the technical regulations described in UIC code 751-3, Third Edition, 1 July 1984.

The UIC radio is an analogue radio, which consists of lineside and mobile (train-borne) equipment.

Radio systems following this basic subset allow for simplex and duplex voice communication and use of operating signals (tones), and for selective calls and for data transmission:

**Main characteristics:**

-   Frequencies:
    -   Train to ground:  
        461,675 MHz ..461,950 MHz.
    -   Ground to train:  
        456,175 MHz ..456,450 MHz.
    -   Frequency spacing 25 kHz
    -   Duplex frequency couples 5,5 MHz apart
    -   Grouping of four channels
-   Sensitivity:
    -   > 1 μV at > 20 dB signal to noise ratio (mobile)
    -   > 2 μV (lineside)
-   Radiating power:
    -   10 W mobile
    -   10 W lineside
-   Antenna characteristics:
    -   λ/4 omnidirectional (mobile)
    -   4 m above rail (mobile)
    -   Omnidirectional or directional (lineside)
    -   In tunnels leaky cables or very directional aerials (lineside)
    -   Terminating resistor 50 Ohms
-   Polarisation:
    -   Vertical
    -   In tunnels, any polarisation
-   Frequency deviation:
    -   &lt; 1,75 kHz for operating tone
    -   &lt; 2,25 kHz for voice
-   Modes of operation:
    -   Mode A, duplex mode for voice and data transmission
    -   Mode B, duplex mode for voice only transmission
    -   Mode C, simplex mode for voice only transmission
-   Switchover of channels onboard
    -   manually by input of channel number
    -   automatic, depending on receiver voltage
-   Operating tones:

|                        |          |
| ---------------------- | -------- |
| - Line free tone:      | 2 280 Hz |
| - General Call tone:   | 1 960 Hz |
| - Pilot tone:          | 2 800 Hz |
| - Emergency Call tone: | 1 520 Hz |

-   Telegram structure:
    -   Sync. header: 1111 1111 0010
    -   Six decimal train number BCD coded
    -   Two positions of information 4 bits each
    -   Seven bit redundancy code, polynomial: 1110 000 1 (H=4)
-   Telegram transmission:
    -   600 bits/sec
    -   FSK, ‘0’ = 1 700 Hz, ‘1’ = 1 300 Hz
-   Messages:
    -   Lineside to train:
        -   CTC to driver
        -   Hot Box
        -   Instruction No 9 (used for remote PA on Class 8100 EMU's)
        -   Stop at next signal
        -   Stop at next station
        -   Instruction No 5 (currently unused)
        -   Instruction No 6 (currently unused)
        -   Instruction No 7 (currently unused)
        -   Danger stop
        -   Test
    -   Train to lineside:
        -   Test
        -   Driver
        -   Guard
        -   Regulator (PABX)
        -   Obstruction on line
        -   Acknowledge
        -   Ready to start
        -   By pass
        -   Running release
        -   Reserved message 1
        -   Reserved message 2
        -   Emergency call
        -   Mode B call

Responsible Member States: Ireland, Hungary

For information only: the same radio system is used in Norway

**UIC Radio Chapter 1- 4 + 6 + 7**

**Description:**

This ground-to-train radio follows the technical regulations described in UIC code 751-3, 3rd edition, 1 July 1984. Chapter 7 edition of 1 January 1988.

The UIC radio is an analogue radio, which consists of lineside and mobile (train-borne) equipment.

Radio systems following this basic subset allow for simplex and duplex voice communication and use of operating signals (tones), and for selective calls and for data transmission. The data transmission capabilities are extended. This feature is not considered mandatory in the UIC leaflet. If it cannot be assured by bilateral or multilateral agreement, it should be used on a national basis only.

**Main characteristics:**

-   Frequencies:
    -   Train to ground:  
        457,450 MHz ..458,450 MHz
    -   Ground to train:
        -   Band A: 467,400 MHz ..468,450 MHz
        -   Band B: 447,400 MHz ..448,450 MHz (only to be used when band A is not available)
    -   Frequency spacing 25 kHz
    -   Duplex frequency couples 10 MHz apart
    -   Grouping of 4 channels, preferred 62 ... 65 for international traffic
    -   Agreement on frequencies used bilateral or multilateral
-   Sensitivity:
    -   > 1 μV at > 20 dB signal to noise ratio (mobile)
    -   > 2 μV (lineside)
-   Radiating power:
    -   6 W mobile
    -   6 W lineside
-   Antenna characteristics:
    -   λ/4 omnidirectional (mobile)
    -   4 m above rail (mobile)
    -   Omnidirectional or directional (lineside)
    -   In tunnels leaky cables or very directional aerials (lineside)
    -   Terminating resistor 50 Ohms
-   Polarisation:
    -   Vertical
    -   In tunnels, any polarisation
    -   Frequency deviation:
    -   &lt; 1,75 kHz for operating tone
    -   &lt; 2,25 kHz for voice
-   Modes of operation:
    -   Mode 1, duplex mode
    -   Mode 2, semiduplex mode
    -   Switchover of channels on-board
    -   manually by input of channel number
    -   automatic, depending on receiver voltage
-   Operating tones:

|                 |          |
| --------------- | -------- |
| - Channel free: | 2 280 Hz |
| - Listening:    | 1 960 Hz |
| - Pilot:        | 2 800 Hz |
| - Warning:      | 1 520 Hz |

-   Telegram structure:
    -   Sync. header: 1111 1111 0010
    -   Six decimal train number BCD coded
    -   Two positions of information 4 bits each
    -   Seven bit redundancy code, polynomial: 1110 000 1 (H=4)
-   Telegram transmission:
    -   600 bits/sec
    -   FSK, ‘0’ = 1 700 Hz, ‘1’ = 1 300 Hz
-   Messages (coding given in hexadecimal representation)
    -   Lineside to train:

|                               |     |
| ----------------------------- | --- |
| - Speech                      | 08  |
| - Emergency stop              | 09  |
| - Test                        | 00  |
| - Run faster                  | 04  |
| - Run slower                  | 02  |
| - Announcement by loudspeaker | 0C  |
| - Written order               | 06  |
| - Extension of telegram       | 03  |

-   Train to lineside:

|                                   |     |
| --------------------------------- | --- |
| - Communication desired           | 08  |
| - Acknowledgement of order        | 0A  |
| - Advice                          | 06  |
| - Test                            | 00  |
| - Train staff wish to communicate | 09  |
| - Telephone link desired          | 0C  |
| - Extension of telegram           | 03  |

-   Extension of telegram (only if requested by code 03)
    -   Radiotelephone system with simultaneous digital message transmission
        -   Duplex exchange of voice information
        -   Duplex exchange of data messages of any length
        -   Simplex exchange of voice information between mobiles in the same radio section
        -   Speech-data time-division multiplexing (mobile to lineside):
            -   260 msec data transmission
            -   780 msec compressed speech
        -   HDLC frame structure according to ISO for data transmission (lineside to mobile)
        -   1 200 bit/sec
        -   FSK, ‘0’ = 1 800 Hz, ‘1’ = 1 200 Hz

Responsible Member State: France

**Introduction to UK Systems**

The system called NRN (National Radio Network) is installed over the whole of the UK rail network including the high-speed lines which are the backbone of the UK high-speed network. These consist of:

-   West Coast Main Line (London-Glasgow)
-   East Coast Main Line (London-Edinburgh)
-   Great Western Main Line (London-Bristol/South Wales)

The system called cab secure is installed in high traffic suburban areas around London, Liverpool and Glasgow, some of which may include lines forming part of the high-speed network. In addition, all main lines in the south-east, including the existing Channel Tunnel Route from the coast to London (Waterloo), are equipped with the Cab Secure system.

Mainline passenger trains and freight trains are fitted with NRN whilst suburban and some intermediate traffic equipped with CSR. In general trains are only equipped with one form of radio but a few trains that travel in areas of both NRN and CSR is equipped with both forms of radio. This in particular applies to trains which are equipped with CSR but spend parts of their operating cycle outside the CSR infrastructure area.

**BR 1845 Issues G and H (lineside)**

**BR 1661 Issue A (train-borne)**

**Commonly called cab secure Radio**

**Description:**

This ground-to-train radio follows the technical regulations described in Railtrack Specifications (BR Specification 1845 Issues G and H and in BR 1661 Issue A).

The cab secure radio is an analogue radio, which consists of lineside and mobile (train-borne) equipment.

Radio systems following this basic subset allow for duplex voice communication and use of operating signals (tones), and for selective calls and for data transmission.

**Main characteristics:**

-   Frequencies:
    -   Train to ground:  
        448,34375 ..448,48125 MHz  
        (Note: There are additional channels for which the information is to be obtained)
    -   Ground-to-train:  
        454,84375 MHz ..454,98125 MHz
    -   Frequency spacing 12,5 kHz
    -   Duplex frequency couples 6,5 MHz apart
    -   Agreement on frequencies used bilateral or multilateral
-   Sensitivity:
    -   1 μV at > 20 dB signal to noise ratio (mobile)
    -   &lt;2 μV (lineside)
-   Radiating power:
    -   10 W mobile
    -   10 W lineside
-   Antenna characteristics:
    -   λ/4 omnidirectional (mobile)
    -   4 m above rail (mobile)
    -   Omnidirectional or directional (lineside)
    -   In tunnels leaky cables or very directional aerials (lineside)
    -   Terminating resistor 50 Ohms
-   Polarisation:
    -   Vertical
    -   In tunnels, horizontal
-   Frequency deviation:
    -   300 Hz for CTCSS tones
    -   1,5 kHz for data transmission
    -   1,75 kHz for emergency tone
    -   &lt; 2,5 kHz for voice
-   Modes of operation:
    -   Mode 1, duplex mode
-   Switchover of channels on-board
    -   manually by input of channel number
    -   automatic, depending on message sent from control centre
-   Operating tones:

|                   |                   |
| ----------------- | ----------------- |
| - CTCSS:          | X, Y, Z, 203,5 Hz |
| - Emergency call: | 1 520 Hz          |

-   Telegram structure:
    -   Sync. header: 0010001111101011
    -   Information elements:
        -   Signalling telegrams (three bytes):
            -   Message Type (system free, system busy, general call, emergency acknowledged, etc.)
            -   Area code
            -   Channel number
        -   Data telegrams (eight bytes):
            -   Message Type (system free, system busy, general call, emergency acknowledged, etc.)
            -   Area Code
            -   Channel number plus train number in five decimal character or four alphanumeric character BCD coded format, or signal number (three bytes).
            -   Train Stock number (six digits) (three bytes)
    -   seven bit redundancy code, polynomial: 110011011 (H=4)
-   Telegram transmission:
    -   1 200 bits/sec
    -   FFSK, ‘0’ = 1 800 Hz, ‘1’ = 1 200 Hz
-   Messages (coding given in hexadecimal representation)
    -   Lineside to train:  

|                               |     |
| ----------------------------- | --- |
| - Test                        | 00  |
| - Speech                      | 02  |
| - Announcement by loudspeaker | 04  |
| - Wait at signal              | 06  |
| - Emergency stop              | 0A  |
| - Change area, system free    | 0C  |
| - Change area, system busy    | 0E  |

-   Train to lineside:

|                         |     |
| ----------------------- | --- |
| - Test                  | 80  |
| - Communication desired | 82  |
| - Set up signal number  | 84  |
| - Emergency answer      | 86  |
| - Busy                  | 88  |
| - Cancel call           | 90  |
| - DSD alarm             | 96  |

Responsible Member State: United Kingdom

**BR 1609 Issue 2**

Commonly called National Radio Network (NRN)

**Description:**

This ground-to-train radio follows the technical regulations described in Railtrack Specification BR 1609, Issue 2, August 1987.

The National Radio Network is an analogue radio which consists of lineside and mobile (train-borne) equipment.

Radio systems following this basic subset allow for duplex voice communication (lineside), simplex voice communication (train-borne), broadcast mode and use of operating signals (tones), for selective calls and for data transmission.

**Main characteristics:**

-   Frequencies: Subband 2 of the 174 MHz to 225 MHz band
    -   196,85 to 198,3 MHz train-to-ground
    -   204,85 to 206,3 MHz ground-to-train
    -   Frequency spacing 12,5 kHz
    -   Duplex frequency couples 8,0 MHz apart
    -   Not all the frequencies within the bands indicated are used
-   Sensitivity:
    -   &lt; 0,6 μV at 12 dB signal to noise ratio (mobile)
    -   &lt; 0,3 μV at 12 dB signal to noise ratio (lineside)
-   Radiating power:
    -   > 25 W mobile
    -   > 25 W lineside
-   Antenna characteristics:
    -   λ/4 Omnidirectional (mobile)
    -   4 m above rail (mobile)
    -   Omnidirectional or directional (lineside)
    -   Terminating resistor 50 Ohms
    -   No coverage in tunnels
-   Polarisation:
    -   Vertical
-   Modes of operation:
    -   Duplex mode (fixed to fixed)
    -   Simplex mode (fixed to mobile)
    -   Switchover of channels on-board
    -   Manual input of common signalling channel. Most journeys in the UK are within one area and the driver enters it at the start of the journey.
    -   Automatic change to voice channel following a message sent from control centre.
-   Audio frequency range:
    -   300 Hz ... 2 500 Hz for speech
-   Frequency deviation:
    -   &lt; 2,5 kHz
-   Message transmission:
    -   1 200 bits/sec
    -   FFSK, ‘0’ = 1 800 Hz, ‘1’ = 1 200 Hz
-   Message structure:
    -   Data modulation for all RF signalling shall conform to MPT1323 Section 6, with message formats generally as defined in MPT1327
-   Message types from a train:
    -   Complete number required. It will contain the identity of the radio. It is sent once after receipt of a ‘channel free’ telegram
    -   Clear-down
    -   PTT telegram which is sent each time the transmitter is keyed. It gives the identity of the radio
    -   Auto-reply telegram when the radio is selectively called. It contains the identity of the radio
    -   Emergency call. It contains the identity of the radio. It does not require receipt of a free telegram
    -   Priority call
-   Message types to a train:
    -   Selective calling telegram. This initiates an auto-reply telegram
    -   Channel free telegram.
    -   Go to channel telegram. This directs the radio to a particular channel, opens the loudspeaker and sounds an alert tone
    -   Clear-down telegram. This clears the call, closes the loudspeaker and returns the radio to the call set-up channel
    -   Call fail telegram. This is the same as clear-down but also indicates call failure to the user.
    -   General call telegram. This is a special version of the go to channel instruction

Responsible Member State: United Kingdom

**FS ETACS and GSM**

**Description:**

The solution for radio train to ground communication working today at FS is primarily based on the use of services supplied by the public operator on the analogue (ETACS) and the digital (GSM) mobile cellular networks in the 900 MHz band. These networks have been implemented with an external subsystem, developed by the operator together with FS in order to manage some special features as requested by FS, related for example to:

-   addressing of train and station calls through functional numbers in place of the terminal number;
-   closed group features with specific barring conditions;
-   configuration and handling of specialised data bases directly by FS people to characterise access rights to services for each kind of users, and so on.

Thanks to the wide radio coverage supplied by the two public cellular systems on the FS railway network, the general train to ground communication needs can be satisfied in this way.

The additional features were negotiated and implemented by FS in cooperation with the public service provider. They are implemented in highly reliable distributed computer systems. They are therefore part of the application layer in the ISO/OSI layer model.

Responsible Member State: Italy

**UIC Radio Chapter 1-4 (TTT radio system installed at Cascais line)**

**Description:**

This ground-to-train radio follows the technical regulations described in UIC code 751-3, 3Third Edition, 1 July 1984. It is a minimum subset necessary for international railway traffic.

The UIC radio is an analogue radio, which consists of lineside and mobile (train-borne) equipment.

Radio systems following this basic subset allow for simplex and half-duplex voice communication and use of operating signals (tones), but not for selective calls and for data transmission:

**Main characteristics:**

-   Frequencies:
    -   Train-to-ground:  
        457,700 MHz ..457,800 MHz
    -   Ground to train:  
        Band A: 467,625 MHz . 467,875 MHz
    -   Frequency spacing 12,5 kHz
    -   Duplex frequency couples 10 MHz apart
    -   Grouping of four channels, preferred 62; 63; 73 and 75 for international traffic
-   Sensitivity:
    -   > 1  mV at > 20 dB signal to noise ratio (mobile)
    -   > 2  mV (lineside)
-   Radiating power:
    -   6 W mobile
    -   6 W lineside
-   Antenna characteristics:
    -   λ/4 omnidirectional (mobile)
    -   4 m above rail (mobile)
    -   Omnidirectional or directional (lineside)
    -   In tunnels leaky cables or helical antennas (lineside)
    -   Terminating resistor 50 Ohms
-   Polarisation:
    -   Vertical
    -   In tunnels, any polarisation
-   Frequency deviation:
    -   0,9 \* 0,05 kHz for operating tone
    -   &lt; 2,3 kHz for voice
-   Modes of operation:
    -   Mode 1, half-duplex mode
    -   Mode 1, simplex mode
-   Switchover of channels on-board:
    -   manually by input of group number
    -   automatic inside the group, depending on receiver voltage
-   Operating tones:

|                 |          |
| --------------- | -------- |
| - Channel free: | 2 280 Hz |
| - Listening:    | 1 960 Hz |
| - Pilot:        | 2 800 Hz |
| - Warning:      | 1 520 Hz |

Responsible Member State: Portugal

**TTT radio system CP_N**

**Description:**

This TTT radio system is a tailored one, designed for voice and data communications and according CP requirements.

The CP_N radio is an analogue radio, which consists of lineside and mobile (train-borne) equipment.

Radio system use digital selective call (according MPT 1327 — 1 200 bit/s FFSK) and 50 baud subaudio FSK for base station signalling.

The radio allows simplex and half-duplex voice communication and half-duplex for selective calls and for data transmission.

**Main characteristics:**

-   Frequencies:
    -   Train-to-ground:  
        457,700 MHz ..457,800 MHz
    -   Ground to train:  
        Band A: 467,625 MHz . 467,875 MHz
    -   Frequency spacing 12,5 kHz
    -   Duplex frequency couples 10 MHz apart
    -   Grouping of four channels, preferred 62; 63; 73 and 75 for international traffic
-   Sensitivity:
    -   1  mV at > 20 dB signal to noise ratio (mobile)
    -   2  mV (lineside)
-   Radiating power:
    -   6 W mobile
    -   6 W lineside
-   Antenna characteristics:
    -   λ/4 omnidirectional (mobile)
    -   4 m above rail (mobile)
    -   Omnidirectional or directional (lineside)
    -   In tunnels leaky cables or helical antennas (lineside)
    -   Terminating resistor 50 Ohms
-   Polarisation:
    -   Vertical
    -   In tunnels, any polarisation
-   RF Modulation:
    -   Radiomodem 1 200 b/s, FM
    -   Radiomodem (Tx only) 50 baud subaudio, FM
    -   Voice in PM
-   Frequency deviation:
    -   1,75 kHz for FFSK (1 200 bit/s)
    -   0,3 kHz for FSK (50 baud)
    -   &lt; 2,3 kHz for voice
-   Modes of operation:
    -   Mode 1, half-duplex mode
    -   Mode 1, simplex mode
-   Switchover of channels on-board:
    -   manually by input of group number
    -   automatic inside the group, depending on receiver voltage
-   Telegram structure:
    -   According MPT 1327
-   Telegram transmission:
    -   1 200 bits/sec
    -   FFSK, ‘0’ = 1 800 Hz, ‘1’ = 1 200 Hz

Responsible Member State: Portugal

**The PKP radio system**

**Description:**

Radio system, which is installed in Poland on lines under consideration for Interoperability.

The PKP 150 MHz band radio is an analogue radio, which consists of track-side, on-board and handheld equipment.

Radio system allow for simplex voice communication and use of operating signals (tones) for selective calls and generally not for data transmission. The system has an integrated radiostop function.

**Main characteristics:**

-   Frequencies:
    -   Train-to-ground and ground-to-train: 150 MHz ... 156 MHz
    -   Frequency spacing: 25 kHz (to be changed to 12,5 kHz)
-   Sensitivity:
    -   > 0,8 μV at > 20 dB signal to noise ratio
-   Radiating power:
    -   6 W (track-side and on-board)
-   Antenna characteristics:
    -   λ/4 omnidirectional (on-board)
    -   λ/2 omnidirectional (track-side)
    -   In tunnels leaky cables (track-side)
    -   Terminating resistor 50 Ohms
-   Polarisation:
    -   Vertical
    -   In tunnels, any polarisation
-   Modes of operation:
    -   Simplex mode
-   Switchover of channels:
    -   Manually by input of channel number
-   Audio frequency range:
    -   300 Hz ... 3 000 Hz for voice (to be reduced below 2 700 Hz when introducing 12,5 kHz spacing)
-   Selective call operating tones:

|                                           |               |
| ----------------------------------------- | ------------- |
| - Trains (vehicles), odd number:          | f1 = 1 160 Hz |
| - Trains (vehicles), even number:         | f2 = 1 400 Hz |
| - Track-side (permanent operating posts): | f3 = 1 670 Hz |

-   Frequency deviation:
    -   &lt; 5 kHz for voice
-   Selective group call:
    -   single operating tone longer than 1 second
-   Radiostop function:
    -   can be activated by pressing single button (sealed) both track-side and on-board,
    -   causes vehicle emergency braking (if activated on-board) and sending continuous sequence of 3x100 ms f1, f2 and f3 operating tones followed by 500 ms space,
    -   initiates vehicle emergency braking if the sequence (f1, f2 and f3) is received twice,
    -   is using valve in brake pneumatic system mounted in a second pneumatic channel (first channel is used by SHP AWS and vigilance system).
-   Network equipped with automatic recording posts
    -   data transmission limited to equipment identification number

Responsible Member State: Poland

**VR Train Radio**

Commonly called Linjaradio (Finnish meaning line radio).

Description:

This ground-to-train radio is a tailored VHF radio system and follows the technical regulations in Finnish Railways.

The line radio network is an analogue radio which consists of lineside and mobile (train-borne) equipment.

Radio systems following this basic subset allow for duplex voice communication (between lineside and train), semi-duplex voice communication (between drivers), and driver calls to controller by selective call tones.

**Main characteristics:**

-   Frequencies:
    -   Grouping of three channels (numbers 1-3)
    -   Train to ground:
        -   172,350 MHz ..173,100 MHz
    -   Ground-to-train:
        -   167,700 MHz ..168,500 MHz
    -   Frequency spacing 25 kHz
    -   Duplex frequency couples 4,50 MHz or 4,65 MHz apart
-   Sensitivity:
    -   > 1 μV at > 20 dB signal to noise ratio (mobile)
    -   > 2 μV (lineside)
-   Radiating power:
    -   15 W mobile
    -   10 W lineside
-   Antenna characteristics:
    -   λ/4 omnidirectional (mobile)
    -   4 m above rail (mobile)
    -   Omnidirectional or directional (lineside)
    -   In tunnels leaky cables or very directional aerials (lineside)
    -   Terminating resistor 50 Ohms
-   Polarisation:
    -   Vertical
    -   In tunnels, any polarisation
-   Frequency deviation:
    -   &lt; 1,75 kHz for operating tone
    -   &lt; 3,0 kHz for voice
-   Modes of operation:
    -   Mode 1, duplex mode (driver-controller)
    -   Mode 2, semi-duplex mode (driver-driver)
-   Switchover of channels on-board
    -   manually by input of channel number
    -   automatic inside the group, depending on receiver voltage
-   Operating tones:
    -   None
-   Selective call tones:
    -   2 500 Hz, 2 900 Hz

Responsible Member State: Finland

**TRS — The Czech Railways radio system**

**Description:**

Railway radio communication system TRS is designed for the operational duplex communication between the running engine driver and a dispatcher or a signaller by means of the ribbon network along the track.

The system TRS enables duplex communication for conversation, routine information (commands, reports), general call and emergency call transmission and semiduplex communication between drivers by means of the retransmission in the base station reach, namely conversation and emergency call transmission. The system concept enables creating the special outfitting set which can operate in the simplex network on frequencies in band 160 MHz for simplex communication of engine drivers and other subscribers on a beforehand selected channel.

Selective calling with the train six-digits number shall be transmitted in the direction dispatcher (signaller) to driver, identification (by the train number) shall be transmitted in the direction train — dispatcher (signaller).

Routine information (commands and reports) transmission is realised by means of a telegram. System TRS is outfitted with the digital transmission in the coded form of a short telegram FFSK 1 200 bps in both directions. One of commands is assigned to the train remote stop that can be activated by a dispatcher or a signaller and causes vehicle emergency braking (if an adapter to ATP type LS 90 or driver vigilance equipment is present on-board).

System TRS is fully compatible at the control signals level in accordance with mandatory recommendation UIC 751-3. It means it is possible to accomplish the conversation, general calling and emergency call among the TRS and systems manufactured by other producers. Communication is accomplished on four internationally co-ordinated frequencies in the band 450 MHz range A according to UIC.

**Main characteristics:**

-   Frequencies:
    -   Operating mode: Duplex on groups of four frequencies  
        Simplex in band 457,400 — 458,450 MHz
-   Sensitivity:
    -   150  mV
-   Radiating power:
    -   6 W
-   Modes of operation:
    -   Mode 1, duplex mode
    -   Mode 2, semiduplex mode
-   Operating tones:

|                 |          |
| --------------- | -------- |
| - Channel free: | 2 280 Hz |
| - Listening:    | 1 960 Hz |
| - Pilot:        | 2 800 Hz |
| - Warning:      | 1 520 Hz |

Responsible State: Czech Republic

**The LDZ radio system**

**Description:**

The train radio system (TRS) is an analogue simplex voice communication and used for operative train operation. All sections of LDZ network are equipped with this system.

The TRS is designed with use of track-side (distributive radio-sets (DRS), and up to 28 local radio-sets (LRS), connected to each other by a two-wires communication channel) and mobile (on-board radio-sets (BRS) and handheld radio-sets (HRS)) equipment.

Six frequencies in the band of 1 000 — 1 700 Hz are used for selective connection of 28 LRS's.

**Main Characteristics:**

-   Frequencies:

|                                        |                         |
| -------------------------------------- | ----------------------- |
| - Train-to-ground and ground to train: | 2 130 kHz — basic,      |
|                                        | 2 150 kHz — subsidiary, |

-   Sensitivity:
    -   ≤ 50 μkV at 20 dB signal to noise ratio
-   Radiating power:
    -   ≤ 12 W (track-side and on-board)
-   Antenna characteristics:
    -   λ/4 omnidirectional (track-side)
    -   λ/12 omnidirectional (on-board)
    -   Terminating resistor 50 or 75 Ohms depending on radio-set type.
-   Polarisation:
    -   Vertical
-   Modes of operation:
    -   simplex mode
-   Switchover of channels:
    -   manually by mechanical switching
-   Audio frequency range:
    -   300 Hz ... 3 000 Hz for voice, selective calls, operating signals
-   Selective call operating tones:

|                                         |               |
| --------------------------------------- | ------------- |
| - BRS — LRS                             | f1 = 1 400 Hz |
| - BRS — DRS                             | f2 = 700 Hz   |
| - BRS — HRS (maintenance, movable unit) | f3 = 2 100 Hz |
| - BRS — BRS                             | f4 = 1 000 Hz |
| - DRS — BRS                             | f4 = 1 000 Hz |
| - LRS — BRS                             | f3 = 1 000 Hz |

-   Transmission frequency deviation:
    -   ≤ 3 kHz ≥ 1,5 kHz for selective calls
    -   ≤ 3 kHz for voice
-   Network equipped with automatic recording posts
-   LRS antenna types:
    -   Г — mode
    -   Inclined ray
    -   Inductive powering of open-wired power supply lines (not steel wires)
    -   Specific handling of high voltage power supply lines (10 kV)
    -   Specific wave guide

Besides the TRS, there is used an intra-station radio-communication system, which includes shunting, maintenance-technological and special communication for emergency conditions. This system is designed based on zone principle and works in the ranges of 150 and 450 MHz in bands about 5 — 10 MHz.

Responsible Member State: Latvia

**CH — Greek Railways radio system**

**Description:**

This ground-to-train radio system partially follows the technical regulations prescribed in UIC code 751-3, Third Edition, 1 July 1984. It is a minimum subset necessary for national railway traffic. It is an analogue system supporting half-duplex voice communication. Selective calls, operating signals (tones) and data transmission have not been in use.

**Main Characteristics:**

-   Frequencies:
    -   Train-to-ground and ground-to-train :  
        149,870 — 149,970 MHz and 150,290 — 150,350 MHz  
        Frequency spacing 20 kHz.  
        10 channels have been implemented from the two above bands.
-   Sensitivity:
    -   > 1 μV at > 20 dB signal to noise ratio (train-borne)
    -   > 2 μV (lineside)
-   Radiating power:
    -   10 W (train-borne)
    -   18 W (lineside)
-   Antenna characteristics:
    -   λ/4 (train-borne)
    -   3λ/4 (lineside)
    -   Omnidirectional
    -   No coverage in tunnels
    -   Terminating resistor 50 Ohms
-   Polarisation:
    -   Vertical
-   Frequency deviation:
    -   &lt;2,3 kHz (for voice)
-   Mode of operation:
    -   Half-duplex
-   Switchover of channels on-board:
    -   Manually by input of channel number

Responsible Member State: Greece

**UIC Radio Chapter Bulgaria**

(for information only)

**Description:**

This ground-to-train radio follows the technical regulations described in UIC code 751-3, Third Edition, 1 July 1984. It is a minimum subset necessary for international railway traffic.

The UIC radio is an analogue radio, which consists of line-side and mobile (train-borne) equipment.

Radio systems following this basic subset allow for simplex and duplex voice communication and use of operating signals (tones), and for selective calls and for data transmission.

**Main characteristics:**

-   Frequencies:
    -   Train-to-ground:  
        457,450 MHz ..458,450 MHz.
    -   Ground to train:  
        Band A: 467,400 MHz ..468,450 MHz.
-   Frequency spacing: 25 kHz
-   Duplex frequency couples: 10 MHz apart
-   Grouping of four channels, preferred 62 ... 65 for international traffic
-   Sensitivity:
    -   > 2 μV (mobile)
-   Radiating power:
    -   6 W mobile
    -   6 W lineside
-   Antenna characteristics:
    -   λ/4 omnidirectional (mobile)
    -   4 m above rail (mobile)
    -   omnidirectional or directional (lineside)
-   In tunnels leaky cables or very directional aerials (lineside)
-   Terminating resistor 50 Ohms
-   Polarisation:
    -   Vertical
    -   In tunnels, any polarisation
-   Modes of operation:
    -   Mode 1, duplex mode
    -   Mode 2, semiduplex mode
-   Frequency deviation:
    -   1,75 kHz for control signal
    -   1,75 kHz for voice
    -   3,50 kHz nominal
-   Switchover of channels onboard:
    -   manually by input of channel number
    -   automatic inside the group
-   Operating signals:

|                          |          |
| ------------------------ | -------- |
| - Free channel signal:   | 2 280 Hz |
| - Listening signal:      | 1 960 Hz |
| - Pilot tone:            | 2 800 Hz |
| - Emergency signal:      | 1 520 Hz |
| - Station master signal: | 1 840 Hz |
| - Traction unit signal:  | 2 984 Hz |
| - Island signal:         | 1 669 Hz |

-   Telegram structure:
    -   Ton frequency sequence call consist of eight tone frequency elements with the following meaning:
        -   six elements of 100 ms for train No
        -   1 100 ms separating frequency
        -   one element 100 ms order or message (from TU)
        -   and with variable length 400 ms … 1 400 ms order or message (to TU)

Responsible State: Bulgaria

**Estonian Railways train communication network**

Estonian Railway's train communication network has been equipped according to the Ministry of Transport and Communication of Estonia Declaration No 39 from 9 July 1999‘Technical regulations for railway operation’.

Railways train radio communication network consists of two subsystems, namely track-to-train radio communication system and area (or regional) radio communication systems.

Track-to-train radio communication system provide voice communication with all types of trains and locomotives on main and branch lines within the country.

Area radio communication systems provide full radio coverage within operational area of railway stations for station operators and locomotive drivers.

With the integrated train radio communication network are covered all the lines and railway station around the country.

The main system for track-to-train radio communications Estonian Railways operate with SmarTrunk II decentralised (scan based) digital trunking radio communication system. This modular system contains components like dispatcher's centre equipment, site repeaters, station operator radio terminals, mobile radios on trains and portable radios.

**Trunking system main data:**

-   VHF 146-174Mhz frequency band
-   14 duplex channels
-   semi-duplex operation

On railway stations in local area communications Motorola GM350 and GM Pro series base radios operate on VHF simplex channels.

Motorola GM350 and GM160 radios on the trains can communicate with different radio infrastructures installed within the country, on main lines and in station areas.

Personnel responsible for safe and efficient railway operations have in use Motorola GP and P series portable radios.

To control rail traffic for trains coming from neighbour countries Latvia and Russia, Estonian Railways in parallel with the main communication network have still in operation special trans-regional train communication system on simplex channels 2 130 kHz and 2 150 kHz.

Responsible Member State: Estonia.

**Lithuanian Railways train radio system**

**Description:**

The train radio system (TRS) is an analogue simplex voice communication and used for operative train operation. All sections of LG network are equipped with this system.

The TRS is designed with use of track-side (distributive radio-sets (DRS)), and up to local radio-sets (LRS), connected to each other by a two-wires communication channel) and mobile (on-board radio-sets (BRS)) equipment.

Six frequencies in the band of 1 000 — 1 700 Hz are used for selective connection of LRS's.

**Main characteristics:**

-   Frequencies:

|                                        |                         |
| -------------------------------------- | ----------------------- |
| - Train to ground and ground to train: | 2 130 kHz — basic,      |
|                                        | 2 150 kHz — subsidiary, |

-   Sensitivity: 
    -   ≤ 50 μkV at 20 dB signal to noise ratio
-   Radiating power:
    -   ≤ 12 W (track-side and on-board)
-   Antenna characteristics:
    -   λ/4 omnidirectional (track-side)
    -   λ/12 omnidirectional (on-board)
-   Terminating resistor 50 or 75 Ohms depending on radio-set type.
-   Polarisation:
    -   Vertical
-   Modes of operation:
    -   simplex mode
-   Switchover of channels:
    -   manually by mechanical switching
-   Audio frequency range:
    -   300 Hz ... 3 000 Hz for voice, selective calls, operating signals
-   Selective call operating tones:

|             |               |
| ----------- | ------------- |
| - BRS — LRS | f1 = 1 400 Hz |
| - BRS — DRS | f2 = 700 Hz   |
| - BRS — BRS | f4 = 1 000 Hz |
| - DRS — BRS | f4 = 1 000 Hz |
| - LRS — BRS | f3 = 1 000 Hz |

-   Transmission frequency deviation:
    -   ≥1,5 kHz ≤ 3 kHz for selective calls
    -   ≤ 3 kHz for voice
-   Network equipped with automatic recording posts
-   LRS antenna types:
    -   Г — mode
    -   T — mode
    -   Inclined ray
    -   Inductive powering of open-wired power supply lines (not steel wires)
    -   Specific handling of high voltage power supply lines (10 kV)
    -   Specific wave guide

**Shunting radio communication system**

**Description:**

For shunting in bigger railway stations is used the simplex analogical radio communication system for voice transmission of 150 MHz diapason. Radio stations of this system are used only in local radio networks, which are not interconnected. The system allows the radio communication by open channel between stationary (traffic order operators), mobile (shunting locomotives) and portable (shunting crew) objects.

**Main characteristics:**

-   Frequencies:
    -   150,375 — 155,800 MHz and 150,290 — 150,350 MHz
-   Frequency spacing 25 kHz.
-   Sensitivity:
    -   > 1 μkV at 20 dB signal to noise ratio
-   Radiating power:
    -   ≤ 25 W (track-side)
    -   ≤ 12 W (on-board)
    -   ≤5 W (handheld)
-   Polarisation:
    -   Vertical
-   Modes of operation:
    -   simplex mode
-   Switchover of channels:
    -   manually by mechanical switching
-   Transmission frequency deviation:
    -   ≤ 3 kHz

Responsible Member State: Lithuania

## Part 3: Transition matrix between Class A and B systems (signalling)

**_PURPOSE OF THE MATRIX_**

This matrix is to provide a text concerning the scope of the transitions relevant for interoperability on the European high-speed and conventional rail networks.

**_INTRODUCTION_**

The following matrix gives an overview of the possible transitions between different Class B-systems as defined in this Annex and between Class A and Class B systems.

The matrix does not mandate any technical solutions for either the ERTMS/ETCS-system or the concerned STMs defined in this Annex. Those are documented either in the technical specifications of the control-command subsystem (referenced in Chapter 5 of both control-command TSIs for the trans-European high-speed and conventional rail systems) or in the relevant national documentation of the Class B-systems or the STMs, respectively. It is important to note that the matrix does not define any additional technical requirements for either the ERTMS/ETCS system or the STMs. The matrix provides information only about transitions that could occur on the high-speed and conventional rail networks.

The matrix can serve as a tool to assist with technical and economical decisions in the implementation of the Directives 96/48/EC and 2001/16/EC.

As far as transitions between two Class-B systems are concerned, the requirement for interoperability is that the technical solution for the transition is not in contradiction with the TSIs and, in particular, it is in line with the referenced documentation concerning the ERTMS/ETCS system. It must be stated, that the actual Class 1 specification only supports STM transitions (see SRS section 5.10 especially 5.10.3.11 and section 7.4.2.9). The operational regulation regarding transition between two Class B systems is regarded as national issue.

**_TRANSITION MATRIX_**

**How to read the matrix**

The diagonal of the matrix lists the Class A and all Class B systems relevant for the High-speed and Conventional Trans European Rail Networks.

Each field of the matrix is filled, either by a number (indicate that a transition is permissible between the systems in the column/row in which the field occurs) or by grey colour, to indicate that no transition exists, nor is any foreseen.

The number indicates the countries responsible for the specification of the transition and the associated procedures.

The transitions between the Class A and Class B systems (first column) shall be performed as described in the document SUBSET 035.

Example:

Image

**System transitions**

Where a transition is performed by ETCS STM, the terms defined in the document SUBSET-035 should be used.

**System transitions (Class A and B)**

The matrix identifies the required operational transitions. An operational transition is one in which one system takes over the responsibility for train supervision from another system. At such a transition the driver usually experiences one ore more of the following:

-   A change in the way the train movement is supervised
-   A change in how the driver interacts with the system

Image

**Member States responsible for transition**

1.  Netherlands, Belgium
2.  Italy, France
3.  Spain, Portugal
4.  Netherlands, Germany
5.  Italy, Austria
6.  France, Belgium, Luxembourg, Germany
7.  Italy, France
8.  France, Belgium, Luxembourg
9.  France Germany
10. Spain
11. Germany, Austria
12. Italy
13. Italy, France
14. Austria, Italy
15. France, Italy
16. Spain
17. Spain
18. Netherlands, Belgium
19. Belgium
20. Belgium, Germany
21. France, Belgium
22. France
23. France
24. Belgium, France
25. France, United Kingdom (Transition occurs at UK end of Channel Tunnel)
26. France
27. France
28. France
29. Denmark, Sweden
30. Germany, Denmark
31. Austria, Hungary
32. Austria, Czech Republic, Germany, Slovak Republic
33. Hungary, Slovak Republic, Czech Republic
34. France, Switzerland
35. Germany, Switzerland
36. France, Switzerland
37. United Kingdom
38. United Kingdom (only for trains with Vmax > 160 km/h)
39. Germany, Poland
40. Poland. Czech Republic, Slovak Republic
41. Ireland, United Kingdom
42. Lithuania, Poland (between ALSN and SHP)

## Part 4: Electromagnetic characteristic of train detection systems used in Member States

The electromagnetic characteristics of train detection systems used in Member States are listed here including the test specification.

Open point -

(1)  In Estonia only 50 Hz is used

# ANNEX C

**LINE SPECIFIC CHARACTERISTICS AND TRAIN SPECIFIC CHARACTERISTICS TO BE PUT IN THE REGISTERS ACCORDING TO ARTICLE 24 OF DIRECTIVE 2001/16/EC**

**General requirements**

As stated in Chapter 7, the line-specific characteristics defined in this Annex shall be included in the Register of Infrastructure by the infrastructure manager.

As stated in Chapter 7, the train-specific characteristics defined in this Annex shall be included in the Register of Rolling Stock by the railway undertaking.

As stated in section 6.2 (control-command subsystem), as a pre-condition for operating a train, the corresponding Register of Rolling Stock and Register of Infrastructure have to be cross-checked for interoperability.

Annex C deals with those aspects of the control-command assemblies which are covered neither by Annex A nor by Annex B, and with the options permitted for Class A and Class B systems and interfaces (see Annex D, Figure 8).

Information on specific conditions on RS for operation of train detection systems must be indicated in the Registers.

**Register of Infrastructure**

This TSI allows some options of equipment, functions and infrastructure-related values. In addition, where TSI requirements do not cover the whole control-command track-side assembly, special requirements in the context of existing technical systems and in particular the use of specific operational requirements are possible and are the responsibility of the infrastructure manager.

Such information concerns for example:

-   choices in the frame of technical compatibility requirements listed in Annex A,
-   choices in the frame of technical compatibility requirements listed in Annex B,
-   EMC-values (because of the use of equipment which is not covered by TSI requirements, for instance axle-counter-systems),
-   climatic conditions and physical conditions along the line.

This information has to be available for and used by the railway undertakings in the form of a line specific handbook (Register of Infrastructure) which can also contain other particularities of other TSI's (e.g. the TSI Traffic Operation and Management contains in the Rule Book Annex B systems and degraded modes)

The Register of Infrastructure may be specific to one line or a group of lines having the same characteristics.

The objective is that the requirements and characteristics stated in the Register of Infrastructure and in the Register of Rolling Stock accord with the TSIs; particularly they must not be a hindrance to interoperability.

**Register of Rolling Stock**

In the frame of this TSI, for the railway undertaking, some choices of equipment, functions and values related to the type of train are foreseen. In addition, because TSI requirements do not cover the whole control-command on-board assembly the infrastructure manager needs additional information concerning the use of Class B systems, and the characteristics of the train which are relevant for track-side non Class B systems. This information concerns, for example:

-   choices in the frame of technical compatibility requirements listed in Annex A,
-   choices in the frame of technical compatibility requirements listed in Annex B,
-   EMC-values (because of the use on the lines concerned of equipment which is not covered by TSI requirements,
-   geometric and electrical parameters of the train like length, maximal distance of axles in the train, length of the nose of the first and of the last car of the train, maximal electrical resistance between the wheels of an axle (in context with Annex A, Appendix 1 (rolling stock characteristics necessary to be compatible with train detection systems) because of the track-circuit design arrangement),
-   braking parameters for Class A system
-   braking parameters for Class B systems
-   general braking parameters
-   types of brakes
-   eddy current brake installed
-   magnetic brake installed
-   climatic conditions and physical conditions in which the train is specified to operate.

This information has to be available for and to be used by the infrastructure managers by means of a train specific handbook (Register of Rolling Stock) which can also address the possibility or the need of auxiliary functions for the train to be manageable or to be managed by control-command functions, e.g. for passage of neutral sections, speed reduction in special circumstances depending of the train and line characteristics (tunnels) and particularities of other TSIs.

The Register of Rolling Stock can be specific to one train or a category of trains having the same characteristics

**Lists of specific characteristics and requirements**

The following list is the mandatory requirement for the Register of Infrastructure and for the Register of Rolling Stock in order to describe sufficiently the specific characteristics and requirements, and to facilitate interoperability. The list deals only with technical issues, the operational issues are contained in the TSI traffic operation and management.

The requirements may be satisfied by the application of a standard. In this case, the reference concerned must be given in these handbooks.

Otherwise, any special requirements (methods of measurement) must be inserted into or appended to the Register of Rolling Stock and the Register of Infrastructure.

For Class B systems, the measures implemented in the context of the responsible Member State given in Annex B apply. The Register of Infrastructure shall include the following items:

-   responsible Member State,
-   name of Annex B subsystem,
-   version and placing into service date,
-   speed restrictions and other Class B specific conditions/requirements, due to system limitations,
-   further details according to the lists below.

List of specific technical characteristics and the requirements associated with an interoperable line and with an interoperable train

| No  | Infrastructure Register                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | Rolling Stock Register                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1.  | <ul><li>Infrastructure manager (1)</li><li>Country (1)</li><li>Line segment extremity 1 (1)</li><li>Line segment extremity 2 (1)</li></ul>For each of the different parts of the CCS track-side assembly (EIRENE functions and interfaces, ETCS/ERTMS functions and interfaces, Train detection system, Hot axle box detector, EMC) when installed in steps:<ul><li>EC verification (yes or no)</li><li>date of the certificate of conformity (display first/last one)</li><li>notified body: first/last</li><li>date of EC declaration of verification (display first/last one)</li><li>date or placing in service (display first/last one)</li><li>Comments (if no EC verification, specific cases, …)</li></ul>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | <ul><li>Keeper (1)</li><li>national number of the train set or of the vehicle (1)</li><li>if it's a train set, national number of each vehicle of the train set (1)</li></ul>For each of the different parts of the CCS on-board assembly (EIRENE functions and interfaces, ETCS/ERTMS functions and interfaces) when installed in steps:<ul><li>EC verification (yes or no)</li><li>date of the certificate of conformity of the control-command on-board assembly (display first/last one)</li><li>notified body: first/last</li><li>date of EC declaration of verification of the control-command on-board assembly (display first/last one)</li><li>date or placing in service of the control-command on-board assembly (display first/last one)</li><li>Comments (if no EC verification, specific cases, …)</li></ul> |
| 2   | <ol type="a"><li>ERTMS/ETCS level(s) of application, optional functions installed track-side and required on-board, functionality not installed track-side (e.g. shunting), national values to be used and system version number including the placing in service date of this version,</li><li>ERTMS/GSM-R radio, optional functions as specified in the FRS, and the system version number including placing in service date of this version.</li></ol>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | <ol type="a"><li>ERTMS/ETCS level of application, optional functions installed and system version number including placing in service date of this version,</li><li>ERTMS/GSMR radio, optional functions according to the FRS and system version number including placing in service date of this version.</li></ol>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| 3.  | For ERTMS/ETCS Level 1 with infill-function:<br/>which technical implementation is required of Rolling Stock                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | For ERTMS/ETCS Level 1 with infill-function:<br/>which technical implementation is used.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| 4.  | Indicate for<ol type="a"><li>each Class B train protection, control and warning system, and</li><li>each Class B radio system</li></ol>installed on the interoperable line, the versions (including period of validity of these version, and if there is a need for more than one system to be active simultaneously and the responsible Member State).                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | Indicate for<ol type="a"><li>each Class B train protection, control and warning system, and</li><li>each Class B radio system</li></ol>installed on the interoperable train, the versions (including period of validity of theses version and if there is a need of more than one system to be active simultaneously and the responsible Member State).                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| 5.  | Special technical conditions required to switch over between different Class B train protection, control and warning systems.<br/>Special technical conditions required to switch over between ERTMS/ETCS and Class B systems.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      | Special conditions implemented on-board to switch over between different Class B train protection, control and warning systems.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| 6.  | Special technical conditions required to switch over between different radio systems.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | Special conditions implemented on-board to switch over between different radio systems.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| 7.  | Technical degraded modes of:<ol type="a"><li>ERTMS/ETCS,</li><li>Class B train protection, control and warning systems,</li><li>Class B radio systems</li><li>lineside signalling.</li></ol>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        | Available technical degraded modes for:<ol type="a"><li>ERTMS/ETCS,</li><li>Class B train protection, control and warning systems,</li><li>Class B radio systems</li></ol>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| 8.  | Speed limits applied because of limited braking performance, e.g. because of braking distances available and because of gradients:<ol type="a"><li>to ERTMS/ETCS operating modes,</li><li>to Class B train protection, control and warning systems.</li></ol>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | National technical rules for operating Class B systems, relevant for the trains (e.g. requirements on braking performances, data corresponding with UIC leaflet 512 (8th edition of 1.1.79 and 2 Amendments), …).<ol type="a"><li>Speed limits related to train characteristics and to be supervised by control-command,</li><li>Braking characteristics input data for ERTMS/ETCS and Class B train protection, control and warning systems.</li></ol>                                                                                                                                                                                                                                                                                                                                                                    |
| 9.  | Susceptibility of track-side control-command equipment to emission from trains in terms of electromagnetic compatibility with respect to admission of trains. To be specified where available according to European Standards (prEN 50238 and other future standards — to be defined) to meet safety and reliability/availability targets.<br/>Permissibility to use eddy-current brake (types)<br/>Permissibility to use magnetic brake (types)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | Electromagnetic emission of the train with respect to admission of the train in terms of electromagnetic compatibility. To be specified where available according to European Standards (prEN 50238 and other future standards — to be defined) to meet safety and reliability/availability targets.<br/>Eddy-current brake installed (type)<br/>Magnetic brake installed (type)                                                                                                                                                                                                                                                                                                                                                                                                                                           |
| 10. | Climatic conditions and physical conditions along the line. In accordance with Annex A, Index A5                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | Climatic conditions and physical conditions in which the on-board assembly can work. In accordance with Annex A, Index A4                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| 11. | The requirements for technical solutions concerning implemented derogation's according Directives 96/48/EC and 2001/16/EC have to be described.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | The rules for technical solutions concerning implemented derogation's according Directives 96/48/EC and 2001/16/EC have to be described.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| 12. | HABD                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
| 13. | Minimum length of track section<br/>Minimum distance between end of track section and fouling point<br/>Minimum differential distance of the opposite ends of adjacent tracks sections<br/>Minimum shunting sensitivity of track circuit<br/>Use of eddy current brakes<br/>Use of magnetic brakes<br/>Unrestricted sanding permitted (yes or description of restrictions)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | Maximum distance between adjacent wheelsets<br/>Maximum distance between front end and wheelset<br/>Minimum wheelbase<br/>Minimum axlebase<br/>Minimum wheel width<br/>Minimum height of tyre<br/>Minimum flange width<br/>Minimum flange height<br/>Minimum axle load<br/>Wheel material<br/>Maximum resistance between opposite wheels of a wheelset<br/>Minimum vehicle impedance<br/>Maximum sanding output<br/>Possibility of sanding override by driver<br/>Use of eddy current brakes<br/>Equipped with two pairs of rail friction-shoes whose electrical base is greater or equal to 16 000 mm.                                                                                                                                                                                                                    |
| 14. | Specific cases<br/>Limitations on the relationship between axle distance and wheel diameter (Germany)<br/>Longitudinal distance from first axle or last axle to the nearest end of the vehicle not bigger than 3 500 mm (Poland, Belgium)<br/>The distance between each of the first five axles of a train (or all axles if the train has less than five) not less than 1 000 mm (Germany)<br/>The distance between first and last axle of a vehicle not less than 6 000 mm (Belgium)<br/>The distance between first and last axle of a lone vehicle or train-set bigger than 15 000 mm (France, Belgium)<br/>Minimum diameter of wheels not smaller than 450 mm (France)<br/>Minimum axle load not less than 5 tonnes (Germany, Austria, Sweden, Belgium)<br/>Minimum vehicle mass not less than 90 tonnes (Belgium)<br/>When the distance between first and last axle of a lone vehicle or train-set greater or equal to 16 000 mm, a lone vehicle or train-set mass shall be greater than 90 tonnes. When this distance is less than 16 000 mm, and greater or equal to 15 000 mm, the mass shall be less than 90 tonnes and greater or equal to 40 tonnes, the vehicle must be equipped with two pairs of rail friction-shoes whose electrical base is greater or equal to 16 000 mm (France, Belgium)<br/>Minimum dimension of metal mass of a vehicle (Germany, Poland)<br/>Maximum reactance between running surfaces of a wheel-set (Poland, France)<br/>Additional requirements on shunting parameter of a vehicle (Netherlands)<br/>Required impedance between pantograph and wheels more than 1,0 Ohm inductive at 50 Hz for 3 kVDC (Belgium)<br/>No sanding ahead of the leading axle on multiple units below 40km/h (United Kingdom)<br/>The magnetic brake and eddy current brake is not permitted at the first bogie of a leading vehicle (Germany). |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |

(1)  For information only, this will be part of the introduction of the relevant register and will be deleted when the register exists.

# ANNEX D

**TSI control-command (conventional rail system)**

This figure shows the principle only

Figure 8

Image

# ANNEX E

## MODULES FOR INTEROPERABILITY CONSTITUENTS

### Module B: Type examination

1.  This module describes that part of the procedure by which a notified body ascertains and attests that a type, representative of the production envisaged, meets the provisions of the TSI that apply to it.

2.  The application for the EC type-examination must be lodged by the manufacturer or his authorised representative established within the Community.  
    The application must include:

3.  the name and address of the manufacturer and also, if the application is lodged by the authorised representative, his name and address,
4.  a written declaration that the same application has not been lodged with any other notified body,
5.  the technical documentation, as described in point 3.  

    The applicant must place at the disposal of the notified body a specimen, representative of the production envisaged and hereinafter called ’type’.  

    A type may cover several versions of the Interoperability Constituent provided that the differences between the versions do not affect the provisions of the TSI.  

    The notified body may request further specimens if needed for carrying out the test programme.  

    If no type tests are requested within the type examination procedure, and the type is sufficiently defined by the technical documentation, as described in point 3, the notified body may agree, that no specimens are placed at its disposal.

6.  The technical documentation must enable the conformity of the interoperability constituent with the requirements of the TSI to be assessed. It must, as far as relevant for such assessment, cover the design, manufacture, maintenance and operation of the interoperability constituent.  

    The technical documentation must contain:  

7.  a general type-description,
8.  conceptual design and manufacturing information, for example drawings and schemes of components, sub-assemblies, circuits, etc.,
9.  descriptions and explanations necessary for the understanding of the design and manufacturing information, maintenance and the operation of the interoperability constituent,
10. conditions of integration of the interoperability constituent in its system environment (sub-assembly, assembly, subsystem) and the necessary interface conditions,
11. conditions for use and maintenance of the interoperability constituent (restrictions of running time or distance, wear limits etc),
12. the technical specifications, including European specifications (1) with relevant clauses, applied in full or in part,
13. descriptions of the solutions adopted to meet the requirements of the TSI in cases where the European specifications have not been applied in full,
14. results of design calculations made, examinations carried out, etc.,
15. test reports.

16. The notified body must:  

    4.1. examine the technical documentation,

    4.2. verify that any specimen(s) required for test has (have) been manufactured in conformity with the technical documentation, and carry out or have carried out the type tests in accordance with the provisions of the TSI and/or the relevant European specifications,  

    4.3. where a design review is requested in the TSI, perform an examination of the design methods, the design tools and the design results to evaluate their capability to fulfil the requirements for conformity for the interoperability constituent at the completion of the design process,  

    4.4. where a review of the manufacturing process is requested in the TSI, perform an examination of the manufacturing process devised for manufacturing the interoperability constituent, to evaluate its contribution to product conformity, and/or examine the review carried out by the manufacturer at the completion of the design process,  

    4.5. identify the elements which have been designed in accordance with the relevant provisions of the TSI and the European specifications as well as the elements which have been designed without applying the relevant provisions of those European Specifications;  

    4.6. perform or have performed the appropriate examinations and necessary tests in accordance with points 4.2, 4.3 and 4.4 to establish whether, where the manufacturer has chosen to apply the relevant European specifications, these have actually been applied;  

    4.7. perform or have performed the appropriate examinations and necessary tests in accordance with points 4.2, 4.3 and 4.4 to establish whether, where the relevant European specifications have not been applied, the solutions adopted by the manufacturer meet the requirements of the TSI;  

    4.8. agree with the applicant the location where the examinations and necessary tests will be carried out.  

17. Where the type meets the provisions of the TSI, the notified body must issue a type-examination certificate to the applicant. The certificate must contain the name and address of the manufacturer, conclusions of the examination, conditions for its validity and the necessary data for identification of the approved type.  

    The time period of validity shall be no longer than five years.  

    A list of the relevant parts of the technical documentation must be annexed to the certificate and a copy kept by the notified body.  

    If the manufacturer or his authorised representative established within the Community is denied a type-examination certificate, the notified body must provide detailed reasons for such denial.  

    Provision must be made for an appeals procedure.  

18. The applicant must inform the notified body that holds the technical documentation concerning the type-examination certificate of all modifications to the approved product which must receive additional approval where such changes may affect the conformity with the requirements of the TSI or the prescribed conditions for use of the product. In this case the notified body shall perform only those examinations and tests that are relevant and necessary to the change(s).This additional approval may be given either in the form of an addition to the original type-examination certificate, or, by the issue of a new certificate after withdrawal of the old one.

19. If no modifications as in point 6 have been made, the validity of an expiring certificate can be extended for another period of validity. The applicant will apply for such a prolongation by a written confirmation that no such modifications have been made, and the notified body issues a prolongation for another period of validity as in point 5, if no contrary information exists. This procedure can be reiterated.

20. Each notified body must communicate to the other notified bodies the relevant information concerning the type-examination certificates and additions issued, withdrawn or refused.

21. The other notified bodies may receive, on request, copies of the type-examination certificates issued and/or their additions. The annexes to the certificates (see subsection 5) must be kept at the disposal of the other notified bodies.

22. The manufacturer or his authorised representative established within the Community must keep with the technical documentation copies of type-examination certificates and their additions for a period of 10 years after the last interoperability constituent has been manufactured. Where neither the manufacturer nor his authorised representative is established within the Community, the obligation to keep the technical documentation available is the responsibility of the person who places the interoperability constituent on the Community market.

## Module D: Production quality management system

1.  This module describes the procedure whereby the manufacturer or his authorised representative established within the Community who satisfies the obligations of point 2 ensures and declares that the interoperability constituent concerned is in conformity with the type as described in the type-examination certificate and satisfies the requirements of the TSI that apply to it.

2.  The manufacturer must operate an approved quality management system for production, final product inspection and testing as specified in point 3 and is subject to monitoring as specified in point. 4.

3.  Quality management system  

    3.1. The manufacturer must lodge an application for assessment of his quality management system with a notified body of his choice, for the interoperability constituents concerned.  

      The application must include:  

    -   all relevant information for the product category representative for the interoperability constituents envisaged,
    -   the documentation concerning the quality management system,
    -   the technical documentation of the approved type and a copy of the type-examination certificate, issued after the completion of the type examination procedure of Module B (type examination).
    -   a written declaration that the same application has not been lodged with any other notified body,  

    3.2. The quality management system must ensure compliance of the interoperability constituents with the type as described in the type-examination certificate and with the requirements of the TSI that apply to them. All the elements, requirements and provisions adopted by the manufacturer shall be documented in a systematic and orderly manner in the form of written policies, procedures and instructions. The quality management system documentation must permit a consistent interpretation of the quality programmes, plan, manuals and records.  

    It must contain in particular an adequate description of:  

4.  the quality objectives and the organisational structure,
5.  responsibilities and powers of the management with regard to product quality,
6.  the manufacturing, quality control and quality management techniques, processes and systematic actions that will be used,
7.  the examinations, checks and tests that will be carried out before, during and after manufacture, and the frequency with which they will be undertaken,
8.  the quality records, such as inspection reports and test data, calibration data, qualification reports of the personnel concerned, etc.,
9.  the means to monitor the achievement of the required product quality and the effective operation of the quality management system.  

    3.3. The notified body assesses the quality management system to determine whether it satisfies the requirements of point 3.2. It presumes compliance with these requirements if the manufacturer implements a quality system for production, final product inspection and testing in respect of the Standard EN/ISO 9001-2000, which take into consideration the specificity of the interoperability constituent for which it is implemented.  

      When the manufacturer operates a certified quality management system, the notified body shall take this into account in the assessment.  

      The audit must be specific for the product category, which is representative for the interoperability constituent. The auditing team must have at least one member experienced as an assessor in the product technology concerned. The evaluation procedure must include an inspection visit to the manufacturer's premises.  

      The decision must be notified to the manufacturer. The notification must contain the conclusions of the examination and the reasoned assessment decision.

    3.4. The manufacturer must undertake to fulfil the obligations arising out of the quality management system as approved and to uphold it so that it remains adequate and efficient.  

      The manufacturer or his authorised representative established within the Community shall keep the notified body that has approved the quality management system informed of any intended updating of the quality management system.  

      The notified body must evaluate the modifications proposed and decide whether the amended quality management system will still satisfy the requirements of point 3.2 or whether a re-assessment is required.  

      It must notify its decision to the manufacturer. The notification must contain the conclusions of the examination and the reasoned assessment decision.

10. Surveillance of the quality management system under the responsibility of the notified body.  

    4.1. The purpose of surveillance is to make sure that the manufacturer duly fulfils the obligations arising out of the approved quality management system.  

    4.2. The manufacturer must allow the notified body entrance for inspection purposes to the locations of manufacture, inspection and testing, and storage and must provide it with all necessary information, in particular:  

11. the quality management system documentation,  
12. the quality records such as inspection reports and test data, calibration data, qualification reports of the personnel concerned, etc.  

    4.3. The notified body must periodically carry out audits to make sure that the manufacturer maintains and applies the quality management system and must provide an audit report to the manufacturer.  

      The frequency of the audits shall be at least once a year.  

      When the manufacturer operates a certified quality management system, the notified body shall take this into account in the surveillance.

    4.4. Additionally the notified body may pay unexpected visits to the manufacturer. During such visits the notified body may carry out, or cause to be carried out, tests to verify that the quality management system is functioning correctly, if necessary. The notified body must provide the manufacturer with a visit report and, if a test has taken place, with a test report.

13. Each notified body must communicate to the other notified bodies the relevant information concerning the quality management system approvals, issued, withdrawn or refused.  

    The other notified bodies may receive on request copies of the quality management system approvals issued.

14. The manufacturer must, for a period of 10 years after the last product has been manufactured, keep at the disposal of the national authorities:  

15. the documentation referenced to in the second indent of point 3.1,
16. the updating referenced to in the second paragraph of point 3.4,
17. the decisions and reports from the notified body in the final paragraph of point 3.4 and in points 4.3 and 4.4.

18. The manufacturer or his authorised representative established within the Community must draw up the EC declaration of conformity of the interoperability constituent. The content of this declaration shall include at least the information indicated in Annex IV(3) of Directives 96/48/EC or 2001/16/EC. The EC declaration of conformity and the accompanying documents must be dated and signed.  

    The declaration must be written in the same language as the technical documentation and must contain the following:  

19. the Directive references (Directives 96/48/EC or 2001/16/EC and other directives to which the interoperability constituent may be subject),
20. the name and address of the manufacturer or his authorised representative established within the Community (give trade name and full address and in the case of an authorised representative also give the trade name of the manufacturer or constructor),
21. description of the interoperability constituent (make, type, etc.),
22. description of the procedure (module) followed in order to declare conformity,
23. all of the relevant descriptions met by the interoperability constituent and in particular any conditions of use,
24. name and address of notified body (bodies) involved in the procedure followed in respect of conformity and date of certificates together with the duration and conditions of validity of the certificates,
25. reference to the TSI and any other relevant TSI and where appropriate reference to European specification (2),
26. identification of the signatory empowered to enter into commitments on behalf of the manufacturer or of his authorised representative established within the Community.  

    The certificates to be referred to are:  

27. the quality management system approval indicated in point 3,
28. the type-examination certificate and its additions,

29. The manufacturer or his authorised representative established within the Community must keep a copy of the EC declaration of conformity for a period of 10 years after the last interoperability constituent has been manufactured.  

    Where neither the manufacturer nor his authorised representative is established within the Community, the obligation to keep the technical documentation available is the responsibility of the person who places the interoperability constituent on the Community market.

30. If additional to the EC declaration of conformity an EC declaration of suitability for use for the interoperability constituent is requested in the TSI, this declaration has to be added, after being issued by the manufacturer under the conditions of Module V.

### Module F: Product verification

1.  This module describes the procedure whereby a manufacturer or his authorised representative established within the Community checks and attests that the interoperability constituent concerned and subject to the provisions of point 3 is in conformity with the type as described in the EC type examination certificate and satisfies the requirements of the TSI that apply to it.

2.  The manufacturer must take all measures necessary in order that the manufacturing process ensures conformity of each interoperability constituents with the type as described in the type-examination certificate and with the requirements of the TSI that apply to it.

3.  The notified body must carry out the appropriate examinations and tests in order to check the conformity of the interoperability constituent with the type as described in the EC type examination certificate and with the requirements of the TSI. The manufacturer (3) can choose either an examination and testing of every interoperability constituent as specified in point 4 or an examination and testing of interoperability constituents on a statistical basis, as specified in point 5..

4.  Verification by examination and testing of every interoperability constituent  

    4.1. Each product shall be individually examined and appropriate tests shall be carried out in order to verify the product conformity with the type as described in the type-examination certificate and with the requirements of the TSI that apply to it. When a test is not set out in the TSI, (or in an European Standard quoted in the TSI), the relevant European Specifications (4), or equivalent tests are to be used.  

    4.2. The notified body must draw up a written certificate of conformity for the approved products relating to the tests carried out.  

    4.3. The manufacturer or his authorised representative must ensure that he is able to supply the notified body's certificates of conformity on request.

5.  Statistical verification  

    5.1. The manufacturer must present his interoperability constituents in the form of homogeneous lots and shall take all measures necessary in order that the manufacturing process ensures the homogeneity of each lot produced.  

    5.2. All interoperability constituents must be available for verification in the form of homogeneous lots. A random sample shall be drawn from each lot. Each interoperability constituents in a sample shall be individually examined and appropriate tests shall be carried out to ensure the product conformity with the type as described in the type-examination certificate and with the requirements of the TSI which apply to it and to determine whether the lot is accepted or rejected. When a test is not set out in the TSI (or in an European Standard quoted in the TSI), the relevant European Specifications or equivalent tests are to be used.  

    5.3. The statistical procedure must use appropriate elements (statistical method, sampling plan etc.), depending on the characteristics to be assessed, as specified in the TSI.  

    5.4. In the case of accepted lots, the notified body shall draw up a written certificate of conformity relating to the tests carried out. All interoperability constituents in the lot may be placed on the market except those interoperability constituents from the sample, which were found not to be in conformity.  

    If a lot is rejected, the notified body or the competent authority must take appropriate measures to prevent placing of that lot on the market. In the event of frequent rejection of lots the notified body may suspend the statistical verification.  

    5.5. The manufacturer or his authorised representative established within the Community must ensure that he is able to supply the notified body's certificates of conformity on request.  

6.  The manufacturer or his authorised representative established within the Community must draw up the EC declaration of conformity of the interoperability constituent. 

    The content of this declaration shall include at least the information indicated in Annex IV(3) of Directives 96/48/EC or 2001/16/EC. The EC declaration of conformity and the accompanying documents must be dated and signed.  

    The declaration must be written in the same language as the technical documentation and must contain the following:  

7.  the Directive references (Directives 96/48/EC or 2001/16/EC and other directives to which the interoperability constituent may be subject),
8.  the name and address of the manufacturer or his authorised representative established within the Community (give trade name and full address and in the case of an authorised representative also give the trade name of the manufacturer or constructor),
9.  description of interoperability constituent (make, type, etc.),
10. description of the procedure (module) followed in order to declare conformity,
11. all of the relevant descriptions met by the interoperability constituent and in particular any conditions of use,
12. name and address of notified body (bodies) involved in the procedure followed in respect of conformity and date of certificates together with the duration and conditions of validity of the certificates,
13. reference to the TSI and any other relevant TSI and where appropriate reference to European specifications,
14. identification of the signatory empowered to enter into commitments on behalf of the manufacturer or of his authorised representative established within the Community.  

    The certificates to be referred to are:  

15. the type-examination certificate and its additions,
16. the certificate of conformity as mentioned in points 4 or 5.

17. The manufacturer or his authorised representative established within the Community must keep a copy of the EC declaration of conformity for a period of 10 years after the last interoperability constituent has been manufactured.  

    Where neither the manufacturer nor his authorised representative is established within the Community, the obligation to keep the technical documentation available is the responsibility of the person who places the interoperability constituent on the Community market.

18. If additional to the EC declaration of conformity an EC declaration of suitability for use for the interoperability constituent is requested in the TSI, this declaration has to be added, after being issued by the manufacturer under the conditions of Module V.

### Module H2: Full quality management system with design examination

1.  This module describes the procedure whereby a notified body carries out an examination of the design of an interoperability constituent and the manufacturer or his authorised representative established within the Community who satisfies the obligations of point 2 ensures and declares that the interoperability constituent concerned satisfies the requirements of the TSI that apply to it.

2.  The manufacturer must operate an approved quality management system for design, production and final product inspection and testing as specified in point 3 and shall be subject to surveillance as specified in point 4.

3.  Quality management system.

    3.1. The manufacturer must lodge an application for assessment of his quality management system with a notified body of his choice, for the interoperability constituents concerned.  

    The application must include:  

4.  all relevant information for the product category representative for the interoperability constituent envisaged,
5.  the quality management system's documentation,
6.  a written declaration that the same application has not been lodged with any other notified body.  

    3.2. The quality management system must ensure compliance of the interoperability constituent with the requirements of the TSI that apply to it. All the elements, requirements and provisions adopted by the manufacturer must be documented in a systematic and orderly manner in the form of written policies, procedures and instructions. This quality management system documentation shall ensure a common understanding of the quality policies and procedures such as quality programmes, plans, manuals and records.  

    It must contain in particular an adequate description of:  

7.  the quality objectives and the organisational structure,
8.  responsibilities and powers of the management with regard to design and product quality,
9.  the technical design specifications, including European specifications (5), that will be applied, and, where the European specifications will not be applied in full, the means that will be used to ensure that the requirements of the TSI that apply to the interoperability constituent will be met,
10. the design control and design verification techniques, processes and systematic actions that will be used when designing the interoperability constituents pertaining to the product category covered,
11. the corresponding manufacturing, quality control and quality management system techniques, processes and systematic actions that will be used,
12. the examinations, checks and tests that will be carried out before, during and after manufacture, and the frequency with which they will be undertaken,
13. the quality records, such as inspection reports and test data, calibration data, qualification reports of the personnel concerned, etc.,
14. the means to monitor the achievement of the required design and product quality and the effective operation of the quality management system.  

    The quality policies and procedures shall cover in particular the assessment phases, such as design review, review of manufacturing processes and type tests, as they are specified in the TSI, for different characteristics and performances of the interoperability constituent.  

    3.3. The notified body must assess the quality management system to determine whether it satisfies the requirements of point 3.2. It presumes compliance with these requirements if the manufacturer implements a quality system for design, production, final product inspection and testing in respect of the standard EN/ISO 9001-2000, which takes into consideration the specificity of the interoperability constituent for which it is implemented.  

    When the manufacturer operates a certified quality management system, the notified body shall take this into account in the assessment.  

    The audit must be specific for the product category, which is representative for the interoperability constituent. The auditing team must have at least one member experienced as an assessor in the product technology concerned. The evaluation procedure shall include an assessment visit to the manufacturer's premises.  

    The decision must be notified to the manufacturer. The notification must contain the conclusions of the audit and the reasoned assessment decision.  

    3.4. The manufacturer must undertake to fulfil the obligations arising out of the quality management system as approved and to uphold it so that it remains adequate and efficient.  

    The manufacturer or his authorised representative established within the Community shall keep the notified body that has approved the quality management system informed of any intended updating of the quality management system.  

    The notified body must evaluate the modifications proposed and decide whether the amended quality management system will still satisfy the requirements of point 3.2 or whether a re-assessment is required.  

    It must notify its decision to the manufacturer. The notification shall contain the conclusions of the evaluation and the reasoned assessment decision.  

15. Surveillance of the quality management system under the responsibility of the notified body  

    4.1. The purpose of surveillance is to make sure that the manufacturer duly fulfils the obligations arising out of the approved quality management system.  

    4.2. The manufacturer must allow the notified body entrance for inspection purposes to the locations of design, manufacture, inspection and testing, and storage, and shall provide it with all necessary information, including:  

16. the quality management system documentation,
17. the quality records as foreseen by the design part of the quality management system, such as results of analyses, calculations, tests, etc.,
18. the quality records as foreseen by the manufacturing part of the quality management system, such as inspection reports and test data, calibration data, qualification reports of the personnel concerned, etc.  

    4.3. The notified body must periodically carry out audits to make sure that the manufacturer maintains and applies the quality management system and shall provide an audit report to the manufacturer. When the manufacturer operates a certified quality management system, the notified body shall take this into account in the surveillance.  

    The frequency of the audits shall be at least once a year.  

    4.4. Additionally the notified body may pay unexpected visits to the manufacturer. At the time of such visits, the notified body may carry out tests or have them carried out in order to check the proper functioning of the quality management system where necessary. It must provide the manufacturer with a visit report and, if a test has been carried out, with a test report.

19. The manufacturer must, for a period of 10 years after the last product has been manufactured, keep at the disposal of the national authorities:  

20. the documentation referenced in the second indent of the second subparagraph of point 3.1,
21. the updating referenced to in the second subparagraph of point 3.4,
22. the decisions and reports from the notified body in the final subparagraph of point 3.4 and in points 4.3 and 4.4.  

23. Design examination  

    6.1. The manufacturer must lodge an application for examination of the design of the interoperability constituent with a notified body of his choice.  

    6.2. The application must enable the design, manufacture, maintenance and operation of the interoperability constituent to be understood, and shall enable conformity with the requirements of the TSI to be assessed.  

      It must include:  

    -   a general type-description,
    -   the technical design specifications, including European specifications, with relevant clauses, that have been applied in full or in part,
    -   any necessary supporting evidence for their adequacy, in particular where the European specifications and the relevant clauses have not been applied,
    -   the test programme,
    -   conditions for integration of the interoperability constituent in its system environment (sub-assembly, assembly, subsystem) and the necessary interface conditions,
    -   conditions for use and maintenance of the interoperability constituent (restrictions of running time or distance, wear limits etc.),
    -   a written declaration that the same application has not been lodged with any other notified body.  

    6.3. The applicant shall present the results of tests (6), including type tests when required, carried out by its appropriate laboratory or on their behalf.  

    6.4. The notified body must examine the application and assess the results of the tests. Where the design meets the provisions of the TSI that apply to it, the notified body must issue an EC design examination certificate to the applicant. The certificate shall contain the conclusions of the examination, conditions for its validity, the necessary data for identification of the approved design and, if relevant, a description of the product's functioning.  

    The time period of validity shall be no longer than five years.  

    6.5. The applicant must keep the notified body that has issued the EC design examination certificate informed of any modification to the approved design. Modifications to the approved design must receive additional approval from the notified body that issued the EC design examination certificate where such changes may affect the conformity with the requirements of the TSI or the prescribed conditions for use of the product. In this case the notified body shall perform only those examinations and tests that are relevant and necessary to the change(s). This additional approval shall be given in the form of an addition to the original EC design examination certificate.  

    6.6. If no modifications as in point 6.4 have been made, the validity of an expiring certificate can be extended for another period of validity. The applicant will apply for such a prolongation by a written confirmation that no such modifications have been made, and the notified body issues a prolongation for another period of validity as in point 6.3 if no contrary information exists. This procedure can be reiterated.  

24. Each notified body must communicate to the other notified bodies the relevant information concerning the quality management system approvals and the EC design examination certificates, which it has issued, withdrawn or refused.  

    The other notified bodies may receive on request copies of:  

25. the quality management system approvals and additional approvals issued and
26. the EC design examination certificates and additions issued  

27. The manufacturer or his authorised representative established within the Community must draw up the EC declaration of conformity of the interoperability constituent.  

    The content of this declaration shall include at least the information indicated in Annex IV(3) of Directives 96/48/EC or 2001/16/EC. The EC declaration of conformity and its accompanying documents must be dated and signed.  

    The declaration must be written in the same language as the technical documentation and must contain the following:  

28. the Directive references (Directives 96/48/EC or 2001/16/EC and other directives to which the interoperability constituent may be subject),
29. the name and address of the manufacturer or his authorised representative established within the Community (give trade name and full address and in the case of an authorised representative also give the trade name of the manufacturer or constructor),
30. description of interoperability constituent (make, type, etc.),
31. description of the procedure (module) followed in order to declare conformity,
32. all of the relevant descriptions met by the interoperability constituent and in particular any conditions of use,
33. name and address of notified body (bodies) involved in the procedure followed in respect of conformity and date of certificates together with the duration and conditions of validity of the certificates,
34. reference to the TSI and any other relevant TSI and where appropriate to European specifications,
35. identification of the signatory empowered to enter into commitments on behalf of the manufacturer or of his authorised representative established within the Community.  

    The certificates to be referred to are:  

36. the quality management system approval and surveillance reports indicated in point 3 and 4,
37. the EC design examination certificate and its additions.

38. The manufacturer or his authorised representative established within the Community must keep a copy of the EC declaration of conformity for a period of 10 years after the last interoperability constituent has been manufactured.  

    Where neither the manufacturer nor his authorised representative is established within the Community, the obligation to keep the technical documentation available is the responsibility of the person who places the interoperability constituent on the Community market.

39. If additional to the EC declaration of conformity an EC declaration of suitability for use for the interoperability constituent is requested in the TSI, this declaration has to be added, after being issued by the manufacturer under the conditions of Module V.

## MODULES FOR THE EC VERIFICATION OF SUBSYSTEMS

### Module SB: Type examination

1.  This module describes the EC verification procedure whereby a notified body checks and certifies at the request of an contracting entity or its authorised representative established within the Community, that a type of a control-command subsystem, representative of the production envisaged,  

2.  complies with this TSI and any other relevant TSI, which demonstrate that the essential requirements (7) of Directive 2001/16/EC (8) have been met
3.  complies with the other regulations deriving from the Treaty.  

    The type examination defined by this module could include specific assessment phases — design review, type test or review of manufacturing process, which are specified in the relevant TSI.

4.  The contracting entity (9) must lodge an application for EC verification (through type examination) of the subsystem with a notified body of his choice.  

    The application must include :  

5.  name and address of the contracting entity or its authorised representative,
6.  the technical documentation, as described in point 3.

7.  The applicant must place at the disposal of the notified body a specimen of the subsystem (10), representative of the production envisaged and hereinafter called ‘type’.  

    A type may cover several versions of the subsystem provided that the differences between the versions do not affect the provisions of the TSI.  

    The notified body may request further specimens if needed for carrying out the test programme.  

    If so required for specific test or examination methods and specified in the TSI or in the European specification (11) referenced to in the TSI, a specimen or specimens of a subassembly or assembly or a specimen of the subsystem in a pre-assembled condition shall to be provided.  

    The technical documentation and specimen(s) must enable the design, manufacture, installation, maintenance and operation of the subsystem to be understood, and shall enable conformity with the provisions of the TSI to be assessed.  

    The technical documentation must include:  

8.  a general description of the subsystem, overall design and structure,
9.  the Infrastructure and/or Rolling Stock (subsystem) Register, including all information as specified in the TSI
10. conceptual design and manufacturing information, for example drawings, schemes of components, subassemblies, assemblies, circuits, etc.,
11. descriptions and explanations necessary for the understanding of the design and manufacturing information, the maintenance and the operation of the subsystem,
12. the technical specifications, including European specifications, that have been applied,
13. any necessary supporting evidence for the use of the above specifications, in particular where European specifications and the relevant clauses have not been applied in full,
14. a list of the interoperability constituents to be incorporated into the subsystem,
15. copies of the EC declarations of conformity or suitability for use of interoperability constituents and all the necessary elements defined in annex VI of the directives,
16. evidence of conformity with regulations deriving from the treaty (including certificates),
17. technical documentation regarding the manufacture and the assembly of the subsystem,
18. a list of manufacturers, involved in the subsystem's design, manufacturing, assembly and installation,
19. conditions for use of the subsystem (restrictions of running time or distance, wear limits etc),
20. conditions for maintenance and technical documentation regarding the maintenance of the subsystem,
21. any technical requirement that must be taken into account during production, maintenance or operation of the subsystem,
22. results of design calculations made, examinations carried out, etc.
23. test reports.  

    If the TSI requires further information for the technical documentation, this shall be included.

24. The notified body must:  

    4.1. Examine the technical documentation;  

    4.2. Verify that the specimen(s) of the subsystem or of assemblies or subassemblies of the subsystem, has (have) been manufactured in conformity with the technical documentation, and carry out or have carried out the type tests in accordance with the provisions of the TSI and the appropriate European specifications. Such manufacture shall be verified using an appropriate assessment module;  

    4.3. Where a design review is requested in the TSI, perform an examination of the design methods, the design tools and the design results to evaluate their capability to fulfil the requirements for conformity for the subsystem at the completion of the design process;  

    4.4. Identify the elements which have been designed in accordance with the relevant provisions of the TSI and the European specifications as well as the elements which have been designed without applying the relevant provisions of those European specifications;  

    4.5. Perform or have performed the appropriate examinations and necessary tests in accordance with points 4.2. and 4.3 to establish where the relevant European specifications have been chosen, these have actually been applied;  

    4.6. Perform or have performed the appropriate examinations and necessary tests in accordance with point 4.2. and 4.3. to establish whether the solutions adopted meet the requirements of the TSI when the appropriate European specifications have not been applied;  

    4.7. Agree with the applicant the location where the examinations and necessary tests will be carried out.  

25. Where the type meets the provisions of the TSI, the notified body shall issue a type-examination certificate to the applicant. The certificate shall contain the name and address of the contracting entity and the manufacturer(s) indicated in the technical documentation, conclusions of the examination, conditions for its validity and the necessary data for identification of the approved type.  

    A list of the relevant parts of the technical documentation must be annexed to the certificate and a copy kept by the notified body.  

    If the contracting entity is denied a type-examination certificate, the notified body must provide detailed reasons for such denial.  

    Provision must be made for an appeals procedure.

26. Each notified body must communicate to the other notified bodies the relevant information concerning the type-examination certificates issued, withdrawn or refused.

27. The other notified bodies may receive on request copies of the type-examination certificates issued and/or their additions. The annexes to the certificates must be kept at the disposal of the other notified bodies.

28. The contracting entity must keep with the technical documentation copies of type-examination certificates and any additions throughout the service life of the subsystem. It must be sent to any other Member State which so requests.

29. The applicant must inform the notified body that holds the technical documentation concerning the type-examination certificate of all modifications which may affect the conformity with the requirements of the TSI or the prescribed conditions for use of the subsystem. The subsystem must receive additional approval in such cases. This additional approval may be given either in the form of an addition to the original type-examination certificate, or by issue of a new certificate after withdrawal of the old certificate.

### Module SD: Production quality management system

1.  This module describes the EC verification procedure whereby a notified body checks and certifies, at the request of an contracting entity or its authorised representative established within the Community, that a control-command subsystem, for which already a type-examination certificate has been issued by a notified body:  

2.  complies with this TSI and any other relevant TSI, which demonstrate that the essential requirements (12) of Directive 2001/16/EC (13) have been met,
3.  complies with the other regulations deriving from the Treaty,  

    and may be placed in service.

4.  The notified body carries out the procedure, under the condition, that:  

5.  the type examination certificate issued prior to the assessment remains valid for the subsystem subject to the application,
6.  the contracting entity (14) and the main contractors involved are satisfying the obligations of point 3.
7.  the ‘main contractors’ refers to companies, whose activities contribute to fulfil the essential requirements of the TSI. It concerns:
8.  the company responsible for the whole subsystem project (including in particular responsibility for subsystem integration),
9.  other companies only involved in a part of the subsystem project, (performing for example assembly or installation of the subsystem);
10. it does not refer to manufacturer sub contractors supplying components and interoperability constituents.

11. For the subsystem that is subject of the EC verification procedure, the contracting entity, or the main contractors when employed, shall operate an approved quality management system for manufacture and final product inspection and testing as specified in point 5 and which shall be subject to surveillance as specified in point 6.  

    When the contracting entity itself is responsible for the whole subsystem project (including in particular responsibility for subsystem integration), or the contracting entity is directly involved in the production (including assembly and installation), it has to operate an approved quality management system for those activities, which shall be subject to surveillance as specified in point 6.  

    If a main contractor is responsible for the whole subsystem project (including in particular responsibility for subsystem integration), it must operate in any case an approved quality management system for manufacture and final product inspection and testing, which shall be subject to surveillance as specified in point 6.

12. EC verification procedure  

4.1. The contracting entity must lodge an application for EC verification of the subsystem (through production quality management system), including co-ordination of the surveillance of the quality management systems, as under point 5.3 and 6.5. with a notified body of its choice. The contracting entity must inform the manufacturers involved of this choice and of the application.  

4.2. The application must enable the design, manufacture, assembly, installation, maintenance and operation of the subsystem to be understood, and shall enable conformity with the type as described in the type-examination certificate and the requirements of the TSI to be assessed.  

  The application must include:  

-   name and address of the contracting entity or its authorised representative,
-   the technical documentation regarding the approved type, including the type examination certificate, as issued after completion of the procedure defined in Module SB (type-examination),

    and, if not included in this documentation,  

-   a general description of the subsystem, its overall design and structure,
-   the technical specifications, including European specifications, that have been applied,
-   any necessary supporting evidence for the use of the above specifications, in particular where these European specifications, and the relevant clauses have not been applied in full. This supporting evidence must include the results of tests carried out by the appropriate laboratory of the manufacturer or on his behalf.
-   The Infrastructure and/or Rolling Stock(subsystem) Register, including all information as specified in the TSI,
-   the technical documentation regarding the manufacture and the assembly of the subsystem,
-   evidence of conformity to other regulations deriving from the treaty (including certificates) for the production phase
-   a list of the interoperability constituents to be incorporated into the subsystem,
-   copies of the EC declarations of conformity or suitability for use with which the constituents must be provided, and all the necessary elements defined in annex VI of the directives,
-   a list of manufacturers, involved in the subsystem's design, manufacturing, assembly and installation,
-   the demonstration, that all stages, as mentioned under point 5.2, are covered by quality management systems of the contracting entity, if involved, and/or of the main contractors, and the evidence of their effectiveness,
-   indication of the notified body, responsible for the approval and surveillance of these quality management systems.  

    4.3. The notified body shall fist examine the application concerning the validity of the type examination and the type examination certificate.  

    If the notified body considers the type examination certificate no longer remains valid or is not appropriate and that a new type examination is necessary, it shall justify its decision.

-   Quality management system  

    5.1. The contracting entity, if involved, and the main contractors, when employed, must lodge an application for assessment of their quality management systems with a notified body of their choice.  

    The application must include:  

-   all relevant information for the subsystem envisaged,
-   the quality management system documentation.
-   the technical documentation of the approved type and a copy of the type examination certificate, issued after the completion of the type examination procedure of Module SB (type-examination).  

    For those only involved in a part of the subsystem project, the information to be provided is only that for the relevant part.

    5.2. For the contracting entity or the main contractor responsible for the whole subsystem project, the quality management systems shall ensure overall compliance of the subsystem with the type as described in the type-examination certificate and overall compliance of the subsystem with the requirements of the TSI. For other main contractor, their quality management system(s) has (have) to ensure compliance of their relevant contribution to the subsystem with the type as described in the type-examination certificate and with the requirements of the TSI.  

    All the elements, requirements and provisions adopted by the applicant(s) must be documented in a systematic and orderly manner in the form of written policies, procedures and instructions. This quality management system documentation shall ensure a common understanding of the quality policies and procedures such as quality programmes, plans, manuals and records.  

    It must contain in particular an adequate description of the following items:  

-   for all applicant(s):
-   the quality objectives and the organisational structure,
-   the corresponding manufacturing, quality control and quality management techniques, processes and systematic actions that will be used,
-   the examinations, checks and tests that will be carried out before, during and after manufacture, assembly and installation, and the frequency with which they will be carried out,
-   the quality records, such as inspection reports and test data, calibration data, qualification reports of the personnel concerned, etc.,
-   and also for the contracting entity or the main contractor responsible for the whole subsystem project:
-   responsibilities and powers of the management with regard to overall subsystem quality, including in particular the subsystem integration management.  

    The examinations, tests and checking shall cover all of the following stages:  

-   structure of subsystem, including, in particular, civil-engineering activities, constituent assembly, final adjustment,
-   final testing of the subsystem,
-   and, where specified in the TSI, the validation under full operation conditions.  

    5.3. The notified body chosen by the contracting entity must examine, if all stages of the subsystem as mentioned under point 5.2 are sufficiently and properly covered by the approval and surveillance of the quality management system(s) of the applicant(s) (15).  

    If the conformity of the subsystem with the type as described in the type-examination certificate and the compliance of the subsystem with the requirements of the TSI is based on more than one quality management system, the notified body shall examine in particular:  

-   if the relations and interfaces between the quality management systems are clearly documented,
-   and if overall responsibilities and powers of the management for the compliance of the whole entire subsystem for the main contractors are sufficiently and properly defined.  

    5.4. The notified body referenced to in point 5.1. must assess the quality management system to determine whether it satisfies the requirements referenced in point 5.2. It presumes compliance with these requirements if the manufacturer implements a quality system for production, final product inspection and testing in respect of the standard EN/ISO 9001 — 2000, which takes into consideration the specificity of the interoperability constituent which it is implemented.  

    When an applicant operates a certified quality management system, the notified body shall take this into account in the assessment.  

    The audit shall be specific for the subsystem concerned, taking into consideration the specific contribution of the applicant to the subsystem. The auditing team must have at least one member experienced as an assessor in the subsystem technology concerned.  

    The evaluation procedure shall include an assessment visit to the applicant's premises.  

    The decision must be notified to the applicant. The notification must contain the conclusions of the examination and the reasoned assessment decision.  

    5.5. The contracting entity, if involved, and the main contractors shall undertake to fulfil the obligations arising out of the quality management system as approved and to uphold it so that it remains adequate and efficient.  

    They must keep the notified body that has approved the quality management system, informed of any significant change that will affect the fulfilment of the TSI requirements by the subsystem.  

    The notified body must evaluate the modifications proposed and decide whether the amended quality management system will still satisfy the requirements referenced in point 5.2 or whether a re-assessment is required.  

    lt must notify its decision to the applicant. The notification shall contain the conclusions of the examination and the reasoned assessment decision.

-   Surveillance of the quality management system(s) under the responsibility of the notified body  

    6.1. The purpose of surveillance is to make sure that the contracting entity, if involved, and the main contractors, duly fulfil the obligations arising out of the approved quality management system.  

    6.2. The contracting entity, if involved, and the main contractors must send to the notified body referenced in point 5.1 (or have sent) all the documents needed for that purpose including the implementation plans and technical records concerning the subsystem (as far as relevant for the specific contribution of the applicants to the subsystem), in particular:  

-   the quality management system documentation, including the particular means implemented to ensure that:
-   for the contracting entity or main contractor, responsible for the whole subsystem project, overall responsibilities and powers of the management for the compliance of the whole entire subsystem are sufficiently and properly defined,
-   for each applicant, the quality management system is correctly managed for achieving integration at subsystem level,
-   the quality records as foreseen by the manufacturing part (including assembly and installation) of the quality management system, such as inspection reports and test data, calibration data, qualification reports of the personnel concerned, etc.

    6.3. The notified body must periodically carry out audits to make sure that the contracting entity, if involved, and the main contractors, maintain and apply the quality management system and must provide an audit report to them. When those operate a certified quality management system, the notified body shall take this into account in the surveillance.  

    The frequency of the audits shall be at least once a year, with at least one audit during the time period of performing relevant activities (manufacture, assembly or installation) of the subsystem being the subject of the EC verification procedure mentioned under point 8.

    6.4. Additionally the notified body may pay unexpected visits to the relevant sites of the applicant(s). At the time of such visits, the notified body may conduct complete or partial audits and may carry out or cause to be carried out tests, in order to check the proper functioning of the quality management system where necessary. It must provide the applicant(s) with an inspection report and also, audit and/or test reports, as appropriate.

    6.5. The notified body chosen by the contracting entity and responsible for the EC verification, if not carrying out the surveillance of all the quality management system(s) concerned, must co ordinate the surveillance activities of any other notified body responsible for that task, in order:  

-   to be ensured that correct management of interfaces between the different quality management systems relating to subsystem integration has been performed,
-   to collect, in liaison with the contracting entity, the necessary elements for the assessment to guarantee the consistency and the overall supervision of the different quality management systems.  

    This coordination includes the rights of the notified body:  

-   to receive all documentation (approval and surveillance), issued by the other notified bodies,
-   to witness the surveillance audits in point 6.3,
-   to initiate additional audits as in point 6.4 under its responsibility and together with the other notified bodies.

-   The notified body as referenced in point 5.1. must have entrance for inspection purposes, audit and surveillance to the locations of building sites, production workshops, locations of assembly and installations, storage areas and where appropriate, prefabrication and testing facilities and, more general, to all premises which it considers necessary in order to carry out its tasks, in accordance with the applicant's specific contribution to the subsystem project.

-   The contracting entity, if involved, and the main contractors must, for a period of 10 years after the last subsystem has been manufactured, keep at the disposal of the national authorities:  

-   the documentation referenced in the second indent of the second subparagraph of point 5.1,
-   the updating referenced in the second subparagraph of point 5.5,
-   the decisions and reports from the notified body, which are, referenced in points 5.4, 5.5 and 6.4.

-   Where the subsystem meets the requirements of the TSI, the notified body must then, based on the type examination and the approval and surveillance of the quality management system(s), draw up the certificate of conformity intended for the contracting entity, who shall in turn draw up the EC declaration of verification intended for the supervisory authority in the Member State within which the subsystem is located and/or operates.  

    The EC declaration of verification and the accompanying documents must be dated and signed. The declaration must be written in the same language of the technical file and must contain at least the information included in Annex V of the Directive.

-   The notified body chosen by the contracting entity shall be responsible for compiling the technical file that has to accompany the EC declaration of verification. The technical file shall include at least the information indicated in the Article 18(3) of the Directive, and in particular as follows:  

-   all necessary documents relating to the characteristics of the subsystem,
-   a list of interoperability constituents incorporated into the subsystem,
-   copies of the EC declarations of conformity and, where appropriate, of the EC declarations of suitability for use, which said constituents must be provided in accordance with Article 13 of the Directive, accompanied, where appropriate, by the corresponding documents (certificates, quality management system approvals and surveillance documents) issued by the notified bodies,
-   all elements relating to the maintenance, the conditions and limits for use of the subsystem,
-   all elements relating to the instructions concerning servicing, constant or routine monitoring, adjustment and maintenance,
-   the type-examination certificate for the subsystem and the accompanying technical documentation as defined in the Module SB (type-examination),
-   evidence of conformity with other regulations deriving from the treaty (including certificates)
-   certificate of conformity of the notified body as mentioned under point 9, accompanied by corresponding calculation notes and countersigned by itself, stating that the project complies with the Directive and the TSI, and mentioning, where appropriate, reservations recorded during performance of the activities and not withdrawn. The certificate should also be accompanied by the inspection and audit reports drawn up in connection with the verification, as mentioned in points 6.3 and 6.4 and in particular:
-   the Infrastructure and/or Rolling Stock (subsystem) Register, including all information as specified in the TSI.

-   Each notified body must communicate to the other notified bodies the relevant information concerning the quality management system approvals issued, withdrawn or refused.  

    The other notified bodies may receive on request copies of the quality management system approvals issued.

-   The records accompanying the certificate of conformity must be lodged with the contracting entity.  

    The contracting entity within the Community must keep a copy of the technical file throughout the service life of the subsystem; it must be sent to any other Member State which so requests.

### Module SF: Product verification

1.  This module describes the EC verification procedure whereby a notified body checks and certifies at the request of an contracting entity or its authorised representative established within the Community, that a control-command subsystem, for which a type-examination certificate has already been issued by a notified body,  

2.  complies with this TSI and any other relevant TSI, which demonstrate that the essential requirements (16) of Directive 2001/16/EC (17) have been met
3.  complies with the other regulations deriving from the Treaty and may be placed into service.

4.  The contracting entity (18) must lodge an application for EC verification (through product verification) of the subsystem with a notified body of his choice.  

    The application shall include:  

5.  The name and address of the contracting entity or its authorised representative
6.  the technical documentation.

7.  Within that part of the procedure the contracting entity checks and attests that the subsystem concerned is in conformity with the type as described in the type examination certificate and satisfies the requirements of the TSI that apply to it.  

    The notified body shall carrying out the procedure under the condition that the type examination certificate issued prior to the assessment remains valid for the subsystem subject to the application.

8.  The contracting entity must take all measures necessary in order that the manufacturing process (including assembly and integration of interoperability constituents by main contractors (19) when employed) ensures conformity of the subsystem with the type as described in the type-examination certificate and with the requirements of the TSI that apply to it.

9.  The application must enable the design, manufacture, installation, maintenance and operation of the subsystem to be understood, and shall enable conformity with the type as described in the type-examination certificate and the requirements of the TSI to be assessed.  

    The application must include:  

10. the technical documentation regarding the approved type, including the type examination certificate, as issued after completion of the procedure defined in Module SB (type-examination),  

    and, if not included in this documentation:  

11. a general description of the subsystem, overall design and structure,
12. the Infrastructure and/or Rolling Stock (subsystem) register, including all information as specified in the TSI,
13. conceptual design and manufacturing information, for example drawings, schemes of components, subassemblies, assemblies, circuits, etc.,
14. the technical documentation regarding the manufacture and the assembly of the subsystem,
15. the technical specifications, including European specification, that have been applied,
16. any necessary supporting evidence for the use of the above specifications, in particular where these European specification and the relevant clauses have not been applied in full,
17. evidence of conformity to other regulations deriving from the treaty (including certificates) for the production phase,
18. a list of the interoperability constituents, to be incorporated into the subsystem,
19. copies of the EC declarations of conformity or suitability for use with which said constituents must be provided and all the necessary elements defined in annex VI of the directives,
20. a list of manufacturers involved in the subsystem's design, manufacture, assembly and installation,  

    If the TSI requires further information for the technical documentation, this shall be included.

21. The notified body shall first examine the application concerning the validity of the type examination and the type examination certificate.  

    If the notified body considers the type examination certificate no longer remains valid or is not appropriate and that a new type examination is necessary, it shall justify its decision.  

    The notified body must carry out the appropriate examinations and tests in order to check the conformity of the subsystem with the type, as described in the type examination certificate and with the requirements of the TSI. The notified body shall examine and testing of every subsystem manufactured as a serial product, as specified in point 4

22. Verification by examination and testing of every subsystem (as a serial product)  

7.1. The notified body must carry out the tests, examinations and verifications, to ensure conformity of the subsystems, as serial products as provided for in the TSI. The examinations, tests and checking shall extend to the stages as provided for in the TSI:  

7.2. Each subsystem (as serial product) must be individually examined, tested and verified (20) in order to verify its conformity with the type as described in the type-examination certificate and the requirements of the TSI that apply to it. When a test is not set out in the TSI, (or in an European Standard quoted in the TSI), the relevant European Specifications or equivalent tests are to be used.

8.  The notified body may agree with the contracting entity (and the main contractors) the locations where the tests will be carried out and may agree that final testing of the subsystem and, whenever required in the TSI, tests or validation under full operating conditions, are carried out by the contracting entity under direct supervision and attendance of the notified body.  

The notified body shall have entrance for testing and verification purposes to production workshops, locations of assembly and installations, and where appropriate, prefabrication and testing facilities in order to carry out its tasks as provided for in the TSI.

9.  Where the subsystem meets the requirements of the TSI, the notified body must, draw up the certificate of conformity intended for the contracting entity, which in turn draws up the EC declaration of verification intended for the supervisory authority in the Member State where the subsystem is located and/or operates.  

These NB activities shall be based on the type examination and the tests, verifications and checks carried out on all serial products as indicated in point 7 and required in the TSI and/or in the relevant European specification,  

The EC declaration of verification and the accompanying documents must be dated and signed. The declaration must be written in the same language of the technical file and must contain at least the information included in Annex V of the Directive.

10. The notified body shall be responsible for compiling the technical file that has to accompany the EC declaration of verification. The technical file shall include at least the information indicated in Art.18 (3) of the Directives, and in particular as follows:  

11. all necessary documents relating to the characteristics of the subsystem
12. the Infrastructure and/or Rolling Stock (subsystem) register, including all information as specified in the TSI,
13. the list of interoperability constituents incorporated into the subsystem,
14. copies of the EC declarations of conformity and, where appropriate, of the EC declarations of suitability for use, which the constituents must be provided in accordance with Article 13 of the Directive, accompanied, where appropriate, by the corresponding documents (certificates, quality management system approvals and surveillance documents) issued by the notified bodies,
15. all elements relating to the maintenance, the conditions and limits for use of the subsystem,
16. all elements relating to the instructions concerning servicing, constant or routine monitoring, adjustment and maintenance,
17. the type-examination certificate for the subsystem and accompanying technical documentation, as defined in the Module SB (type-examination),
18. certificate of conformity of the notified body as mentioned in point 9, accompanied by corresponding calculation notes and countersigned by itself, stating that the project complies with the directive and the TSI, and mentioning, where appropriate, reservations recorded during performance of activities and not withdrawn. The certificate should also be accompanied, if relevant, by the inspection and audit reports drawn up in connection with the verification.

19. The records accompanying the certificate of conformity must be lodged with the contracting entity.  

The contracting entity must keep a copy of the technical file throughout the service life of the subsystem; it must be sent to any other Member State which so requests.

### Module SH2: Full quality management system with design examination

1.  This module describes the EC verification procedure whereby a notified body checks and certifies, at the request of an contracting entity or its authorised representative established within the Community, that a control-command subsystem:  

    -   complies with this TSI and any other relevant TSI, which demonstrate that the essential requirements (21) of Directive 2001/16/EC (22) have been met,
    -   complies with the other regulations deriving from the Treaty and may be placed in service.

2.  The notified body shall carry out the procedure, including a design examination of the subsystem, under the condition, that the contracting entity (23) and the main contractors involved are satisfying the obligations of point 3  

    The ‘main contractors’ refers to companies, whose activities contribute to fulfil the essential requirements of the TSI. It concerns:  

    -   the company responsible for the whole subsystem project (including in particular responsibility for subsystem integration),
    -   other companies only involved only in a part of the subsystem project (performing for example design, assembly or installation of the subsystem).  

    It does not refer to manufacturer sub contractors supplying components and interoperability constituents.

3.  For the subsystem that is subject of the EC verification procedure, the contracting entity or the main contractors, when employed, shall operate an approved quality management system for design, manufacture and final product inspection and testing as specified in point 5 and which shall be subject to surveillance as specified in point 6.  

    The main contractor responsible for the whole subsystem project (including in particular responsibility for subsystem integration), must operate in any case an approved quality management system for design, manufacture and final product inspection and testing, which shall be subject to surveillance as specified in point 6.  

    In the case that the contracting entity itself is responsible for the whole subsystem project (including in particular responsibility for subsystem integration) or that the contracting entity is directly involved in the design and/or production (including assembly and installation), it shall operate an approved quality management system for those activities, which shall be subject to surveillance as specified in point 6.  

    Applicants which are only involved in assembly and installation, may operate only an approved quality management system for manufacture and final product inspection and testing.

4.  EC verification procedure  

    4.1. The contracting entity must lodge an application for EC verification of the subsystem (through full quality management system with design examination), including co ordination of surveillance of the quality management systems as in points 5.4 and 6.6, with a notified body of its choice. The contracting entity must inform the manufacturers involved of his choice and of the application.  

    4.2. The application must enable the design, manufacture, assembly, installation, maintenance and operation of the subsystem to be understood, and shall enable conformity with the requirements of the TSI to be assessed.  

    The application must include:  

5.  name and address of the contracting entity or its authorised representative,
6.  the technical documentation including:
7.  a general description of the subsystem, overall design and structure,
8.  the technical design specifications, including European specifications, that have been applied,
9.  any necessary supporting evidence for the use of the above specifications, in particular where the European specifications and the relevant clauses have not been applied in full.
10. the test programme
11. the Infrastructure and/or Rolling Stock (subsystem)Register, including all information as specified in the TSI,
12. the technical documentation regarding the manufacture, the assembly of the subsystem,
13. a list of the interoperability constituents to be incorporated into the subsystem,
14. copies of the EC declarations of conformity or suitability for use with which the constituents must be provided and all the necessary elements defined in annex VI of the Directives,
15. evidence of conformity to other Regulations deriving from the Treaty (including certificates)
16. a list of all manufacturers, involved in the subsystem's design, manufacturing, assembly and installation,
17. conditions for use of the subsystem (restrictions of running time or distance, wear limits etc.),
18. conditions for maintenance and technical documentation regarding the maintenance of the subsystem
19. any technical requirement that must be taken into account during production, maintenance or operation of the subsystem
20. the explanation, of how all stages, as mentioned in point 5.2, are covered by quality management systems of the mains contractor(s) and/or of the contracting entity, if involved, and the evidence of their effectiveness,
21. indication of the notified body(ies) responsible for the approval and surveillance of these quality management systems.  

    4.3. The contracting entity shall present the results of examinations, checking and tests (24), including type tests when required, carried out by its appropriate laboratory or on their behalf.  

    4.4. The notified body must examine the application concerning the design examination and assess the results of the tests. Where the design meets the provisions of the Directive and of the TSI that apply to it must issue a design examination report to the applicant. The report shall contain the conclusions of the design examination, conditions for its validity, the necessary data for identification of the design examined and, if relevant, a description of the subsystem's functioning.  

    If the contracting entity is denied a design examination report, the notified body must provide detailed reasons for such denial.  

    Provision must be made for an appeals procedure.

22. Quality management system  

    5.1. The contracting entity, if involved, and the main contractors, when employed, must lodge an application for assessment of their quality management systems with a notified body of their choice.  

    The application must include:  

23. all relevant information for the subsystem envisaged,
24. the quality management system documentation.  

    For those only involved in a part of the subsystem project, the information to be provided is only that for the relevant part.  

    5.2. For the contracting entity or the main contractor responsible for the whole subsystem project, the quality management system shall ensure overall compliance of the subsystem with the requirements of the TSI.  

    The quality management system(s), for other main contractor(s), has (have) to ensure compliance of their relevant contribution to the subsystem, with the requirements of the TSI.  

    All the elements, requirements and provisions adopted by the applicants must be documented in a systematic and orderly manner in the form of written policies, procedures and instructions. This quality management system documentation shall ensure a common understanding of the quality policies and procedures such as quality programmes, plans, manuals and records.  

    The system must contain in particular an adequate description of the following items :  

25. for all applicants:
26. the quality objectives and the organisational structure,
27. the corresponding manufacturing, quality control and quality management techniques, processes and systematic actions that will be used,
28. the examinations, checking and tests that will be carried out before, during and after design, manufacture, assembly and installation and the frequency with which they will be carried out,
29. the quality records, such as inspection reports and test data, calibration data, qualification reports of the personnel concerned, etc.,
30. for the main contractors, as far as relevant for their contribution to the design of the subsystem :
31. the technical design specifications, including European specifications (25), that will be applied and, where the European specifications will not be applied in full, the means that will be used to ensure that the requirements of the TSI that apply to the subsystem will be met,
32. the design control and design verification techniques, processes and systematic actions that will be used when designing the subsystem,
33. the means to monitor the achievement of the required design and subsystem quality and the effective operation of the quality management systems in all phases including production.
34. and also for the contracting entity or the main contractor responsible for the whole subsystem project:
35. responsibilities and powers of the management with regard to overall subsystem quality, including in particular the subsystem integration management.  

    The examinations, tests and checking shall cover all of the following stages:  

36. overall design,
37. structure of the subsystem, including, in particular, civil-engineering activities, constituent assembly, final adjustment,
38. final testing of the subsystem,
39. and, where specified in the TSI, the validation under full operation conditions.  

    5.3 The notified body chosen by the contracting entity must examine, if all stages of the subsystem as mentioned in point 5.2 are sufficiently and properly covered by the approval and surveillance of the quality management system(s) of the applicant(s) (26).  

    If the compliance of the subsystem with the requirements of the TSI is based on more than one quality management system, the notified body shall examine in particular,  

40. if the relations and interfaces between the quality management systems are clearly documented
41. and if overall responsibilities and powers of the management for the compliance of the whole entire subsystem for the main contractor are sufficiently and properly defined.  

    5.4. The notified body referenced in point 5.1 must assess the quality management system to determine whether it satisfies the requirements of point 5.2. It presumes compliance with these requirements if the manufacturer implements a quality system for design, production, final product inspection and testing in respect of the harmonised standard EN/ISO 9001/2000, which takes into consideration the specificity of the interoperability constituent for which it is implemented.  

    When an applicant operates a certified quality management system, the notified body shall take this into account in the assessment.  

    The audit shall be specific for the subsystem concerned, taking into consideration the specific contribution of the applicant to the subsystem. The auditing team must have at least one member experienced as an assessor in the subsystem technology concerned.  

    The evaluation procedure shall include an assessment visit to the applicant's premises.  

    The decision must be notified to the applicant. The notification must contain the conclusions of the examination and the reasoned assessment decision.  

    5.5. The contracting entity, if involved, and the main contractors shall undertake to fulfil the obligations arising out of the quality management system as approved and to uphold it so that it remains adequate and efficient.  

    They must keep the notified body that has approved their quality management system informed of any significant change that will affect the fulfilment of the requirements by the subsystem.  

    The notified body must evaluate any modifications proposed and decide whether the amended quality management system will still satisfy the requirements of point 5.2 or whether a reassessment is required.  

    It shall notify its decision to the applicant. The notification shall contain the conclusions of the examination and the reasoned assessment decision.  

42. Surveillance of the quality management system(s) under the responsibility of the notified body  

6.1. The purpose of surveillance is to make sure that the contracting entity, if involved, and the main contractors duly fulfil the obligations arising out of the approved quality management system(s).  

6.2. The contracting entity, if involved, and the main contractors must send the notified body referenced in point 5.1. (or have sent) all the documents needed for that purpose and in particular the implementation plans and technical records concerning the subsystem (as far as relevant for the specific contribution of the applicant to the subsystem), including:  

-   the quality management system documentation, including the particular means implemented to ensure that:
-   for the contracting entity or the main contractor, responsible for the whole subsystem project, overall responsibilities and powers of the management for the compliance of the whole entire subsystem are sufficiently and properly defined,
-   for each applicant, the quality management system is correctly managed for achieving integration at subsystem level,
-   the quality records as foreseen by the design part of the quality management system, such as results of analyses, calculations, tests, etc.,
-   the quality records as foreseen by the manufacturing part (including assembly, installation and integration) of the quality management system, such as inspection reports and test data, calibration data, competency records of the personnel concerned, etc.  

6.3. The notified body must periodically carry out audits to make sure that the contracting entity, if involved, and the main contractors maintain and apply the quality management system and shall provide an audit report to them. When they operate a certified quality management system, the notified body shall take this into account in the surveillance.  

The frequency of the audits shall be at least once a year, with at least one audit during the time period of performing the relevant activities (design, manufacture, assembly or installation) for the subsystem being the subject of the EC verification procedure mentioned in point 7.  

6.4. Additionally the notified body may pay unexpected visits to the sites mentioned in point 5.2 of the applicant(s). At the time of such visits, the notified body may conduct complete or partial audits and may carry out or cause to be carried out tests in order to check the proper functioning of the quality management system where necessary. It must provide the applicant(s) with an inspection report and, audit and/or test reports as appropriate.  

6.5. The notified body chosen by the contracting entity and responsible for the EC verification, if not carrying out the surveillance of all the quality management system(s) concerned as under point 5, must co ordinate the surveillance activities of any other notified bodies responsible for that task, in order :  

-   to be ensured that correct management of interfaces between the different quality management systems relating to subsystem integration has been performed,
-   to collect, in liaison with the contracting entity, the necessary elements for the assessment to guarantee the consistency and the overall supervision of the different quality management systems.  

This coordination includes the right of the notified body:  

-   to receive all documentation (approval and surveillance), issued by the other notified body(s),
-   to witness the surveillance audits as in point 5.4,
-   to initiate additional audits as in point 5.5 under its responsibility and together with the other notified body(s).

-   The notified body as referenced under point 5.1. must have entrance for inspection purposes, audit and surveillance to the locations of design, building sites, production workshops, locations of assembly and installation, storage areas and. where appropriate, prefabrication or testing facilities and, more general, to all premises which it considers necessary for its task, in accordance with the applicant's specific contribution to the subsystem project.

-   The contracting entity, if involved, and the main contractors must, for a period of 10 years after the last subsystem has been manufactured, keep at the disposal of the national authorities:  

-   the documentation referenced in the second indent of the second subparagraph of point 5.1,
-   the updating referenced in the second subparagraph of point 5.5,
-   the decisions and reports from the notified body which are referenced in the points 5.4, 5.5 and 6.4.

-   Where the subsystem meets the requirements of the TSI, the notified body must then, based on the design examination and the approval and surveillance of the quality management system (s), draw up the certificate of conformity intended for the contracting entity, who shall in turn draw up the EC declaration of verification intended for the supervisory authority in the Member State within which the subsystem is located and/or operates.  

    The EC declaration of verification and the accompanying documents must be dated and signed. The declaration must be written in the same language of the technical file and must contain at least the information included in Annex V of the Directive.

-   The notified body chosen by the contracting entity shall be responsible for compiling the technical file that has to accompany the EC declaration of verification. The technical file shall include at least the information indicated in Article 18(3) of the Directive, and in particular as follows:  

-   all necessary documents relating to the characteristics of the subsystem,
-   the list of interoperability constituents incorporated into the subsystem,
-   copies of the EC declarations of conformity and, where appropriate, of the EC declarations of suitability for use, which the constituents must be provided in accordance with Article 13 of the Directive, accompanied, where appropriate, by the corresponding documents (certificates, quality management system approvals and surveillance documents) issued by the notified,
-   evidence of conformity to other regulations deriving from the treaty (including certificates),
-   all elements relating to the maintenance, the conditions and limits for use of the subsystem,
-   all elements relating to the instructions concerning servicing, constant or routine monitoring, adjustment and maintenance,
-   certificate of conformity of the notified body as mentioned under point 9, accompanied by corresponding calculation notes and countersigned by itself, stating that the project complies with the Directive and the TSI, and mentioning, where appropriate, reservations recorded during performance of the activities and not withdrawn. The certificate should also be accompanied, if relevant, by the inspection and audit reports drawn up in connection with the verification, as mentioned in points 6.4 and 6.5;
-   the Infrastructure and/or Rolling Stock (subsystem) Register, including all information as specified in the TSI.  

-   Each notified body must communicate to the other notified bodies the relevant information concerning the quality management system approvals and the EC design examination reports, which it has issued, withdrawn or refused.  

The other notified bodies may receive on request copies of:  

-   the quality management system approvals and additional approvals issued and
-   the EC design examination reports and additions issued.

-   The records accompanying the certificate of conformity must be lodged with the contracting entity  

The contracting entity must keep a copy of the technical file throughout the service life of the subsystem; it must be sent to any other Member State which so requests.

### Module SG: Unit Verification

1.  This module describes the EC verification procedure whereby a notified body checks and certifies, at the request of an contracting entity or its authorised representative established within the Community, that a control-command subsystem:  

2.  complies with this TSI and any other relevant TSI, which demonstrate that the essential requirements (27) of Directive 2001/16/EC (28) have been met,
3.  complies with the other regulations deriving from the Treaty,  

    and may be placed in service.

4.  The contracting entity (29) must lodge an application for EC verification (through unit verification) of the subsystem with a notified body of his choice.  

    The application shall include:  

5.  name and address of the contracting entity or its authorised representative,
6.  the technical documentation.

7.  The technical documentation must enable the design, manufacture, installation and operation of the subsystem to be understood, and shall enable conformity assessment with the requirements of the TSI.  

    The technical documentation must include:  

8.  a general description of the subsystem, its overall design and structure,
9.  the Infrastructure and/or Rolling Stock (subsystem) register, including all information as specified in the TSI,
10. conceptual design and manufacturing information, for example drawings, schemes of components, sub-assemblies, assemblies, circuits, etc.,
11. descriptions and explanations necessary for the understanding of the design and manufacturing information and the operation of the subsystem,
12. the technical specifications, including European specifications (30), that have been applied,
13. any necessary supporting evidence for the use of the above specifications, in particular where European specifications and the relevant clauses have not been applied in full,
14. a list of the interoperability constituents to be incorporated into the subsystem,
15. copies of the EC declarations of conformity or suitability for use with which said constituents must be provided and all the necessary elements defined in annex VI of the directives,
16. evidence of conformity with other regulations deriving from the treaty (including certificates),
17. technical documentation regarding the manufacture and the assembly of the subsystem,
18. a list of manufacturers involved in the subsystem's design, manufacturing, assembly and installation,
19. conditions for use of the subsystem (restrictions of running time or distance, wear limits etc.),
20. conditions for maintenance and technical documentation regarding the maintenance of the subsystem,
21. any technical requirement that must be taken into account during production, maintenance or operation of the subsystem,
22. results of design calculations made, examinations carried out, etc.,
23. all other appropriate technical evidences, which can demonstrate that previous checking or tests have been successfully performed, under comparable conditions, by independent and competent bodies,  

    If the TSI requires further information for the technical documentation, this shall be included.

24. The notified body must examine the application and the technical documentation, and identify the elements which have been designed in accordance with the relevant provisions of the TSI and the European specifications, as well as the elements which have been designed without applying the relevant provisions of those European specifications.  

    The notified body must examine the subsystem and perform (or participate to) the appropriate and necessary tests to establish whether, where the relevant European specifications have been chosen, these have actually been applied or whether the solutions adopted meet the requirements of the TSI when the appropriate European specifications have not been applied;  

    The examinations, tests and checks shall extend to the following stages as provided for in the TSI:  

25. overall design,
26. structure of the subsystem, including, in particular and when relevant, civil-engineering activities, constituent assembly, overall adjustments,
27. final testing of the subsystem,
28. and, whenever specified in the TSI, the validation under full operational conditions.  

    The notified body shall take into account previous checking or tests that have been successfully performed, under comparable conditions by other independent and competent bodies (31). The notified body will then decide as to whether it shall use the results of these checks or tests. If it accepts, then the notified body shall investigate the evidences of these previous checking or test and shall establish the conformity of their results with the requirement of the TSI. In all case the notified body keeps the final responsibility of them.

29. The notified body may agree with the contracting entity the locations where the tests will be carried out and may agree that final subsystem tests and, whenever required in the TSI, tests in full operating conditions, are carried out by the contracting entity under direct supervision and attendance of the notified body.

30. The notified body must have entrance for testing and verification purposes to the locations of design, building sites, production workshops, locations of assembly and installations, and where appropriate, prefabrication and testing facilities in order to carry out its tasks as provided for in the TSI.

31. Where the subsystem meets the requirements of the TSI, the notified body must then, based on the tests, verifications and checks carried out as required in the TSI and/or in the relevant European specifications, draw up the certificate of conformity intended for the contracting entity, who shall in turn draw up the EC declaration of verification intended for the supervisory authority in the Member State where the subsystem is located and/or operates.  

    The EC declaration of verification and the accompanying documents must be dated and signed. The declaration must be written in the same language as the technical file and must contain at least the information included in Annex V of the Directive.

32. The notified body shall be responsible for compiling the technical file that has to accompany the EC declaration of verification. The technical file has to include at least the information indicated in Article 18(3) of the Directive, and in particular as follows :  

33. all necessary documents relating to the characteristics of the subsystem,
34. the list of interoperability constituents incorporated into the subsystem,
35. copies of the EC declarations of conformity and, where appropriate, of the EC declarations of suitability for use, which the constituents must be provided in accordance with Article 13 of the Directive, accompanied, where appropriate, by the corresponding documents (certificates, quality management system approvals and surveillance documents) issued by the notified bodies,
36. all elements relating to the maintenance, the conditions and limits for use of the subsystem,
37. all elements relating to the instructions concerning servicing, constant or routine monitoring, adjustment and maintenance,
38. certificate of conformity of the notified body as mentioned in point 7, accompanied by corresponding calculation notes and countersigned by itself, stating that the project complies with the directive and the TSI, and mentioning, where appropriate, reservations recorded during performance of activities and not withdrawn; the certificate should also be accompanied, if relevant, by the inspection and audit reports drawn up in connection with the verification,
39. evidence of conformity with other regulations deriving from the treaty (including certificates),
40. the Infrastructure and/or Rolling Stock (subsystem) register, including all information as specified in the TSI.

41. The records accompanying the certificate of conformity must be lodged with the contracting entity. The contracting entity must keep a copy of the technical file throughout the service life of the subsystem; it must be sent to any other Member State which so requests.

(1)  The definition of a European specification is indicated in Directives 96/48/EC and 2001/16/EC. The guide for application of HS TSIs explains the way to use the European specifications.

(2)  The definition of a European specification is indicated in Directives 96/48/EC and 2001/16/EC. The guide for application of HS TSIs explains the way to use the European Specifications.

(3)  The manufacturer's discretion may be limited in specific TSIs.

(4)  The definition of a European specification is indicated in Directives 96/48/EC and 2001/16/EC. The guide for application of HS TSIs explains the way to use the European Specifications.

(5)  The definition of a European specification is indicated in Directives 96/48/EC and 2001/16/EC. The guide for application of HS TSIs explains the way to use the European Specifications.

(6)  The presentation of the results of the tests can be at the same time as the application or later.

(7)  The essential requirements are reflected in the technical parameters, interfaces and performance requirements, which are set out in Chapter 4 of the TSI.

(8)  This module could be used in the future when the TSIs of HS Directive 96/48/EC are updated.

(9)  In the module, ‘the contracting entity’ means ‘the subsystem contracting entity, as defined in the Directive or his authorised representative established within the Community’.

(10)  The relevant section of a TSI may define specific requirements in this regard.

(11)  The definition of a European specification is indicated in Directives 96/48/EC and 2001/16/EC. The guide for application of HS TSIs explains the way to use the European Specifications.

(12)  The essential requirements are reflected in the technical parameters, interfaces and performance requirements, which are set out in Chapter 4 of the TSI.

(13)  This module could be used in the future when the TSIs of the HS Directive 96/48/EC are updated.

(14)  In the module, ‘the contracting entity’ means ‘the subsystem contracting entity, as defined in the Directive, or his authorised representative established within the Community’.

(15)  For the rolling stock TSI, the notified body may participate to the final in service test of locomotives or train set in the conditions specified in the relevant chapter of the TSI.

(16)  The essential requirements are reflected in the technical parameters, interfaces and performance requirements set out in Chapter 4 of the TSI.

(17)  This module could be used in the future when the TSIs of HS Directive 96/48/EC are updated.

(18)  In the module, ‘the contracting entity’ means ‘the subsystem contracting entity, as defined in the Directive, or his authorised representative established within the Community’.

(19)  The ‘main contractors’ refers to companies, whose activities contribute to fulfil essential requirements of the TSI. It concerns the company that can be responsible for the whole subsystem project or other companies only involved in a part of the subsystem project, (performing for example assembly or installation of the subsystem).

(20)  In particular, for the rolling stock TSI, the notified body will participate in the final in service testing of rolling stock or train set. This will be indicated in the relevant chapter of the TSI.

(21)  The essential requirements are reflected in the technical parameters, interfaces and performance requirements, which are set out in Chapter 4 of the TSI.

(22)  This module could be used in the future when the TSIs of the HS directive 96/48/EC are updated.

(23)  In the module, ‘the contracting entity’ means ‘the subsystem contracting entity, as defined in the Directive, or his authorised representative established within the Community’.

(24)  The presentation of the results of the tests can be at the same time as the application or later.

(25)  The definition of an European specification is indicated in Directives 96/48/EC and 2001/16/EC and in the guidelines for application of HS TSIs.

(26)  For the rolling stock TSI, the notified body may participate to the final in service test of rolling stock or train set in the conditions specified in the relevant chapter of the TSI.

(27)  The essential requirements are reflected in the technical parameters, interfaces and performance requirements, which are set out in Chapter 4 of the TSI.

(28)  This module could be used in the future when the TSIs of HS Directive 96/48/EC are updated.

(29)  In the module, ‘the contracting entity’ means ‘the subsystem contracting entity, as defined in the Directive, or his authorised representative established within the Community’.

(30)  The definition of an European specification is indicated in Directives 96/48/EC and 2001/16/EC and in the guidelines for application of HS TSIs.

(31)  The conditions to entrust previous checking and tests must be similar than the conditions, respected by a notified body to subcontract activities (see point 6.5 of the Blue Guide on the New Approach); in particular, the notified body is allowed to take into account these appropriate evidences can be solely if these bodies shall respect the same criteria of independence and competence than the notified bodies

# ANNEX F

## CONFORMITY ASSESSMENT PROCEDURE

### Assessment of maintenance arrangements

1.  This conformity assessment procedure describes that part of the procedure by which a Body authorised by the MS ascertains and attests that the maintenance arrangements, representative of the maintenance envisaged, meet the provisions of the relevant TSI and ensure the respect of the basic parameters and essential requirements during the subsystem life.

2.  The application for assessment of the maintenance arrangements must be lodged by the contracting entity (or his authorised representative established within the Community), which proposes the maintenance arrangements, with the body authorised by the MS.  

    The application shall include:  

3.  the name and address of the contracting entity and if the application is lodged by the authorised representative, his name and address in addition,
4.  a written declaration that the same application has not been lodged with any other Body,
5.  any technical requirement, resulting from the design phase, that must be taken into account during maintenance,
6.  the maintenance arrangements documentation, as described in point 3,
7.  the technical documentation as described in point 4.  

    The copy of the maintenance arrangement documentation submitted shall be the final version approved by the applicant.  

    The body authorised by the MS may request further copies if needed for carrying out the assessment.

8.  The maintenance arrangements documentation shall contain at least the following elements:  

9.  a description of how the maintenance arrangements shall be implemented, used and controlled,
10. details of all maintenance required to be carried out, including its frequency,
11. operational scenarios showing how necessary feedback information (and all other information relating to the maintenance) flows around the subsystem and other product/subsystems to support the process of maintenance,
12. procedures (or reference to procedures) for specific processes according to the product/subsystem maintenance operations,
13. a procedure for the management of modifications and updating of the maintenance arrangements,
14. a description of any hardware and software required to read the maintenance arrangements,
15. a description of all necessary elements to make the maintenance arrangements operational (1).

16. The technical documentation must enable assessment of conformity of the maintenance arrangements with the provisions of the TSI. It must, as far as relevant for such assessment, cover the different phases of development of the maintenance arrangements.  

    The technical documentation, which justifies the maintenance arrangements, shall contain:  

17. a general type-description, (overview of how the subsystem works and a description of the technical functionality),
18. a specification stating the conditions and the context within which the subsystem shall be used and maintained,
19. demonstration of consistency between the requirements of the TSI the maintenance organisation, the technical functionality and the maintenance arrangements,
20. descriptions, explanations and all the records necessary for understanding the development of the maintenance arrangements,
21. records of the work done to validate the maintenance arrangements,
22. records of the analysis of equipment used and people affected by the maintenance arrangements,
23. conditions for use and maintenance of the interoperability constituent (restrictions of running time or distance, wear limits, etc.),
24. a list of the technical specifications, against which the maintenance arrangements of the subsystem have been validated.

25. The body authorised by the MS must :  

26. identify the relevant provisions of the TSI with which the maintenance arrangement must comply,
27. check that the maintenance arrangements documentation and technical documentation are complete and in accordance with the points 3 and 4,
28. perform an examination of each development phase of the maintenance arrangements and their results to evaluate:
29. if each phase has been managed in a controlled manner,
30. the capability to fulfil the requirements for conformity for the maintenance arrangements,
31. document its findings with regards to compliance of the maintenance arrangement with the TSI provisions.

32. Where the maintenance arrangements meet the provisions of the TSI, the body authorised by the MS shall issue the maintenance arrangements examination report to the applicant. The report shall contain the name and address of the contracting entity, conclusions of the examination, conditions for its validity, reference to the subsystem maintained and the necessary data for identification of the maintenance arrangements.  

    The relevant parts of the technical documentation, including the description of maintenance arrangements and their conditions of implementation, must be annexed to the report and a copy kept by the body authorised by the MS.  

    If the contracting entity is denied a maintenance arrangements examination report, the body authorised by the MS must provide detailed reasons for such denial.  

    Provision must be made for an appeals procedure.  

    (1)  For this, it is necessary that the maintenance arrangements define for example:  

33. the procedures and instructions for implementation,
34. the training or qualifications needs,
35. checks, validation, surveillance, inspections, tests, records and the criteria of acceptance of the subsystem when the different stages of the maintenance operations shall be carried out,
36. conditions of use of specific tools or utilities for maintenance operations or tests.

# ANNEX G

## OPEN POINTS

PRIORITY OF AN OPEN POINT

It shall be distinguished between two priorities

Priority 1 (P1): The most urgent part

Priority 2 (P2): The least urgent part

**Interfaces**

Section 4.3

Level crossing functionality (P1)

Interfaces with OPE TSI (P1)

Interfaces with TSI rolling stock traction units and coaches (P1)

**Annex A**

|           |                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| --------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Index 1   | FRS (for the subject of level crossings) (P1 linked to LX)                                                                                                                                                                                                                                                                                                                                                                        |
| Index 16  | The FFFIS for Euroloop is currently available as a draft only (UNISIG SUBSET-044 version 2.1.0) due to the shift of the frequency band. It shall become legally binding once the open issues (e.g. frequency allocation, compatibility with existing systems, cross tests) have been resolved and a final version produced. All parties involved are committed to support the work to have a final version available by mid-2005. |
| Index 24  | Clarification and amendment specification, for awakening (P1)                                                                                                                                                                                                                                                                                                                                                                     |
| Index B32 | Guideline for references (P1)                                                                                                                                                                                                                                                                                                                                                                                                     |
| Index 36  | STM test specification (P1)                                                                                                                                                                                                                                                                                                                                                                                                       |
| Index 28  | Reliability — availability requirements (P1)                                                                                                                                                                                                                                                                                                                                                                                      |
| Index 41  | JRU Test Specification (P1) linked to Index 55                                                                                                                                                                                                                                                                                                                                                                                    |
| Index 42  | Requirements for vigilance (P2)                                                                                                                                                                                                                                                                                                                                                                                                   |
| Index 44  | Odometry FIS (P2)                                                                                                                                                                                                                                                                                                                                                                                                                 |
| Index 45  | K interface (P1)                                                                                                                                                                                                                                                                                                                                                                                                                  |
| Index 47  | Requirements on risk and hazard analysis for interoperability (P1)                                                                                                                                                                                                                                                                                                                                                                |
| Index 48  | Test specification for mobile equipment GSM-R(P1)                                                                                                                                                                                                                                                                                                                                                                                 |
| Index 50  | Test specification for Euroloop (P1)                                                                                                                                                                                                                                                                                                                                                                                              |
| Index 51  | Ergonomic aspects of the DMI (P1)                                                                                                                                                                                                                                                                                                                                                                                                 |
| Index 53  | ETCS values of variables controlled by UIC (P1)                                                                                                                                                                                                                                                                                                                                                                                   |
| Index 54  | Quality of service user requirements (provisionally) (P1)                                                                                                                                                                                                                                                                                                                                                                         |
| Index 55  | Juridical recorder baseline requirements (P1 for the overall)                                                                                                                                                                                                                                                                                                                                                                     |
| Index 57  | Requirements on pre-fitting of ERTMS on-board equipment (P1)                                                                                                                                                                                                                                                                                                                                                                      |
| Index 58  | RBC — RBC interface (P1)                                                                                                                                                                                                                                                                                                                                                                                                          |
| Index 59  | Requirements on pre-fitting of ERTMS track side equipment (P1)                                                                                                                                                                                                                                                                                                                                                                    |
| Index 60  | ETCS version management (P1)                                                                                                                                                                                                                                                                                                                                                                                                      |
| Index 61  | GSM-R version management (P1)                                                                                                                                                                                                                                                                                                                                                                                                     |

**GSM-R:**

Interconnection and roaming between GSM-R networks (P1)
Border crossing (P1)
Definition of operational rules for GSM-R (P1)
GPRS and ASCI (P2)
GSM-R version management (change control management) (P1)

**Annex A — Appendix 1: (P1)**

|       |                                                                            |
| ----- | -------------------------------------------------------------------------- |
| 2.1.5 | Relation between axle distance and wheel diameter                          |
| 3.2.1 | Metal free space around wheels                                             |
| 3.3.1 | Metal mass of a vehicle                                                    |
| 3.5.5 | Additional requirements on locomotives and multiple units                  |
| 4.1   | Use of sanding equipment                                                   |
| 4.2.1 | Use of composite brake blocks                                              |
| 5.1.1 | Electromagnetic interferences (traction current)                           |
| 5.3.1 | Electromagnetic interferences (electric, magnetic, electromagnetic fields) |

**Annex A — Appendix 2: (P1)**

HABD

**Annex B, part 4**

**ETCS Class 1 CCM related open points**

Specification of some of the ETCS variables (P1)

**Additional interfaces**

Functionality and interfaces of staff protection systems to the signalling system (P2)

Interface with service brake. This will have to be examined during the elaboration of the TSI for rolling stock.

# ANNEX H

**SYNTHESIS OF ETCS-NET CORRIDORS**

**ETCS-Net conventional rail sections in Annex II of Decision No 884/2004/EC  (1)**

**Railway axis Berlin-Verona/Milan-Bologna-Naples-Messina-Palermo**

-   Halle/Leipzig-Nuremberg
    \-Nuremberg-Munich
    \-Munich-Kufstein
    \-Kufstein-Innsbruck
    \-Brenner Tunnel, cross-border section;
    \-Verona-Napolles
    \-Milano-Bologna

**Betuwe line**

**Railway axis Lyon-Trieste-Divaèa/Koper-Divaèa-Ljubljana-Budapest-Ukrainian border**

\-Lyon-St Jean de Maurienne

\-Mont-Cenis tunnel, cross-border section;

\-Bussoleno-Turin

\-Turin-Venice

\-Venezia-Ronchi Sud-Trieste Divaèa

\-Koper-Divaèa -Ljubljana
\-Ljubljana-Budapest

**Multimodal axis Portugal/Spain-rest of Europe**

-   La Coruña– Porto
    \-Porto-Valladolid

**Nordic triangle railway/road axis**

-   Railway projects in Sweden including Stockholm-Malmö, Stockholm-Charlottenberg (Norwegian border) and Kornsjö (Norwegian border)-Göteborg-Malmö.
    \-Kerava-Lahti
    \-Helsinki-Vainikkala (Russian border)

**Freight railway axis Sines-Madrid-Paris**

\-New high-capacity rail axis across the Pyrenees;

\-Sines-Badajoz
\-Algeciras-Bobadilla

**Railway axis Paris-Strasbourg-Stuttgart-Vienna-Bratislava**

-   Baudrecourt-Strasbourg-Stuttgart with the Kehl bridge as cross-border section
    \-Stuttgart-Ulm
    \-Munich-Salzburg, cross-border section;
    \-Salzburg-Vienna
    \-Vienna-Bratislava, cross-border section

**Fehmarn Belt railway axis**

-   Fehmarn Belt fixed rail/road link
    \-Railway for access in Denmark from Öresund
    \-Railway for access in Germany from Hamburg
    \-Railway Hanover-Hamburg/Bremen

**Railway axis Athens-Sofia-Budapest-Vienna-Prague-Nuremberg/Dresden**

-   Greek/Bulgarian border-Kulata-Sofia-Vidin/Calafat
    \-Curtici-Brasov (towards Buchurest and Constanta)
    \-Budapest-Vienna, cross-border section;
    \-Bøeclav-Prague-Nuremberg, with Nuremberg-Prague as cross-border section.
    \-Railway axis Prague-Linz

**Railway axis Gdansk-Warszaw-Brno/Bratislava-Vienna**

-   Gdansk-Warszaw-Katowice
    \-Katowice-Bøeclav
    \-Katowice-Zilina-Nove Mesto n.V.

**Railway axis Lyon/Genoa-Basel-Duisburg-Rotterdam/Antwerp**

-   Lyon-Mulhouse-Mülheim (2), with Mulhouse-Mülheim as cross-border section
    \-Genoa-Milano/Novara-Swiss border
    \-Basel-Karlsruhe
    \-Frankfurt (or Mainz)-Mannheim;
    \-Duisburg-Emmerich
    \-‘Iron Rhine’ Rheidt-Antwerp, cross-border section

**Railway/road axis Ireland/United Kingdom/continental Europe**

-   Felixstowe-Nuneaton
-   Crewe-Holyhead

**‘Rail Baltica’ axis Warsaw-Kaunas-Riga-Tallinn-Helsinki**

-   Warsaw-Kaunas-Vilnius
    \-Kaunas-Riga
    \-Riga-Tallinn

**‘Eurocaprail’ on the Brussels-Luxembourg-Strasbourg railway axis**

-   Brussels-Luxembourg-Strasbourg (2012).

**ETCS-Net conventional rail sections not covered by Annex II of Decision No 884/2004/EC. Set I  (3)**

**TEN Corridor II — E20 in the Berlin-Warsaw axis, Poland**

**TEN Corridor III — E30 between western border (Zgorzelec) and Cracow, Poland**

**TINA/AGTC double track line CE-59 — north south traffic from Scandinavia to Balkans, Poland.**

**Budapest–Bucharest–Constanta (part of Pan-European Corridor IV).**

**Ljubljana–Zagreb/Belgrade/Bar/Skopje–Thessaloniki (part of Pan-European Corridor X).**

**ETCS-Net conventional rail sections not covered by Annex II of Decision No 884/2004/EC. Set II**

**Antwerp-Athus/Bettembourg-Basel-Milan**

**Hallsberg/Mjölby, Sweden**

**ETCS on Oresund connection through Denmark over Storebelt link**

**Aachen — Horka/Frankfurt (O), Germany**

**Germany**

-   Kehl-Salzburg
-   Flensburg–Kufstein
-   Emmerich–Basel some parts through Germany
-   Hamburg–Bad Schandau
-   Darmstart–Passau

**France**

-   Metz–Dijon–Lyon–Avignon–Perpignan (Spanish border)
-   Le Havre–Rouen–Amien–Arras
-   Paris–Tours–Bordeaux–Dax
-   Paris–Reims–Metz (TGV EST)
-   Paris–Macon–Lyon (TGV Sud-Est)
-   Calais–Metz

**Stockholm-Nyland-Umea**

**ETCS-Net high-speed rail sections  (4)**

**High-speed railway axis Paris-Brussels/Brussels-Cologne-Amsterdam-London**

-   Channel Tunnel-London
-   Brussels-Liège-Cologne
-   Brussels-Rotterdam-Amsterdam

**High-speed railway axis of south-west Europe**

-   Lisbon/Porto-Madrid
-   Madrid-Barcelona
-   Cordoba — Seville
-   Barcelona-Figueras-Perpignan
-   Perpignan-Montpellier
-   Montpellier-Nîmes
-   Madrid-Vitoria-Irún/Hendaye
-   Irún/Hendaye-Dax, cross-border section
-   Dax-Bordeaux
-   Bordeaux-Tours

**High-speed railway axis east**

-   Paris-Baudrecourt
-   Metz-Luxembourg
-   Saarbrücken-Mannheim

**West Coast Main Line**

**High-speed rail interoperability on the Iberian peninsula**

-   Madrid-Andalucía
-   North-east
-   Madrid-Levante and Mediterranean
-   North/North-west corridor, including Vigo-Porto
-   Extremadura

(1)  The implementation of ERTMS/ETCS in the high-speed rail sections of projects included in this list are covered by Decision 2002/731/EC.

(2)  Including the TGV Rhine-Rhône, minus the western branch.

(3)  Projects wholly or partly situated in Member States where Regulations (EC) No 1260/1999 and (EC) No 1264/1999 (Cohesion Funds) apply.

(4)  Implementation covered by Decision 2002/731/EC.
