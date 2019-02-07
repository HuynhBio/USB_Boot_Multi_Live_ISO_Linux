This folder is used to extract the Kaspersky Rescue Disk 10.0 AV ISO files

1. Extract all /boot and /rescue folders from the rescue.iso file and copy them to the root of the E2B second parition.

\boot
\rescue
\_ISO (E2B files)
etc.

2. Now move the \boot folder into the \rescue folder.

\rescue
\rescue\boot
\_ISO (E2B files)
etc.

Note that for persistent updates, you will need to create a larger 400MB .imgPTNLBAa23 file containing a 'Kaspersky Rescue Disk 10.0' folder.
See www.easy2boot.com for more details.