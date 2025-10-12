---
Company: CompTIA
Course: A+
Teacher: Professor Messer
Exam Code: 220-1201
Difficulty: Easy
Topic: Network tools
URL:
---
## Network Cabling & Diagnostic Tools
### Cable crimpers

- Attach connectors (RJ-45, RJ-11, coax) to cable ends.
- Metal prongs pierce insulation and secure the connector to the sheath.
- Used on coaxial, twisted pair, and fiber.
- Final step before cable testing.
    

#### Crimping best practices:
- Use quality crimpers, wire strippers, and snips.
- Match connector type to cable (solid vs stranded).
- Practice for consistency.

---
### Wi-Fi analyzer

- Hardware analyzers bypass OS limitations.
- Show 802.11 details: frequencies, channels, signal strength, APs, interference.
- Spectrum analyzers reveal non-Wi-Fi noise (microwaves, Bluetooth, etc.).

Use case: Identifying coverage gaps, channel overlap, and interference sources.

---
### Tone generator and probe

- Used for tracing cables through walls or bundles.
- Tone generator injects an analog tone into a wire.
- Probe detects tone inductively (no metal contact).
- Works with modular jacks, coax, and punch-down blocks.
    
Result: Hear a two-tone sound to identify the correct cable end.

---

### Punch-down tool

- Inserts wires into insulation displacement contacts (IDC).
- Used on 66-blocks, 110-blocks, and patch panels.
- Simultaneously seats and trims wires.

#### Punch-down best practices:

- Keep wire pairs twisted as close to termination as possible.
- Maintain organized layout and labeling.
- Document everything (labels, diagrams, written records).
    
---
### Cable testers

- Check continuity and pinout (simple wire map).
- Identify missing pins, opens, shorts, or crossed pairs.
- Basic testers verify wiring; advanced certifiers test performance (attenuation, crosstalk, loss).

Note: Not for frequency or signal quality testing unless using a certifier.

---
### Loopback plugs
- Short transmit and receive pins together on a port.
- Used to test physical port functionality.
- Common types: RS-232 (9-pin or 25-pin), Ethernet, T1, fiber.
    
Note: Not a crossover cable — it loops back on itself for testing.

---
### Taps and port mirrors
- Used for capturing or monitoring network traffic.
- Tap (hardware): placed inline to duplicate traffic; may be active or passive.
- Port mirror (SPAN): switch feature that sends a copy of selected traffic to another port.

#### Difference:
- Taps are physical and reliable; port mirrors are software-based and may drop packets under load.