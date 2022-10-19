## Mips組合語言HelloWorld補上傳 
```asm
    li $v0,4      # $v0=4 命令號4，代印字串
    la $a0,msg    # 載入msg之字串位址
    syscall       # 呼叫系同執行命令號 相當於Masm的 INT 21H
    li $v0,10     # Exit 相當於Masm的 MOV AH,4CH
    syscall       # 呼叫系同執行命令號 相當於Masm的 INT 21H
```
備註：mips的註解為`#`，不知道為啥我上面沒有變色可能是我[CODE]打錯了QQ
