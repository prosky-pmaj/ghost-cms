ghost-cms
=======================
This is a TestObject for ghost-test-suite basing on Ghost framework with intencionaly introduced bugs

### Install and run:
1. Download and install Nodejs 6.9.5:
	- Windows 64-bit: https://nodejs.org/dist/v6.9.5/node-v6.9.5-x64.msi
	- Windows 32-bit: https://nodejs.org/dist/v6.9.5/node-v6.9.5-x86.msi
	- Mac: https://nodejs.org/dist/v6.9.5/node-v6.9.5.pkg
	- Linux 64-bit: https://nodejs.org/dist/v6.9.5/node-v6.9.5-linux-x64.tar.xz
	- Linux 32-bit: https://nodejs.org/dist/v6.9.5/node-v6.9.5-linux-x86.tar.xz
	- For any other platform, please check: https://nodejs.org/dist/v6.9.5/

2. Check if Nodejs is properly installed:
	- Open Command Prompt (Windows) or Terminal (Mac) or Bash (Linux)
		- Execute this command: node -v (The output should be "6.9.5")
		- Execute this command: npm -v (The output should be "3.10.10")

3. Run the application:
	- Open Command Prompt (Windows) or Terminal (Mac) or Bash (Linux) with administration privileges (IMPORTANT!)
	- Go to the "src" folder (Located on the same folder of this file)
	- Execute this command (*): npm install --development
	- Execute this command: npm start --development
		(*) The first time you execute this command, it will take some time downloading the required packages

4. Open browser and point to:
	- Public website: http://localhost:2368
	- Administration website: http://localhost:2368/ghost

5. Administration website user:
	- Email: admin@prosky.org
	- Password: admin123
