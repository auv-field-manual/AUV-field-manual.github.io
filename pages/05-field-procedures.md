---
layout: home
permalink: /field-procedures
title: "Field procedures"
excerpt: ""
image:
  feature: /banners/05_banner.jpg
---
{% include toc.html class="toc-left" h_min=2 h_max=3 %}

## **Onboard**** ****sample**** ****acquisition**** **

Complete an on-site briefing. Prior to deployment, a deployment briefing should always be completed to ensure the operation can be completed safely. Always take a precautionary approach to risks associated with vehicle deployment. See Chapter 1 for further information about risk assessments.

Set up and test AUV system. Allow sufficient time during survey mobilisation to undertake system checks, calibrations and testing of equipment and account for unforeseen problems; in most cases it will be possible to complete all system setup and tests within half a day. The conduct of pre-start checks should be noted in the trip log and any test failures specifically recorded for later-reference. Detailed settings for each component should be made using relevant operations manuals (e.g. USBL operations manual etc.).

*On-deck** **tests** **should** **include,** **but** **not** **limited** **to,** **the** **following** **checks:*

* on-board data storage

* on-board power

* cameras 

* strobe lighting 

* iridium beacon, RF and emergency strobes

* propellers

* all blanking plugs are installed

* correct and new corrodible link attached emergence ascent drop weight

* crane and associated shackles are working order

* check all seals/o-rings and blanking plugs are good working order

* check all surface communications

*Wet** **testing** **should** **include** **checks** **of** **the** **following:*

* USBL and internal navigation (e.g. compass and avoidance sonar)

* cameras and strobes

* through-water communications

*Acoustic** **tracking** **setup*

* Set position of GPS receiver. *Differential** **GPS** **is** **mandatory** **for** **repeat** **site** **monitoring.*

* Deploy USBL transceiver (e.g. pole or vessel mounted).

* Measure offsets of USBL transceiver head to GPS receiver and put offsets into navigation system.

Conduct AUV transects

*Pre-** **deployment*

* Transects should only be undertaken in areas where the substratum is known/mapped (often in the form of multibeam mapping) as to avoid entrapment and potential loss of AUV. Do not deploy blind, as this increases the risk of equipment loss and damage, as well as unnecessary impact on potentially vulnerable ecosystems.

* Once final transect locations have been determined, provide the locations of the transects (usually in ESRI shapefile format) and associated multibeam maps (in geotif format) to the AUV engineers responsible for uploading missions. Cross-check the uploaded transect corresponds to the correct area on the geotif (i.e. ensure the geographic coordinates are defined for all spatial data).

* The flight elevation of AUV should be set and maintained at ~ 2m from the seafloor to facilitate a consistent field of view. General sampling methodology can be found in Williams et al. (2012[)](https://paperpile.com/c/ymogqX/cwva). Although this needs to be informed by 'survey question', camera type and performance, illumination type and output power, etc.

* Prepare for AUV launch and recovery on deck, and ensure only essential personnel participate in its preparation and deployment.

* Place USBL transceiver in water and ensure functionality.

* Correctly insert the deployment release pin.

*AUV** **deployment** **and** **retrieval*

1. Disconnect any power or data cables, ensuring any blanking plugs are fitted prior to deployment.

2. Install sacrificial ballast weights. Ensure that there is sufficient time allocated to transect when selecting corrodible link.

3. Vessel master must ensure the vessel is positioned at the start of the transect start location.

4. Following the signal to deploy from the vessel Master, use the crane and/or A-Frame to lift and guide the AUV from the deck into the water.

5. Minimise the time taken from when the AUV is let out of reach, to when it is lowered in the water, so as to reduce potential swing and impact against the vessel.

6. Using appropriate software (see Pre-Survey Preparations), monitor the AUVs progress to the seabed and start of transect location. Note the start time of transect using a timer as this will be used to determine when the sacrificial weight will be automatically released (if fitted) in the case of an emergency.

7. Confirm data is being recorded where possible (e.g. recording indicators, hard drive operating).

8. Ask the vessel's Master to follow the AUV during transects, to maintain USBL communication and AUV tracking.

9. Monitor weather forecast conditions prior to and during deployment to maintain safe working environment. Consider aborting operations if local weather and forecast conditions are marginal. 

10. When the transect is complete or if the transect is being aborted, advise the vessel Master of the intention to retrieve the AUV.

11. Watch for the AUV to resurface, ensuring only required personnel are near open transom. Avoid approaching the AUV looking into the sun as this increases the risks of collision.

12. Use grapple hook to connect the lift line to the AUV for retrieval. At least three personnel should be present with hooks to avoid the AUV colliding with vessel *[Recommended]*.

13. Shut down the AUV and connect relevant power or data cables.

14. Remove the sacrificial ballast weights.

15. For the last transect of the day, wash down the AUV with freshwater, unplug the USBL and turn off emergency beacons.

16. Raise the USBL transducer (if pole mounted) before moving vessel to next location.

*Procedures** **for** **seabed** **entanglement** **or** **loss** **of** **communications** **with** **AUV*

Potential entanglement of the AUV is always a possibility. The following procedures should be followed upon entanglement:

1. Log the last known position of the AUV.

2. Send an abort code to AUV to manually end the transect.

3. If the AUV appears entangled (i.e. not moving), a mini remotely operated vehicle (ROV) should be used to locate and retrieved the unit. If the AUV is trapped under a ledge/cave, or ensnared in fishing line or kelp, the automatic release of the sacrificial weights may cause issues with recovery of the unit. Under such circumstances it is recommended that a ROV is deployed to recover the AUV.

4. If the AUV is fitted with a sacrificial dump weight, which automatically releases after a user defined period, it may surface on its own. Once it’s on the surface, use the fitted iridium beacon, RF, GPS and emergency strobes to locate unit.

5. Ensure that you check AUV thoroughly for damage before redeployment.

*Completion** **of** **operations*

Prior to any vessel movement or engine start-up, operators should check the following:

* All equipment is clear of the water, including the USBL transducer pole.

* AUV is shut down.

* All gear is safely stowed.

* All power and data cables are connected.

* An "All Clear to Move" command is given to vessel Master when the AUV team is satisfied it is OK for the vessel to move on.

## **Onboard**** ****data**** ****processing and storage**

6. Once the AUV transect is complete, it is good practice to download associated raw imagery and associated positional data. Imagery and associated positional data should be checked to ensure no failures have occurred, including but not limited to the following: 

* Miss-timing between image capture and strobes (i.e. dark/black imagery)

* Failure of one of the stereo cameras

* Failure of positional logging

1. Name data files according to established conventions. File naming conventions are important for ensuring both efficient and effective management of field data and its integration into appropriate data management repositories. It is important to note that these conventions will differ among agencies and academic institutions.

2. Ensure accurate recording of metadata. Metadata is a descriptive data source comprised of information that may be used to process the images or information therein Durden et al. (2016). While it is important to follow agency specific protocols for capturing metadata, it is also essential that metadata is sufficient enough in detail to satisfy conformance checks for subsequent data release via AODN. Minimum data for each transect should contain as follows:     

* Campaign (i.e. Survey identifier)

* Station/event number 

* Platform

* Latitude and longitude (WGS 1984 in decimal degrees with a minimum of 6 decimal places *[Recommend]*)

* Altitude

* Depth

* Time and date stamp

* AUV orientation (roll, pitch, heading) 

* Precision details (e.g. type of navigation system used and its associated errors) 

* Data provenance 

3. Backup data. This is necessary to ensure all data collected in the field is safely returned and securely backed-up at host facilities, prior to quality control and public release. Onboard copies of data should be made as soon as practical following acquisition. When operating external to a network, it is recommended that all data be backed up on a RAID or a NAS that contain built-in storage redundancy in case of hard-drive failure. A duplicate copy of all data onto external hard drives for transportation back to host facilities is *[Recommended]*. 
