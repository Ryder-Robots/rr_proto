# rr_proto
Protobuf headers used amongst edge facing nodes, clients, and micro-controllers.

# Messages available for Serial communication

### Commands
| ID      | CONSTANT        |  SENSOR   | DESCRIPTION              |
| ------  | --------------  | --------- | ------------------------ |
| 200     | MSP_SET_RAW_RC  | Motors.   | Sets motors              |


### Monitor Commands

| ID.     | CONSTANT        |  SENSOR   | DESCRIPTION                            |
| ------  | --------------  | --------- |  ------------------------------------- |
| 100     | MSP_IDENT       | NA        | protocol version + capability variable |
| 102     | MSP_RAW_IMU     | IMU       | Monitor IMU details                    |
| 104     | MSP_MOTOR       | MOTORS    | Set, or monitor motors.                |
| 105     | MSP_RAW_SENSORS | Range     | Range sensors                          |