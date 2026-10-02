# Mechanical Development

This document expands on the public mechanical development history of DOKY. Detailed PCB and firmware information is intentionally excluded.

## V1 — Proof of Concept

The first mechanical prototype used a NEMA 17 stepper motor connected to a custom cycloidal gearbox manufactured in PA6-CF. Its purpose was to evaluate the basic valve-actuation concept before developing a complete enclosure.

## V2 — Complete Enclosure and Field Fit

V2 introduced an elongated enclosure with rounded corners, manufactured as a complete prototype. Custom TPU gaskets were designed and printed for the enclosure interfaces to reduce water ingress.

The assembly was installed on an existing valve to verify dimensions, alignment and installation geometry. The physical integration was successful, but the NEMA 17 and reduction system did not provide enough torque to operate the valve.

## V3 — Modular Architecture and High-Torque Actuation

V3 reorganized the enclosure into functional sections referred to during development as rings. Different sections were designed around the components mounted in each part of the system.

The drive system was replaced by a DOCYKE 305 N·m actuator with a manufacturer-built metal planetary gearbox. A custom metal coupling was added to transmit torque between the actuator and the valve.

A complete fit test was performed before field installation. In the field, the new actuation system was able to open and close the valve easily.

Some enclosure joints required additional sealing during installation, and epoxy putty was applied as a field adaptation.

## Current Material Testing

Dense TPU coupling prototypes are being evaluated as proof-of-concept parts for a future mechanical idea. The final application remains under development and is intentionally not described in detail.

## Public Documentation Scope

The public repository documents mechanical design decisions, manufacturing, integration and field validation. It does not publish detailed PCB design files, schematics, Gerbers or firmware source code.
