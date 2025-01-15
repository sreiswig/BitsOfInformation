# The RGB Server Concept

The RGB Server is a development server containing a consumer GPU from AMD, NVIDIA, And Intel.
Target is to be able to run Llama3.2 Vision 90B model this takes at minimum 64GB vram total.

Run an optimization algorithm to find satisfiable configurations of components.

Components:
 - StarTech 12U Adjustable 4 Post Open Frame Server Rack
 - SilverStone Technology RM51 5U Rackmount Server Chassis
 - AMD Radeon Pro W6800 32GB Graphic Card | 250W Peak
 - Sparkle Intel Arc A770 Titan OC Edition, 16GB GDDR6, ThermalSync, Torn Cooling, Axial Fan, Metal Backplate, SA770T-16GOC | 225W
 - GeForce RTX 4060 Ti 16 GB | 165W
 - AMD Ryzen Threadripper Pro 5955WX, 16 core, 32-Thread Desktop Processor | 280W
 - 256 GB ram
 - 1200 W power supply
 - 2 x 4 TB SSD
 - 2 X 8 TB HDD
 - NixOS
 - Ran into issue with install not sure what's the cause yet
 - All works
 - Setup LAN Network
 - Setup Remote Desktop on LAN only
 - Setup sycl dev environment
 - devenv and direnv not working automatically using rdp
