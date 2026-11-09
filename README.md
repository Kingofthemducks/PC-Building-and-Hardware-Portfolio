![Build 1](./images/Build%201.jpg)
Build 01 – Legacy AMD System & PSU Failure
Overview
An older AMD-based desktop system built around the AM3 platform. The original configuration was relatively modest, with an entry-level graphics card and a 500W power supply.

Original Hardware Specifications
Component	Specification
CPU	AMD Athlon II X4 640
Motherboard	AM3 motherboard
RAM	8GB DDR3
GPU	NVIDIA GeForce GT 730
PSU	500W
Hardware Incident – PSU Failure
During the initial power-on attempt, the power supply failed.

The PSU was replaced, after which the system underwent hardware checks to determine whether the failure had affected other components.

Fortunately, the components tested appeared to have survived the incident, and the system operated following the replacement.

Graphics Performance
The NVIDIA GT 730 was a significant performance limitation in this configuration. Based on my experience, even older alternatives such as the GTX 550 Ti, GTX 650 Ti or GT 1030 would have offered a more suitable experience, depending on the specific model and workload.

Key Takeaways
Diagnosing a failed power supply.
Replacing the PSU and checking connected components.
Verifying system operation following a hardware failure.
Identifying GPU bottlenecks in older hardware configurations.


![Build 2](./images/Build%202.jpg)
![Build 7](./images/Build%207.jpg)
Build 02 – Personal PC & Hardware Upgrades
Overview
My personal desktop system, originally built around Intel's 8th-generation Core platform. Over time, the system received several graphics card upgrades while retaining its original CPU platform and DDR4 memory.

Original Hardware Configuration
Component	Specification
CPU	Intel Core i7-8700K
Motherboard	MSI Z370 chipset motherboard
GPU	MSI GeForce GTX 1050
RAM	DDR4
Platform	Intel LGA1151
Graphics Card Upgrade History
The system went through three GPU configurations:

MSI GTX 1050 – Original entry-level graphics card, which became a performance limitation for the i7-8700K.
ASUS ROG STRIX RX 580 – A substantial graphics performance improvement, used for several years.
NVIDIA RTX 3070 – A major upgrade that significantly increased graphics performance.
The RTX 3070 remains in the system. In more CPU-intensive workloads, the older i7-8700K platform can become a limiting factor, particularly compared with newer processors offering stronger single-core performance.

Mixed DDR4 Memory Configuration
One unusual aspect of this build is its mixed-memory configuration. Rather than using a matched memory kit, the system runs three different DDR4 modules:

Memory Module	Speed	Voltage
Ballistix	2 × 4GB, 2400MHz	1.2V
HyperX	3200MHz	1.2V
Kingston Fury RGB	3600MHz	1.35V
The modules have operated together without system crashes in my experience.

This is an interesting example of DDR4 memory flexibility, although mixed modules do not guarantee compatibility or operation at their advertised speeds. The motherboard and memory controller determine the final supported configuration and operating frequency.

Key Takeaways
Incremental GPU upgrades across multiple hardware generations.
Identifying CPU and GPU performance limitations.
Working with mixed DDR4 memory modules.
Observing real-world memory compatibility and system stability.
Maintaining and upgrading an existing PC rather than replacing the entire platform.


![Build 3](./images/Build%203%20Case%20Only.jpg)

(Sadly I could not find a picture of the full build when done so I just added the case for reference)

Build 03 – Ryzen 5 8500F & RTX 3070 Custom PC
Overview
A custom desktop PC planned and assembled for a friend who was transitioning from console gaming to PC gaming.

I helped select the components, planned the configuration and assembled the system from scratch.

Hardware Specifications
Component	Specification
CPU	AMD Ryzen 5 8500F
GPU	NVIDIA GeForce RTX 3070
Motherboard	ASRock A620
RAM	Not specified
Storage	1TB SSD
PSU	500W
Initial Boot Issue – No Display Output
After assembling the system, the first power-on attempt produced no display output.

After initial checks, I changed the RAM configuration from slots A1/B1 to A2/B2, following the motherboard's recommended memory population order.

The system successfully booted on the next attempt and has operated since.

GPU Inspection
During the build, I also noticed visible corrosion on the used RTX 3070 heatsink.

The card's previous operating and storage conditions were unknown. Possible explanations include exposure to moisture, prolonged storage in a humid environment or previous use in demanding conditions. However, the exact cause could not be established through visual inspection alone.

Despite its appearance, the GPU was operational at the time of testing.

Key Takeaways
Planning a complete PC configuration for a first-time PC user.
Component selection and hardware assembly.
Troubleshooting a no-display boot issue.
Understanding motherboard RAM slot population requirements.
Inspecting second-hand hardware before installation.
Verifying system functionality after assembly.

![Build 4](./images/Build%204.jpg)

## Build 04 – AMD Phenom II X6 1090T System

### Hardware Configuration

| Component | Specification |
|---|---|
| CPU | AMD Phenom II X6 1090T |
| Motherboard | ASUS AM3 |
| RAM | 8GB (2 × 4GB) DDR3 1600MHz, Dual Channel |
| GPU | Sapphire AMD Radeon R9 280X |
| PSU | 600W |
| Storage | 500GB HDD, 5200 RPM |

### Fault Diagnosis and Troubleshooting

This was one of the most unpredictable systems I have worked with. It suffered from an intermittent no-display issue, particularly after a power outage or when the power cable was disconnected.

When the issue occurred, the PC would power on without displaying anything on the monitor or producing the usual POST beep. Interestingly, it would often start working again after remaining connected to power for some time.

I initially suspected the GPU or memory, as both can cause display and POST-related problems.

**Troubleshooting timeline:**

1. **GPU replacement:** Replaced the Sapphire R9 280X during a later upgrade, but the issue persisted.
2. **RAM replacement:** Replaced the memory modules approximately a year later, but the motherboard continued exhibiting the same behaviour.
3. **Platform replacement:** Eventually replaced the motherboard, CPU and RAM with an Intel platform.

The fact that the issue continued after both the GPU and RAM replacements strongly suggested a motherboard-related fault.

### Final Hardware Upgrade

| Component | Replacement |
|---|---|
| CPU | Intel Core i5-3570 |
| Motherboard | H61 chipset motherboard |
| RAM | 16GB (2 × 8GB) DDR3 1600MHz, Dual Channel |

The platform replacement completely eliminated the recurring no-display issue.

### Additional Observation – Thermal Behaviour

The original Phenom II X6 1090T system also exhibited unusually high operating temperatures. Despite having a relatively large CPU cooler installed, the system became extremely hot after approximately 30 minutes of operation. On some occasions, the exterior of the PC case became uncomfortably hot to the touch.

The exact cause of the excessive heat was never established, but it was another unusual characteristic of this system.

### Key Takeaways

- Diagnosing intermittent POST and display failures requires testing multiple components rather than assuming the GPU is responsible.
- Replacing individual components helped narrow down the likely source of the fault.
- The motherboard was the likely cause, based on the issue persisting through GPU and RAM replacements and disappearing after the platform upgrade.
- Long-term system stability and thermal behaviour are just as important as successful initial booting.

![Build 5](./images/Build%205.jpg)
## Build 05 – Ubuntu Linux Platform Migration

### Original Hardware Configuration

| Component | Specification |
|---|---|
| CPU | Intel Core i5-4690K |
| Motherboard | MSI Z87 chipset, LGA 1150 |
| RAM | 16GB DDR3 1600MHz (2 × 4GB + 1 × 8GB) |
| GPU | NVIDIA GeForce GTX 1050 Ti |
| Operating System | Ubuntu Linux |

### Platform Upgrade

The original owner received another computer from a friend who no longer needed it. The donated system contained a Ryzen 5 processor and 16GB of DDR4 memory, providing an opportunity to upgrade the existing machine.

I selected the better-quality 80 PLUS-certified power supply from the available hardware and transferred the Ryzen-based platform into the existing system, retaining the GTX 1050 Ti.

### Hardware Configuration After Upgrade

| Component | Specification |
|---|---|
| CPU | AMD Ryzen 5 (exact model unspecified) |
| Motherboard | AMD-compatible motherboard (exact model unspecified) |
| RAM | 16GB DDR4 2600MHz (2 × 8GB) |
| GPU | NVIDIA GeForce GTX 1050 Ti |
| Power Supply | Higher-quality 80 PLUS-certified PSU |
| Operating System | Existing Ubuntu Linux installation |

### Linux Compatibility and Troubleshooting

One of the main reasons I found this upgrade interesting was the existing Ubuntu installation. I wanted to see how well Linux would handle a complete platform change, particularly when moving from an Intel processor and motherboard to an AMD-based system.

To my surprise, Ubuntu booted successfully on the first attempt without requiring a clean installation.

Initial performance was somewhat sluggish, but after addressing the relevant driver and platform configuration issues, the system became more responsive.

The successful migration demonstrated how Linux can handle significant hardware changes while retaining an existing operating system installation.

### Key Takeaways

- Tested an existing Ubuntu installation after a complete Intel-to-AMD platform migration.
- Successfully booted the operating system without reinstalling it.
- Worked through post-upgrade driver and configuration issues.
- Reused existing hardware while improving the overall platform.
- Gained practical experience with Linux hardware compatibility and system migration.

### Personal Reflection

This project increased my interest in Linux and open-source operating systems. Ubuntu and other Linux distributions have become increasingly accessible, with improved hardware support, usability and software availability.

I find the decreasing reliance on proprietary software and the growing range of lightweight Linux distributions particularly interesting. Linux is becoming a more practical alternative for everyday computing, rather than being limited to specialised technical environments.

![Build 6](./images/Build%206.jpg)
## Build 06 – ASUS TUF RTX 3080 Gaming PC

### Hardware Configuration

| Component | Specification |
|---|---|
| CPU | AMD Ryzen 7 5700G |
| GPU | ASUS TUF Gaming GeForce RTX 3080 OC 10GB |
| RAM | 32GB DDR4 |
| Storage | 1TB SSD + HDD |
| PSU | 650W |
| Operating System | Windows 11 |

### Initial Condition

This was a second-hand PC that had been tested before purchase. The buyer had previously used consoles and had limited experience with desktop PC hardware.

The system initially appeared to be in good condition. Both storage drives had relatively low usage, and Windows 11 was freshly installed on the SSD.

However, after approximately two days of normal use, the system developed a startup problem.

### Fault Diagnosis

When switched on, the computer repeatedly became stuck on the ASUS motherboard splash screen. Restarting the system several times did not resolve the issue.

After a few restart attempts, an unusual rattling and banging noise started coming from inside the case.

I removed the side panel and investigated the source of the noise by checking the fans, PSU and other moving components. The noise was eventually traced to the secondary HDD.

### Troubleshooting and Resolution

Since Windows 11 was installed on the SSD and the HDD contained no important data, I disconnected the secondary drive to isolate the suspected fault.

After disconnecting the HDD:

- The system successfully passed the ASUS motherboard splash screen.
- Windows 11 booted normally from the SSD.
- The computer operated without further startup issues.

The failing HDD was therefore isolated as the cause of the boot problem.

### Final Outcome

The PC continued operating normally using its SSD. The owner was able to use the computer without further issues and has remained satisfied with the system.

### Key Takeaways

- A secondary storage device can prevent a computer from completing its startup process, even when the operating system is installed on another drive.
- Mechanical noises from an HDD can indicate physical failure.
- Disconnecting individual components is an effective way to isolate hardware faults.
- Understanding the boot process helps distinguish storage-related problems from motherboard or operating system failures.






