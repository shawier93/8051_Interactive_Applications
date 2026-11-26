# Appointment Registration Demonstration

[Repository overview](../README.md)

Demonstrate a registration menu that uses status answers and a month to select a stored appointment response.

## Implementations

Memory versions isolate month and status calculations. Display and keypad versions add prompts and confirmation. Interrupt versions require an external event at particular stages. The accepted yes/no values differ, so follow the source-specific example.

| Implementation | Input | Output |
| --- | --- | --- |
| [LCD Status And Month Prompts](LCD%20Status%20and%20Month%20Prompts/README.md) | Stored values or prompted choices | LCD and internal result bytes |
| [Keypad Status And Month Entry](Keypad%20Status%20and%20Month%20Entry/README.md) | Keypad | LCD and internal result bytes |
| [Memory Dose State Update](Memory%20Dose%20State%20Update/README.md) | Values stored in memory | Internal memory |
| [LCD Registration Confirmation](LCD%20Registration%20Confirmation/README.md) | Stored values or prompted choices | LCD and internal result bytes |
| [Interrupt Registration Validation](Interrupt%20Registration%20Validation/README.md) | Keypad | LCD and internal result bytes |
| [LCD Registration Alternate Prompts](LCD%20Registration%20Alternate%20Prompts/README.md) | Stored values or prompted choices | LCD and internal result bytes |
| [Memory Registration Status Flags](Memory%20Registration%20Status%20Flags/README.md) | Values stored in memory | Internal memory |
| [Keypad Appointment Display](Keypad%20Appointment%20Display/README.md) | Keypad | LCD and internal result bytes |
| [Keypad Appointment Confirmation](Keypad%20Appointment%20Confirmation/README.md) | Keypad | LCD and internal result bytes |
