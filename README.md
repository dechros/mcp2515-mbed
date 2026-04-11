# mcp2515-mbed

MCP2515 CAN controller driver ported to ARM Mbed. Wraps Mbed `SPI` and `DigitalOut` objects to provide standard/extended frame send and receive, configurable bitrate and clock, filters and masks, and the usual MCP2515 register helpers.

## Usage

Drop `mcp_can.h`, `mcp_can.cpp`, and `mcp_can_dfs.h` into an Mbed OS project and construct `MCP_CAN` with pointers to your `SPI` bus and chip-select `DigitalOut`.

See source for build instructions.
