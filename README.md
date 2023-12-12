# TwilightPortal API Gateway

Welcome to the TwilightPortal API Gateway of our E-Commerce System. This component serves as a centralized entry point for the frontend, routing calls to various microservices, and validating user tokens.

## Table of Contents

- [Overview](#overview)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)

## Overview

The TwilightPortal API Gateway is a component that acts as a central entry point for our e-commerce system. It routes incoming calls from the frontend to the appropriate microservices and handles token validation for user authentication.

## Prerequisites

Ensure you have the following installed:

- Node.js
- NPM (Node Package Manager)
- Kafka (for event-driven communication)

## Installation

1. Clone the repository.
2. Navigate to the twilight-portal-api directory.
   ```bash
   cd twilight-portal-api
   ```
3. Install dependencies.
   ```bash
   npm install
   ```

## Usage

1. Set up environment variables for configuration.
   - Check the `.env.example` file for guidance.
   - Create a `.env` file and add the necessary configuration.

2. Start the TwilightPortal API Gateway.
   ```bash
   npm start
   ```

3. Ensure the Kafka server is running to enable event-driven communication.
