<img width="2752" height="1536" alt="image" src="https://github.com/user-attachments/assets/ab39d4ae-6d3e-4981-b15c-3df062f2578d" />

# Ring-Minus-One-For-Redteamer

The materials for demo

## Minivisor

A minimalisic hypervisor for Windows on Intel processors.

## Directory structure

- [hvcore/](hvcore/) - The OS agnostic parts of the hypervisor, ie, the core. This code, in particular
  [hvcore/src/host.rs](hvcore/src/host.rs) is where you should look into.
- [minivisor/](minivisor/) - The Windows specific parts of the hypervisor. The module entry point is
  in [minivisor/src/lib.rs](minivisor/src/lib.rs).
