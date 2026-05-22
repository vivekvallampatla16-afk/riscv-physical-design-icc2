# Clock Summary

Source: sanitized summary from ICC2 `report_clocks`.

| Clock | Period | Waveform | Attributes | Source |
|---|---:|---|---|---|
| PCI_CLK | 7.50 | {0 3.75} | propagated | pclk |
| SDRAM_CLK | 4.10 | {0 2.05} | propagated | sdram_clk |
| SD_DDR_CLK | 4.10 | {0 2.05} | propagated, generated | sd_CK |
| SD_DDR_CLKn | 4.10 | {2.05 4.1} | propagated, generated | sd_CKn |
| SYS_2x_CLK | 2.30 | {0 1.15} | propagated | sys_2x_clk |
| SYS_CLK | 4.60 | {0 2.3} | propagated, generated | I_CLOCKING/sys_clk_in_reg/Q |
| v_PCI_CLK | 7.50 | {0 3.75} | virtual | - |
| v_SDRAM_CLK | 4.10 | {0 2.05} | virtual | - |

Generated-clock relationships:

| Generated clock | Master source | Generated source | Master clock | Modification |
|---|---|---|---|---|
| SD_DDR_CLK | sdram_clk | sd_CK | SDRAM_CLK | div(1), combinational |
| SD_DDR_CLKn | sdram_clk | sd_CKn | SDRAM_CLK | div(1), combinational, inverted |
| SYS_CLK | sys_2x_clk | I_CLOCKING/sys_clk_in_reg/Q | SYS_2x_CLK | div(2) |
