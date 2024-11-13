# ag2pc-KDF-TLS1.2
The authenticated garble circuit implementation of key derivation function of TLS 1.2

# Usage
- Install the `emp-toolkit` including `emp-tool`, `emp-ot`, `emp-sh2pc`, `emp-ag2pc`
- `circuits`: place the `.txt` files in `emp-tool/emp-tool/circuits/files/bristol_format`
- `src`: place the `.cpp` and `.h` files in `emp-ag2pc/test`, and add `add_test_case_with_run(KDF_384)`, `add_test_case_with_run(KDF_448)` into `CMakeLists` 