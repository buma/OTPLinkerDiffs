###Added support for Mapbuilder

    Correctly linked 530/789 (67%) stations for maribor_clean.osm.gz
    Not checked: 4 stations.
    Correctly linked 39/49 (80%) stations for portland_small.osm.pbf
    Not checked: 1169 stations.
    Correctly linked 4/22 (18%) stations for milan_italy_small.osm.pbf
    Not checked: 979 stations.

Points are transit stops.
Lines are wanted edges (Edges to which stops should be connected) and current edges (Edges to which stops are connected).

With red/green are marked incorrect/correct connected wanted edges.
Same with dark red/dark green and current edges.

Same edge and stop can appear multiple times most of them appear twice once for each direction.

MARIBOR
No change because Maribor doesn't have shape files.

PORTLAND
TriMet:1136 and TriMet:1126 are now connected correctly with 2 streetlinks (It weren't previously)
TriMet:4964 is now incorrectly connected with only one streetLink (It was incorrect before with 2 streetlinks)

MILANO:
One Streetlink on AMAT_Milan_feed:11145 was previously unconnected now it isn't found
