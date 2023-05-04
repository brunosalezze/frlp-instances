These files are p01, p02, ..., p31

These data files are the ones considered in:
"XXXXXXX"
by Authors,
Journal YYYYYY

The format of data files is as described below.

The first line contains the following information:

        e c p

where

        e = number of edges
		
        c = number of od nodes

        p = number of od pairs with trips

The next m lines contain, for each edge, the following information:

        i a b l

where

        i = Edge ID
		
        a = node ID of the first node
        
        b = node ID of the second node

        l = lenght of the edge
        

The next n lines contain, for each OD node, the following information:

        d

where

        a = node ID
        
The next line d lines contains the information about the od pairs with trips:

        a b t

where

        a = node ID of the first OD node
        
        b = node ID of the second OD node
        
        t = number of trips between a and b
