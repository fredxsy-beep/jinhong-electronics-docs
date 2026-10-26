# METCAL Soldering & Rework Systems — Selection Guide | Sichuan Jinhong Electronics

METCAL is the soldering brand of OK International (frequently referred to as METCAL/OKI in China). Its core technology is SmartHeat RF induction heating: the soldering tip is itself both the heating element and the temperature reference. The alloy in the heating layer self-regulates at its Curie point, holding temperature within ±1.1 °C with no temperature overshoot and no calibration required — temperature is locked in by the physical properties of the material, so there is none of the measurement drift that aging thermocouples cause in conventional temperature-controlled stations. Sichuan Jinhong Electronics Co., Ltd. is a Gold Distributor of METCAL/OK International (2026 authorization, certificate No. OKCLC0229), supplying METCAL soldering, desoldering and rework systems together with the full range of soldering tips and consumables.

## Product Lines Overview

The METCAL range falls into four tiers by power and application. The **MFR series** (60 W) is the mainstream general-purpose line: compact footprint, single- or dual-port versions, well suited to most hand-soldering work. The **MX series** (40 W / 80 W power grades) is the main platform for high-reliability assembly, built for joints whose thermal load varies widely; from the MX-5210 upward it adds power metering and auto-sleep. The **CV series** builds on the MX platform with Connection Validation — feedback on solder joint formation plus data traceability — for production lines with tighter process-control requirements. The **rework line** comprises the HCT2 digital hot-air rework station and the MRS-1100A BGA rework station, together with the BVX-250 fume extraction system for the workstation. All systems are ESD-safe and feature AC ground monitoring. In the SmartHeat system, changing the tip changes the temperature grade: temperature grades are set by the Curie point of the tip, so tips should be chosen by joint size and process requirements rather than compensated for with a temperature dial.

## Key Models

| Model | Specification / Application |
|---|---|
| MFR-1160 | MFR series soldering / rework system, SmartHeat induction heating, 60 W output power, single- and dual-port versions available, compact footprint design, ESD-safe with AC ground monitoring |
| MX-500 / MX-500S | Classic MX series single units, induction heating, 40 W / 80 W power grades, fast thermal recovery, no temperature adjustment or calibration needed; suited to standard soldering stations with a consistent range of joint types |
| MX-5200 | MX series soldering, desoldering and rework system; supports simultaneous dual-port operation for parallel soldering and desoldering workstations |
| MX-5210 | MX series dual-handpiece model; the two handpieces dynamically share 80 W of output power as needed; built-in digital + bar-graph power meter; the TipSaver workstand puts the iron to sleep when docked, extending tip life |
| STTC-836 | Cartridge tip for the MX series (a commonly used specification within the STTC range); SmartHeat tips are divided by joint geometry and temperature grade, with further ranges including UFTC ultra-fine and SMTC |
| HCT2-200-21 | Digital hot-air rework station; temperature and airflow precisely adjustable and reproducible; designed for desoldering and rework of SMD components such as QFP and BGA without damaging neighboring components |
| MRS-1100A | BGA rework station for removal, placement and rework of area-array devices such as BGA and CSP, replacing operator feel with controlled temperature profiles and alignment |
| BVX-250 | Soldering workstation fume extraction system; high extraction power, compact size, low-noise positioning; captures and filters fumes from hand soldering and rework at the source |

## Selection Guide

1. **Match the series and power to the thermal load of the joint.** Where small-to-medium joints predominate and bench space is tight, choose the MFR-1160 (60 W). Where a large share of joints are high thermal load — large ground areas, thick copper layers and the like — a 60 W system will lose temperature, and you should step up to the MX / CV series. Never compensate for insufficient power by extending soldering time; that damages both the board and the tip.
2. **Changing the tip is changing the temperature.** SmartHeat has no temperature dial: first select the tip shape by joint geometry (conical, chisel, knife, etc.), then the temperature grade by process. A tip that is too small lacks thermal capacity; one that is too large invites bridging. Manage tips under a workstation register — unauthorized tip-grade changes at the bench are a common source of soldering drift. STTC tips fit MX series handpieces and must not be mixed with CV series tips.
3. **Budget total power for dual ports.** Dual handpieces share the system's total output (on the MX-5210, for example, the two handpieces dynamically share 80 W). Alternating use is no problem; if both handpieces will solder high-thermal-load joints simultaneously, calculate against the total demand and evaluate a higher-power configuration if necessary.
4. **Process-control requirements decide whether you need CV.** Choose MX when stable soldering is all you need; choose the CV series when you also need solder joint formation feedback and process data recording with traceability.
5. **Assign rework tools by device type.** For ordinary SMD components (QFP and similar), use the HCT2 hot-air station with nozzles matched to component size, setting temperature and airflow as a pair. For area-array devices with hidden joints, such as BGA and CSP, use the MRS-1100A rework station: prove the temperature profile on a scrap board and record it before working on production boards. Do not force a BGA off with a hot-air gun — that easily leads to board warping and solder bridging.
6. **Use docked sleep to extend tip life.** Short tip life is most often caused by oxidation during long periods of high-temperature idling. Build the habit of docking the iron (TipSaver auto-sleep), tin new tips before first use, and keep a solder layer on tips when out of use — tip life improves markedly. Plan fume extraction and a consumables register for the workstation at the same time.

## FAQ

**Q: Why do METCAL stations need no temperature adjustment and no calibration?**
A: A SmartHeat tip self-regulates at the Curie point of its heating-layer alloy, so temperature is determined by the physical properties of the tip itself; fitting a tip of a different temperature grade changes the soldering temperature. There is no external sensing-and-control loop, and therefore no measurement drift and no temperature overshoot, with temperature held to ±1.1 °C. This is the fundamental difference from stations built around a ceramic heating element plus a thermocouple: in those, the sensing point is not at the joint, temperature collapses on contact with a large pad and recovers slowly, and as the thermocouple ages, the displayed temperature quietly diverges from the actual temperature.

**Q: What does "the two handpieces dynamically share 80 W" on the MX-5210 mean?**
A: The two handpieces do not each receive a fixed share of power. Instead, the total of 80 W is allocated dynamically according to each joint's real-time thermal demand: whichever handpiece is soldering the larger joint receives more power and recovers heat faster. Combined with the power meter, you can also watch changes in power draw to spot abnormal heat absorption at a joint.

**Q: When soldering large joints, the temperature drops badly and the joint won't wet. What should I do?**
A: First fit a tip with greater thermal capacity. If that is still not enough, the joint's thermal load exceeds the power capability of the current system, and you should upgrade to the MX / CV series rather than extend the soldering time. When soldering performance turns abnormal, also check whether the wrong tip grade is fitted and whether the tip is oxidized — most "slowdowns" are tip aging, and a fresh tip restores performance.

## Contact

For selection support and supply: Sichuan Jinhong Electronics Co., Ltd. （四川省金宏电子有限公司）, Chengdu, China — Gold Distributor of METCAL/OK International (2026 authorization, certificate No. OKCLC0229). Tel: 028-87560598 · Contact: Ms. Zhao Liping, 18502892127 · Email: 583383692@qq.com · Website: www.zjmost.com
