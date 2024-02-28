# Network generation hackathon


# Introduction

This will be an informal hackathon on generating, modelling and
modifying geographic representations of transport networks.

The hackathon will be held on TBC from 11:00 to 17:00 at the ATI.

# Agenda

The event will be split into 2 parts: demo of existing tools plus
sharing of ideas and the hackathon itself. The rough timings will be as
follows (these can be adjusted on the day):

- 11:00 - 11:05: Introduction and welcome (Robin Lovelace)

- 11:05 - 12:00: Demo of existing tools and sharing of ideas

  - 11:05 - 11:20: Demo of `od2net` tool developed at the ATI (Dustin
    Carlino)
  - 11:20 - 11:30: Demo of network simplification and joining algorithms
    and prototype tools (Robin Lovelace)
  - 11:30 - 11:45: Demo of walkability, cyclability, accessibility and
    traffic stress estimation methods for routing and network
    generation/analysis (Chris Conlan)
  - 11:45 - 12:00: Discussion of ideas for the hackathon, team formation

- 12:00 - 13:00: Lunch

- 13:00 - 16:00: Hackathon

- 16:00 - 17:00: Presentations and discussion

# Modus operandi: how we work

- To join the hackathon remotely join the Teams meeting (email Robin,
  Dustin or Chris for the link)
- Focus on GitHub for issues: any questions welcome on the [issue
  tracker](https://github.com/Robinlovelace/netgenhack/issues)
- Forking the repo and contributions welcome and encouraged for sharing
  code
- Please don’t commit and push big files to the repo: use releases
  instead, see https://github.com/Robinlovelace/netgenhack/releases for
  input datasets

# Hackathon ideas (see slides for details)

- Writing new rules to generate LTS or other measures of network quality
  from OSM data
- Testing network simplification on OSM to see possible benefits from a
  policy perspective
- Testing out od2net on different datasets and test cases
- Get command-line interfaces to od2net working

# Input datasets

We will use existing input datasets including:

- [OpenStreetMap](https://www.openstreetmap.org/)
- [Ordnance Survey Open
  Roads](https://www.ordnancesurvey.co.uk/business-and-government/products/os-open-roads.html)
- OD data (2011 and 2021) from WICID

Although these datasets are available nationally we will provide subsets
of them for ease of use:

- Small area (e.g. covering ATI and direct surroundings)
- Medium area (e.g. covering York)
- Large area (e.g. covering Yorkshire and the Humber)

# Outcomes

The hackathon will be an opportunity to develop new tools and ideas for
network generation and analysis. It will also build skills and foster
collaboration between researchers and practitioners in the field.

- Skills development: hackathons are a great way to learn new skills and
  share knowledge, especially with new tools such as the `od2net` tool
  developed at the ATI and network simplification tools developed at the
  University of Leeds (see https://nptscot.github.io/networkmerge/ for
  details)
- New tools and better documentation and understanding: we hope the
  hackathon will lead to a step change in some of the tools available
  for network generation and analysis, including
  - Better documentation of the `od2net` and network simplification
    tools
  - More use cases, identification of bugs and improvements to the tools
- Ideas for future work
  - How the tools can be used in policy
  - Research directions
