# mortezaghasemkhani
@echo off
setlocal

:loop
echo. > empty.txt
git add empty.txt
git commit -m "Auto commit"
git push
timeout /t 1 /nobreak
goto loop
