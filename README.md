# Anomaly Detection in Server Machine Dataset

## Group Members
- Saad Khalid
- Jithin Thomas

## Dataset Link
The dataset used for this project can be accessed at the following link: [SMD Dataset on GitHub](https://github.com/NetManAIOps/OmniAnomaly).

## Use Case
This project focuses on detecting anomalies in server machine performance metrics to enhance operational efficiency in large-scale computing environments. By analyzing server metrics, we aim to identify unusual patterns indicative of potential issues such as:

- **Server Overloads**: Sudden spikes in CPU or memory usage that could lead to system crashes.
- **Malfunctions**: Irregular behavior that may suggest hardware or software failures.
- **Security Breaches**: Unusual network traffic patterns that could indicate unauthorized access or cyberattacks.

Effective anomaly detection is crucial for preemptively addressing these issues, ensuring continuous service availability, and maintaining user trust.

## Dataset Description
The **Server Machine Dataset (SMD)** consists of multivariate time series data collected from a large internet company's server machines. The dataset captures various performance metrics, including:

- **CPU Usage**: The percentage of CPU resources utilized.
- **Memory Usage**: The amount of RAM consumed by applications.
- **Network Traffic**: The volume of data transmitted and received over the network.
- **Disk IO**: Input/Output operations per second on disk drives.
- **Process Count**: The number of active processes running on the server.

### Anomalies
In this dataset, anomalies are defined as deviations from the normal operational patterns of the server machines. Anomalies can manifest in various forms, such as:

- **Spikes**: Sudden increases in resource usage.
- **Dips**: Unexplained drops in performance or resource availability.
- **Trends**: Gradual changes that signal potential future issues.

These anomalies can help in pinpointing the underlying causes of performance degradation, which is essential for effective system monitoring and maintenance.

## Dataset Statistics
- **Total Samples**: Approximately 5,000,000 entries.
- **Percentage of Anomalies**: Roughly 1.5% of the data points are labeled as anomalies, indicating that they represent rare but critical events.
- **Features**: The dataset consists of 12 different sensor features collected at regular intervals, providing a comprehensive view of server health.
- **Time Interval**: Data is collected every minute, allowing for fine-grained analysis of trends and anomalies over time.

## Conclusion
This project aims to leverage unsupervised learning techniques to detect these anomalies and analyze model errors. By examining why certain data points are classified incorrectly, we can improve detection accuracy and refine our anomaly detection strategies.

For further inquiries or contributions, feel free to contact us!
