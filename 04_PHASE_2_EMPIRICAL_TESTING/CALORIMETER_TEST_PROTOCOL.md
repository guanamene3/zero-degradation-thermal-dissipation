# Phase II Physical Validation: Calorimeter Test Protocol

**Document ID:** `PROTO-CAL-01`  
**Test Spec:** Steady-State and Transient Thermal Performance Verification  

---

## 1. Test-Bench Architecture

Physical validation is conducted on a closed-loop guarded hot plate calorimeter test-bed:
* **Heater Core:** High-purity oxygen-free copper (OFHC) cartridge block with a calibrated $10.0\text{ mm} \times 10.0\text{ mm}$ square contact pedestal.
* **Thermocouple Array:** Embedded Type-T micro-thermocouples located at $1.0\text{ mm}$, $2.0\text{ mm}$, and $3.0\text{ mm}$ below the interface contact plane to calculate heat flux via Fourier's Law ($q'' = -k \frac{dT}{dz}$).
* **Interface Material:** Indium foil preform ($0.05\text{ mm}$ nominal thickness) under standard mounting pressure of $300\text{ kPa}$.

---

## 2. Testing Sequence

1. **Baseline Stabilization (0 to 2 Hours):**
   * Apply a low calibration flux of $100\text{ W/cm}^2$ until temperature equilibrium ($\frac{dT}{dt} < 0.1^\circ\text{C}/\text{min}$) is achieved.
2. **Ramp to Benchmark Load (Hours 2 to 3):**
   * Increment thermal load linearly at $50\text{ W/cm}^2$ every 3 minutes up to the full challenge specification of $1{,}200\text{ W/cm}^2$ (total continuous thermal power: $120\text{ W}$).
3. **48-Hour Continuous Burn-In (Hours 3 to 51):**
   * Continuous operation at $1{,}200\text{ W/cm}^2$.
   * Log junction temperature ($T_j$), surface temperature distribution, and sink delta every 10 seconds.
   * Disqualification trigger: Any sustained period where $T_j > 65.0^\circ\text{C}$ for $>30\text{ continuous seconds}$.
4. **Thermal Gradient Thermography (Hour 50):**
   * Capture radiometric infrared thermal images using a calibrated FLIR A6700sc camera (or equivalent) through the optical view-port.
   * Verify surface temperature gradient across the $10\text{ mm} \times 10\text{ mm}$ active zone does not exceed $5.0^\circ\text{C}$.
5. **Thermal Shock Cycling (Hours 52 to 72):**
   * Subject the assembly to 250 cycles between $-20^\circ\text{C}$ and $+85^\circ\text{C}$ (ramp rate $\ge 15^\circ\text{C}/\text{min}$).
   * Re-measure post-cycling thermal interface resistance ($R_{th}$) to verify degradation does not exceed $5\%$.
