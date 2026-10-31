# Spårbarhetsmatrix (Traceability Matrix)

| Krav | Funktion | Testfall | Indata | Förväntat | Faktiskt | Status |
|---|---|---|---|---|---|---|
| REQ-01 | classify_temperature() | TC-01 | 20 | `NORMAL` | `NORMAL` | Godkänd |
| REQ-01 | classify_temperature() | TC-02 | 30 | `NORMAL` | `NORMAL` | Godkänd |
| REQ-01 | classify_temperature() | TC-03 | 50 | `NORMAL` | `NORMAL` | Godkänd |
| REQ-01 | classify_temperature() | TC-04 | 85 | `VARNING`| `VARNING`| Godkänd |
| REQ-02 | is_valid_temperature() | TC-05 | 90 | Felmeddelande | Felmeddelande | Godkänd |
| REQ-03 | read_temperature()     | TC-06 | abc| Ogiltig inmatning | Ogiltig inmatning | Godkänd |