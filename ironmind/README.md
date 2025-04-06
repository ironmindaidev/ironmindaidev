# IronMind AI Agent

IronMind AI Agent is a sophisticated node monitoring and traffic scheduling system that acts as an intelligent "brain" for managing network nodes. It provides real-time monitoring, intelligent traffic distribution, and node performance scoring.

## Features

- Real-time node status monitoring (uptime, bandwidth, latency)
- Intelligent traffic distribution
- Node performance scoring and $IRON token rewards
- Automatic node isolation and recovery
- Historical data tracking
- RESTful API for integration

## Architecture

The system is composed of several core modules:

- `monitor.js`: Node health monitoring
- `scheduler.js`: Traffic distribution
- `scoring.js`: Node performance scoring
- `isolation.js`: Node isolation management
- `database.js`: Data persistence
- `config.js`: System configuration

## Installation

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Configure the system in `ai-agent/config.js`
4. Start the agent:
   ```bash
   npm start
   ```

## API Endpoints

- `GET /health`: System health check
- `GET /nodes/status`: Get all nodes status
- `POST /nodes/assign`: Assign best node to user
- `GET /nodes/scores`: Get node performance scores
- `GET /nodes/isolated`: Get isolated nodes

## Configuration

Edit `ai-agent/config.js` to customize:

- Monitoring intervals
- Node isolation thresholds
- Scoring weights
- Database settings
- API configuration

## Development

The system is designed to be modular and extensible. Key areas for extension:

1. AI Learning Module (Phase 2)
2. Database backend (Redis/MongoDB)
3. Custom scoring algorithms
4. Additional monitoring metrics

## License

MIT License 