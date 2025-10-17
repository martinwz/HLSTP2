# HLSTP2

# Vitis HLS bugs

## Miscompile bugs

| No.  |                           Bug Report Title                             |    Status     |
| :--: | :---------------------------------------------------------: | :-----------: | 
|  1  | [The simulation output of the code synthesized with Vitis HLS 25.1 is inconsistent with the expectations.](https://adaptivesupport.amd.com/s/question/0D5Pd00000ocbEjKAI/the-simulation-output-of-the-code-synthesized-with-vitis-hls-251-is-inconsistent-with-the-expectations)  | Pending  |
|  2  | [The code compiled with Clang without errors; however, Vitis HLS 25.1 reported a co-simulation failure.](https://adaptivesupport.amd.com/s/question/0D5Pd00000ocnbSKAQ/the-code-compiled-with-clang-without-errors-however-vitis-hls-251-reported-a-cosimulation-failure)  | Pending |
|  3  | [CSIM passed, but in the end, Vitis HLS 25.1 reports co-simulation failed.](https://adaptivesupport.amd.com/s/question/0D5Pd00000pEUk3KAG/csim-passed-but-in-the-end-vitis-hls-251-reports-cosimulation-failed)    | Pending  |
|  4  | [Vitis HLS 25.1 seems unable to synthesize a simple code correctly.](https://adaptivesupport.amd.com/s/question/0D5Pd00000v13CrKAI/vitis-hls-251-seems-unable-to-synthesize-a-simple-code-correctly?language=en_US)    | Pending  |

## Crash bugs

| No.  |                           Bug Report Title                              |    Status     |
| :--: | :---------------------------------------------------------:  | :-----------: |
|  1  | [Issues with Combining Redundant Instructions Leading to Vitis Crash.](https://adaptivesupport.amd.com/s/question/0D5Pd00000p80VVKAY/issues-with-combining-redundant-instructions-leading-to-vitis-crash)  | **Confirmed** |
|  2  | [Vitis HLS 25.1 stops abnormally after performing if-conversion on hyperblocks.](https://adaptivesupport.amd.com/s/question/0D5Pd00000pD7b0KAC/vitis-hls-251-stops-abnormally-after-performing-ifconversion-on-hyperblocks) | **Confirmed**  |
|  3  | [Vitis HLS 25.1 may crash at 'Instruction simplification'.](https://adaptivesupport.amd.com/s/question/0D5Pd00000qvftPKAQ/vitis-hls-251-may-crash-at-instruction-simplification)  | **Confirmed** |
|  4  | [Vitis HLS 25.1 crashes without reporting any warnings or errors.](https://adaptivesupport.amd.com/s/question/0D5Pd00000sCAeFKAW/vitis-hls-251-crashes-without-reporting-any-warnings-or-errors) | Pending  |
 

## Tool Failure bugs
| No.  |                           Bug Report Title                             |    Status     |
| :--: | :---------------------------------------------------------: | :-----------: | 
|  1  | [Vitis HLS 25.1 always reports an error while synthesizing a simple code.](https://adaptivesupport.amd.com/s/question/0D5Pd00000sKBD9KAO/vitis-hls-251-always-reports-an-error-while-synthesizing-a-simple-code?language=en_US)  | Pending |

## Performance bugs
| No.  |                           Bug Report Title                             |    Status     |
| :--: | :---------------------------------------------------------: | :-----------: | 
|  1  | [Vitis HLS 25.1 hangs after the 'Performance' phase of compilation.](https://adaptivesupport.amd.com/s/question/0D5Pd00000s6XWgKAM/vitis-hls-251-hangs-after-the-performance-phase-of-compilation) | Pending | 


# Bambu bugs

## Miscompile bugs

| No.  |                           Bug Report Title                             |    Status     |
| :--: | :---------------------------------------------------------: | :-----------: | 
|  1  | [Bambu 24.10 may contain a bug that causes it to fail to synthesize a simple program.](https://github.com/ferrandi/PandA-bambu/issues/366)  | **Confirmed**  |
|  2  | [Bambu may be unable to synthesize the code correctly.](https://github.com/ferrandi/PandA-bambu/issues/370)  | Pending |
|  3  | [Bambu may generate wrong Verilog code.](https://github.com/ferrandi/PandA-bambu/issues/371)    | Pending  |
|  4  | [Bambu 24.10 finishes the synthesis process, but the generated HDL code outputs a wrong result.](https://github.com/ferrandi/PandA-bambu/issues/374)    | Pending  |
|  5  | [Bambu 24.10 may generate HDL code that does not meet expectations.](https://github.com/ferrandi/PandA-bambu/issues/375)    | Pending  |
 

## Crash bugs

| No.  |                           Bug Report Title                              |    Status     |
| :--: | :---------------------------------------------------------:  | :-----------: |
|  1  | [Simple code makes bambu-24.10 crash.](https://github.com/ferrandi/PandA-bambu/issues/362)  | **Confirmed** |
|  2  | [Bambu24.10 stops in Frontend::RebuildInitialization2 and reports 'segmentation fault'.](https://github.com/ferrandi/PandA-bambu/issues/363) | Pending  |
|  3  | [Bambu crashed during the Frontend::eSSA stage.](https://github.com/ferrandi/PandA-bambu/issues/365)  | Pending | 
 

## Tool Failure bugs
| No.  |                           Bug Report Title                             |    Status     |
| :--: | :---------------------------------------------------------: | :-----------: | 
|  1  | [Bambu 24.10 reports 'unexpected condition'.](https://github.com/ferrandi/PandA-bambu/issues/367)  | Pending |
|  2  | [Bambu-24.10 stops synthesize the code and reports 'absl::btree_map::at'.](https://github.com/ferrandi/PandA-bambu/issues/368)  | Pending |

## Performance bugs
| No.  |                           Bug Report Title                             |    Status     |
| :--: | :---------------------------------------------------------: | :-----------: | 
|  1  | [Bambu 24.10 executes BitValueIPA and BitValueOpt without termination.](https://github.com/ferrandi/PandA-bambu/issues/372)  | Pending |


