# Project Duality Format Specs
This document serves as an information sheet designed to explain what the formats used by Duality serve as, as well as when they should be used.

## Project Duality Knowledge Store (PDKS)
The `*.pdks` extension denotes a knowledge store. This format is where the modular user-end comes into play. These files will store information about both what the AI learns as well as basic usage. However, proper usage of this information (if it is ported into an instance not tailored to handle said information) can **not** be guaranteed, as some of the usage capabilities are defined in the root AI.

## Project Duality Instance
The `*.pdi` extension denotes an AI as a whole. It inclues 100% of the information in the AI. This allows for easy porting of your AI to other devices. In order to ensure ease of access, the user can utilize the interface included with Duality to export some knowledge as a `PDKS`, as well as view what other `PDKS` files have been imported to the AI.
