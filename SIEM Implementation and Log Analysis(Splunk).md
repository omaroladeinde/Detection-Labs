# SIEM Implementation and Log Analysis(Splunk)

## Objective

The Detection Lab project aimed to establish a controlled environment for simulating and detecting cyber attacks. The primary focus was to ingest and analyze logs within a Security Information and Event Management (SIEM) system, generating test telemetry to mimic real-world attack scenarios. This hands-on experience was designed to deepen understanding of network security, attack patterns, and defensive strategies.

### Skills Learned

- Advanced understanding of SIEM concepts and practical application with splunk.
- Proficiency in analyzing and interpreting logs.
- Ability to generate and recognize attack signatures and patterns.
- Enhanced knowledge of network protocols and security vulnerabilities.
- Development of critical thinking and problem-solving skills in cybersecurity.

### Tools Used

- Security Information and Event Management (SIEM) system for log ingestion and analysis.
- Network analysis tools (such as Wireshark) for capturing and examining network traffic.
- Telemetry generation tools to create realistic network traffic and attack scenarios.

## Steps
Certainly! Let's dive deeper into each step with more detail and include relevant images:

### Step-by-Step Guide to Downloading and Configuring Splunk for Log Ingestion

#### Step 1: Download and Install Splunk Enterprise

1. **Navigate to Splunk's Website:**
   Go to [Splunk's official website](https://www.splunk.com/) and locate the download section.

2. **Choose the Version:**
   Select the appropriate version of Splunk Enterprise based on your operating system (Windows, Linux, or macOS).

3. **Download and Install:**
   Follow the installation instructions provided on the Splunk website to download and install Splunk Enterprise on your machine.

   ![Download Splunk](splunk-download.png)

#### Step 2: Launch Splunk Web and Log In

1. **Open Splunk Web:**
   After installation, open a web browser and enter `http://localhost:8000` (replace `localhost` with the IP address of your Splunk server if accessing remotely).

2. **Log in with Default Credentials:**
   Use the default credentials to log in (`admin` / `changeme`). You will be prompted to change the password on first login.

   ![Splunk Login](splunk-login.png)

#### Step 3: Configure Data Inputs

1. **Navigate to Settings:**
   Click on `Settings` in the top menu bar, then select `Data inputs`.

2. **Add Data Inputs:**
   To ingest logs, click on `Add Data` and choose the appropriate data type (Network data, System logs, Application logs, etc.).

   ![Add Data Inputs](add-data-inputs.png)

3. **Configure Input Method:**
   Follow the prompts to configure the input method. For example, to ingest system logs, you might choose to monitor files or directories where the logs are stored. Configure other settings like sourcetype, index, and host as necessary.

   ![Configure Input Method](configure-input-method.png)

#### Step 4: Monitor and Analyze Data

1. **Navigate to Search & Reporting:**
   Click on `Search & Reporting` in the top menu bar to start querying and analyzing the ingested data.

2. **Run Queries:**
   Use Splunk's search processing language (SPL) to run queries and generate reports on the ingested logs. Utilize fields and filters to refine your search results.

   ![Search and Reporting](search-and-reporting.png)

#### Step 5: Create Dashboards and Alerts (Optional)

1. **Navigate to Dashboards:**
   Click on `Dashboards` in the top menu bar to create visualizations and dashboards based on your data.

2. **Set up Alerts:**
   Configure alerts to notify you when specific conditions are met within your data. Define alert criteria, actions (such as email notifications), and scheduling.

   ![Create Dashboards](create-dashboards.png)

#### Step 6: Manage Splunk Configuration (Optional)

1. **Navigate to Settings:**
   Use the `Settings` menu to manage configurations such as user roles, indexes, and data inputs.

2. **Advanced Configuration:**
   Customize Splunk's configuration files (`inputs.conf`, `props.conf`, etc.) for more advanced settings and optimizations. Adjust settings for performance tuning, data retention policies, and more.

   ![Manage Configuration](manage-configuration.png)

#### Step 7: Monitor Splunk Performance (Optional)

1. **Navigate to Monitoring Console:**
   Access the `Monitoring Console` from the `Settings` menu to monitor Splunk's health, performance, and usage statistics.

2. **Optimize Performance:**
   Use monitoring data to optimize your Splunk deployment for better performance and scalability. Monitor resource utilization, index size, and search performance to identify bottlenecks and areas for improvement.

   ![Monitoring Console](monitoring-console.png)

### Conclusion

By following these detailed steps, you can effectively download, install, configure, and utilize Splunk Enterprise for ingesting and analyzing network, application, and system logs. Adjust configurations and settings based on your specific requirements and log sources to maximize the utility and efficiency of Splunk in your organization's IT operations and security monitoring.
