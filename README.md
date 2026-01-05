# Power-Supply---5V-fix-and-variable-2V---24V

 Technical Specifications
 Input Specifications

* **Input Voltage:**

  * 220–240V AC, 50Hz (via step-down transformers)
* **Isolation:**

  * Transformer-based galvanic isolation from mains supply
 Output Specifications

| Parameter              | Output-1 (Variable)      | Output-2 (Fixed)      |
| ---------------------- | ------------------------ | --------------------- |
| Output Voltage         | 2V – 24V DC (adjustable) | 5V DC                 |
| Regulation Type        | Linear (LM317)           | Linear (7805)         |
| Maximum Output Current | 1A                       | 1A                    |
| Voltage Stability      | Line & load regulated    | Line & load regulated |
| Ripple Voltage         | Low (filtered)           | Low (filtered)        |
 Major Components Used

Transformers

* Step-down transformers used to reduce AC mains voltage to suitable AC levels for rectification.
* Provides electrical isolation and safety.

 Rectification

* **Full-wave bridge rectifiers** used in both channels.
* Converts AC voltage into pulsating DC.

 Filtering

* **Electrolytic capacitors (470µF)** used for ripple reduction.
* Smooth DC voltage before regulation.

 Voltage Regulation

* **LM317 Adjustable Voltage Regulator**

  * Output voltage controlled using an external potentiometer.
  * Output voltage range set using resistor network.
* **7805 Fixed Voltage Regulator**

  * Provides stable +5V output.

 Protection Components

* **Diodes** across regulators to protect against reverse current and capacitor discharge.
* Prevents damage during power-off or short-circuit conditions.

 Electrical Characteristics

* **Line Regulation:** Maintains constant output voltage under input voltage variations.
* **Load Regulation:** Maintains stable voltage with varying load current.
* **Thermal Protection:**

  * Built-in thermal shutdown in LM317 and 7805 ICs.
* **Current Limiting:**

  * Internal current limiting provided by regulators.

 Simulation Details

* Designed and simulated using **Proteus Design Suite**.
* Voltage levels verified using virtual voltmeters.
* Load variation tested to confirm regulation behavior.

 Design Constraints

* Linear regulation used (lower efficiency but low noise).
* Heat dissipation considered for 1A operation.
* Suitable for educational and laboratory applications.

 Applications

* Powering analog and digital electronic circuits
* Embedded system prototyping
* Laboratory experiments
* Educational demonstrations



Just tell me what you want next 😊
