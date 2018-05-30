# VeoCL
Amoveo OpenCL miner

for AMD & Nvidia GPU´s

Donations:

dystophia (VeoCL author):
`BONJmlU2FUqYgUY60LTIumsYrW/c6MHte64y5KlDzXk5toyEMaBzWm8dHmdMfJmXnqvbYmlwim0hiFmYCCn3Rm0=`

brianmct (Windows build):
`BPbZHatSG6EtD/KnzSfvu9i/lTSFccHXMl883zWTN07b1puDrpDSen2yaR6zIbZfSxS59ZI0jhN9SkHLnSir/B8=`

# Usage
Compile with "make"

run:

`./clientnvidia <address> <poolip:poolport/work> <OpenCL platform ID>`

or

`./clientamd <address> <poolip:poolport/work> <OpenCL platform ID>`

`OpenCL platform ID` is typically 0, but can be 1 or 2 if you have integrated graphics enabled, or a mixed AMD/Nvidia rig.

NOTE: do not include `http://` in the pool address.

Example:

`./clientnvidia BPbZHatSG6EtD/KnzSfvu9i/lTSFccHXMl883zWTN07b1puDrpDSen2yaR6zIbZfSxS59ZI0jhN9SkHLnSir/B8= amoveopool2.com:80/work/ 0`
