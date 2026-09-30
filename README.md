## TechHub SuperApp Print Agent
The TechHub SuperApp Print Agent is a lightweight Windows service that connects the TechHub SuperApp to a local printer. It monitors the SuperApp’s print queue, securely claims available picklist jobs, downloads their PDFs, and prints them using native Windows printer APIs.
The agent supports real-time job notifications through WebSockets, automatic polling when WebSockets are unavailable, configurable print scaling and resolution, failure reporting, temporary-file cleanup, and automatic recovery from unexpected errors.
Key Features
- Native Windows PDF printing
- Secure token-based API authentication
- Real-time WebSocket job notifications
- Automatic polling fallback
- Configurable printer, resolution, scaling, and retry intervals
- Print completion and failure reporting
- Automatic cleanup of downloaded PDF files
- Continuous recovery after connection or processing errors
