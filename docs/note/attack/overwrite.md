# 修改内存

?> 威胁安全的，无非就三种：一读一写一执行

!> 不该看到的被看到了，不安全

!> 不能修改的被修改了，不安全

!> 不该去的地方他去了，不安全

攻击的步骤就是先读再写后执行
（信息泄漏，信息篡改，控制流非预期转移）

可以说攻击的目的主要是修改内存，搞破坏嘛

## 劫持控制流


## 任意写(1 byte)

> Arbitrary Memory Overwrite (Write-What-Where) 

数组上溢

?> write backwards with negative array indexes.

wpictf-nanowrite

## 任意写(2 bytes)

## 任意写(3 bytes)

hfctf-MarksMan