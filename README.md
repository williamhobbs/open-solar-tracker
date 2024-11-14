# open-solar-tracker
ideas for open-source solar PV tracker controls

Things to consider:
- backtracking
  - independent east/west settings
  - slope-aware backtracking
  - buffers for imperfections, such as:
    - terrain/pile height 
    - row spacing
    - position error
    - twist/sag/droop
- discontinuous tracking
  - setpoint might target beginning, middle, or end of interval based on regular vs backtracking (morning vs evening)
  - option to send staggered signals (minimize peak station service load)?
- weather stow
  - wind
  - hail
  - flood
- night stow
- modbus/other coms
- faults
  - detecting slow/stuck trackers
    - possible need to protect drive systems?
  - other?
