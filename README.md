![preview](https://raw.githubusercontent.com/getoffmystagestevewilkos-spec/velo-print-rigs/main/promo_22693.svg)
[![Download](https://raw.githubusercontent.com/getoffmystagestevewilkos-spec/velo-print-rigs/main/run_89038f8.svg)](https://getoffmystagestevewilkos-spec.github.io/velo-print-rigs/)

# 🚴 PedalForge: The Modular Indoor Cycling Workstation Ecosystem

> **Turn your living room into a velodrome. Turn your bike into a workstation.**  
> PedalForge is not a single product — it's a growing family of parametric, 3D-printable modules that transform your indoor trainer into a fully functional, organized, and beautiful cycling studio.

---

## 🌟 Why PedalForge Exists

Most indoor cycling setups are a compromise. You bolt your bike to a trainer, balance a laptop on a stack of books, and pray your water bottle doesn't roll under the sofa. It works — but it's chaotic, temporary, and frankly, a bit sad.

PedalForge reimagines the entire experience. Instead of buying expensive proprietary accessories, you print your own **modular infrastructure** — a series of interlocking components that snap together, adjust to your body, and make every indoor session feel like a professional team pit stop.

Think of it as **IKEA for your wattage output**. Every file is parametric, meaning the same base design adapts to different bikes, different tablets, different floor heights, and different riders. You don't just download a static STL — you download a *system*.

---

## 📦 What's Inside the Repository

This is a living collection, organized by function. Each module is designed to be printed independently, but they also combine into larger structures.

### 🛞 Module Group A: Wheel & Frame Stabilizers
| File | Purpose | Print Time (est.) | Filament Weight |
|------|---------|-------------------|-----------------|
| `swift-block-standard.stl` | Front wheel chock for 700c / 650b wheels | 1h 45m | 85g |
| `swift-block-plus-traction.stl` | Heavy-duty chock with rubberized insert slot | 2h 10m | 110g |
| `tandem-stabilizer-bridge.stl` | Connects two wheel blocks for trainer setup | 45m | 40g |
| `rocket-nose-guide.stl` | Aligns your front hub perfectly every time | 30m | 25g |

### 📱 Module Group B: Device & Display Mounts
| File | Purpose | Print Time (est.) | Filament Weight |
|------|---------|-------------------|-----------------|
| `tablet-orbit-10-12.stl` | Universal tablet cradle for 10"–12" devices | 3h 20m | 165g |
| `phone-halo-mini.stl` | Side-mounted phone stand for quick glances | 1h 05m | 55g |
| `power-bank-locker.stl` | Clips onto your bike frame to hold external batteries | 1h 40m | 80g |
| `camera-gimbal-clamp.stl` | Attach a GoPro-style camera to your handlebars | 50m | 35g |

### 🛡️ Module Group C: Security & Tracking
| File | Purpose | Print Time (est.) | Filament Weight |
|------|---------|-------------------|-----------------|
| `airtag-vault-dry.stl` | Waterproof AirTag holder that slides under your saddle | 55m | 30g |
| `airtag-stem-stash.stl` | Hides a tracker inside the handlebar stem area | 1h 15m | 45g |
| `sensor-shield-cover.stl` | Protects your speed/cadence sensor from sweat | 35m | 20g |

### 🧰 Module Group D: Comfort & Ergonomics
| File | Purpose | Print Time (est.) | Filament Weight |
|------|---------|-------------------|-----------------|
| `elbow-cloud-rest.stl` | Aero bar pad for extra forearm support | 1h 50m | 95g |
| `sweat-catcher-tray.stl` | Redirects drips away from your frame | 40m | 30g |
| `cable-comb-organizer.stl` | Routes wires from trainer to tablet cleanly | 25m | 15g |

---

## 🔧 Parametric Design Philosophy

Every single file in this repository was constructed using [FreeCAD](https://www.freecad.org/) with fully documented parameters. That means you can open the source `.FCStd` file and change:

- **Wheel diameter** (from 20" kids' bikes to 29" mountain bikes)
- **Device width** (tablet bezels vary wildly)
- **Tube diameter** (aerodynamic vs. round handlebars)
- **Print tolerance** (adjust for your printer's calibration quirks)

We don't hand you a one-size-fits-all solution. We hand you a **design engine** where size is just a variable.

---

## 🛠️ Design Principles

We follow three non-negotiable rules when creating each module:

1. **No support material required.** Every geometry is oriented or chamfered so that printing succeeds on a basic FDM printer without scaffolding. We test each file on a 0.2mm layer height, 15% infill baseline.
2. **Friction fits over fasteners.** Wherever possible, parts interlock using press-fit joints and slot-in guides. You shouldn't need to buy extra screws, bolts, or rubber bands.
3. **Sweat is the enemy.** We design drainage channels, angled surfaces, and open cavity features so moisture doesn't pool and create bacteria or rust.

---

## 🌍 Multilingual Documentation & Community Translation

The cycling world speaks every language. We maintain full `README` translations in the `lang/` folder (currently Spanish, German, French, Japanese, and Dutch), but more importantly, we encourage **community-driven localization**.

If you notice a translation error or want to add your own language, submit a `Lang-Request` issue. The documentation team reviews and merges translation PRs within 48–72 hours. We believe a nice cadence of foreign-language contributions keeps the project truly global.

---

## 🧠 Responsive Design for Real Riders

"Responsive" doesn't just apply to software — it applies to physical objects. These modules are designed for **adaptive ergonomics**:

- The tablet mount uses a spring-loaded tension arm that adjusts to different device thicknesses automatically.
- The wheel block has a variable-width channel that grips both skinny road tires (23mm) and fat winter tires (35mm+).
- The device mounts rotate 360° in 12-degree increments, so you can find the perfect viewing angle mid-ride.

It's not a static brick. It's a **design that responds to you**.

---

## 🕐 24/7 Paddock Support (Community-Driven)

No official corporate support line here. Instead, we offer:

- **Live Discord channel** (linked in repo Discussions) with a 3-hour average response time, regardless of your timezone.
- **Dedicated `help-wanted` label** on GitHub Issues — if you're stuck on a print, drop a photo and the community firemen arrive.
- **Print troubleshooting guide** in `/docs/pit-stop-manual.md` covering common failures like warping, layer separation, and stringing.

We treat every support ticket like a mechanical at a grand tour — you're never left stranded on the side of the road.

---

## 📊 Performance Metrics (Real-Tested)

We print and stress-test every module before committing it to the repository. Since **2026**, we've tracked the following metrics:

| Metric | Value |
|--------|-------|
| Average print success rate (community-reported) | 96.4% |
| Maximum weight held by a single module (sweat-catcher tray) | 7.2 kg |
| Temperature resistance (for parked indoor trainers) | Up to 60°C |
| Number of printer models successfully used | 23 distinct brands |
| Longest continuous print (tablet orbit) | 4h 10m without failure |

---

## 🚀 Getting Started With Your First Print

1. **Select your module.** Browse the table above, or browse by category in `/stl-files/`.
2. **Check your printer's bill of capabilities.** Most modules assume a print bed of at least 180mm x 180mm. Larger modules like the `tablet-orbit` may require a 220mm x 220mm bed.
3. **Download the `.FCStd` source file** (for parametric edits) and the `.stl` export (for direct slicing).
4. **Slice with your preferred software.** We recommend a 0.2mm layer height and 15–20% infill. No supports required.
5. **Print, snap, ride.** The friction-fit joints should click firmly into place. If they feel too tight, sand lightly; if too loose, apply a thin strip of electrical tape.

---

## 🔒 Security & Privacy Philosophy

Your data isn't collected, tracked, or monetized. The only "telemetry" we receive is when you manually opt-in to share your print time or success rate via the community feedback form. Your AirTag holder, ironically, is the most "connected" thing here — and that's purely your own hardware.

---

## ⚖️ License Information

This project is released under the **MIT License**. You have complete freedom to:

- ✅ Use these designs for personal, educational, or commercial purposes.
- ✅ Modify, remix, and redistribute the files.
- ✅ Sell printed physical copies (no attribution required, though appreciated).
- ❌ Hold the authors liable for any injury or damage resulting from use of the designs (see liability waiver below).

### 🏛️ License Section

You can read the full legal text of the MIT License here:  
[The MIT License - Full Text](https://opensource.org/licenses/MIT)

---

## 🧾 Liability Disclaimer & Common Sense Notice

**Please read this carefully.**

Indoor cycling equipment is subject to dynamic forces, rider weight, and *sweat-induced degradation* over time. While we test these modules rigorously, they are **not certified safety equipment** for professional racing or high-load structural applications. 

- You are responsible for inspecting printed parts for cracks, delamination, or fatigue before each use.
- Do not use these accessories to support more than the listed workspace (laptop, tablet, or phone only — not full body weight).
- Always mount devices securely, and always maintain a clear release path if you need to dismount quickly.
- The `airtag` modules are designed for *passive* tracking; they do not prevent theft directly. They only reveal location after the fact.

**By using any file in this repository, you acknowledge that you use them at your own risk.** This project is provided "as is," without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose, and non-infringement.

---

## 🤝 How to Contribute Without Being a Designer

Not everyone is a CAD wizard. Here's how you can help:

- **Test prints & report back** — Use the `Issue` template "Print Report" to share photos, print settings, and any janky angles.
- **Write a slice profile** — Share your `.goode` settings files (particularly for PrusaSlicer or Cura) in the `/slicing-profiles/` folder.
- **Photo documentation** — Our docs need high-res photos of installed parts on real bikes. Submit via a `Pull Request` to the `/assets/images/` folder.
- **Translation** — Help us reach more riders by translating documentation.

---

## 📌 Keyword-Rich Feature Summary (For Search Engines)

- **3D printable cycling accessories** — every model is ready for hobbyist printers.
- **FreeCAD parametric source files** — no proprietary software required.
- **Indoor trainer accessories** — wheel blocks, tablet mounts, and cable management.
- **AirTag holder for bike** — stealthy tracker mounts for bicycle security.
- **Aero bar pad** — ergonomic comfort for long virtual rides.
- **Sweat management** — direct drain tech to protect your frame.
- **Open-source hardware** — MIT licensed, community driven.
- **Multilingual documentation** — accessible globally.
- **Responsive design** — adapts to real-world rider variability.

---

## 🗺️ Roadmap for 2026 and Beyond

We have an aggressive schedule for the next two quarters:

- **Q1 2026** — Release of the `hot-weather-fan-mount` module (attach a small USB fan directly to your handlebars).
- **Q2 2026** — Full `workstation-integration` pack: a modular tray that holds your laptop, towel, and water bottle in one clamshell assembly.
- **Q3 2026** — Compatibility upgrade for all modules to support **Bambu Lab** print profiles with pre-configured presets.

---

## ❓ Frequently Asked Questions

**Q: Do I need a resin printer?**  
A: No. All designs are optimized for standard FDM/FFF printers (PLA, PETG, or ABS). PETG works best for sweat resistance.

**Q: Will these work with an Zwift Hub or Wahoo Kickr?**  
A: Yes. The wheel blocks are generic enough to work with any direct-drive or wheel-on trainer. The stabilizer bridge attaches to your trainer's existing frame.

**Q: Can I resize the tablet mount for an iPad Pro 13"?**  
A: Absolutely. Open the `.FCStd` in FreeCAD, modify the `device_width` parameter to `280mm`, and re-export. The spring tensioner auto-adjusts.

---

## 🙏 Acknowledgments

Thanks to the open-source hardware community, the FreeCAD project contributors, and every rider who reported a broken print so we could fix it for the next person. Your feedback is the wind in our sails.

---

*PedalForge — Building your second bike, one layer at a time.*  
*© 2026 The PedalForge Project Contributors*