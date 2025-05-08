# Mac Models Comparison for Audio/Video Production (May 2025)

## Table of Contents
- [Introduction](#introduction)
- [Mac Model Specifications](#mac-model-specifications)
  - [Intel-Based Macs](#intel-based-macs)
  - [Apple Silicon Macs](#apple-silicon-macs)
- [Performance Insights](#performance-insights)
- [Audio Production Requirements](#audio-production-requirements)
  - [Key Requirements](#key-requirements)
  - [Best Performance vs. Value Mac Models](#best-performance-vs-value-mac-models)
  - [Models to Avoid](#models-to-avoid)
- [Recommendations by Use Case](#recommendations-by-use-case)
  - [Summary Table](#summary-table)
  - [Price vs. Performance Comparison](#price-vs-performance-comparison)
- [Logic Pro Optimization](#logic-pro-optimization)
  - [Memory Optimization](#memory-optimization)
  - [Plugin Efficiency](#plugin-efficiency)
  - [CPU/Performance Tweaks](#cpuperformance-tweaks)
  - [Storage/Streaming](#storagestreaming)
  - [Thermal/Noise Considerations](#thermalnoise-considerations)
- [Logic Pro Track & Plugin Load Estimates](#logic-pro-track--plugin-load-estimates)
- [External Storage Recommendations](#external-storage-recommendations)
- [Final Recommendations](#final-recommendations)
  - [Logic Pro High-Performance Setup](#logic-pro-high-performance-setup)
  - [Logic Pro Capability Chart](#logic-pro-capability-chart)
  - [Special Considerations](#special-considerations)

## Introduction

- This document provides an updated comparison of Mac models for audio and video production, including their Geekbench 6 scores, original retail prices, and current used market values as of May 2025. Hopefully this helps other musicians and engineers make informed decisions.
- Note that for "reasonable" Intel mac baselines, I used the following two models for reference--_was shocked to see how poorly they perform when compared to even the old M1 and mac mini Apple Silicon_):
    - [MacBook Pro 15-inch (2018)](https://everymac.com/systems/apple/macbook_pro/specs/macbook-pro-core-i9-2.9-15-mid-2018-true-tone-display-touch-bar-specs.html)
    - [Mac Pro (2019)](https://everymac.com/systems/apple/mac_pro/specs/mac-pro-16-core-3.2-xeon-w-silver-tower-workstation-2019-specs.html)
#### Of course you should do your own research!


## Mac Model Specifications

### Intel-Based Macs

| Model                          | Processor                     | Single-Core Score | Multi-Core Score | Original Price | Current Used Price |                             |
| ------------------------------ | ----------------------------- | ----------------- | ---------------- | -------------- | ------------------ | --------------------------- |
| **MacBook Pro 15-inch (2018)** | Intel Core i9-8950HK (6-core) | 1,048             | 5,084            | $2,799-$3,099   | ~$800-$950         | ([EveryMac][6])             |
| **Mac Pro (2019)**             | Intel Xeon W-3245 (16-core)   | 1,128             | 14,464           | $7,999         | ~$5,200-$6,000     | ([EveryMac][1], [Apple][2]) |

*Note: Original prices are based on Apple's pricing at launch. Current used prices are approximate and based on recent listings.*

### Apple Silicon Macs

| Model                           | Processor                | Single-Core Score | Multi-Core Score | Original Price | Current Used Price |                                            |
| ------------------------------- | ------------------------ | ----------------- | ---------------- | -------------- | ------------------ | ------------------------------------------ |
| **Mac mini (M4, 2024)**         | Apple M4 (10-core)       | 3,916             | 14,678           | $599           | ~$550              |                                            |
| **Mac mini (M4 Pro, 2024)**     | Apple M4 Pro (14-core)   | 3,823             | 22,342           | $1,299         | ~$1,150            |                                            |
| **Mac Studio (M1 Max, 2022)**   | Apple M1 Max (10-core)   | 2,418             | 12,642           | $1,999         | ~$1,400            |                                            |
| **Mac Studio (M1 Ultra, 2022)** | Apple M1 Ultra (20-core) | 2,396             | 18,384           | $3,999         | ~$3,500            |                                            |
| **Mac Studio (M2 Max, 2023)**   | Apple M2 Max (12-core)   | 2,804             | 14,885           | $1,999         | ~$1,800            |                                            |
| **Mac Studio (M2 Ultra, 2023)** | Apple M2 Ultra (24-core) | 2,777             | 21,379           | $3,999         | ~$3,059            |                                            |
| **Mac Studio (M3 Max, 2024)**   | Apple M3 Max             | 3,070             | 14,721           | $1,999         | ~$1,900            |                                            |
| **Mac Studio (M3 Ultra, 2025)** | Apple M3 Ultra (28-core) | 3,247             | 28,169           | $3,999         | ~$3,800            |                                            |
| **Mac Studio (M4 Max, 2025)**   | Apple M4 Max (14-core)   | 4,049             | 23,763           | $1,999         | ~$1,950            | ([Apple][3], [Tech Reviews][4], [eBay][5]) |

*Note: Original prices are based on Apple's pricing at launch. Current used prices are approximate and based on recent listings.*

## Performance Insights

* **Intel vs. Apple Silicon**: The transition from Intel processors to Apple Silicon has resulted in significant performance gains. For instance, the base M4 Mac mini outperforms the 2019 Mac Pro in both single-core and multi-core benchmarks.

* **M-Series Progression**: Each new generation of Apple's M-series chips brings notable improvements. The M4 Max, for example, delivers a substantial boost in single-core performance compared to its predecessors.

* **M3 Ultra vs. M4 Max**: While the M4 Max excels in single-core tasks, the M3 Ultra's higher core count gives it an edge in multi-core performance, making it more suitable for heavily threaded workloads.

## Audio Production Requirements

For audio production (Logic Pro, 32–64 tracks, heavy VI and plugin usage), the most critical factors are:

### Key Requirements

| Factor                          | Why It Matters                                                                                                                         |
| ------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------- |
| **High Single-Core Speed**      | Most DAWs, including Logic Pro, process many tasks single-threaded (plugin chains, UI responsiveness).                                 |
| **Moderate to High Multi-Core** | Parallel tasks like offline bouncing, some plugin types (e.g., reverbs, convolution), and video editing/export use multi-core heavily. |
| **Large Unified Memory (RAM)**  | VI libraries, effects, and real-time processing thrive on RAM—32GB minimum, 64GB+ preferred.                                           |
| **Fast Storage**                | Sample library streaming, quick project load/save. NVMe SSDs are essential.                                                            |
| **Thermal Efficiency/Silence**  | Fans ramping up or throttling can disrupt studio work—Apple Silicon has a big advantage here.                                          |

### Best Performance vs. Value Mac Models

#### Top Tier (Money no object, pro studio)

| Model                   | Why it's ideal                                                                                                                                                             |
| ----------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Mac Studio M3 Ultra** | Best multi-core performance, excellent single-core, supports 192GB RAM (perfect for 64+ track sessions with huge VI libraries).                                            |
| **Mac Studio M4 Max**   | Leading single-core scores (great for plugin-heavy sessions), 14 high-performance cores, supports up to 128GB RAM, far more cost-effective than Ultra for audio workloads. |

#### Optimal Value

| Model                             | Why it's ideal                                                                                                                                         |
| --------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Mac Studio M2 Max (or M3 Max)** | Excellent single-core, good multi-core, supports 96–128GB RAM. Used pricing (~$1,800–$1,900) makes this a superb value for serious audio producers. |
| **Mac mini M4 Pro**               | Great single-core, surprising multi-core for the price (~$1,150). 64GB RAM limit means it's best for medium sessions or satellite workstations.      |

### Models to Avoid

| Model                       | Why not ideal                                                                                                                                                                 |
| --------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **MacBook Pro 15" 2018 i9** | Too old, throttles under load, limited RAM, Intel architecture inefficient for modern DAWs.                                                                                   |
| **Mac Pro 2019 Xeon**       | Surprisingly low single-core, poor value compared to Apple Silicon. Even if RAM and GPU look tempting, real-world Logic Pro performance lags behind newer Minis and Studios. |

## Recommendations by Use Case

### Summary Table

| Use Case                                    | Recommended Mac (2025)                               |
| ------------------------------------------- | ---------------------------------------------------- |
| **Flagship studio (no compromises)**        | Mac Studio M3 Ultra (or wait for M4 Ultra late 2025) |
| **Pro studio, best performance per dollar** | Mac Studio M4 Max or M3 Max                          |
| **Medium/advanced home studio**             | Mac Studio M2 Max or M3 Max                          |
| **Secondary/satellite system or portable**  | Mac mini M4 Pro                                      |

### Price vs. Performance Comparison

| Model               | Single-Core | Multi-Core | Max RAM | New / Used Price    |
| ------------------- | ----------- | ---------- | ------- | ------------------- |
| Mac mini M4 Pro     | 3,823       | 22,342     | 64GB    | $1,299 / ~$1,150    |
| Mac Studio M2 Max   | 2,804       | 14,885     | 96GB    | $1,999 / ~$1,800    |
| Mac Studio M3 Max   | 3,070       | 14,721     | 128GB   | $1,999 / ~$1,900    |
| Mac Studio M4 Max   | 4,049       | 23,763     | 128GB   | $1,999 / ~$1,950    |
| Mac Studio M3 Ultra | 3,247       | 28,169     | 192GB   | $3,999 / ~$3,800    |

## Logic Pro Optimization

### Memory Optimization

* **Use unified RAM wisely**: M-series Macs share RAM between CPU & GPU. Avoid loading *all* samples into memory—use disk streaming where possible.
* **Purge unused samples** in Kontakt, Omnisphere, etc.
* Upgrade to **96GB or 128GB RAM** if using big orchestral templates (Spitfire, EastWest).

### Plugin Efficiency

* Prioritize **native Apple Silicon** versions of plugins.
* Update older plugins to latest ARM64 builds—Rosetta adds CPU overhead.
* Use **"freeze" tracks** for heavy VIs not being actively edited.

### CPU/Performance Tweaks

* **Buffer Size**:
  * Tracking: 64–128 samples (lower latency).
  * Mixing/Mastering: 256–512+ (frees CPU).
* Enable **Multithreading** in Logic's preferences (Settings → Audio → Processing Threads → Automatic/Highest).
* Turn off **low-latency mode** when mixing to avoid CPU constraints.

### Storage/Streaming

* Store *sample libraries* on separate **external NVMe drives** (Thunderbolt 3/4 preferred).
* Leave **macOS and Logic Pro projects** on the internal SSD for fastest access.

### Thermal/Noise Considerations

* Mac Studios and Minis stay virtually silent even under load.
* Avoid older Intel Macs—they throttle and run hot under plugin-heavy loads.

## Logic Pro Track & Plugin Load Estimates

Assumptions:
* **Track** = 1 audio track with 1 compressor + 1 EQ plugin.
* **Virtual Instrument (VI)** = 1 software instrument + moderate FX chain.
* **Heavy Plugins** = CPU-intensive synths (Omnisphere, Diva) or convolution reverbs.

| Mac Model               | Audio Tracks (light FX) | VI Tracks (moderate FX) | Heavy Plugins (Diva, Omnisphere) |
| ----------------------- | ----------------------- | ----------------------- | -------------------------------- |
| **Mac mini M4 Pro**     | 300+                    | ~80–100                 | ~40–50 simultaneous             |
| **Mac Studio M2 Max**   | 400+                    | ~100–120                | ~50–60 simultaneous             |
| **Mac Studio M3 Max**   | 450+                    | ~110–130                | ~55–65 simultaneous             |
| **Mac Studio M4 Max**   | 500+                    | ~120–150                | ~60–75 simultaneous             |
| **Mac Studio M3 Ultra** | 600+                    | ~160–200                | ~80–90 simultaneous             |

**Notes**:
* *Light Audio Mixing* scales very well across all models.
* *Virtual Instruments* (especially modeled synths and sample libraries) are **memory** and **single-core** hungry.
* *Heavy Plugins* can **crush** old Intel Macs after 20–30 instances — M4 Max can easily run 60+!

## External Storage Recommendations

**Goal:** Fast loading of VI sample libraries (Kontakt, Spitfire, etc.) and Logic projects without bottlenecks.

| Drive Model                   | Interface       | Typical Speed (Read) | Why Recommended             | Price (USD)   |
| ----------------------------- | --------------- | -------------------- | --------------------------- | ------------- |
| **Samsung T9 Portable SSD**   | USB 3.2 Gen 2x2 | ~2,000 MB/s          | Fast, portable, reliable    | ~$200 (2TB)   |
| **Sabrent Rocket XTRM-Q 4TB** | Thunderbolt 3/4 | ~2,800 MB/s          | Best for massive libraries  | ~$499 (4TB)   |
| **OWC Envoy Pro FX**          | Thunderbolt 3/4 | ~2,700 MB/s          | Rugged, pro-grade enclosure | ~$300 (2TB)   |
| **Crucial X9 Pro 2TB**        | USB 3.2 Gen 2   | ~1,050 MB/s          | Good budget portable        | ~$120 (2TB)   |

## Final Recommendations

### Logic Pro High-Performance Setup

| Component           | Recommendation                                     |
| ------------------- | -------------------------------------------------- |
| **Mac**             | Mac Studio M4 Max (or M3 Ultra if doing video too) |
| **RAM**             | 96GB or 128GB (64GB only if absolutely needed)     |
| **Storage**         | Internal 2TB NVMe + External 2TB+ Thunderbolt SSD  |
| **Audio Interface** | Thunderbolt (UA Apollo, RME, Antelope) preferred   |
| **Plugins**         | Use native Apple Silicon versions                  |
| **Settings**        | Large buffer during mixing, freeze unused tracks   |

### Logic Pro Capability Chart

| Model               | Tracks | VIs | Heavy Plugins | RAM Recommendation |
| ------------------- | ------ | --- | ------------- | ------------------ |
| Mac mini M4 Pro     | 300    | 80  | 40            | 64GB max           |
| Mac Studio M2 Max   | 400    | 100 | 50            | 96GB preferred     |
| Mac Studio M3 Max   | 450    | 110 | 55            | 128GB preferred    |
| Mac Studio M4 Max   | 500    | 120 | 60            | 128GB recommended  |
| Mac Studio M3 Ultra | 600    | 160 | 80            | 192GB possible     |

### Special Considerations

If your sessions use a lot of **Omnisphere**, **Kontakt** with **multi-mic positions**, **FabFilter** chains, or heavy **convolution reverbs**, favor:

* **M4 Max** for best real-time feel (almost no latency).
* **M3 Ultra** if bouncing or rendering massive final projects.

[1]: https://everymac.com/systems/apple/mac_pro/specs/mac-pro-16-core-3.2-xeon-w-silver-tower-workstation-2019-specs.html "Mac Pro 16-Core 3.2 (2019) Specs - EveryMac.com"
[2]: https://www.apple.com/shop/buy-mac/mac-mini/m4 "Buy Mac mini with M4 Chip - Apple"
[3]: https://www.apple.com/shop/buy-mac/mac-mini/m4-pro "Buy Mac mini with M4 Pro Chip - Apple"
[4]: https://www.lbtechreviews.com/test/computer/mac-studio-m1-ultra "Review: Mac Studio M1 Ultra | Mac Studio Can Save You Money"
[5]: https://www.ebay.com/shop/apple-studio-m1-max?_nkw=apple+studio+m1+max "Apple Studio M1 Max - eBay"
[6]: https://everymac.com/systems/apple/macbook_pro/specs/macbook-pro-core-i9-2.9-15-mid-2018-true-tone-display-touch-bar-specs.html "MacBook Pro Core i9 2.9 15-inch (Mid-2018) Specs - EveryMac.com"
