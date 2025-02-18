---
  title: Bindook (BIK)
---

--8<-- "includes/abbreviations.md"
## Positions

| Name | Callsign | Frequency | Login ID |
| ---- | -------- | --------- | -------- |
| **Bindook** | **Melbourne Centre** | **129.800** | **ML-BIK_CTR** |
| <span class="indented">Wollongong :material-information-outline:{ title="Non-standard position"} | Melbourne Centre | 125.000 | ML-WOL_CTR |
| <span class="indented">Gundagai :material-information-outline:{ title="Non-standard position"} | Melbourne Centre | 128.400 | ML-GUN_CTR |

!!! abstract "Non-Standard Positions"
    :material-information-outline: Non-standard positions may only be used in accordance with [VATPAC Air Traffic Services Policy](https://vatpac.org/publications/policies){target=new}.  
    Approval must be sought from the **bolded parent position** prior to opening a Non-Standard Position, unless [NOTAMs](https://vatpac.org/publications/notam){target=new} indicate otherwise (eg, for events).

### CPDLC

The Primary Communication Method for BIK is Voice.

[CPDLC](../../../client/cpdlc) may be used in lieu when applicable.

The CPDLC Station Code is `YBIK`.

!!! tip
    Even though BIK's Primary Communication Method is Voice, CPDLC may be used for Overfliers.

## Airspace

<figure markdown>
![Bindook Airspace](../assets/bik.png){ width="700" }
  <figcaption>Bindook Airspace</figcaption>
</figure>

BIK assumes responsibility of the airspace within 45nm of SY DME above `FL285`.  
GUN assumes responsibility of the airspace within the lateral limits of the CB TCU above `FL245`, except for the region to the south west, which is assumed by ELW(BLA).

!!! note
    BIK does not assume the CB TCU in the absence of a CB TCU controller. Assumption of the CB TCU is the responsibility of ELW(BLA). Controllers may choose to verbally coordinate the release of the CB TCU to either sector/subsector.

### Reclassifications
#### CB TCU
When **CB TCU** is offline, CB TCU (Class C `SFC` to `A085`) reverts to Class G, and is administered by ELW(BLA).

### Nowra Airspace Releases
When **NW TCU** is online, R421 is activated and administered by the TCU controller from `SFC` to `F125`. 

!!! tip
    Display the lateral limits of the NW TCU by activating R421 in the Restricted Areas window.

During times of high traffic, NW TCU may request the release of R420F up to `F300`.

!!! phraseology
    <span class="hotline">**NW TCU** -> **WOL**</span>: "There's a preplanned military exercise about to commence, request release of R420F up to F300"  
    <span class="hotline">**WOL** -> **NW TCU**</span>: "R420F released to you F125 to F300"  
    <span class="hotline">**NW TCU** -> **WOL**</span>: "R420F released F125 to F300" 

With R420F released to NW TCU, transiting aircraft will need to be coordinated or rerouted. Every effort will be made to accommodate these aircraft on track, but if NW TCU can't accommodate them, they must be vertically or laterally rerouted to avoid the restricted area. NW TCU will communicate this requirement.

See [Nowra Airspace](../../terminal/nowra.md#airspace) for more details about the lateral boundaries of the Nowra restricted areas.

## Sector Responsibilities
### Bindook (BIK)
BIK will provide final sequencing actions and descent into YSSY.

For aircraft overflying the SY TMA, place *'O/FLY'* in the LABEL DATA field.

Refer to the [Sequencing into YSSY](#sequencing-into-yssy) notes below for runway and STAR selection notes.

### Wollongong (WOL)
WOL is reponsible for issuing STAR clearances, initial descent, and sequencing actions for aircraft inbound to YSCB. WOL is also responsible for issuing STAR clearance to Non-jet aircraft for YSSY which depart from an aerodrome within the subsector.
    
### Gundagai (GUN)
GUN is reponsible for issuing STAR clearances and initial descent for aircraft inbound to YSSY. 
    
GUN is also responsible for initial sequencing actions into YSSY. Aircraft cruising above `F250` should be assigned *no lower* than `F250` and handed to BIK for further descent. Aircraft cruising below `F250` should be transferred to BIK at their cruise level.

Refer to the [Sequencing into YSSY](#sequencing-into-yssy) notes below for runway and STAR selection notes.

### Sequencing into YSSY
Sequencing arrivals from the west into YSSY is a joint responsibility of GUN and BIK. Initial sequencing actions should be performed by GUN, with fine tuning and any holding required issued by BIK.

Aircraft from the south/west shall be assigned **runway 16R/34L** during PROPS. However, some situations may warrant the use of the alternate runway (16L/34R), such as heavy aircraft operationally requiring the longer runway from the north or large volumes of traffic requiring the use of both runways to minimise delay. In this case, coordination must be conducted with Brisbane Centre or Sydney Flow (if operating) to ensure that the sequence is built in an efficient and orderly way.

!!! phraseology
    <span class="hotline">**BIK** -> **ARL**</span>: "Southwest of Sydney, VOZ421, with your concurrence will be assigned runway 34R for sequencing"  
    <span class="hotline">**ARL** -> **BIK**</span>: "Concur, VOZ421 runway 34R, required landing time 22 due sequence from the north"  
    <span class="hotline">**BIK** -> **ARL**</span>: "Runway 34R, landing time 22, VOZ421"

Jet aircraft for YSSY shall be assigned the **RIVET** STAR.  
Non-jet aircraft for YSSY shall be assigned the **ODALE** STAR.

!!! tip
    Whilst the preference is to keep jet/non-jet aircraft assigned the default STAR as above, there are situations where the sequence may be improved by assigning the adjacent STAR (e.g. a non-jet assigned the RIVET STAR). This is most common when assigning the alternate runway to an arrival.   
    
    Either **SY TCU** or **BIK** may propose utilising the adjacent STAR where two aircraft with significantly different cruise/descent speeds will be required to overtake or pass abeam each other to achieve a sequenced landing time, or if assigned different runways. This technique can allow aircraft to be processed for different runways independently with minimal delay by using the built-in separation afforded by the STAR height requirements.  

    In this case, coordination should be conducted to ensure that both controllers agree and no additional conflicts are created as a result (particularly with aircraft inbound from the north/east).

!!! phraseology
    **BIK:** "JST421, amended tracking and STAR available"  
    **JST421:** "JST421, go ahead"  
    **BIK:** "JST421, recleared direct AKMIR thence WELSH, ODALE, for the ODALE7 arrival, runway 34R, maintain F350"  
    **JST421:** "Recleared direct AKMIR, WELSH, ODALE, for the ODALE7 arrival, runway 34R, maintain F350, JST421"

#### Adjacent Feeder Fixes
Aircraft assigned the **same runway** inbound via **RIVET** and **ODALE**, must be considered to be on the **same STAR** for sequencing purposes. That is, they must be at least **2 minutes** apart at their respective Feeder fixes.

### Sequencing into YSCB
Aircraft assigned the **same runway** inbound via **LEECE** and **BUNGO**, must be considered to be on the **same STAR** for sequencing purposes. That is, they must be at least **2 minutes** apart at their respective Feeder fixes.

## STAR Clearance Expectation
### Handoff
Aircraft being transferred to the following sectors shall be told to Expect STAR Clearance on handoff:

| Transferring Sector | Receiving Sector | ADES | Notes |
| ---- | -------- | --------- | --------- |
| WOL | ELW(BLA) | YMML, YMAV | Jets only |
| WOL | GUN | YSSY | |

### First Contact
Aircraft being transferred from the following sectors shall be given STAR Clearance on first contact:

| Transferring Sector | Receiving Sector | ADES | Notes |
| ---- | -------- | --------- | --------- |
| ELW(BLA), YWE(GTH), WOL | GUN | YSSY | |

## Coordination
### SY TCU
#### Airspace
SY TCU is responsible for the airspace within a 45nm radius of TESAT, `SFC` to `F285`.

Refer to [Sydney TCU Airspace Division](../../../terminal/sydney/#airspace-division) for information on airspace divisions when **SAS**, **SDN**, **SDS** and/or **SRI** are online.

#### Arrivals/Overfliers
Voiceless for all aircraft:

- With ADES **YSSY**; and  
- Assigned a STAR; and  
- Tracking via **RIVET**, assigned `A100`; or  
- Tracking via **ODALE**, assigned `A090`

All other aircraft coming from BIK CTA must be **Heads-up** Coordinated to SY TCU prior to **20nm** from the boundary.

#### Departures
Voiceless for all aircraft:

- Assigned the lower of `F280` or the `RFL`; and
- that enter BIK airspace via any of the *Green Shaded Corridors* below

<figure markdown>
![SY TCU Voiceless Coordination Corridors](../assets/sytcucoordgate.png){ width="700" }
  <figcaption>SY TCU Voiceless Coordination Corridors</figcaption>
</figure>

All other aircraft going to BIK CTA will be **Heads-up** Coordinated by SY TCU.

### CB TCU
#### Airspace
The Vertical limits of the CB TCU are `SFC` to `F245`.

Refer to [Canberra TCU Airspace Division](../../../terminal/canberra/#airspace-division) for information on airspace divisions when **CBW** is online.

Refer to [Reclassifications](#cb-tcu) for operations when CB TCU is offline.

#### Arrivals/Overfliers
Voiceless for all aircraft:

- With ADES **YSCB**; and  
- Assigned a STAR; and  
- Assigned `F130`

All other aircraft coming from BIK CTA must be **Heads-up** Coordinated to CB TCU prior to **20nm** from the boundary.

!!! note
    These coordination requirements apply to aircraft entering the CB TCU, even if the airspace is owned by ELW/BLA

#### Departures
Voiceless for all aircraft:
 
- Tracking via **AVBEG**, **AKMIR**, or **CULIN**; and  
- Assigned the lower of `F240` or the `RFL`

All other aircraft going to BIK CTA will be **Heads-up** Coordinated by CB TCU.

### NW TCU
#### Airspace
The vertical limits of the NW TCU are `SFC` to `F125`, and up to `F300` in R420F when activated.

Refer to [Nowra Airspace Releases](#nowra-airspace-releases) for operations with R421 and/or R420F released.

#### Arrivals/Overfliers
Voiceless for all aircraft:

- With ADES **YSNW**; and   
- Tracking direct to the NWA TACAN or YSNW; and  
- Assigned `F130`

All other aircraft coming from BIK(WOL) CTA must be **Heads-up** Coordinated to NW TCU prior to **20nm** from the boundary.

!!! note
    With R420F released to NW TCU, the majority of aircraft tracking via the NWA TACAN will need to be heads up coordinated as per above.

#### Departures
Voiceless for all aircraft:
 
- Tracking via a published airway; and  
- Assigned the lower of `F120` or the `RFL`

All other aircraft going to BIK(WOL) CTA will be **Heads-up** Coordinated by NW TCU.

### Enroute
As per [Standard coordination procedures](../../../controller-skills/coordination/#enr-enr), Voiceless, no changes to route or CFL within **50nm** to boundary.

That being said, it is *advised* that BIK give **Heads-up Coordination** to the relevant sector, prior to **50nm** from the boundary, for **any aircraft not on the Q29 or V169 airways**. 

#### TSN (Oceanic)
As per [Standard coordination procedures](../../../controller-skills/coordination/#pacific-units), Voiceless, no changes to route or CFL within **15 mins** to boundary.

Aircraft must have their identification terminated and be instructed to make a position report on first contact with the next (procedural) sector.

!!! phraseology
    **BIK**: "QFA121, identification terminated, report position to Brisbane Radio, 124.65"

### BIK Internal
Changes to the CFL are permitted up to the boundary for aircraft transiting BIK/GUN/WOL airspace internally. It is *advised* that BIK/WOL/GUN give **Heads-up Coordination** to the relevant sector, prior to **20nm** from the boundary, for **any aircraft not on the Q29, Y59, W113, or V169 airways**. 