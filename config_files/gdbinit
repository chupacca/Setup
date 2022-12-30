#source /home/kali/.gdbinit-gef.py
source /home/kali/Documents/tools/pwndbg/gdbinit.py


set context-clear-screen on
set follow-fork-mode parent

source /home/kali/Documents/tools/splitmind/gdbinit.py

python
import splitmind
(splitmind.Mind()
  .right(of="main", display="stack", size="61%")
  .below(of="stack", display="disasm", size="65%")
  .below(of="main", display="regs", size="28%")
  .show("legend", on="disasm")
).build()
end

#set context-code-lines 30
#set context-source-code-lines 30
set context-sections  "regs args code disasm stack backtrace"
