# Report Notes

The original reports were not added directly because they contained tool-license messages, local server paths, and long low-level net details. This repository uses sanitized summary reports instead.

The implementation reports identify the block/top as `ORCA_TOP`. In this repository, the project is presented as a 32-bit RISC-V physical design project, while preserving the implementation top name as reported by ICC2.

Important limitation: the uploaded report set does not include a clean post-route/final timing QoR report. Therefore, this repository should not claim final timing closure unless a separate post-route timing report is added.

The routing check output contained detailed floating-net/open-net information and license logs, so it is not included as a public report. Use a short final route/DRC summary only after the report is reviewed and cleaned.
