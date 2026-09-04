# Wireshark Network Traffic Analysis

## Project Overview

This project demonstrates network traffic analysis and TLS handshake investigation using Wireshark on Windows.

The analysis was performed on captured network traffic to examine TLS communication, identify handshake stages, and understand how secure connections are established.

## Tools Used

- Wireshark
- Windows

## Analysis Performed

The following TLS handshake packets were analyzed:

- Client Hello
- Server Hello
- Certificate
- Server Key Exchange
- Server Hello Done
- Client Key Exchange
- Change Cipher Spec
- Encrypted Handshake Message

## Key Findings

The analysis showed the different stages of a TLS 1.2 handshake.

The Client Hello packet contained supported cipher suites and TLS extensions.

The Server Hello packet showed the server's response and selected connection parameters.

The Certificate packet contained the server certificate chain.

The Server Key Exchange and Client Key Exchange packets showed the use of Elliptic Curve Diffie-Hellman key exchange.

After the Change Cipher Spec message, the handshake messages were encrypted.

## Learning Objectives

- Understand network packet analysis.
- Analyze TLS handshake traffic.
- Identify different TLS handshake stages.
- Examine cipher suites and TLS extensions.
- Practice basic network security analysis using Wireshark.

## Disclaimer

This project was performed for educational purposes using network traffic captured from my own device.
