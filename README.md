# NGC-6121

Astrometric analysis of globular cluster Messier 4. Using a two dimensional gaussian mixture model, the stellar members of the cluster are extracted solely using on sky movement, or proper motions. Potential this could serve as a way to automate the detection of moving groups, whether it be an open/globular cluster or tidal streams. I also analyze the kinematics in both galactocentric and action-angle coordinate systems. Suprisingly, I accidently find a high velocity halo star visiting the cluster on its way around the galactic buldge.

Despite having excellent $(u,v,w)$ data, the parallaxes have high errors due to the distance of the cluster. When plotted in cartesian coordinates this becomes apparent as the cluster takes an elongated shape in the data. This is also an interesting feature of the data as one would have to partition the galaxy in elongated spherical coordinates in which $d\rho$ is proportional to the parallax error at some distance in order to encase an entire cluster.

# CLUSTERFINDER

The ideas outlined above are key components in my current research. Having a way to extract cluster members from a known location is one thing, detecting them is another. I'm in the process of parallelizing a cluster detection algorithm that relies solely on the two-dimensional motions of stars. This is significant because radial velocity measurements become hard to come across at further distances (1$kpc$ +) and there are certaintly undetected clusters and streams in the local galaxy that have yet to be detected. The discovery of these objects could fuel other areas of astrophysics such as galactic evolution and the analysis of dark matter on small spatial scales.
