# utack_brouter_data  
  
All data used for bike routing with BRouter (found at https://github.com/abrensch/brouter ) 
At the moment it contains a BRouter profile  
  
######What is this profile useful for?
The profile was built for some light touring or commuting with a city bike.  
It priorizies good ways and easy riding, but will suggest some more offroad ways to avoid traffic.  
  
######What does it do differently from most other profiles out there?  
It was developed with "dense" OSM cities in mind, and should cover all oneway and cycleway tag situations found in OSM.  
It evaluates all ways with the same logic - no heuristic assumptions are made based on waytype.  
It has a method to find the waycost taking all types of road quality indicators into consideration (smoothness, surface, tracktype, mtb:scale, sac-scale).  
It is generally carefuly - it avoids uncertain situations like reversible traffic, barriers or not explicitly whitelisted highway types.  
All this means it takes a bit longer to calculate routes than most other profiles, but hopefully it should cover mostly everything found in OSM.  

######Related things
If you are looking for highly configurable profiles for a variety of other purposes give a try to  
https://github.com/poutnikl/Brouter-profiles

