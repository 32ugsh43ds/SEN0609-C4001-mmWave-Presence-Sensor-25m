# SEN0609-C4001-mmWave-Presence-Sensor-25m
/*  * /*
 * ESP32-C6 SuperMini × DFRobot C4001 — Clean single-file sketch
 * - No simulator. Real sensor over UART1 (RX=20, TX=21, 9600).
 * - Boot configurator forces Speed-mode + sensor window (100..2000 cm).
 * - All presence logic on ESP (EMA + delay/hold + ignoreNear + speed gating + deadband).
 * - Minimal HTML UI (built-in) + JSON API; LED active-LOW per your wiring.
 */
