BRAVE shares part of the data produced during its research in order to make them profitable to the 6G scientific and technological community. This data can be freely used for private activities. However, if exploited into a published or patented work, we kindly ask users to properly acknowledge the help by BRAVE partners.

The subTHz kiosk aims at downloading huge data rates; thus, we consider here the kiosk antenna as the “transmitter” and the user equipements as the “receivers”. The simulated scenario is composed of a fixed kiosk transmitter located in a wide indoor avenue in a shopping mall. More precisely, the kiosk transmitter is in the middle of a large patio, facing an intersection between two avenues; the transmitter vicinity may be considered as “open”, as shown in Fig. 17. The simulated receivers are distributed over the surface of half a disk in front of the kiosk transmitter with radius 10 m. Fig. 18 (right) illustrates the various receiver positions that have been predicted, with a specific antenna orientation at each position i.e. towards the kiosk. All receiver positions are in line-of-sight (LoS).

The transmitter and receivers have each an antenna array of rectangular shape, composed of dual-polar antenna elements (either V/H or +/-45° linear polarizations at the transmitter, and V/H polarizations at the receiver). The size of the transmit antenna array is (16 x 8) x 2 polarizations. The size of the receive antenna array is (8 x 8) x 2 polarizations.
The channel properties are simulated for a central frequency of 150 GHz, and a channel bandwidth of 2 GHz divided into 20 sub-carriers.

The channel H matrix between the transmitter and all receivers is saved into a Matlab file. For each receiver, the H matrix is formed of 128 x 64 x 20 = 163 840 complex coefficients. One coefficient corresponds to the propagation channel gain between one transmit antenna element and one receive antenna element for a specific sub-carrier.
Note that if someone wants to get the H matrix for smaller antenna array, e.g. for a 8 x 8 MIMO system, and for a single frequency, then a relevant sub-matrix can easily be extracted from the full predicted matrix.

![Kiosk environment](https://github.com/jbdore/BRAVE/blob/fc62e4759bb38f52521c7a3678bdaa6baccbaba3/illustrations/Kiosk_fig1.png)
Fig. 1: Kiosk environment.

![Side view](https://github.com/jbdore/BRAVE/blob/fc62e4759bb38f52521c7a3678bdaa6baccbaba3/illustrations/Kiosk_fig2.png)
Fig. 2: Side view – three different considered transmitter heights and orientations (left); Top view – position and orientation of the receiver antennas (right).

We simulated twelve different transmitter situations, with an omni-directional or directional radiation pattern (at the antenna element), three different heights, and two polarization states (V/H or +/-45°).

The LoS direct-path is dominant. However, there are some significant reflections on the ground, ceiling, pilar and surrounding walls that contribute to the channel diversity, thus leads to fading variations along the H matrix in both spatial and frequency dimensions. As expected, those variations reduce when changing the transmit omni-directional antenna for a directional pattern.

[DOWNLOAD](https://github.com/jbdore/BRAVE/blob/663fb5e988a5408f1d2ce96994a28cd093af52da/dataset/kiosk-channel-data/BRAVE%20-%20Description%20of%20the%20kiosk%20scenario%20-%20v1-3.pdf) the user data guidelines.

[DOWNLOAD](https://github.com/jbdore/BRAVE/tree/663fb5e988a5408f1d2ce96994a28cd093af52da/dataset/kiosk-channel-data) the Kiosk V/H omni-directional MIMO channel data.

For any question or download of other channel files, please contact [M. Yoann Corre](mailto:ycorre@siradel.com), with following email’s object: “BRAVE – Request on kiosk MIMO channel data”.
