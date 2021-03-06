# ExcREXS
type: "object"
description : >
## Description
General Purpose Rotating Excitation System Model.  This model can be used to represent a wide range of excitation systems whose DC power source is an AC or DC generator. It encompasses IEEE type AC1, AC2, DC1, and DC2 excitation system models.

## Data Model
  - properties:
    - e1:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Field voltage value 1 (E1).  Typical Value = 3. Default: 0.0
    - e2:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Field voltage value 2 (E2).  Typical Value = 4. Default: 0.0
    - fbf:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Rate feedback signal flag (Fbf). Typical Value = fieldCurrent. Default: None
    - flimf:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Limit type flag (Flimf).  Typical Value = 0. Default: 0.0
    - kc:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Rectifier regulation factor (Kc).  Typical Value = 0.05. Default: 0.0
    - kd:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Exciter regulation factor (Kd).  Typical Value = 2. Default: 0.0
    - ke:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Exciter field proportional constant (Ke).  Typical Value = 1. Default: 0.0
    - kefd:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Field voltage feedback gain (Kefd).  Typical Value = 0. Default: 0.0
    - kf:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Rate feedback gain (Kf).  Typical Value = 0.05. Default: 0
    - kh:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Field voltage controller feedback gain (Kh).  Typical Value = 0. Default: 0.0
    - kii:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Field Current Regulator Integral Gain (Kii).  Typical Value = 0. Default: 0.0
    - kip:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Field Current Regulator Proportional Gain (Kip).  Typical Value = 1. Default: 0.0
    - ks:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Coefficient to allow different usage of the model-speed coefficient (Ks).  Typical Value = 0. Default: 0.0
    - kvi:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Voltage Regulator Integral Gain (Kvi).  Typical Value = 0. Default: 0.0
    - kvp:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Voltage Regulator Proportional Gain (Kvp).  Typical Value = 2800. Default: 0.0
    - kvphz:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : V/Hz limiter gain (Kvphz).  Typical Value = 0. Default: 0.0
    - nvphz:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Pickup speed of V/Hz limiter (Nvphz).  Typical Value = 0. Default: 0.0
    - se1:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Saturation factor at E1 (Se1).  Typical Value = 0.0001. Default: 0.0
    - se2:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Saturation factor at E2 (Se2).  Typical Value = 0.001. Default: 0.0
    - ta:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Voltage Regulator time constant (Ta).  Typical Value = 0.01. Default: 0
    - tb1:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Lag time constant (Tb1).  Typical Value = 0. Default: 0
    - tb2:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Lag time constant (Tb2).  Typical Value = 0. Default: 0
    - tc1:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Lead time constant (Tc1).  Typical Value = 0. Default: 0
    - tc2:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Lead time constant (Tc2).  Typical Value = 0. Default: 0
    - te:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Exciter field time constant (Te).  Typical Value = 1.2. Default: 0
    - tf:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Rate feedback time constant (Tf).  Typical Value = 1. Default: 0
    - tf1:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Feedback lead time constant (Tf1).  Typical Value = 0. Default: 0
    - tf2:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Feedback lag time constant (Tf2).  Typical Value = 0. Default: 0
    - tp:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Field current Bridge time constant (Tp).  Typical Value = 0. Default: 0
    - vcmax:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Maximum compounding voltage (Vcmax).  Typical Value = 0. Default: 0.0
    - vfmax:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Maximum Exciter Field Current (Vfmax).  Typical Value = 47. Default: 0.0
    - vfmin:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Minimum Exciter Field Current (Vfmin).  Typical Value = -20. Default: 0.0
    - vimax:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Voltage Regulator Input Limit (Vimax).  Typical Value = 0.1. Default: 0.0
    - vrmax:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Maximum controller output (Vrmax).  Typical Value = 47. Default: 0.0
    - vrmin:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Minimum controller output (Vrmin).  Typical Value = -20. Default: 0.0
    - xc:
      - x-ngsi:
        - type: Property
        - model: https://schema.org/Number
      - type: "number"
      - description: : Exciter compounding reactance (Xc).  Typical Value = 0. Default: 0.0
