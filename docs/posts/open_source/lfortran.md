# LFortran: A Modern Twist on a Classic Language

I worked on [LFortran](https://github.com/lfortran/lfortran) as the
full time contractor funded by [GSI Technology](https://gsitechnology.com/)
from December 2021 to August 2023. I also received a grant from [Sovereign Tech Fund](https://www.sovereigntechfund.de/) to work on some
challenging parts of the compilers like LLVM codegeneration and
optimization passes.

## Milestones

Throughout my journey, I had the privilege of contributing to several significant milestones:

1. [LFortran Breakthrough: Now Building Legacy and Modern Minpack](https://lfortran.org/blog/2023/05/lfortran-breakthrough-now-building-legacy-and-modern-minpack/)
2. [LFortran Compiles fastGPT
](https://lfortran.org/blog/2023/09/lfortran-compiles-fastgpt/)
3. [LFortran Compiles dftatom](https://lfortran.org/blog/2023/10/lfortran-compiles-dftatom/)
4. [LFortran Compiles 60% of Scipy](https://lfortran.org/blog/2024/01/lfortran-compiles-60-of-scipy/)


## More about LFortran

Fortran, a stalwart in the world of scientific computing, has been around
for over 60 years. Renowned for its speed and efficiency in numerical
computations, it's been the workhorse for countless scientific
breakthroughs. However, Fortran has also gained a reputation for being
complex and lacking the interactive nature of some modern languages.

LFortran is a modern, open-source (BSD licensed) compiler built on top of
LLVM, a powerful compiler infrastructure. It aims to bridge the gap between the
traditional Fortran experience and the interactive workflow of languages
like Python and MATLAB.

### Advantages

This combination allows LFortran to offer several key advantages:

- **LLVM for Efficiency:**  LLVM is known for its ability to generate
highly optimized code for various architectures. LFortran leverages this
strength to ensure your Fortran code runs efficiently on modern hardware.
- **Compiles to Binaries:** While the interactive mode is a significant
perk, LFortran can also compile your code into standalone executables.
This allows you to create programs that can be run on different systems
without needing the LFortran environment.
- **Multiple Backends:** LFortran boasts flexibility with its support for
various backends, including LLVM, C, and C++. This
allows for code generation tailored to specific hardware or deployment
environments.
- **Interactive Environment:** Unlike traditional Fortran compilers that
require separate compilation and execution steps, LFortran allows you to
write and run Fortran code interactively. This is still a working
prototype but can be easily extended to support fully.

### Modular Design

The underlying architecture of LFortran is designed with modularity in mind.  Two core components, the Abstract Syntax Tree (AST) and Abstract Semantic Representation (ASR), are independent modules. This allows developers to leverage these components for building custom tools and functionalities on top of LFortran.
