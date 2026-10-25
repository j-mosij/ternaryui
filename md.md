Unified Core Executable: All functional modules (UI layout, WebGL/2D math canvas, audio synthesizer, tryte-compression logic, and PQC wrappers) are contained within a single file.
Purified DOM Injection Layer: Employs DOMPurify to sanitize all real-time status output, system state logs, and user inputs before injecting them into the DOM tree.
5-Trit Tryte-x5 Math Engine: Maps spatial parametric floats directly into balanced ternary (3 
5
 =243 states) representations, enabling lightweight tensor calculations directly inside client-side JavaScript.
Hardware & Side-Channel Protections:
Anti-Cloning Serial Token: Generates a unique, non-repudiable fingerprint bound to execution timing and low-level hardware canvas signatures.
RAM & EM Emission Noise Masking: Spawns asynchronous dummy heap allocation loops (Float64Array) to equalize memory consumption profiles and flatten hardware-frequency side-channel signatures.
Post-Quantum Cryptographic Key Derivation: Integrates Web Crypto API primitives to simulate lattice-based encapsulation protocols for local engine communication.
