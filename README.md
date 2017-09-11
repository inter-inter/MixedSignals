# MixedSignals
Basic Surface Routing and Cueing Engine for Touch Designer

Mixed Signals is an experimental surface routing and cueing engine for Touch Designer. It is designed to implement some of the basic functionality found in simpler video engines such as QLab. The cueing system is contained in "project1". It sends cue messages to "project 2", mixing output from user-generated scenes into one of eight comps and routing them to one of six outs. The system is designed so that scenes can be created using the full possibilities of Touch Designer, with media either loaded independently, routed from an external source, or pulled recursively from the comps. Because "project2" is separated, it can easily be ported to one or several other computers for use in distributed systems.

Future improvements will include:
- addition of "live" and "show" cueing system modes
- improved performance management
- fade engine bug fixes
- ability to dynamically limit or increase number of comps and outs
- improved GUI

Mixed Signals was developed by Andrew Maillet and Wladimiro Woyno in association with the Wooster Group.
www.andrewmaillet.com
http://wawr.ca/
www.thewoostergroup.org
