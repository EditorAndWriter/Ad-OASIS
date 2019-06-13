# Ad-OASIS
Requirements for verifiable OMID SDK caching of onboard ad impression beacons
## Introduction
The onboard advertising marketplace intrinsically encompasses a diversity of metadata interfaces.
<figure>
	<img src="Figures/General Architecture.png" />
	<figcaption>Figure 1: Numerous Interfaces</figcaption>
</figure>


Because mainstream advertisers often seek automated access to the total available market (TAM), uniform workflow specifications will increase the attractiveness of each individual publishers' inventory.
## Scope
This specification establishes commonality between various onboard advertising workflow instantiations. Implementation consistency will facilitate relationships with other entities in the advertising industry workflow such as well-known verification providers.
## Terms and Definitions  
**Well-Known Verification Providers:**
vendors of anti-fraud services - examples include Moat, Double-Verify, IAS

**OMID SDK:**
IAB Open Measurement Software Development Kit 
## Business Requirements
### Feature Functionality
Onboard advertising ecosystems shall support commercial message presentations that are manditory. These flight phase specific advertisement availabilities include messages that are presented automatically when a passenger initially interacts with a seat back interface. Manditory presentation features shall also support advertisements that are presented automatically when a passenger owned device initally connects to an onboard system.

### Verification Provider IVT (anti-ad-fraud) Mileposts
+ Impressions
+ Viewability
+ Quartiles
+ Originating IP address of beacons 
+ Time stamp consistency
+ Chain of custody records
### Reporting Workflow Integrity
Beacon logs shall be made available to well-known verification providers in a timely manner.
## Interface Considerations
Ad Start, Quartiles, and other impression verification data formats shall conform to OMID API Version 1.0 (https://iabtechlab.com/omsdk/docs/api)
### Environmental Data to be Gathered
+ Content adjacency
+ Ad server ID
+ Tail number relationship to ad server
+ Various 429 data bus items such as time of day, flight number, elapsed time, phase of flight, and city pairs
+ Chain of custody records
### Reporting Workflow Integrity
Beacon logs shall be made accessible to well-known verification providers in a timely manner.

 
