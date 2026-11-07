Leaf Engine Sound v0.11.3 — Netlify static website.
Changes: e-Pedal off-throttle mix below 10%; pedal lift reduces load; reliable GPS corrects virtual speed/gear with smoothing; motor samples use equal-power blending; shift RPM and limiter audio improved; unchanged read-only OBD.
Safety: audio simulation only; brake is inferred, NOT measured. GPS accuracy and latency vary. No commands control the car. Test app configuration with car parked.
Original engine sound assets from Mark Easting engine-audio; see LICENSE-engine-audio.txt. Check WAV rights separately before public redistribution.

Versao 0.11.4: diagnostico leitura DIDs Pelican e Claude com comparacao GPS. Nenhuma fonte CAN e adotada automaticamente.


v0.11.5: manual VCM speed opt-in via 797/79A/221102, GPS fallback; speed polls occur between pedal queries on a shared ELM channel and may slow pedal cadence. IDs unique per ECU; ATCAF1 dependent parser.

Version 0.11.7: improved WAV partial loading and multi-line DID parsing; retains v0.11.6 diagnostics, e-Pedal and GPS.
