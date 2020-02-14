@echo off

set tmp=C:\bat\tmp.txt
set folder = C:\bat
cd C:\bat

for /d %%i in (20201223*) do (
	for %%j in (%%i\*.txt) do (
		 rem findstr "apple" %%j > %tmp%
		 copy %%j %folder%
		 rem %%j >> %tmp%
	)
)
