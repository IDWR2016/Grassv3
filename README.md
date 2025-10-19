# Grassv3


This repository contains the code for `getgrass-bot`, a bot designed to establish WebSocket connections through various HTTP and SOCKS proxies, specifically aimed at farming for Grass Airdrop Season 2.

## Overview

`getgrass-bot` connects to a specified WebSocket server using both HTTP and SOCKS proxies. It leverages the `ws` library for WebSocket communication and integrates the `https-proxy-agent` and `socks-proxy-agent` libraries for enhanced proxy support. This allows for more versatile and resilient connections, accommodating a wider range of proxy types.

## Installation

1. Clone this repository to your local machine:

   ```bash
   https://github.com/IDWR2016/Grassv3.git
   ```

2. Navigate to the project directory:

   ```bash
   cd Grassv3
   ```

3. Install the required dependencies using npm:

   ```bash
   pip install -r requirements.txt
   ```

## Usage + Proxy

1. Buy Premium Proxy for 100% network status grass Visit[https://www.birdproxies.com/@IDWR]

2. Obtain your user ID from the Getgrass website:

   - Visit [https://app.getgrass.io/dashboard](https://app.grass.io/register?referralCode=iplB6wIcmOBdmJE).
   - Open your browser's developer tools (usually by pressing F12 or right-clicking and selecting "Inspect").
   - Go to the "Console" tab.
   - Paste the following command and press Enter:

     ```javascript
     localStorage.getItem('userId');
     ```

   - Copy the value returned, which is your user ID.


3. edit file named `config.json` in the project directory and list your user IDs, each on a new line, like so:

   ```text
  "user_ids": ["your user id"],
   ```

4. To specify proxies, create a file named `proxies.txt` in the project directory and add your desired proxy URLs, following the same new-line format, like this:

   ```text
   http://username:password@hostname:port
   socks5://username:password@hostname:port
   ```

5. To run the `getgrass-bot`, execute the following command in your terminal:

   ```bash
   python bot.py
   ```
## Contribution

If you find this project useful, please consider giving it a star on GitHub! Your support motivates further development and enhancements.

My Telegram Channel : https://t.me/Idwroff
Support Me : 

Solana Address : BioDmvTUnJ6TXWNzn1aWqM8R8Q6HvztQnsFh8DXMJjBr
