10 PEI Core is started.

11 Pre-memory CPU initialization is started.

12~14 Reserved.

15 Pre-memory North-Bridge initialization is started.

16~18 Reserved.

19 Pre-memory South-Bridge initialization is started.

1A~2A Reserved.

2B~2F Memory initialization.

31 Memory installed.

32~36 CPU PEI initialization.

37~3A IOH PEI initialization.

3B~3E PCH PEI initialization.

3F~4F Reserved.

60 DXE Core is started.

61 NVRAM initialization.

62 Installation of the PCH runtime services.

63~67 CPU DXE initialization is started.

68 PCI host bridge initialization is started.

69 IOH DXE initialization.

6A IOH SMM initialization.

6B~6F Reserved.

70 PCH DXE initialization.

71 PCH SMM initialization.

72 PCH devices initialization.

73~77 PCH DXE initialization (PCH module specific).

78 ACPI Core initialization.

79 CSM initialization is started.

7A~7F Reserved for AMI use.

80~8F Reserved for OEM use (OEM DXEinitialization codes).

90 Phase transfer to BDS (Boot Device Selection) from DXE.

91 Issue event to connect drivers.Regular Boot

92 PCI Bus initialization is started.

93 PCI Bus hot plug initialization.

94 PCI Bus enumeration for detecting how many resources are requested.

95 Check PCI device requested resources.

96 Assign PCI device resources.

97 Console Output devices connect(ex.Monitor is lighted).

98 Console input devices connect(ex.PS2/USB keyboard/mouse are activated).

99 Super IO initialization.

9A USB initialization is started.

9B Issue reset during USB initialization process.

9C Detect and install all currently connected USB devices.

9D Activated all currently connected USB devices.

9E~9F Reserved.

A0 IDE initialization is started.

A1 Issue reset during IDE initialization process.

A2 Detect and install all currently connected IDE devices.

A3 Activated all currently connected IDE devices.

A4 SCSI initialization is started.

A5 Issue reset during SCSI initialization process.

A6 Detect and install all currently connected SCSI devices.

A7 Activated all currently connected SCSI devices.

A8 Verify password if needed.

A9 BIOS Setup is started.

AA Reserved.

AB Wait user command in BIOS Setup.

AC Reserved.

AD Issue Ready To Boot event for OS Boot.

AE Boot to Legacy OS.

AF Exit Boot Services.

B0 Runtime AP installation begins.

B1 Runtime AP installation ends.

B2 Legacy Option ROM initialization.

B3 System reset if needed.

B(4,5) USB(PCI) device hot plug-in.

B6 Clean-up of NVRAM.

B7 Reconfigure NVRAM settings.

B8~BF Reserved.

C0~CF Reserved.

E0 S3 Resume is stared(called from DXE IPL).

E1 Fill boot script data for S3 resume.

E2 Initializes VGA for S3 resume.

E3 OS S3 wake vector call.S3 Resume

F0 Recovery mode will be triggered due to invaild firmware volume detection.

F1 Recovery mode will be triggered by user decision.

F2 Recovery is started.

F(3,4)Recovery firmware image is found(loaded)

F5~F7 Reserved for future AMI progress codes.

50~55 Memory initialization error occurs.

56 Invalid CPU type or speed.

57 CPU mismatch.

58 CPU self test failed or possible CPU cache error.

59 CPU micro-code is not found or micro-code update is failed.

5A Internal CPU error.

5B Reset PPI is failed.

5C~5F Reserved.

D(0,1,2)-(CPU,IOH,PCH) initialization error.

D3 Some of the Architectural Protocols are not available.

D4 PCI resource allocation error. Out of Resources.

D5 No Space for Legacy Option ROM initialization.

D(6,7) No Console Output(input) Devices are found.

D8 It is an invaild password.

D9~DA Can't load Boot Option.

DB Flash update is failed.

DC Reset protocol is failed.

DE~DF Reserved.

E8 S3 resume is failed.

E9 S3 Resume PPI is not found.

EA S3 Resume Boot Script is invaild.

EB S3 OS Wake call is failed.

EC~EF Reserved.

F8 Recovery PPI is invaild.

F9 Recovery capsule is not found.

FA Invalid recovery capsule.

FB~FF Reserved.
