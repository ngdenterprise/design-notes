# NEO Developer Experience Design Notes

This repository contains Design Notes describing developer tools for the
[NEO project](https://github.com/neo-project).

Design Notes is a process for making and disseminating architecturally
important design decisions. [NGD Seattle](https://github.com/ngdseattle)
is using this process to drive decisions across several projects related
to the NEO developer experience, including 
[NEO Express](https://github.com/neo-project/neo-express) and the
[NEO Smart Contract Debugger for Visual Studio Code](https://github.com/neo-project/neo-debugger).

The Design Note process was pioneered by
[Galen Hunt](https://www.microsoft.com/en-us/research/people/galenh/)
on several projects at Microsoft and was released publicly as part of
[Microsoft's xlang project](http://github.com/Microsoft/xlang).

The Design Note process is described in
[DN00](DN00%20-%20The%20Design%20Note%20Process​.md). This document is
project independent by design. The remaining documents in this repository
are specific to the NEO developer experience and are prefixed with "NDX".

This repository contains the following foundational design notes:

* [NDX-DN01](NDX-DN01%20-%20NEO%20Developer%20Experience.md) describes
  the goals and guiding principles of a world-class experience for developers
  targeting the NEO platform.
* [NDX-DN02](NDX-DN02%20-%20NEO-FX%20Unified%20Programming%20Model.md) describes
  NEO's unified programming model.
* [NDX-DN03](NDX-DN03%20-%20NEO%20Express%20Development%20Blockchain.md) describes
  NEO Express, a NEO blockchain client application, optimized for development
  scenarios.
* [NDX-DN04](NDX-DN04%20-%20NEO%20Smart%20Contract%20Debugging.md) describes the
  NEO Smart Contract Debugger for Visual Studio Code.
* [NDX-DN05](NDX-DN05%20-%20NEO%20Toolkit%20for%20.NET.md) describes the libraries
  and tools used by .NET developers to target the NEO platform.

This repository also contains the following design notes that describe
enhancements to the NEO developer experience foundation.

* [NDX-DN10](NDX-DN10%20-%20NEO%20Express%20Server%20Mode.md) describes an
  improvement to enable NEO Express to be integrated into tools and IDEs
  such as VSCode
* [NDX-DN11](NDX-DN11%20-%20NEO%20Debug%20Info%20Specification.md) describes
  the format of debug information that will be generated by NEO smart contract
  compilers and will be consumed by the NEO Smart Contract debugger.
* [NDX-DN12](NDX-DN12%20-%20Neo%20Express%20Invoke%20Files.md) describes the 
  format of neo-express contract invocation files.

Additional Design Notes will be added in the future.
