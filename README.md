# BlueprintUE_DistanceAttenuation
The very basic function here was written to simulate physically based free-field sound propagation in UE4 by blueprint. 
It uses a conversion between UE4 volume level to sound pressure level based on dynamic range of the sound system which was assumed as 100 dB. 
Application includes two functions first for calculating the distance between source and recevier and second for calculating new volume. 
To use copy the codes and paste them into UE4 blueprint editor. The attenıuation volume app in blueprint class, two functions must be created and connected to first person character and target sound source.
