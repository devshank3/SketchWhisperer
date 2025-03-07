# Technical Architecture

## Frontend (Blazor WebAssembly)
- Responsive SPA interface
- Canvas-based drawing component with JavaScript interop
- Real-time game state management
- SignalR client connection
- User authentication and profile management

## Backend (ASP.NET Core)
- SignalR hub for real-time communication
- User authentication and session management
- Game logic and state management
- Azure OpenAI service integration
- Scoring and leaderboard systems

## Real-Time Communication (SignalR)
- Drawing data transmission
- Game state synchronization
- Player actions and events
- Chat message broadcasting
- AI hint distribution

## AI Integration (Azure OpenAI)
- Drawing analysis using Computer Vision API
- Progressive hint generation using GPT models
- Context-aware clue system
- Drawing assistance suggestions
- End-of-round commentary generation

## Data Storage
- User profiles and authentication
- Game history and statistics
- Word lists and categories
- Optional replay functionality
