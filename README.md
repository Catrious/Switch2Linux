# Switch2Linux
Run Linux on your Switch 2! <br>
NOTE: This was not tested, and may not work, so report issues in, well, issues. <br>
REQUIREMENTS: <Br>
A Switch 2 <br>
A computer <br>
seabios.bin <Br>
vgabios.bin <br>
alpine-linux.iso <br>
<br>
HOW TO RUN: <br>
0. Make sure your Switch 2 and PC are on the same Wi-Fi. <br>
1. Open cmd or Terminal on your PC. <br>
2. Install Python (if needed). <br>
3. Run ```ipconfig``` (if on Windows) or ```ifconfig``` (if on Mac/Linux) and write down your IPv4 adress. <br>
4. Run ```python -m http.server 8000``` in the same directory as all of the files. <br>
5. Use the Switch 2 DNS trick (to open the browser). <BR>
6. Type ```http://{your-ipv4-address}:8000``` in the address bar. <br>
Now you have Linux on your Switch 2! <br>
<br>
TROUBLESHOOTING: <br>
Black screen when Linux is running: <br>
1. Wait 30-45 seconds (because it may be launching) <br>
2. Make sure you have all 3 files in the same directory as index.html <br>
3. Refresh the site <br>
If nothing worked, please make a issue in the Issues tab, and i will try to fix it. <br>
