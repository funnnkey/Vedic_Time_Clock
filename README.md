# Vedic Clock

This project is a live digital and analog Vedic time clock built in `vedic_clock.html`.
It converts standard clock time into traditional Vedic units and displays both systems together.

## What This Is

The clock shows:

- Normal time (`HH:MM:SS AM/PM`)
- Vedic time in hierarchical units:
  - `Muhurta` (30 per day)
  - `Kala` (30 per Muhurta)
  - `Kastha` (30 per Kala)
  - `Nimesha` (18 per Kastha)

It includes:

- Digital Vedic format
- A detailed multi-ring analog Vedic dial
- A second analog clock in a familiar style using `1-15` for the Muhurta cycle

## Why It Is Important

Vedic timekeeping preserves a classical Indian framework for understanding time as nested cycles rather than only hours and minutes.  
Using this clock helps connect traditional temporal concepts with modern real-time display.

It is useful for:

- Learning and teaching Vedic units visually
- Comparing modern and traditional time side-by-side
- Building intuition for cyclic and layered time models

## Why This Is an Effective Way to Divide Time

This system is effective because it is:

- **Structured:** Each unit breaks cleanly into the next (`30 -> 30 -> 30 -> 18`), giving consistent hierarchy.
- **Granular:** It supports both broad periods (Muhurta) and very fine precision (Nimesha).
- **Scalable:** The same model works for digital readout and analog dials.
- **Intuitive in cycles:** Repeating circular divisions map naturally to clock faces, making progression easy to track.

In this implementation, the day is split into two equal Muhurta halves (`1-15 AM`, `1-15 PM`) to make usage more familiar while preserving Vedic structure.

## File

- Main app: `vedic_clock.html`
