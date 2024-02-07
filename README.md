# Using-Steganography-For-Hiding-TCP-Handshake

Introduction

This repository contains the implementation of an innovative approach to network security: using steganography to hide the TCP handshake process. This project aims to enhance security in network communications by concealing the initial stages of a TCP connection.

About the Project

Steganography is the art of hiding information within other non-secret text or data. In this project, we apply steganography to the TCP handshake process, making the initiation of TCP connections less detectable and more secure against network surveillance and analysis.

Key Features

Innovative Use of Steganography: Integrates steganography techniques with the TCP handshake process.
Enhanced Security: Aims to provide an additional layer of security in network communication.
Customizable: Allows for modification and customization to suit specific network environments.

Getting Started

Prerequisites

To run the project, only one package is required: scapy. For windows command to install is pip install scapy; for macintosh the command is pip3 install scapy.

Running the project.

1) Clone it with this command: git clone https://github.com/Vishal-Prakash-1/Using-Steganography-For-Hiding-TCP-Handshake.git
2) Navigate to the project directory: cd Using-Steganography-For-Hiding-TCP-Handshake
3) Run the files in the following order: server.py -> eavesdropper.py -> client.py -> client-manipulated.py
4) Once client and client-manipulated is running, in client or client-manipulated terminal, transfer the files using following command: get <file_name> or upload <file_name>. Observe the output in eavesdropper terminal.
