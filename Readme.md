### Updated with master (commit 75127cc4984a2f4b70099b04ed7)
And ignoring possibleTransitLinksOnly in getClosestEdges

    Correctly linked 710/793 (90%) stations for maribor_clean.osm.gz
    Not checked: 5 stations.
    Correctly linked 57/68 (84%) stations for portland_small.osm.pbf
    Not checked: 1168 stations.
    Correctly linked 12/22 (55%) stations for milan_italy_small.osm.pbf
    Not checked: 980 stations.

Points are transit stops.
Lines are wanted edges (Edges to which stops should be connected) and current edges (Edges to which stops are connected).

With red/green are marked incorrect/correct connected wanted edges.
Same with dark red/dark green and current edges.

Same edge and stop can appear multiple times most of them appear twice once for each direction.


MARIBOR
No change

PORTLAND
Added some transit stops in Portland
Some of them on bridges to test connecting on different levels. Some were just visually very wrongly connected.

MILANO:
No change
