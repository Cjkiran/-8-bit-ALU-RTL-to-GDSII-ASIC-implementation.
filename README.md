# 8-bit-ALU-RTL-to-GDSII-ASIC-implementation.
ASIC Design @ 2025 
# 🧠 Flow Summary (RTL to GDSII)

# The filelist Contains:

![Screenshot 2025-01-23 125653](https://github.com/user-attachments/assets/10c9351f-1968-4b40-8250-d45e4923ee23)

# run file 

![Screenshot 2025-01-23 125634](https://github.com/user-attachments/assets/a8271fce-6ab1-4502-a578-d03b344826d6)

# 1. RTL Design
Connect all blocks in alu_top.v.

![Screenshot 2025-01-23 125713](https://github.com/user-attachments/assets/d760f19e-01b7-412c-a708-a6484d1d5a39)

Write a testbench alu_top_tb.v.

![Screenshot 2025-01-23 125713](https://github.com/user-attachments/assets/86581cbd-06d9-4fa0-9b11-cac1479288f3)

# 2 Simulation using Synopsys VCS

![Screenshot 2025-01-23 125430](https://github.com/user-attachments/assets/241cc530-8390-4a30-96ad-6986776e079e)

![waveform ](https://github.com/user-attachments/assets/bb79f178-df28-4aed-acf3-4c25677b20b8)

# Synthesis using DC Shell

![Screenshot from 2025-02-06 14-24-09 (1)](https://github.com/user-attachments/assets/d54de8b2-22aa-42e5-b27e-8bd22c60a4f1)

![Screenshot from 2025-02-06 14-37-28 (1)](https://github.com/user-attachments/assets/114c57ae-3ad9-474c-86d3-48a2d6e609b4)

![schematic 2 (1)](https://github.com/user-attachments/assets/4899afc6-2255-4cd7-8a6d-065f3f94a6aa)


# report_area: shows total cell area, breakdown by module

![Screenshot from 2025-02-06 14-38-35 (1)](https://github.com/user-attachments/assets/ff6b4b34-d606-43d8-8973-4d9e81acc585)


# report_timing: reports slack, critical paths, and setup/hold checks

![Screenshot from 2025-02-06 14-27-07](https://github.com/user-attachments/assets/3490b259-3394-462b-9bf7-b95538feb353)


# report_power: provides dynamic and leakage power estimations

![power (2)](https://github.com/user-attachments/assets/91827456-141f-4be6-ad54-2624b17d9368)





