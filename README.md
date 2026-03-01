# Black-day-book
Prior art disclosure: offline survival knowledge device with e-ink display, 1TB+ storage, solar charging and EMP shielding. CC BY 4.0
═══════════════════════════════════════════════════
BLACK DAY BOOK
Offline Survival Knowledge Device
Open Hardware Prior Art Disclosure

Author: Mykola Karmanov
Contact: karmanov5991@gmail.com
═══════════════════════════════════════════════════

PRIOR ART DECLARATION

This document constitutes a public prior art
disclosure of the BLACK DAY BOOK concept.
It is intentionally published to prevent
any third party from obtaining patent
protection on this concept or any
implementation of it.

This disclosure is "enabling" — it contains
sufficient technical detail for a person
skilled in the art to implement the concept.

Licensed under Creative Commons CC BY 4.0
https://creativecommons.org/licenses/by/4.0/
Any use requires attribution to original author.

═══════════════════════════════════════════════════
CORE CONCEPT (10 DEFINING PRINCIPLES)
═══════════════════════════════════════════════════

The BLACK DAY BOOK is defined exclusively
by these 10 principles, regardless of
physical dimensions, materials, or
specific components used:

  1. E-ink display (any size or type)
  2. Zero wireless — no WiFi, Bluetooth,
     GPS, cellular, NFC, or any radio
  3. 1TB+ offline knowledge storage
  4. Solar charging built into device
  5. Physical buttons as primary input
  6. EMP shielding (Faraday enclosure)
  7. Curated survival knowledge base
     pre-loaded on device
  8. Multi-source power: battery +
     solar + manual backup
  9. Handheld portable form factor
  10. Purpose-built exclusively for
      offline catastrophe use

Any device implementing all 10 principles
is an implementation of this concept.

═══════════════════════════════════════════════════
PROBLEM STATEMENT
═══════════════════════════════════════════════════

During major catastrophes — war, EMP attacks,
solar storms, grid collapse, occupation —
all connected devices become useless.

Existing e-readers (Kindle, Kobo, reMarkable)
have 32-64GB storage maximum and require
internet for full functionality.

No device currently exists that combines:
  - Offline-first design (zero wireless)
  - Large curated knowledge base (1TB+)
  - Solar + battery + manual power
  - Military-grade physical protection
  - EMP Faraday shielding
  - Purpose-built for catastrophe scenarios

═══════════════════════════════════════════════════
TECHNICAL IMPLEMENTATION
(Enabling Disclosure)
═══════════════════════════════════════════════════

DISPLAY SUBSYSTEM
  Technology:    Electrophoretic E-Ink
                 (e.g. E Ink Kaleido, Carta 1200)
  Size:          4" to 6" (reference: 5.2" square)
  Resolution:    300 DPI minimum
  Controller:    IT8951 e-ink controller chip
  Interface:     SPI or USB to main processor
  Backlight:     Optional warm LED array
                 PWM controlled, <50mA draw

MAIN PROCESSOR SUBSYSTEM
  Architecture:  ARM Cortex-A series
  Reference:     Rockchip RK3566 SoC
                 or equivalent low-power ARM
  RAM:           2GB LPDDR4 minimum
  Interface:     PCIe or eMMC bus to storage

STORAGE SUBSYSTEM
  Internal:      eMMC 5.1 or NVMe SSD
                 1TB minimum (VERSION 1TB)
                 2TB minimum (VERSION 2TB)
  External:      microSD XC slot
                 supporting up to 2TB
  Filesystem:    ext4 or squashfs (read-only)

POWER SUBSYSTEM
  Battery:       LiPo flat cell
                 10,000 mAh minimum
                 3.7V nominal
                 Protection circuit (BMS)
  Solar:         Monocrystalline silicon panel
                 Built into rear or lid surface
                 5-10W peak output
                 MPPT charge controller
  Manual backup: Hand crank DC generator
                 Built-in or USB-C attached
                 Output: 5V regulated
  Charge IC:     CN3791 MPPT or equivalent
  USB-C:         Power Delivery input/output
  Indicator:     E-ink battery % on status bar

EMP PROTECTION SUBSYSTEM
  Method:        Faraday cage
  Material:      Copper mesh or
                 solid aluminum enclosure
  Thickness:     0.5mm minimum copper
                 or 1mm aluminum
  Seams:         Conductive gaskets at all joints
  Ports:         Filtered connectors
                 (ferrite + capacitor filters)
  Goal:          Attenuation >60dB at 1GHz

PHYSICAL PROTECTION
  Standard:      MIL-STD-810H
  Ingress:       IP67 minimum
  Drop:          2 meters onto concrete
  Temperature:   -20°C to +60°C operating
  Screen:        Gorilla Glass or equivalent
                 chemically strengthened glass

INPUT SUBSYSTEM
  Primary:       Minimum 6 physical buttons
                 Up / Down / Left / Right
                 Select / Back
  Material:      Tactile switches rated 1M+ cycles
  Design:        Operable with winter gloves
  Optional:      Capacitive touch layer on e-ink
                 (secondary input only)

SOFTWARE SUBSYSTEM
  OS:            Linux kernel 5.x minimal build
                 Read-only root filesystem
                 No network stack compiled in
  Reader:        Kiwix 3.x engine
                 (open source, ZIM format)
  Document:      PDF + EPUB reader
  Search:        Xapian full-text search index
                 Pre-built at factory
  Maps:          OsmAnd or equivalent
                 OpenTopoMap tiles offline
  UI:            Custom minimal menu system
                 Button-navigable hierarchy
  Languages:     Ukrainian + English minimum
  Boot time:     <10 seconds to readable content

═══════════════════════════════════════════════════
INTENTIONALLY ABSENT — BY DESIGN
═══════════════════════════════════════════════════

  NO WiFi (no wireless chipset installed)
  NO Bluetooth (no wireless chipset installed)
  NO GPS (no GNSS module installed)
  NO cellular (no modem installed)
  NO camera (no image sensor installed)
  NO microphone (no audio input installed)
  NO NFC (no NFC chipset installed)
  NO cloud connectivity
  NO user accounts
  NO telemetry or tracking

  Absence of wireless is a core design
  requirement, not a cost-saving measure.

═══════════════════════════════════════════════════
PRE-LOADED KNOWLEDGE BASE
═══════════════════════════════════════════════════

All content from public domain,
open license, or government sources.

  CATEGORY                          SIZE
  ────────────────────────────────────────
  Wikipedia EN + UA (Kiwix ZIM)    345 GB
  WikiHow offline (Kiwix ZIM)       60 GB
  Khan Academy offline (Kiwix)      30 GB
  Project Gutenberg 70,000 books    60 GB
  Stack Overflow dump              100 GB
  ────────────────────────────────────────
  Survival manuals                 0.3 GB
    US Army FM 21-76
    Nuclear War Survival Skills
    Tom Brown Field Guides
  ────────────────────────────────────────
  Medicine                           3 GB
    Where There Is No Doctor
    Where There Is No Dentist
    Where Women Have No Doctor
    Emergency War Surgery NATO
    MSF Clinical Guidelines
    WHO Emergency Manuals
    DrugBank offline database
  ────────────────────────────────────────
  Agriculture                      4.5 GB
    FAO Agriculture Manuals
    Seed preservation guides
    Veterinary manuals
    Wild edible plants guides
    Pest management guides
  ────────────────────────────────────────
  Science                            5 GB
    Physics (Feynman, Landau)
    Chemistry (CRC Handbook)
    Biology (Campbell)
    Mathematics textbooks
  ────────────────────────────────────────
  Engineering                      3.4 GB
    Foxfire Book series 1-12
    Practical Action guides
    Machinery's Handbook
    Electronics textbooks
  ────────────────────────────────────────
  Energy                           1.6 GB
    Solar, wind, biogas, hydro
    IRENA technical guides
  ────────────────────────────────────────
  Food preservation                0.1 GB
  Construction                     0.7 GB
  Chemistry and Crafts             0.2 GB
  Navigation and Radio             0.1 GB
  ────────────────────────────────────────
  Maps — OpenTopoMap world         147 GB
    Topographic paper-style
    Roads, terrain, rivers
    Settlements, elevation
  ────────────────────────────────────────
  TOTAL BASE                      ~761 GB
  VERSION 1TB user space          ~239 GB
  VERSION 2TB user space         ~1.2 TB

═══════════════════════════════════════════════════
REFERENCE VERSIONS
═══════════════════════════════════════════════════

  VERSION 1TB
    Internal storage:  1TB
    External slot:     microSD up to 1TB
    Est. retail:       $499

  VERSION 2TB
    Internal storage:  2TB
    External slot:     microSD up to 2TB
    Est. retail:       $699

═══════════════════════════════════════════════════
PRIOR ART SCOPE
═══════════════════════════════════════════════════

This disclosure covers the BLACK DAY BOOK
concept in ALL implementations including
but not limited to:

  - Any physical dimensions or form factor
  - Any storage capacity of 1TB or greater
  - Any e-ink display size or manufacturer
  - Any battery capacity
  - Any solar panel type or configuration
  - Any EMP shielding method or material
  - Any ARM or equivalent low-power processor
  - Any Linux or equivalent minimal OS
  - Any combination of the above

provided the implementation satisfies
all 10 CORE PRINCIPLES defined above.

═══════════════════════════════════════════════════
LICENSE
═══════════════════════════════════════════════════

This concept documentation is published
under Creative Commons CC BY 4.0

You are free to:
  - Share and redistribute this document
  - Build this device for personal use
  - Adapt this concept

Under the condition that:
  - You give appropriate credit to
    the original author
  - You indicate if changes were made

Full license: creativecommons.org/licenses/by/4.0

Original author: Mykola Karmanov
Contact: karmanov5991@gmail.com

═══════════════════════════════════════════════════
