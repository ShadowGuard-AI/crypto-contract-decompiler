![Banner](banner.png)

# crypto-contract-decompiler
Reads a contract bytecode or source text file and writes a short report
listing which of four cryptographic operation names (keccak256, sha256,
ripemd160, modexp) appear as text in it. It does not disassemble or
decompile anything, and it uses no external decompiler; the report
itself labels this a placeholder analysis. A missing input file exits 1.

## Install
`git clone https://github.com/ShadowStrikeHQ/crypto-contract-decompiler`

## Usage
`./crypto-contract-decompiler [params]`

## Parameters
- `-h`: Show help message and exit
- `--output_file`: Path to save the decompiled/analyzed output.
- `--debug`: Enable debug logging.

## License
Copyright (c) ShadowStrikeHQ
