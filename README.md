# python-network-connection-monitor
Python network connection monitoring service with real-time event tracking, structured logging, configuration, and resilient error handling
# Python Network Connection Monitor

A lightweight Python utility for monitoring TCP network connections in real time.

The project detects newly opened and closed TCP connections and records connection activity using structured logging. It is designed as a simple foundation for network-monitoring, automation, and long-running Python service workflows.

## Features

- Real-time TCP connection monitoring
- Detects newly opened connections
- Detects closed connections
- Displays local and remote IP addresses and ports
- Tracks connection status
- Structured console logging
- Persistent log-file output
- Graceful shutdown with `Ctrl+C`
- Simple and maintainable Python architecture

## Technologies

- Python 3
- psutil
- Python logging
- Dataclasses
- TCP/network monitoring

## Installation

Clone the repository:

```bash
git clone https://github.com/duaaaljumaily-max/python-network-connection-monitor.git
cd python-network-connection-monitor
