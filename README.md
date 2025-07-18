# AUV LLM Agent

A Python module for integrating Large Language Models (LLMs) into Autonomous Underwater Vehicle (AUV) mission planning and configuration.

## Features

- Natural language mission planning
- Autonomous configuration generation
- Sensor data and user command processing

## Status

**Development:**  
The LLM Agent integration is under active development. Features and API may change frequently.

## Setup

1. **Hugging Face API Token:**  
   Set your Hugging Face token as `HF_TOKEN` in your environment.

2. **Install dependencies:**  
   ```sh
   pip install pydantic requests python-dotenv
   ```

## Usage

- Example usage: see [`agent/main.py`](agent/main.py)
- The agent processes sensor data and user commands, returning a structured configuration for the vehicle.

## File Structure

- [`agent/llm_agent.py`](agent/llm_agent.py): Main agent logic
- [`agent/config_schema.py`](agent/config_schema.py): Configuration schema
- [`agent/default_config.json`](agent/default_config.json): Default configuration
- [`agent/hf_token.py`](agent/hf_token.py): Hugging Face token management
- [`agent/main.py`](agent/main.py): Example usage
- [`agent/test_agent.py`](agent/test_agent.py): Unit tests

## Notes

This module is not production-ready. Expect frequent
