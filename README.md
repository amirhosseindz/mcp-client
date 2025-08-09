## Key Components Explained

### 1. Client Initialization
The MCPClient class initializes with session management and API clients
Uses AsyncExitStack for proper resource management
Configures the Anthropic client for Claude interactions
​
### 2. Server Connection
Supports both Python and Node.js servers
Validates server script type
Sets up proper communication channels
Initializes the session and lists available tools
​
### 3. Query Processing
Maintains conversation context
Handles Claude’s responses and tool calls
Manages the message flow between Claude and tools
Combines results into a coherent response
​
### 4. Interactive Interface
Provides a simple command-line interface
Handles user input and displays responses
Includes basic error handling
Allows graceful exit
​
### 5. Resource Management
Proper cleanup of resources
Error handling for connection issues
Graceful shutdown procedures