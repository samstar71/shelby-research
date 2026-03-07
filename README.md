# shelby-research
Research and exploration of Shelby decentralized hot storage infrastructure
# Shelby Research

This repository documents my exploration of Shelby — a decentralized hot storage protocol designed for high-performance data delivery for AI and real-time applications.

## Topics I'm Exploring

• Shelby architecture  
• Decentralized hot storage  
• DoubleZero fiber network  
• Aptos verification layer  
• AI object storage  

## Why Shelby Matters

Most decentralized storage systems are designed for archival data. Shelby focuses on real-time data delivery, which is critical for AI workloads, gaming, streaming, and other high-throughput applications.

## Key Components

### Shelby Storage Layer
Provides decentralized object storage optimized for high read performance.

### DoubleZero Network
A global fiber network that provides deterministic bandwidth and predictable routing.

### Aptos Coordination Layer
Ensures verifiable receipts, ownership tracking, and data provenance.

## Goal

The goal of this repository is to understand how decentralized infrastructure can support next-generation AI systems and global data delivery.

---

This repo will continue documenting experiments, ideas, and research about Shelby.
## Shelby Architecture

![Shelby Architecture](shelby-architecture.png)
## Shelby Architecture

![Shelby Architecture](shelby-architecture.png)

### Architecture Overview

Shelby connects applications with decentralized storage providers through RPC gateways.

User requests travel through the public internet to Shelby RPC nodes, which coordinate with decentralized storage providers.

The private network layer powered by DoubleZero enables predictable routing, deterministic bandwidth, and low latency.

Aptos acts as the verification layer, anchoring cryptographic receipts that prove what data was served and when.
