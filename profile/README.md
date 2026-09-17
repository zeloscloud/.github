## Zelos

The data platform for hardware systems. One place to observe, control, test and
analyse a system in real time, from prototype to production.

Hardware teams usually have their data spread across a telemetry viewer, log
files, a test rig and a pile of one-off scripts. Investigating anything means
exporting, converting formats and lining up timestamps by hand. Zelos keeps it
in one workspace.

What is in this org:

- **zelos** is the core, written in Rust, plus the Rust, Go and Python SDKs for
  streaming your own data in over gRPC. Apache-2.0 or MIT.
- **zelos-extension-\*** are the protocol extensions the app loads. CAN, with
  DBC, ARXML, KCD and SYM databases, SocketCAN, PCAN, Kvaser and Vector
  interfaces, CAN FD, and remote capture over SSH. Modbus TCP and RTU. UDS over
  ISO-TP. OCPP, V2G, MQTT, HTTP.
- **zelos-extension-templates** is the template if you want to write your own.

Docs: https://docs.zeloscloud.io
Site: https://zeloscloud.io
Bugs and questions: open an issue on the repo, or info@zeloscloud.io
