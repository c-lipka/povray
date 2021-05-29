---
name: Build error report (Unix: Cross-compiling)
about: Report a problem with compiling POV-Ray for Unix on a different host than the target machine
title: "[BUILD][UNIX] "
labels: compatibility?, OS: Unix
assignees: ''

---

<!-- -----------------------------------------------------------------------------------------------
PLEASE REPLACE any placeholder texts in this report. We know them by heart, and don't need them
repeated in every issue report. Placeholders are marked with square brackets, which we kindly ask
you to remove as well.
Also, PLEASE DELETE any sections that you would leave empty.
------------------------------------------------------------------------------------------------ -->

**Summary**
[Briefly describe your issue here.]

**POV-Ray Version**
  - Incarnation: POV-Ray for Unix
  - Affected source version: [as per Git tag, e.g. v3.8.0-alpha.10023456]
  - Known working source version: [e.g. v3.8.0-alpha.9987654, commit 6789abcd, or N/A]

**Build Environment**
  - Operating system: [e.g. HP-UX 11.31]
  - Hardware architecture: [e.g. pa-risc-2-0, ia64]
  - Compiler: [e.g. clang 3.8]

**Target Environment**
  - Operating system: [e.g. FreeBSD 12.2]
  - Hardware architecture: [e.g. x86, x86-64]

**Build Command Sequence**
~~~
[Please copy the actual command sequence you were using to build POV-Ray here, e.g.
cd unix ; prebuild.sh ; cd ..
./configure --prefix="~/some/where" COMPILED_BY="John Doe <john.doe@fnord.com>"
make check
sudo make install
]
~~~

**Pre-Build Output**
~~~
[If you experience errors in `./configure`, or suspect the root cause to be in `prebuild.sh`,
please copy the _complete_ output of `prebuild.sh` here. Otherwise, please delete this section.]
~~~

**Configure Output**
~~~
[Please copy the complete output of `./configure` here.]
~~~

**Make Output**
~~~
[Please copy any compiler/linker errors and other relevant messages here.
If you experience errors in an earlier build step, please disregard and delete this section.]
~~~

**Additional context** (optional)
[Please add any other context about the problem here, or delete this section.]

**Workaround** (optional)
[If you have managed to work around the issue, please describe that workaround here.
Otherwise please delete this section.]

**Suggested Solution** (optional)
[If you have an idea how to solve the issue for good, please describe it here.
Otherwise please delete this section.]

<!-- -----------------------------------------------------------------------------------------------
NOTE: Please take a moment to PREVIEW your report before submitting it.
------------------------------------------------------------------------------------------------ -->