#### class: `Jug`

#### Attributes
`* handle_type (**string**)
 * capacity (**integer**)
 * is_glass (**boolean**)
 * cap_size (**integer**)
 * liquid_flow (**integer**)
 * liquid_measurement_mark (**array**)`


 #### Methods
 `1. pour_jug (cap_size increases liquid_flow and liquid_measurement_mark go down)
  2. fill_jug (capacity gets replenished and liquid_measurement_mark fills up)
  3. break_jug (is_glass = true)
  4. wash_jug (handle_type and cap_size determine how easy to wash)
  `
