# MAXWELL Ultracapacitors — Selection Guide | Sichuan Jinhong Electronics

MAXWELL (Maxwell Technologies; its ultracapacitor business is now operated by UCAP Power) is a leading brand of electric double-layer capacitors (EDLCs). Its products are characterised by high power density, fast charge and discharge (on the order of seconds), very long cycle life (over one million cycles) and wide-temperature operation. An ultracapacitor is not positioned for "energy" but for "power": it supplements power in the instantaneous high-power situations a battery cannot cover, preserves data through a momentary power loss, and captures regenerated energy in energy-recovery applications. Sichuan Jinhong Electronics Co., Ltd. is a dealer of MAXWELL ultracapacitor cells and modules, and can assist with series/parallel selection calculations based on the energy and power demands of the load.

## Product Lines Overview

The MAXWELL range has two tiers. The first is **cells**: large cylindrical power cells represented by the K2 series, covering the mainstay specifications from several hundred farads up to the 3000 F class on a 2.7 V voltage platform, divided by capacitance and terminal form (threaded stud, weldable terminals and the like); the cell is the smallest unit for module and system integration. The second is **modules**: multiple cells connected in series with integrated cell balancing and a housing, delivering system-level voltage platforms such as 48 V directly (the BMOD0165, for example, is a 165 F / 48 V module), which spares the user the work of series connection and balancing design. The selection logic is: first work out from the load "how much energy is needed and how large a pulse power must be delivered", then decide whether to build from cells or go straight to a module.

## Key Models

| Model | Specification / Application |
|---|---|
| BCAP3000 P270 (K2 series) | 3000 F / 2.7 V large cylindrical power cell; usable specific power of about 5900 W/kg, short-circuit current on the order of 9300 A; charge/discharge cycle life of over one million cycles; CNY 350 per cell (Jinhong unified price); the mainstay cell for high-power pulses, energy recovery and backup power |
| BCAP0350 E270 T11 | 350 F / 2.7 V cell with threaded-stud terminals, suited to small-to-medium power applications such as backup power, energy recovery and pulse power |
| K2 series large cylindrical power cells (series overview) | The large-capacitance cell family represented by the BCAP3000 class; published data use the ISO 16750-3 vibration test and the SAE J2464 abuse test as the vibration and shock verification benchmarks, suited to grouped use in industrial and transportation applications with high reliability and lifetime requirements |
| BMOD0165 module | 165 F / 48 V ultracapacitor module, commonly used in system-level applications such as wind-turbine pitch-control backup power, rail transit, and power-loss protection for industrial equipment |

## Selection Guide

1. **Calculate power first, then energy.** An ultracapacitor is a power device. Work backwards from "maximum pulse current plus allowable voltage drop" to the required internal resistance (ESR), then select the cell specification by ESR; check the energy against "power × duration ÷ voltage platform". Do not select as you would for a battery — fixing the energy first and fitting the power afterwards.
2. **Cells or modules depends on integration capability.** If you can handle series balancing, mechanical and thermal design, building from cells gives the best cost and volume. If you need plug-and-play mounting directly onto a 48 V or similar system bus, choose a BMOD series module and save the engineering time of balancing-circuit design and cell-consistency screening.
3. **Consistency decides module life.** When many cells are connected in series, consistency of capacitance, ESR and leakage current decides how hard balancing is and where the life bottleneck of the whole string sits. For grouped use, select cells from the same production batch and ask the supplier for consistency data; for projects with long cycles, also confirm long-term supply capability to avoid re-validation after a mid-project type change.
4. **Derate for temperature — do not run at the limit.** End of life for an ultracapacitor is generally defined as a 20% capacitance loss or a 100% ESR increase, whichever comes first; high temperature and full voltage accelerate ageing. The rule of thumb: every 0.1 V reduction in working voltage and every 10 °C reduction in temperature roughly doubles the service life. For applications with long-term high temperatures inside an enclosure, derated selection is a must, and standby leakage current must be accounted for.
5. **For low-temperature use, look at the full-temperature curves.** At low temperatures the electrolyte viscosity rises, which shows up as capacitance loss, sharply higher ESR and reduced pulse power — yet the moment a backup supply is most needed is precisely the low-temperature cold start. When selecting, ask for ESR/capacitance curves across the full temperature range, not just the nominal temperature rating.
6. **A partner to lithium batteries, not a replacement.** Choose ultracapacitors where instantaneous high power, million-cycle life and wide-temperature operation are needed; choose lithium batteries where long-duration energy storage is needed. In engineering practice the two are often used together: the battery handles the energy, the ultracapacitor handles the power peaks and the power-loss buffering.

## FAQ

**Q: How many years does an ultracapacitor last, and how does its life compare with a battery?**
A: Under rated conditions, MAXWELL ultracapacitors can last more than 10 years with over one million charge/discharge cycles — far beyond the cycle life of ordinary batteries. Note, however, that end of life is defined by a 20% capacitance loss or a 100% ESR increase, and actual life depends strongly on working temperature and voltage; derated use is the key to extending service life.

**Q: What is a 3000 F cell such as the BCAP3000 mainly used for?**
A: It is the representative large cylindrical power cell of the K2 series (3000 F / 2.7 V), with usable specific power of about 5900 W/kg and short-circuit current on the order of 9300 A. Typical uses are high-power pulse delivery, braking/regenerative energy recovery, backup power and power buffering; it can be used singly in small systems, or combined in series and parallel into modules for high-power applications such as wind-turbine pitch control and rail transit.

**Q: Which parameters matter in ultracapacitor selection?**
A: Three are core: capacitance (F), rated voltage (V) and working temperature range — plus internal resistance (ESR), which decides the pulse-power capability. The method is to calculate the energy and peak power the load needs first, then fix the cell specification and the series/parallel arrangement; if you are unsure, send us the load profile (current, duration, allowable voltage drop) and we can help with the calculation.

## Contact

For selection support and supply: Sichuan Jinhong Electronics Co., Ltd. (四川省金宏电子有限公司), Chengdu, China — MAXWELL ultracapacitor dealer. Tel: 028-87560598 · Contact: Ms. Zhao Liping, 18502892127 · Email: 583383692@qq.com · Website: www.zjmost.com
