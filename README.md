# London Architecture

**The problem:** you're standing in front of a London landmark, looking up, and you have no idea what you're looking at or why it looks that way. Signs, if there are any, give you a name and a date. Wikipedia gives you everything except the answer.

**What this does:** tap **Nearest to me** and it opens the building you're standing at. In 30 seconds you get the essentials: who designed it, how big it is, the one big idea, a timeline, whether you can go in, and what to look for from where you're standing. If you want more, it goes as deep as you like: a 3D card you can tilt, the building rising from blueprint to opening day, every design decision as Intent → Move → Result, and how people move through it.

It covers ten landmark commercial buildings, written for architecture students and curious visitors.

**Live site:** https://snehabaid1998-byte.github.io/london-architecture/

A companion to [Spatial Marvels](https://github.com/snehabaid1998-byte/spatial-marvels).

| | Building | Area | Year | Architect |
|---|---|---|---|---|
| 1 | Lloyd's building | City of London | 1986 | Richard Rogers & Partners |
| 2 | One Canada Square | Canary Wharf | 1991 | César Pelli & Associates |
| 3 | 30 St Mary Axe | City of London | 2004 | Foster + Partners |
| 4 | The Shard | London Bridge | 2012 | Renzo Piano Building Workshop |
| 5 | The Leadenhall Building | City of London | 2014 | Rogers Stirk Harbour + Partners |
| 6 | 20 Fenchurch Street | City of London | 2014 | Rafael Viñoly |
| 7 | Bloomberg London | City of London | 2017 | Foster + Partners |
| 8 | Coal Drops Yard | King's Cross | 2018 | Heatherwick Studio |
| 9 | 22 Bishopsgate | City of London | 2020 | PLP Architecture |
| 10 | Battersea Power Station | Nine Elms | 2022 | WilkinsonEyre (restoration) |

## What each building's story covers

1. **Overview and key facts:** why it exists, the big idea, the lesson for your own work, plus client, architect, engineer, contractor, height, floors, area, cost, listing, awards and nearest stations.
2. **Circulation:** a simplified plan or section with the main route animated, a numbered walk-through, the lesson, and a sketch exercise.
3. **Site, planning and climate:** a plan diagram with north, London's prevailing wind and the sun path, plus the planning story (protected views, flight-path limits, public inquiries) and how the building answers its climate.
4. **Design decisions:** each one set out as **Intent → Move → Result**, with numbered pins on the photo and the 3D card.
5. **Style, materials, timeline,** a 1975–2025 chart comparing all ten, and **sources**.

## How to use it

- **On the street:** press **Nearest to me** (your browser will ask for your location; it never leaves your device). The card under the building shows the 30-second version, plus **Can I go in?** and **Look for**. Access was checked in October 2026; hours and booking rules change, so check the venue before you go.
- **Change building:** swipe, drag, use a two-finger trackpad swipe, press the arrow keys, or tap the page dots.
- **Construction sequence:** hover over the building, or press **Construction ▶**.
- **Depth:** move the pointer or tilt the device. **Sense lid tilt** uses the webcam to read how a laptop screen is moving. The camera image stays in the browser.
- **Hand control:** use the front camera to steer with gestures: move an open palm to look around, swipe left or right to change building, point for the next annotation, pinch to watch it get built, show two fingers for the full story, and make a fist to go back. Hand tracking runs on your device with [MediaPipe Hands](https://github.com/google-ai-edge/mediapipe) (Apache 2.0, files in `mp/`).
- **Link to one building:** add its key after a `#`, for example `#shard`, `#gherkin` or `#battersea`.

## Accuracy

Facts were checked against published sources in October 2026, and each building's story lists them. Wind directions come from London City Airport records for 2019–2023 (METAR, via the [Iowa Environmental Mesonet](https://mesonet.agron.iastate.edu/)). The circulation plans are simplified study diagrams, not measured drawings. Use published drawings for measured work.

## Photo credits

The photos come from Wikimedia Commons. The layers in `photos/` are derivatives and keep each original's license.

| Building | Photographer | License |
|---|---|---|
| Lloyd's building | DanielMichaelPerry | CC0 |
| One Canada Square | mattbuck | CC BY-SA 3.0 |
| 30 St Mary Axe | Carlos Delgado | CC BY-SA 3.0 |
| The Shard | Diego Delso | CC BY-SA 4.0 |
| The Leadenhall Building | Colin | CC BY-SA 4.0 |
| 20 Fenchurch Street | Diliff | CC BY-SA 3.0 |
| Bloomberg London | The wub | CC BY-SA 4.0 |
| Coal Drops Yard | Fred Romero | CC BY 2.0 |
| 22 Bishopsgate | Matt Brown | CC BY 2.0 |
| Battersea Power Station | Alan Hughes | CC BY-SA 2.0 |

Each card links to its photo's Commons page.

Design and code by Sneha Baid.
