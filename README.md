# DRONE STRUCTURAL ASSEMBLY (QUADCOPTER UAV) 🚁

## 1. Overview

The **Quadcopter UAV Structural Assembly** project focuses on designing a **fully integrated drone body** in CAD, including modular motor arms, a central payload/battery enclosure, and structural interfaces for electronics and mounting hardware.  
The goal is to create a concept that is **lightweight, modular, and manufacturable**, while keeping enough structural integrity for real‑world use.
---

## 2. Aim 🎯

- Design a **complete quadcopter UAV body structure** that:
  - Integrates **four motor mount arms**, a **central hub**, and **payload/electronics housing**.  
  - Provides **clearances and mounting points** for motors, ESCs, flight controller, and battery.  
  - Is optimised for **lightweight assembly, maintainability, and structural clearance validation**. 

- Demonstrate skills in **multi‑body assembly design**, **GD&T‑aware interfaces**, and **DFMA‑oriented structural design** within CATIA V5. 

---

## 3. Tech Stack & Tools 🧰

### Software

- **CATIA V5**
  - Part Design  
  - Assembly Design  

### Core Skills Used

- Multi‑body **3D assembly design** and constraint setup.  
- **Modular component design** for easy assembly/disassembly.  
- BOM generation and **2D manufacturing drawing creation**.  
- Fit, clearance, and basic **tolerance validation** across arms and payload areas.  
- Lightweight structural design thinking for UAV applications.
---

## 4. Structural Components & Layout 🧩

Key elements of the assembly:

- **Central hub / main body**  
  - Houses flight controller, receiver, ESCs, and wiring.  
  - Provides mounting bosses, standoffs, and cable routing paths.  

- **Motor arms (x4)**  
  - Radial arms extending from the central hub.  
  - Designed for **modular removal and replacement** (e.g., after a crash).  
  - Incorporate mounting patterns for brushless motors and wire channels.  

- **Payload & battery compartment**  
  - Enclosure or tray for battery pack and potential payload (e.g., camera or sensors).  
  - Designed with CG (center of gravity) considerations for stable flight.  

- **Landing features**  
  - Basic landing legs/feet or provisions for attaching landing gear.  

- **Assembly hardware**  
  - Screws, spacers, and fittings represented in simplified form for clearance checks.  

All parts are created with **3D printing or light fabrication** in mind, balancing strength and mass. 
---

## 5. Modelling Workflow 🧱

1. **Concept & layout**  
   - Define **propeller diameter, motor spacing, and arm length** based on a target UAV size.  
   - Fix the position of the **battery and payload** to maintain good CG.  

2. **Part Design in CATIA V5**  
   - Model the **central hub**, **motor arms**, and **payload mounts** as individual parts.  
   - Add fillets, chamfers, and pocketing for weight reduction.  

3. **Assembly Design**  
   - Assemble all parts with appropriate constraints: concentric, coincident, offset, and angle constraints.  
   - Verify that all motors, props, and arms have sufficient **clearance**.  

4. **Fit & clearance validation**  
   - Check installation space for electronics and wiring.  
   - Ensure no interference between arms, payload, and any optional landing gear.  

5. **Documentation**  
   - Generate a **BOM** for all structural parts.  
   - Prepare **2D drawings** for manufacturing or 3D printing as needed. 

---

## 6. Key Features & Engineering Highlights 🌟

- **Modular arm design**  
  - Each arm is designed as a **replaceable module**, enabling easy maintenance or upgrade of individual sections without redesigning the entire frame.

- **Lightweight structural strategy**  
  - Material is removed where not needed (pockets, cut‑outs) while maintaining stiffness around:
    - Motor mounts  
    - Hub joints  
    - Battery/payload mounting areas. 

- **Clearance & tolerance‑aware design**  
  - Sufficient spacing between:
    - Propeller disks  
    - Arms and central hub  
    - Payload and landing structures  
  - Mating interfaces modelled with **GD&T awareness** for more realistic assembly expectations.

- **Electronics‑ready layout** ⚙️  
  - Central hub provides realistic space for:
    - Flight controller  
    - ESCs  
    - Power distribution and wiring  
  - Routing paths are considered so cables do not interfere with props or moving parts.

- **Portfolio‑friendly concept**  
  - Serves as a great example of **UAV‑related structural design**, showing that you can think about mechanics, packaging, and future integration with avionics. 

---

## 7. Possible Extensions 🚀

- Integrate selection and placement of **actual motors, ESCs, and battery models** from datasheets.  
- Run basic **FEA** on arms and hub to identify stress hotspots under load and during a typical landing.  
- Add **camera gimbal or sensor mounts** to convert it into a more application‑specific UAV.  
- Refine the design for **CFD compatibility** to study airflow around arms and body.  

---

## 8. Author 👨‍💻

**Atharv Nitin Agashe**  
Mechanical Design Engineer · M.Sc. Mechatronics & Robotics  
- Email: `atharvagashe962001@gmail.com`  
- LinkedIn: [www.linkedin.com/in/atharv-agashe9601](https://www.linkedin.com/in/atharv-agashe9601)
