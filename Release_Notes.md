---
pagetitle: Release Notes for MFXSTM32L152 Component Drivers
lang: en
---

::: {.row}
::: {.col-sm-12 .col-lg-4}

::: {.card .fluid}
::: {.sectione .dark}
<center>
# <small>Release Notes for</small> <mark>MFXSTM32L152 Component Drivers</mark>
Copyright &copy; 2015 STMicroelectronics\
    
[![ST logo](../../../../_htmresc/st_logo.png)](https://www.st.com){.logo}
</center>
:::
:::

# License

Licensed by ST under BSD 3-Clause license (the \"License\"). You may
not use this package except in compliance with the License. You may
obtain a copy of the License at:

[https://opensource.org/licenses/BSD-3-Clause](https://opensource.org/licenses/BSD-3-Clause)

# Purpose

This directory contains the MFXSTM32L152 component drivers.

:::

::: {.col-sm-12 .col-lg-8}
# Update History

::: {.collapse}
<input type="checkbox" id="collapse-section22" checked aria-hidden="true">
<label for="collapse-section22" aria-hidden="true">V2.0.3 / 03-April-2019</label>
<div>			

## Main Changes

- Update release notes format

</div>
:::

::: {.collapse}
<input type="checkbox" id="collapse-section20" aria-hidden="true">
<label for="collapse-section20" aria-hidden="true">V2.0.2 / 25-October-2018</label>
<div>			

## Main Changes

- Reformat the BSD 3-Clause license declaration in the files header (replace license terms by a web reference to OSI website where those terms lie)

</div>
:::

::: {.collapse}
<input type="checkbox" id="collapse-section19" aria-hidden="true">
<label for="collapse-section19" aria-hidden="true">V2.0.1 / 02-June-2017</label>
<div>			

## Main Changes

- Update comments to be used for PDSC generation

</div>
:::

::: {.collapse}
<input type="checkbox" id="collapse-section185" aria-hidden="true">
<label for="collapse-section185" aria-hidden="true">V2.0.0 / 24-June-2015</label>
<div>			

## Main Changes

- Add Shunt management of MFXSTM32L152 component
  - new mfxstm32l152_IDD_ConfigShuntNbLimit() and mfxstm32l152_IDD_GetShuntUsed() APIs
- Add mfxstm32l152_WriteReg() API

**[[NOTE]{style="font-size: 10pt; font-family: Verdana; color: black;"}]{.underline}**
This release must be used with BSP Common driver V4.0.0 or later

</div>
:::

::: {.collapse}
<input type="checkbox" id="collapse-section18" aria-hidden="true">
<label for="collapse-section18" aria-hidden="true">V1.2.0 / 28-April-2015</label>
<div>			

## Main Changes

- mfxstm32l152_IO_Config(): remove unnecessary delay
- mfxstm32l152_TS_DetectTouch(): improve TouchScreen speed
- mfxstm32l152_IDD_Config(): add configuration of number of measure to be performed, with delay between 2 measures
  
**[[NOTE]{style="font-size: 10pt; font-family: Verdana; color: black;"}]{.underline}**  
This release must be used with BSP Common driver V3.0.0 or later

</div>
:::

::: {.collapse}
<input type="checkbox" id="collapse-section17" aria-hidden="true">
<label for="collapse-section17" aria-hidden="true">V1.1.0 / 10-February-2015</label>
<div>			

## Main Changes

- Low Power management of MFXSTM32L152 component:
  - New mfxstm32l152_DeInit() and mfxstm32l152_WakeUp() API
  - mfxstm32l152_LowPower() API completed to be MFXSTM32L152 in Standby mode

**[[NOTE]{style="font-size: 10pt; font-family: Verdana; color: black;"}]{.underline}**  
This release must be used with BSP Common driver V2.2.0 or later

</div>
:::

::: {.collapse}
<input type="checkbox" id="collapse-section16" aria-hidden="true">
<label for="collapse-section16" aria-hidden="true">V1.0.0 / 05-February-2014</label>
<div>			

## Main Changes

- First official release of MFXSTM32L152 IO Expander component driver.

**[[NOTE]{style="font-size: 10pt; font-family: Verdana; color: black;"}]{.underline}**  
This release must be used with BSP Common driver V2.1.0 or later

</div>
:::


:::
:::

<footer class="sticky">
For complete documentation on <mark>STM32 Microcontrollers</mark> ,
visit: [http://www.st.com/STM32](http://www.st.com/STM32)
</footer>
