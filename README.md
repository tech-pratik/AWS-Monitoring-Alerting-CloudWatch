# AWS-Monitoring-Alerting-CloudWatch


#  Project Title: AWS Monitoring and Alerting with CloudWatch, SNS, and IAM


# PROJECT DESCRIPTION


This project demonstrates a complete cloud monitoring and incident response system using AWS-native services. It focuses on setting up real-time monitoring with CloudWatch, sending automated alerts via SNS (Simple Notification Service), and enforcing secure access controls with IAM roles and policies. The solution is designed to track system metrics, detect anomalies, and notify relevant stakeholders for rapid resolution, aligning with best practices for cloud support operations.

# TECHNOLOGIES AND SERVICES USED


Technology / Service	Purpose / Use Case
Amazon EC2	Hosted a sample web application to monitor CPU and memory usage
Amazon CloudWatch	Collected metrics, set up alarms, and created dashboards
Amazon SNS	Configured alert notifications via email
AWS IAM	Created roles and policies for secure monitoring and alerting access
CloudWatch Logs Insights	Analyzed logs and extracted operational insights
CloudWatch Dashboards	Visualized resource health and performance

# PROJECT OUTCOME AND KEY RESULTS 


Implemented metric-based monitoring for EC2 instances (e.g., CPUUtilization, Disk Read/Write).

Set CloudWatch alarms to detect threshold breaches (e.g., CPU > 70%) and trigger notifications.

Configured an SNS topic with verified email subscribers to receive real-time alerts.

Designed a centralized CloudWatch dashboard for visibility into application health and trends.

Enforced least-privilege IAM policies for secure, role-based access to monitoring tools.

Demonstrated incident response readiness with alerting workflows and operational insights.

Simulated failures and validated that alerts were received within seconds, ensuring quick actionability.


.

