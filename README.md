# 114-2 可程式邏輯設計實習

以下整理各個 repo 的專案重點，並提供 `README.md` 與 Verilog 程式連結，方便快速查閱。

| Repo | 專案說明 | README.md | Verilog 程式 |
|---|---|---|---|
| `full_sub_1bit` | 1 位元減法器設計，包含半減器與全減器，提供邏輯方程、真值表與模組化架構。 | [README.md](https://github.com/HHVS-IT-CPLD/full_sub_1bit/blob/main/README.md) | [full_sub_1bit.v](https://github.com/HHVS-IT-CPLD/full_sub_1bit/blob/main/full_sub_1bit.v) / [half_sub_1bit.v](https://github.com/HHVS-IT-CPLD/full_sub_1bit/blob/main/half_sub_1bit.v) |
| `full_add` | 1 位元全加器 Verilog 實作，說明輸入輸出、真值表、邏輯方程與多位元串接應用。 | [README.md](https://github.com/HHVS-IT-CPLD/full_add/blob/main/README.md) | [full_add.v](https://github.com/HHVS-IT-CPLD/full_add/blob/main/full_add.v) |
| `full_sub_2bit` | 2 位元減法器，使用二補數法（`A + (~B + 1)`）實現減法並輸出借位。 | [README.md](https://github.com/HHVS-IT-CPLD/full_sub_2bit/blob/main/README.md) | [full_sub_2bit.v](https://github.com/HHVS-IT-CPLD/full_sub_2bit/blob/main/full_sub_2bit.v) |
| `decoder_3_to_8` | 3-to-8 解碼器（one-hot 輸出）Verilog 專案，使用組合邏輯與 `case` 進行解碼。 | [README.md](https://github.com/HHVS-IT-CPLD/decoder_3_to_8/blob/main/README.md) | [decoder_3_to_8.v](https://github.com/HHVS-IT-CPLD/decoder_3_to_8/blob/main/decoder_3_to_8.v) |
| `encoder_8_to_3` | 8-to-3 編碼器專案，內容包含 `always @(*)` 組合邏輯寫法與 one-hot 編碼範例。 | [README.md](https://github.com/HHVS-IT-CPLD/encoder_8_to_3/blob/main/README.md) | [encoder_8_to_3.v](https://github.com/HHVS-IT-CPLD/encoder_8_to_3/blob/main/encoder_8_to_3.v) |
| `half_add` | 半加器 Verilog 設計，實作 `Sum = A ^ B` 與 `Carry = A & B` 的基本算術電路。 | [README.md](https://github.com/HHVS-IT-CPLD/half_add/blob/main/README.md) | [half_add.v](https://github.com/HHVS-IT-CPLD/half_add/blob/main/half_add.v) |
| `full_add_4bit` | 4 位元全加器設計，採行波進位結構，說明整體架構、訊號與實作方式。 | [README.md](https://github.com/HHVS-IT-CPLD/full_add_4bit/blob/main/README.md) | [full_add_4bit.v](https://github.com/HHVS-IT-CPLD/full_add_4bit/blob/main/full_add_4bit.v) / [full_adder_1bit.v](https://github.com/HHVS-IT-CPLD/full_add_4bit/blob/main/full_adder_1bit.v) |
| `BCD_add` | 單位數 BCD 加法器，先做二進位加法再依條件修正（+6），輸出 BCD 個位與十位進位。 | [README.md](https://github.com/HHVS-IT-CPLD/BCD_add/blob/main/README.md) | [BCD_add.v](https://github.com/HHVS-IT-CPLD/BCD_add/blob/main/BCD_add.v) |
