**This repository is to implement a TrustZone project for Cortex-M85 (AN555 FPGA image for MPS3 board)**

- Right now ARM does not provide any TrustZone Example projects.
- This repository is trying to convert a Cortex-M33 TrustZone project to Cortex-M85

*Linker Scripts used in this project*
- Secure Project Linker Script [linker_SSE310MPS3_secure.sct](https://github.com/Tomal-kuet/SSE310_MPS3_AN555_TZ/blob/main/SSE310_S/RTE/Device/SSE-310-MPS3_AN555/linker_SSE310MPS3_secure.sct)
- Non-Secure Project Linker Script: [linker_SSE310MPS3_non_secure.sct](https://github.com/Tomal-kuet/SSE310_MPS3_AN555_TZ/blob/main/SSE310_NS/RTE/Device/SSE-310-MPS3_AN555/linker_SSE310MPS3_non_secure.sct)
