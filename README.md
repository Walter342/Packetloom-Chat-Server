# Packetloom-Chat-Server
Packetloom

A real-time chat server built from scratch in Go — no existing chat or web frameworks. Packetloom implements its own custom protocol over raw TCP sockets to handle message formatting, usernames, and chat rooms, and uses goroutines to support many concurrent client connections at once.

Status

----- Work in progress — currently in early development.

Features
Custom protocol for client-server communication, built directly on raw sockets (not HTTP)
Concurrent handling of multiple clients using goroutines
Chat rooms with usernames and presence tracking
A lightweight command-line client for testing
Why this project

Packetloom is a learning-focused systems project built to understand what happens "under the hood" of real-time networked applications — sockets, custom protocols, and concurrency — without relying on existing frameworks to hide the details.

Tech Stack
Language: Go
Networking: Raw TCP sockets
Concurrency: Goroutines
Roadmap
 Basic TCP server that accepts and echoes a single connection
 Concurrent handling of multiple clients
 Custom message protocol design
 Chat rooms and usernames
 Command-line test client
Getting Started

Instructions for building and running Packetloom will be added here as development progresses.
