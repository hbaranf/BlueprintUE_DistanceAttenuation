# BlueprintUE_DistanceAttenuation
The very basic function here was written to simulate physically based free-field sound propagation in UE4 by blueprint. 
It uses a conversion between UE4 volume level to sound pressure level based on dynamic range of the sound system which was assumed as 100 dB. 
Application includes two functions first for calculating the distance between source and recevier and second for calculating new volume. 
To use the distanceAttenuation, create two functions by copy and paste and connect the nodes in blueprint class. 
