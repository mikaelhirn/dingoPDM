# Case naming logic

- e.g. **S-001-A** where <code>[**S**ingle/**D**ouble]-[Major Number]-[Minor revision]</code>
- The Major Number changes when the case is not compatible with the previous version
- Single = case for one dingoPDM pcb
- Double = case for two dingoPDM pcbs

### Status
- :green_square: : Complete
- :yellow_square: : In Progess
- :red_square: : Not Started

## Improvement targets for the S-001-A case:
| :red_square: | Smaller overall dimensions <br>
| :red_square: | In the XY direction (if the PDM is mounted to the XY plane)<br>
| :red_square: | Sealed<br>
| :red_square: | Allow mounting in the engine bay, for example<br>
| :red_square: | DT connectors are IP68, shoot for IP67 or IP68?<br>

## Bonus targets:
| :red_square: | Design that allows the case to be fully potted<br>
| :red_square: | If someone wants to mount the PDM in a particulary extreme environment<br>
| :red_square: | Design that allows multiple PDMs to be physically connected together<br>
| :red_square: | Similar idea as @Graeme.coard "Double Dingo" design<br>
| :red_square: | Ability to bus power connections?<br>

## Constraints:
| :red_square: | Bottom of the case has to include a heatsink<br>
| :red_square: | The bottom of the PCB must be thermally coupled to the heatsink using 0.5mm thermal pad (3M 5583S, 0.5mm)<br>
| :red_square: | The heatsink has to be clearanced for the battery terminals and DT connector to avoid contact<br>
| :red_square: | The mechanical design of the PCB should not change to allow reverse compatibility:<br>
| :red_square: | Mounting holes<br>
| :red_square: | DT location<br>
| :red_square: | Battery terminal location<br>
| :red_square: | LED locations<br>
| :red_square: | USB port location<br>
| :red_square: | Outside perimeter shape could change if it is warranted<br>
| :red_square: | The inside volume of the case should match the existing case, at a minimum<br>
| :red_square: | To allow clearance for various 12V to 5V converters <br>
| :red_square: | I also solder pins to the test points on development units. Would be nice to be able to still put a case on<br>
| :red_square: | Status, Error and Power LEDs should be visible with the case on<br>
| :red_square: | Need to have a flat location for the sticker (1.5" x 1")<br>
| :red_square: | Case should hold the battery terminal (RedCubes) to prevent twisting when tightening the screw<br>
