
<!--
title: Algeria
description: Algeria (DAAA)
-->

# Algeria (DAAA)

## Scope

ATC members are expected to practise the defined procedures when controlling on VATSIM in the Alger FIR, although are free to deviate from standardised procedures to ensure a safe, orderly and expeditious flow of traffic is maintained.

## Preliminary
## Airspace Boundaries and Classification

| Callsign    | Callsign (Description)                                                | Frequency   |
|-------------|-----------------------------------------------------------------------|-------------|
| DAAA_I_CTR  | <center>MAGHREB CONTROLE ALGER / Algiers Control (Inf.)</center> | 127.300 MHz |
| DAAA_S_CTR  |                                                                       | 132.450 MHz |
| DAAA_NO_CTR |                                                                       | 125.700 MHz |
| DAAA_NE_CTR |                                                                       | 125.400 MHz |
| DAAA_SC_CTR |                                                                       | 131.300 MHz |
| DAAA_SO_CTR |                                                                       | 128.100 MHz |
| DAAA_SE_CTR |                                                                       | 124.100 MHz |
| DAAA_SS_CTR |                                                                       | 123.800 MHz |

## ATS Airspace and Sectorisation

| Airspace          | Owner      | Class | Vertical Boundary |
| -----------------|------------|-------|-------------------|
| SECTEUR CENTRE    | DAAA_I_CTR | D     | 1 500 ft - F245    |
|                   | DAAA_S_CTR | D     | F245 - F450       |
| SECTEUR NORD/OUEST| DAAA_NO_CTR| D     | 1 000 ft - F450   |
| SECTEUR NORD/EST  | DAAA_NE_CTR| D     | 1 500 ft - F450   |
| SECTEUR SUD/CENTRE| DAAA_SC_CTR| E     | 3 000 ft - F450   |
| SECTEUR SUD/OUEST | DAAA_SO_CTR| E     | 3 000 ft - F450   |

| Airspace          | Owner      | Class | Vertical Boundary |
|-------------------|------------|-------|-------------------|
| SECTEUR SUD/EST   | DAAA_SE_CTR| E     | 3 000 ft - F450   |
| SECTEUR SUD/SUD   | DAAA_SS_CTR| E     | 3 000 ft - F450   |
| TMA ALGER         | DAAG_APP   | D     | 1 500 ft - F145   |
| TMA ANNABA        | DABB_APP   | D     | 1 500 ft - F105   |
| TMA CONSTANTINE   | DABC_APP   | D     | 1 500 ft - F105   |
| TMA HASSI MESSAOUD| DAUH_APP   | D     | 1 500 ft - F105   |
| TMA ORAN          | DAOO_APP   | D     | 1 500 ft - F105   |

Alger FIR is split into six en route sectors, all with the callsign “Algiers Control“. These sectors should only be opened during periods of extremely heavy traffic, and only if their corresponding main sector is online, ie. AI (TMA Centre Inférieur) and AS (TMA Centre Supérieur). 

AI is considered the main sector, and in the absence of another ACC controller being online, this position should be opened first and may extend to cover the entirety of the FIR.

## Extended Coverage

When one normal sector is unavailable, the controller of that sector may expand coverage to another normal sector (the "second sector") that has either partially or completely overlapping lateral extents or that has a common lateral border. The entire second sector must be included in this airspace extension.

A controller must set up their client software to transmit and receive on the presumed sector's major frequency while giving extended coverage to an adjacent sector. In order to link all of the frequencies that the controller assumes, controllers must also use the "cross-coupling" feature of the Audio for VATSIM system. When departing or entering nearby sectors, the enroute controller must keep track of sector boundaries and frequency ranges in order to tell pilots to change to the most suitable frequency.

Rules for top-down coverage are applied to the entire airspace that a controller is in charge of.

## Airspace Diagram

## Separation Minima

The minimum horizontal radar separation in areas equipped with secondary surveillance radar systems is 10NM and RVSM is implemented in the Algiers FIR between F290 and F410 inclusive.

## Radar Coverage

Northern sectors as well as parts of the SC and SO sectors in the Algiers FIR are within secondary radar range. Elsewhere, controllers are required to provide procedural service.

When providing procedural ATC, controllers should feel comfortable and make sure that aircraft are appropriately distanced in accordance with the minima.

## Performance-based Separation Minima

ATS routes in the Algiers FIR indicate Category S (remote) airspace, served by ADS-C, CPDLC and VHF which permit the operation of PBN-fixed routes using RNAV 10 (RNP 10) specifications.

For aircraft cruising, climbing, or descending on the same or reciprocal track along airways, this is 50 NM constant or increasing for RNAV-based separation or 5 minutes using separation minima based on time.

Lateral separation between aircraft operating on intersecting tracks or ATS routes shall be established in accordance with the RNAV 10 (RNP10) separation requirements, which are 50 NM.

ADS-C position information requires the maximum periodic reporting intervals for a separation of 50 NM, to be every 27 minutes and every 14 minutes for a separation of 5 minutes.

## Separation Application

Separation shall be applied so that the distance or time between the calculated positions of the aircraft is
never less than the prescribed minimum. This distance or time shall be obtained by one of the following methods:

* When the aircraft are on the same identical track, the distance or time may be calculated by measuring the distances or times to a common point on the track;
* When the aircraft are on the same or reciprocal non-parallel tracks other than those mentioned above, or on crossing tracks, the distance or time shall be calculated by measuring the distances or times to the common point of intersection of the tracks or projected positions of the aircraft; and
* When two aircraft are travelling along parallel tracks with overlapping protection areas, the distance or time must be computed along one of the aircraft's tracks using its calculated position and the point behind the other aircraft's calculated position.

## Handoffs

As much as is practical, the transfer of control must be initiated no later than 5 NMfrom the pertinent sector boundary and no earlier than 30 NM. During the transfer of control, the receiving controller will be notified via the handover in the datastrip and must accept the aircraft first by entering the controller jurisdiction before the transfer of communication is initiated.

### North Sectorisation

## TMA (AI) Centre Inférieur

AI Sector is a high workload, low en route sector that coordinates between DAAGAPP and AS to ensure arrivals are sequenced into Algiers and departures do not conflict with aircraft transiting the AS sector. Additionally, AI offers numerous descents through the TMA sectors. During periods of low traffic activity, AI typically extends to cover the AS sector.

## TMA (AS) Centre Supérieur

AS Sector is a high workload, low en route sector situated on the LECB border, between the TMA sectors. AS must sequence arrivals into numerous international airports in addition to providing services to overflights transiting the FIR in all directions. During periods of low traffic activity, AI typically extends to cover the AS sector.

## TMA (NO) Ouest

Along the boundaries of the GMMM/LECB FIRs, NO is the westernmost sector of the TMA airspace. Transiting aircraft to and from the west, as well as flights into and out of Algiers, make up its primary traffic flows. NO coordinates with DAOOAPP in addition. During periods of low traffic activity, NO typically extends to cover both the combined TMA Centre sector.

## TMA (NE) Est

Along the boundaries of the DTTC/LFMM FIRs, NO is the easternmost sector of the TMA airspace. Transiting aircraft to and from the east, as well as flights into and out of Algiers, make up its primary traffic flows. AI coordinates with DABBAPP and DABCAPP in addition. During periods of low traffic activity, NE typically extends to cover both the combined TMA Centre sector.

### South Sectorisation

## SECTEUR (SC) Sud-Centre


## SECTEUR (SO) Sud-Ouest


## SECTEUR (SE) Sud-Est


## SECTEUR (SS) Sud-Sud