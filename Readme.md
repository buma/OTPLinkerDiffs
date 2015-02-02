###State before updating with master (Commit: e3614064aa77fbe6ba31bdaa383):

    Correctly linked 528/788 (67%) stations for maribor_clean.osm.gz
    Not checked: 4 stations.
    Correctly linked 39/50 (78%) stations for portland_small.osm.pbf
    Not checked: 1182 stations.
    Correctly linked 4/21 (19%) stations for milan_italy_small.osm.pbf
    Not checked: 995 stations.

Points are transit stops.
Lines are wanted edges (Edges to which stops should be connected) and current edges (Edges to which stops are connected).

With red/green are marked incorrect/correct connected wanted edges.
Same with dark red/dark green and current edges.

Same edge and stop can appear multiple times most of them appear twice once for each direction.

MARIBOR
No change because it doesn't have shapes in GTFS

PORTLAND
One Streetlink in TriMet:4964 was previously connected incorrectly now it isn't found
TriMet:1136 and TriMet:1126 are now connected to correct edge with both streetLinks (both were connected incorrectly before)

MILANO:
One Streetlink on AMAT_Milan_feed:13200 and AMAT_Milan_feed:11512 was previously unconnected now it isn't found
