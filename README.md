[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/) 

[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)

[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)

![rgr](https://github.com/user-attachments/assets/c08f0e92-c828-4980-8336-c28b55ae0a9d)

# Real-Time Crypto Price Tracker!

A lightweight tool to fetch and display real-time cryptocurrency prices from the Binance API using WebSocket. Built with a simple and intuitive GUI powered by Dear ImGui.

## Features

- Real-Time Updates: Fetches live cryptocurrency prices directly from Binance via WebSocket.
- Simple GUI: Clean and user-friendly interface using ImGui.
- Customizable: Easily add or remove cryptocurrencies to track by creating new instance of BinanceWebSocket thread.
- Lightweight: Minimalistic design with efficient performance.

## How It Works
The tool connects to Binance's WebSocket API to stream real-time price data for selected cryptocurrencies. The data is displayed in a straightforward GUI, making it easy to monitor price changes.

## Requirements

- C++ compiler (Visual Studio supporting C++11 or later)
- [Dear ImGui](https://github.com/ocornut/imgui) for the GUI
- [Asio](https://think-async.com/Asio/) (standalone)
- [Websocketpp](https://github.com/zaphoyd/websocketpp) for realtime-fetching

## Usage
Clone the repository.

`git clone https://github.com/omarker09/ImGui-Crypto-Websocket.git`

`cd ImGui-Crypto-Websocket`

`open realtime_crypto_websocket.sln`

Build the project using Visual Studio build system.

Run the executable to launch the GUI and start tracking crypto prices.

## End

Feel free to customize this description further to match your project’s specifics!

- [@omarker09](https://github.com/omarker09) 
