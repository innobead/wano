# wasmlet

A development tool and runtime for managing and running (WASI) WASM modules.

## Functions

- Build (WASI) WASM module
- Push WASM module to an OCI registry
- Pull WASM module from an OCI registry
- Run WASM module adaptively for WASI or non-WASI module
- Run WASM module with a specific runtime
- Base on Deno as the runtime by default
- Have commands for managing modules during the development and runtime 

## Commands

- wasmlet build
- wasmlet push
- wasmlet pull
- wasmlet list
- wasmlet run
- wasmlet stop
- waslmlet ps
