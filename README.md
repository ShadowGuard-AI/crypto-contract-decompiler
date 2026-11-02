![Banner](banner.png)

# crypto-contract-decompiler
Reads a contract bytecode or source text file and writes a short report
listing which of four cryptographic operation names (keccak256, sha256,
ripemd160, modexp) appear as text in it. It does not disassemble or
decompile anything, and it uses no external decompiler; the report
itself labels this a placeholder analysis. A missing input file exits 1.

## Install
`git clone https://github.com/ShadowGuard-AI/crypto-contract-decompiler`

## Usage
`python3 main.py BYTECODE_FILE`

## Parameters
- `BYTECODE_FILE`: Path to the bytecode file of the smart contract.
- `-h`: Show help message and exit
- `--output_file`, `-o`: Path to save the decompiled/analyzed output. Default: `output.txt`.
- `--debug`: Enable debug logging.

## License
Licensed under the terms in LICENSE.
