# EST-D-24-12331
Dataset for EST-D-24-12331

Please download ISC Data.zip and ISC Data.z01~z07 before unzip.

columns 1-6: Voltage of cell 1~6 (V)
columns 7-10: Environment temperature 1~4 (degC)
column 11: pack current （A）
column 12: balancing current for the target battery (A)
column 13: balancing current for the other batteries (so zero or close to zero for passive balancing, A)
column 14: target battery, -1 means no battery is being balanced.
column 15: internal use. HW balancing will stop when the value is 9 or 0
column 16: internal counter, add value by 1 every 100 ms
