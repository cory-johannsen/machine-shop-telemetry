# Top level components
* Telemetry agent(s)
** Raw gcode emitter
** CNC data collector
** 3D printer data collector
* Ingest API
** Stateless
** Minimal inspection
** Rapid dispatch
** Low latency
** Fire-and-forget from the agent/data collector
* Ingest pipe
* Persistence API
** CRUD endpoints
* Data store
** Timeseries support
*** Redis
*** Prometheus
