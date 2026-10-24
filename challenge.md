# Challenge: Install It Yourself

1. Program: htop
   - Command: sudo apt install -y htop
   - What it shows: Real-time CPU, memory usage, and running system processes.

2. Apache2 Version:
   - Command: apt show apache2
   - Version offered: Check the output from running that command (e.g., 2.4.58 or similar).

3. Installed Packages Count:
   - Command: apt list --installed | wc -l
   - Count: State the total number returned by your terminal.

4. Alpine Docker Container:
   - Command: sudo docker run --rm alpine echo "Hello from Alpine"

5. Paths of Docker Key and Sources File:
   - Key file path: /etc/apt/keyrings/docker.asc
   - Sources file path: /etc/apt/sources.list.d/docker.sources

6. Remove htop and Prove Gone:
   - Commands:
     sudo apt remove -y htop
     hash -r
     htop
   - Proof: Running htop shows "Command 'htop' not found".
