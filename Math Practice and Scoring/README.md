# Math Practice and Scoring

[Repository overview](../README.md)

Present arithmetic questions, compare the answers with the program’s answer key, and update a score.

## Implementations

One version uses fixed answers in memory. Another computes an answer key from operand tables. Table-driven versions store the operation, operands, expected answer, and score weight together. Their retry and penalty rules must be read separately; they are not all the same quiz.

| Implementation | Input | Output | Implementation notes |
| --- | --- | --- | --- |
| [Fixed Input Answers Weighted Score](Fixed%20Input%20Answers%20Weighted%20Score/README.md) | Values stored in memory | Internal memory | Fixed answer bytes and score penalties |
| [Interrupt Gated Answer Assessment](Interrupt%20Gated%20Answer%20Assessment/README.md) | Keypad | LCD and internal result bytes | Answer key calculated from operand tables |
| [Keypad Answer Assessment](Keypad%20Answer%20Assessment/README.md) | Keypad | LCD and internal result bytes | Answer key calculated from operand tables |
| [LCD Table Driven Scoring](LCD%20Table%20Driven%20Scoring/README.md) | Stored values or prompted choices | LCD and internal result bytes | Question records include answer and score weight |
| [Interrupt Table Driven Scoring](Interrupt%20Table%20Driven%20Scoring/README.md) | Keypad | LCD and internal result bytes | Question records include answer and score weight |
| [Keypad Scoring Board Adaptation](Keypad%20Scoring%20Board%20Adaptation/README.md) | Keypad | LCD and internal result bytes | Question records include answer and score weight |
| [Keypad Table Driven Scoring](Keypad%20Table%20Driven%20Scoring/README.md) | Keypad | LCD and internal result bytes | Question records include answer and score weight |
| [LCD Scoring Port 0 Interface](LCD%20Scoring%20Port%200%20Interface/README.md) | Stored values or prompted choices | LCD and internal result bytes | Question records include answer and score weight |
| [Keypad Scoring Exercise Variant](Keypad%20Scoring%20Exercise%20Variant/README.md) | Keypad | LCD and internal result bytes | Question records include answer and score weight |
