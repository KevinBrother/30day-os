# day_01

1. 先双击运行！cons_nt.bat(其实就是打开cmd窗口)
2. 输入 run 然后回车
-  `copy helloos.img ..\z_tools\qemu\fdimage0.bin
..\z_tools\make.exe -C ../z_tools/qemu`
通过命令就可以看出来 把镜像文件拷贝到qemu中，并重命名，然后再执行make.exe
3. 制作.img 过于麻烦，通过编写nas类似汇编的语法，然后再通过asm编辑成img
  所以运行asm就行
    `
    ..\z_tools\nask.exe helloos.nas helloos.img
    `
