# fw-cyw20829b0 Overview

fw-cyw20829 hosts FW patches for CYW20829B0. The patches are categorized depending on the features they support and TX Power configuration.

## COMPONENT_BTFW-ISOC-TX0
Contains FW patch with ISOC support for 0dBm TX Power.
This component should be used with ISOC applications. To include this component in application, add the lines provided below to application makefile:

- DISABLE_COMPONENTS+= BTFW-TX10
- COMPONENTS+= BTFW-ISOC-TX0

## COMPONENT_BTFW-ISOC-TX10
Contains FW patch with ISOC support for 10dBm TX Power.
This component should be used with ISOC applications. To include this component in application, add the lines provided below to application makefile:

- DISABLE_COMPONENTS+= BTFW-TX10
- COMPONENTS+= BTFW-ISOC-TX10

## COMPONENT_BTFW-PAWR-TX0
Contains FW patch with PAWR support for 0dBm TX Power.
This component should be used with PAWR applications. To include this component in application, add the lines provided below to application makefile:

- DISABLE_COMPONENTS+= BTFW-TX10
- COMPONENTS+= BTFW-PAWR-TX0

## COMPONENT_BTFW-PAWR-TX10
Contains FW patch with PAWR support for 10dBm TX Power.
This component should be used with PAWR applications. To include this component in application, add the lines provided below to application makefile:

- DISABLE_COMPONENTS+= BTFW-TX10
- COMPONENTS+= BTFW-PAWR-TX10

## COMPONENT_BTFW-TX0
Contains FW patch for 0dBm TX Power.
This component should be used with non-PAWR and non-ISOC applications. To include this component in application, add the lines provided below to application makefile:

- DISABLE_COMPONENTS+= BTFW-TX10
- COMPONENTS+= BTFW-TX0

## COMPONENT_BTFW-TX10
Contains FW patch for 10dBm TX Power.
This component should be used with non-PAWR and non-ISOC applications. BSP selects this component by default.

© Infineon Technologies, 2024.