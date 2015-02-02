###State after updating with master (Commit 199cd6ed93fdfc634f59ae1e68e):

    Correctly linked 530/789 (67%) stations for maribor_clean.osm.gz
    Not checked: 4 stations.
    Correctly linked 35/50 (70%) stations for portland_small.osm.pbf
    Not checked: 1175 stations.
    Correctly linked 4/23 (17%) stations for milan_italy_small.osm.pbf
    Not checked: 981 stations.

Reason for changes is commit: a6e55fb8e398a2b09f9d83159eeb7b8991425b11 which changes car preferences in CandidateEdge scoring.

Points are transit stops.
Lines are wanted edges (Edges to which stops should be connected) and current edges (Edges to which stops are connected).

With red/green are marked incorrect/correct connected wanted edges.
Same with dark red/dark green and current edges.

Same edge and stop can appear multiple times most of them appear twice once for each direction.

MARIBOR
MARPROM:116 has 2 streetLinks now

PORTLAND
TriMet:12844 is now connected correctly (It wasn't previously)
TriMet:5027 is now connected only with ine streetLink incorrectly (It was correct before with 2 streetlinks)

MILANO:
Second AMAT_Milan_feed:11512 StreetLink is now found (it wasn't before)
One of  AMAT_Milan_feed:11503 StreetLinks now isn't found (it was before)
