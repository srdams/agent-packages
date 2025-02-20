# SRDAMS Server Monitoring Agent

## Installation Instructions

### Step 1: Download the Agent

To download the latest version of the SRDAMS Server Monitoring Agent, run the following command:

```bash
wget https://github.com/srdams/agent-packages/releases/download/v1.0.0/srdams-server-monitoring-agent_1.0.0.deb
```

### Step 2: Install the Agent

Once the download is complete, install the agent using the following command:

```bash
sudo dpkg -i srdams-server-monitoring-agent_1.0.0.deb
```

### Step 3: Setup the Agent

After installation, set up the agent by executing:

```bash
sudo srdams-server-monitoring-agent
```

### Service Management

The agent is now running as a service. You can manage the service using the following commands:

- **Enable the Service (Optional):**

  ```bash
  sudo systemctl enable srdams-server-monitoring-agent.service
  ```

- **Check Status:**

  ```bash
  sudo systemctl status srdams-server-monitoring-agent.service
  ```

- **Start the Service:**

  ```bash
  sudo systemctl start srdams-server-monitoring-agent.service
  ```

- **Stop the Service:**

  ```bash
  sudo systemctl stop srdams-server-monitoring-agent.service
  ```

- **Restart the Service:**

  ```bash
  sudo systemctl restart srdams-server-monitoring-agent.service
  ```

- **Disable the Service from Starting on Boot:**

  ```bash
  sudo systemctl disable srdams-server-monitoring-agent.service
  ```

- **Uninstall the agent:**

  ```bash
  sudo apt-get purge srdams-server-monitoring-agent
  ```

- **Remove the agent:**

  ```bash
  rm srdams-server-monitoring-agent_1.0.0.deb
  ```

## Additional Information

For any issues or troubleshooting, please refer to the [documentation](#) or contact support.

---

_Note: Ensure that you have the necessary permissions and dependencies installed for successful installation and execution of the agent._
