# cloud-task-2.
# CLOUD COMPUTING 
**COMPANY**: CODTECH IT SOLUTIONS
**NAME**: PRINCE KUMAR 
**INTERN ID**: CT08DG546
**DOMAIN**:: Cloud Computing
**DURATION**: 8 WEEKS
**MENTOR**: NEELA SANTOSH

# Task 2 - Cloud Monitoring with AWS CloudWatch

## Steps Completed:
1. CloudWatch dashboard created - Name: `codtech-task2-dashboard`
2. Metrics added and visualized.
3. Alarm created for CPU Utilization.
4. Alerts tested (optional).

## Screenshots:
- Dashboard
- Alarm configuration
- Alarm triggered (if tested)

## Why CloudWatch?
- Centralized monitoring service.
- Helps detect issues in real-time.
- Can trigger actions automatically.

I learned how to monitor cloud-based applications using AWS CloudWatch, which is a core monitoring and observability service. First, I logged into the AWS Console and opened CloudWatch. I created a custom dashboard to visualize important metrics. For this, I selected a typical example metric: EC2 CPU Utilization, which shows how much processing power an EC2 instance is using.

To do this, I explored the available metrics under the EC2 namespace and added the CPU Utilization metric to my dashboard as a line chart. I adjusted the time range and confirmed that the dashboard updates automatically. Next, I created an Alarm on the same metric. For example, if the CPU Utilization goes above 70% for a certain time period, the alarm will trigger. I configured the alarm to send a notification using Amazon SNS (Simple Notification Service) or by email, so I would be alerted if the threshold was crossed.

I also tested the alarm by generating some load on the instance to check that the alarm status changes correctly. This task helped me understand the concept of proactive monitoring — rather than waiting for something to fail, you get notified early so you can take corrective action.

Finally, I saved screenshots of my dashboard, alarm configuration, and testing results, and documented everything in a README.md on GitHub. Now, if someone asks me in an interview about CloudWatch, I can explain dashboards, alarms, how to create them, and why monitoring and alerting are critical for production systems.


