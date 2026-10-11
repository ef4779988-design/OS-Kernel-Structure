# Operating System - Kernal Components
Welcome to my Operating System repository! This documentation covers the core components of an operating system kernel.

# Core Kernel Components
An operating system kernel is the core foundation of an OS that manages system hardware resources and provides services for application software. Below are the 5 main components of the OS kernel:

# 1. Process Management (CPU Scheduling)
Description: Manages the execution of all processes and threads running on the CPU.
Key Responsibilities:
  * Determines which process gets CPU time and when, using various scheduling algorithms.
  * Handles process creation, suspension, resumption, and termination.
  * Manages Context Switching so the CPU can switch smoothly between multiple tasks.

# 2. Memory Management (Main Memory / RAM)
Description:Tra cks and manages the system's primary memory (RAM) efficiently.
Key Responsibilities:
  * Keeps track of which parts of memory are currently in use and by which process.
  * Allocates and deallocates memory space dynamically as processes require.
  * Manages Virtual Memory and Paging to support large applications even when physical RAM is limited.

# 3. File System Management
Description: Organizes and manages data on secondary storage devices (like Hard Disks and SSDs) into logical files and directories.
Key Responsibilities:
  * Handles file creation, deletion, reading, writing, and renaming operations.
  * Maintains the hierarchical directory and path structure.
  * Manages disk space allocation and enforces File Access Permissions and security.

# 4. Device / I/O Management (Device Drivers)
Description: Acts as an intermediary layer between the operating system and hardware peripheral devices (such as keyboards, mice, monitors, and disk drives).
Key Responsibilities:
  * Communicates with hardware through specialized Device Drivers.
  * Manages hardware Interrupts and I/O requests efficiently.
  * Uses buffering and caching to prevent the fast CPU from waiting on slow I/O devices.

# 5. Inter-Process Communication (IPC) & Synchronization
Description: Enables independent or cooperating processes to safely communicate and share data with one another.
Key Responsibilities:
  * Provides mechanisms like shared memory and message passing for data exchange.
  * Implements synchronization tools (such as Mutexes and Semaphores) to prevent Race Conditions and Deadlocks, ensuring data integrity.
