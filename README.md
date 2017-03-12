# Welcome to Project Mayhem

This organization is all about open and transparent cybersecurity research.

All projects are provided for educational purposes only.   
We **do not** condone the use of our code for harmful purposes.

This document is subject to change and will be updated and improved over time.

## Scope

The following applications fall under the scope of Project Mayhem:

- General malware (Trojans, Worms, Botnets, that kinda stuff)
- Proof-of-concept exploits (Heartbleed, Slow Loris, etc)
- Command-and-control servers and libraries
- Crypters and packers
- Obfuscators and de-obfuscators

## Rules

### Starting a new project

- Use an [OSI-approved license][osi-approved], preferably [MIT license][osi-license-mit] *or* place your work into the [public domain][unlicense].
- Use good judgement when naming your project (avoid overly offensive or inappropriate names).

### Contributing to an existing project

- By contributing you consent to submiting your code under the same license used by the project you're contributing to.

## Conventions

### Programming languages

Generally, **malware** should be written in a **natively compiled mainstream language** (such as C, C++).

The reasons for that are threefold:

- Native languages allow for better optimization and can be hardened against reverse-enginnering more easily.
- Popular languages have a big user base and therefore a higher number of potential contributors.
- Using a popular language lowers the entry-barrier and learning-curve for new contributors.

Languages like C, C++ and Go are preferred, since they are well-known and produce very reliable code.

On the contrary, **exploits and utilities** should be written in a **mainstream scripting language** (such as Ruby, Python, JS).   
They should be easy to use, run on a wide variety of platforms, and ideally without much or any configuration.

Languages like Ruby, Python and Node/JavaScript are preferred, since they are well-known, easy to work with, and have big package ecosystems that allow for rapid development and lower code complexity.

The aforementioned programming languages are _not a strict requirement_.   
Other programming languages are allowed, but please use good judgement.


[osi-approved]: https://opensource.org/licenses
[osi-license-mit]: https://opensource.org/licenses/MIT
[unlicense]: https://unlicense.org/
