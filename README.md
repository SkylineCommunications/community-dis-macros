# community-dis-macros
Collection of DIS Macros created by Skyline Communications developers

# Protocols

## Params

- **Update Name To Desc**: Updates Param.Name with camelCase of Param Descriptions. Perfect for when creating parameters with MIB, all that is required is to update the displayed name. If updating a table, only select the table and provide the table description name.

- **Find PID Space**: Finds a space in PID ID's when creating new PID's. Can be used to find a large gap in ID's if needed for multiple grouped parameters or tables I.E. if you input 10, in the Output pane a message will appear saying "You can start creating your parameters starting with PID 128" and you will be able to create a parameter from PID 128 - PID 137.

## Tools

- **Export OIDs**: Will export a file containing all OIDs being polled by the driver (does not include OIDs being polled via QAction). Perfect for auditing which OIDs are required for a device.