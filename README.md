# Managed File Transfer - SFTP Agent

This agent is paired with this project: https://github.com/mikeacjones/mft-sftp-config-sapi

The role of the agent is to process incoming/outgoing SFTP files configured using the system API above.

Before setting up the agent, you should complete setup for the system api as the agent is dependent.

# Setup

1. Provision an SFTP server using SE Platform
2. Update `SFTP_Config` in `global.xml` with credentials, host, and port.
3. Update `MFT__SFTP_Config_SAPI_Config` with information for connecting to SAPI.
