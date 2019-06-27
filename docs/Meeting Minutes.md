# Meeting Minutes  

This meeting minutes in this file are the summeries of meeting notes from members, for major meetings usually involve participants outside the team. This team had regular and less formal meetings throughout the project. Please see the seperate file for the record. Compiling the bits and pieces from notebooks together has been a good review of the journey this team has gone through.


## 1. Briefing with Jonny  
**Date:** 30 Apr 2019 <br>
**Venue:** Room 610b  
**Attendance:** All team members except Thomas, Johny from micro:bit  

**Discussion:**
* Team members self-introduction
#### From Jonny's briefing
* 3 useful resources from micro:bit suggested by Jonny:
    * tech.microbit.org - documentations for previous work done;
    * microbit.org - accessories guide;
    * github, microbit-dal - the starting point for this project;
* Explanation of requirements:
    * External accessory for the micro:bit
    * BLE keyboard
    * User-friendly
    * Open-ended nature
* Production tools:
    * arm mbed (online editor)
    * MakeCode environment
    * Typescript  
    
**Action Plans:**
* James will get one micro:bit from Amazon
* Jonny would send more micro:bits for the team to use and test
* Research topics:
    * MakeCode Extensions
    * BLE library / profile
    * HID over GATT protocol
    * mega:bit accessory project from last year's Industrial Project group
    * Similar existing accessories e.g. bit:commander
* Summarises research outcomes and questions before next Tuesday
* Propose meeting with academic supervisor

## 2. Initial Concept Brainstorm
**Date:** 2 May 2019 <br>
**Venue:** Level 3 Computer Labs <br>
**Attendance:** All team members

**Discussion:**
* Ideas generated:
    * Feature phone
    * Mouse-like keyboard
    * Customisable controller based on the PS4 controller
    * Music controller based on piano keyboard
* Research outcomes were shared among members.
* Questions about this project and requirements have been gathered for later meetings with Jonny and the academic supervisor. 

**Proposed next team meeting:** Before the end of week 1

## 3. 2nd meeting with Jonny from micro:bit
**Date:** 14 May 2019  
**Venue:** Room 610b  
**Attendance:** All team members and Jonny 

**Discussion:**
* Possible concepts for keyboard: musical keyboard, game controller, fortnite machine, Makey-Makey, joystick, cardboard edge connector, draw and place, copper tape, graphite, ink, papier machine
* MakeCode Extension
* HOGP (HID over GATT protocol) 
* Clarified suggested cost range: similar to micro:bit itself, around 15 US dollars
* Clarified restrictions on power usage of device and accessory
* Additional production design guidelines: Cheap and useful, can be fitted inside a student's bag

**Action Plans:**
* Research existing accessories and similar products on the market
* Continue brainstorming more ideas for the accessory
* Verify BLE functionality of micro:bit
* Meet again early next week

## 4. Team Workshop 
**Date:** 21 May 2019  
**Venue:** Room 408  
**Attendance:** All team members

**Discussion:**
* Listed down the possible inputs:
    - Joysticks?
    - Dial
    - LED indicator
    - Buttons / touch sensors as keys
* Case / shape: inspiration from nintendo
* Drawings of concept: triangle:bit

**Action Plans:**
* Research suitable components for suggested inputs
* Try to realize BLE keyboard service based on micro:bit_presenter
* Seek advices and suggestions from academic supervisor

## 5. 2nd meeting with academic supervisor
23 May 2019, all team members

**discussion**
- triangle:bit and modular design
- physical connection
    - difficulties
    - possible solutions
- electronic connections
    - wire / contacts / connector
    - spin contact pins
    - buses / SPI or I2C network
- feasibility of graphite tracks and copper tape
- introduce a drawing ground

**action points**
- rethink the concept of triangle:bit
- research suitable electronic connector
- verify the conductivity of graphite pencil and copper tape
- verify wires suitable for kids, presumably cable with crocodile clip

## 6, Team Workshop
28 May 2019, all team members

**discussion**
- possible example/tutorial for the accessory: 
    - quiz, 
    - battleship, 
    - blocking, 
    - potentiometer, 
    - pictogram, 
    - maze, 
    - wire loop, 
    - comic box, 
    - pin ball, 
    - crossy road
    
**action points**
- start the work of hardware prototype
- develop mbed code for input signals and related controls for the proposed examples.

## 7, Leaflet and Posters
6 Jun 2019, all team members

**discussion:**
- minimum font for visibility from a distance
- bubble for content on leaflet
- pictures / images
- envelope, printing, marker, crop
- what sections should be included into poster and key points for each section
- who is responsible to which section

**action points**
- review leaflet content and design
- write contents for poster

## 8, Documentation Discussion
18 Jun 2019, all team members

**Discussion**
- what should be included in our documentation
- job division
- github platform and mark down files

**action points**
- start documentation work
- arrange meeting with Jonny on Thursday

## 9, 3rd meeting with Jonny
20 Jun 2019, all team members except Aina

**Discussion**
- issues encountered when merging BLE with DAL
- YOTTA and other production tool for BLE function development and debug
- publish this project on micro:bit's platform
- documentation details
- future works in summer
- potential to talk with accesory producer

**action points**
- keep working on merging BLE with DAL
- keep working on documentation

