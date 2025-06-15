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
| :red_square: | Smaller overall dimensions<br>
| :red_square: | Sealed (to allow mounting in the engine bay, for example. DT connectors are IP68, shoot for IP67 or IP68?)<br>

## Bonus targets:
| :red_square: | Design that allows the case to be fully potted. If someone wants to mount the PDM in a particulary extreme environment<br>
| :red_square: | Design that allows multiple PDMs to be physically connected together (D-001-A shall be designed separately). Similar idea as @Graeme.coard "Double Dingo" design<br>
| :red_square: | Ability to bus power connections?<br>

## Constraints:
- Bottom of the case has to include a heatsink<br>
- The bottom of the PCB must be thermally coupled to the heatsink using 0.5mm thermal pad (3M 5583S, 0.5mm)<br>
- The heatsink has to be clearanced for the battery terminals and DT connector to avoid contact<br>
- The mechanical design of the PCB should not change to allow reverse compatibility:<br>
- Mounting holes<br>
- DT location<br>
- Battery terminal location<br>
- LED locations<br>
- USB port location<br>
- Outside perimeter shape could change if it is warranted<br>
- The inside volume of the case should match the existing case, at a minimum<br>
- To allow clearance for various 12V to 5V converters <br>
- I also solder pins to the test points on development units. Would be nice to be able to still put a case on<br>
- Status, Error and Power LEDs should be visible with the case on<br>
- Need to have a flat location for the sticker (1.5" x 1")<br>
- Case should hold the battery terminal (RedCubes) to prevent twisting when tightening the screw<br>
