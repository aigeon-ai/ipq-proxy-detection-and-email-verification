markdown
# IPQ Proxy Detection and Email Verification MCP Server

## Overview

The 'ipq-proxy-detection-and-email-verification' MCP server is designed to help you identify fraudulent activity and verify email addresses effectively. By leveraging advanced detection methods, this server can identify low-quality IP connections such as proxies, VPNs, and Tor connections, which are often used for malicious purposes. Additionally, the server provides tools to verify the legitimacy of email addresses, helping to eliminate disposable or fake emails commonly used by fraudsters.

## Features

- **Proxy Detection**: Analyze IP addresses in real-time to determine if they are associated with proxies, VPNs, or Tor connections. This feature helps reduce fraud and potential chargebacks by identifying high-risk IP addresses. It's particularly beneficial for affiliate networks, advertisers, merchants, and forums aiming to avoid fraudulent traffic, chargebacks, or spam.

- **Email Verification**: Verify if an email address exists with its mail service provider and detect disposable or fake email addresses. This service is essential for verifying user accounts, detecting fraudulent signups, and cleansing email marketing lists to ensure communication with genuine users.

## Tools

### IPQS Email Verification
- **Purpose**: Verify the existence and legitimacy of an email address with its mail service provider.
- **Use Cases**: Great for verifying user accounts, detecting fraudulent signups, and cleansing email marketing lists.
- **Key Parameters**:
  - `format`: Specify the format of the returned data, available in "json" or "xml".
  - `apikey`: Your API Key, which can be obtained by creating a free account.
  - `email`: The email address you wish to verify.

### IPQS Proxy Detection
- **Purpose**: Analyze an IP address in real-time to detect if it's a proxy, VPN, or Tor connection.
- **Use Cases**: Ideal for reducing fraud, avoiding chargebacks, and blocking unwanted traffic.
- **Key Parameters**:
  - `user_agent`: Optionally pass the user agent variable to flag bad user agents or browsers.
  - `strictness`: Adjust the strictness of the check from 0 (lowest) to 5 (strictest). Default is 0.

## Benefits

- **Fraud Prevention**: By identifying and blocking high-risk connections and fraudulent emails, you can significantly reduce the likelihood of fraud-related issues.
- **Improved Accuracy**: The use of honeypots, real-time blacklists, and forensic analysis ensures high accuracy in detecting proxies and verifying emails.
- **Resource Efficiency**: Utilize up to 5,000 free queries per month, enabling you to effectively manage resources while ensuring secure and accurate verification processes.

Explore the capabilities of the 'ipq-proxy-detection-and-email-verification' MCP server to enhance your security measures and maintain the integrity of your user interactions. Experiment with different settings and leverage these tools to protect your services from fraudulent activities.