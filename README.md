# I-Phish-You.sh

This script is a phishing tool known as "I Phish You 😋🤪" It is designed to create phishing pages for various online services, such as Instagram, Facebook, Snapchat, Twitter, and more. The script provides a menu for selecting the service you want to create a phishing page for, sets up a local web server, and uses tools like Ngrok or Serveo to expose the phishing page to the internet. When a victim interacts with the phishing page, their IP address and login credentials are captured and saved.

To run this tool, you will need the following:

1. Bash Shell: The script is written in Bash and requires a Bash-compatible shell.
2. PHP: The script uses PHP for hosting the phishing pages locally.
3. Curl: Curl is used for various HTTP operations within the script.
4. Ngrok (or Serveo): Ngrok is used for tunneling the local server to the internet. Serveo is also an option for tunneling.

Once you have these dependencies installed, you can run the script. It will prompt you to choose a phishing target, set up a local web server, and provide you with a link to the phishing page. Victims who interact with the phishing page will have their credentials captured and displayed in the script's output.

Please note that using this script for malicious purposes, such as phishing for sensitive information, is illegal and unethical. This script is intended for educational purposes and should only be used on systems and accounts that you own or have explicit permission to test.


 Install Dependencies: required to run the I Phish You 😋🤪 on Termux:

1. **Bash Shell:**
   - Termux already provides a Bash-compatible shell by default. There's no need to install it separately.

2. **PHP (Hypertext Preprocessor):**
   - To install PHP, open your Termux terminal and run the following command:
     ```
     pkg install php
     ```



clone the repository 

# git clone https://github.com/AiJuicy/I-Phish-You.sh.git


Change Directory:

    Navigate to the project's directory using the cd command:

# cd I-Phish-You.sh


Make the Shell Script Executable:

The project likely contains a shell script or other executable files. To make sure you can run them, you might need to make them executable. You can use the chmod command for this purpose. For example:


# chmod +x I-Phish-You.sh

Run the tool:

# ./I-Phish-You.sh
