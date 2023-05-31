The proposed data is a set of multipath channel samples predicted at 150 GHz by the SIRADEL ray-tracing (VolcanoUrban) on the urban scenario described in Deliverable D3.1 (Appendix A.1 and Appendix B). A group of 134 lampposts in this area is considered as virtual subTHz device positions. All possible lamppost-to-lamppost links with range lower than 200 meters are computed, leading to a total of 1873 predicted links to be used for a statistical analysis of received power, SNR, peak throughput depending on link length and type of obstruction (LoS, NLoS, OLoS). A 25 dBi antenna gain at both terminals is considered and aligned towards the strongest ray path of the link.

Data are stored in a Matlab file including a sparse 134×134 cell matrix in which each row/column correspond to a lamppost. Cells are empty if the associated link has a length greater than 200 meters, or if the reciprocal link is already reported in appropriate cell. Each cell contains the following data:

*   Lampposts coordinates;
*   Link length;
*   Type of obstruction;
*   Ray path characteristics (angle of departure, angle of arrival, delay, strength);
*   Received power;
*   SNR
*   Peak throughput obtained with the P-QAM modulation under medium phase noise

DOWNLOAD the user data guidelines.

DOWNLOAD the Matlab data file.
