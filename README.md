# Ingress API Proposal

My idea how a working Ingress API could look like.

The current state in human readable form is available via: [Swagger.io](https://petstore.swagger.io/?url=https://raw.githubusercontent.com/Aradiv/ingress-api-proposal/master/openapi.yml)

The basic concept is:
1. All Agent Identifiable information needs to be explizitly shared by the Agent
2. Game state and static game data is available with an developer apiKey in a limited manner

## What kind of services should be possible?
- Stat comparsion and progress services (Agentstats)
- stat competition services: (EBL, The Grid)
- screenshot services, (ICE, IIDSC)
- mosaik overview and tracking (ingressmosaiks.com)
- inventory managment (multiple)
- own activity visualisation (unique vists/capture maps, own activity heatmap etc)

## What kind of service should not be possible?
- Agent Tracking (without their explizit consent)
- Mass Data scrapping for an area 
- live alerts for status changes.

## Which services are discussable?
historical anonymised activity analyses to render different kind of stats.
- there where 100.000 Hacks in the last 24 hours in $city, 
- in the last year where 3000 different agents in the area active (1767 RES/ 1233 ENL)

The problem with services like this is if the data set is selected to be small enough or otherwise filterable it is possible to track down a single agent or a small group of agents.
