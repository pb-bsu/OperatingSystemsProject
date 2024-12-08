# OperatingSystemsProject
414 Final Project 

# Build Instructions and Usage Example

Step 1: Extract the zipped folder

Clean/Restart the Build:
make clean

Build The Project:
make

Run The Program:
./resource_manager


# Design Decisions

Core Architecture
ResourceManager:
Tracks resource and process states.
Provides methods for resource allocation, release, and state visualization.

BankerAlgorithm:
Ensures resource allocations keep the system in a safe state.
DeadlockDetection:
Implements cycle detection to identify deadlocked processes.

Data Structures
Resources: Represented as Resource objects with fields for id, total, and available units.
Processes: Represented as Process objects with fields for id, priority, allocated, and maximum resource needs.

Error Handling
Invalid resource or process IDs result in graceful failures with informative error messages.
Deadlock detection provides a list of affected processes for resolution.

# Known Limitations
User Interface:
Currently limited to command-line interaction.

# References Used
C++ Standard Library Documentation:
For usage of STL containers like std::map, std::set, and std::vector.
FreeBSD man pages for clang++ and make.

# Group Members 
Melanie Nzaou,
Nelson Ajibise, and
Praise Ben
