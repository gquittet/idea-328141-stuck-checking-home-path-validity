# IDEA-328141 IntelliJ IDEA module stuck on "Checking Home path validity"

## What steps will reproduce the issue?

1. Open the module view 
2. Try to edit one of the modules in the project
3. You can't save the changes.

## What is the expected result?

We can change the module without any problem.

What happens instead?

![Stuck proof](https://youtrack.jetbrains.com/api/files/74-1895410?sign=MTY5MTk3MTIwMDAwMHwxMS02NjI3NTZ8NzQtMTg5NTQxMHw5Sy1hUkVMajJTU0Z2TEpoT2FkanZL%0D%0AOTRsSW5NUUJ5QzVOaExZbmkwUUFjDQo%0D%0A&updated=1691742440338)

It was working fine with the 2023.1.5

Roll back fixed the issue, but I can't use the 2023.2

Maybe related to https://youtrack.jetbrains.com/issue/GTW-3044 and related to https://youtrack.jetbrains.com/issue/PY-62233

---

IntelliJ IDEA 2023.2 (Ultimate Edition)

Build #IU-232.8660.185, built on July 26, 2023

Runtime version: 17.0.7+7-b1000.6 aarch64

VM: OpenJDK 64-Bit Server VM by JetBrains s.r.o.

macOS 13.5

GC: G1 Young Generation, G1 Old Generation

Memory: 4096M

Cores: 8

Metal Rendering is ON

Registry:

ide.experimental.ui=true