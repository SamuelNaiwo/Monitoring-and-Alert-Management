# Monitor & Alert Management

## Why do we need Monitoring?

- Improve hardware usage.

- Prevent incidents and help detect them earlier.
- The image of the company improves.
- Spend less time monitoring the system. (manual effort)

## 4 Golden Rules of Monitoring?

### What to Monitor
- Latency

- Traffic 
- Errors
- Saturation

### How To Monitor
- Monitor everything that matters.

- Monitor proactively.
- Monitor continuously.
- Monitor intelligently.

## What is Alert Management?

- Provides the ability to be notified and aware of current or potential upcoming issues with how their services and systems are functioning. This is composed of many different APIs and microservices.

## What is Amazon SNS (Simple Notification Service)

- A service that provides a message delivery. This could be in the form of email, mobile push notifications, and mobile text messages.

## What is SQS (Simple Queue Service)

- Lets you send, store, and receive messages between software components at any volume, without losing messages or requiring other services to be available.

## What is Amazon CloudWatch?

- Monitors your Amazon Web Services (AWS) resources and the applications you run on AWS in real time. You can use CloudWatch to collect and track metrics.

- You can create alarms that watch metrics and send notifications or automatically make changes to the resources you are monitoring when a threshold is breached.

# Create Alarm with SNS

## Create SNS

1. Search SNS in the search bar and click.

2. Click topics on the sidebar.

3. Click create topic in the orange box.

4. Select the standard box for type.

5. Name your topic to help you understand what the SNS is for.

6. Copy and paste in your display name.

7. Click create topic in orange box

8. Click create subscription in orange box.

9. Select your topic name you created.

10. Select your protocal for example email or sms.

11. Click create subscription in orange box.

12. Open your email and confirm your subscription to the SNS you created to be notified.

## Create Alarm.

1. Search EC2 in search bar and select EC2.

2. Select the instance you would like to create an alarm for.

3. Click the `Actions` tab at the top.

4. Click `Monitor and troubleshoot` then select `Manage CloudWatch alarms`

5. Select `create and alarm box`

6. Under `Alarm notification`, select the SNS topic you created.

7. `Alarm actions` is optional depending on your requirement.

8. Set up the `Alarm thresholds` depending on your requirement.

9. Click `create` in the orange box.

# Create CloudWatch