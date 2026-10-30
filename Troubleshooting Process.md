## Initial Findings

Task Manager showed that CPU utilization had climbed to approximately 95–100%, while memory usage was around 80–83%.

Disk and network usage were relatively low, so they did not appear to be the main cause of the slowdown.

Looking at the Processes tab, Outlook was one of the highest CPU-consuming applications. Multiple Outlook-related processes were using a significant amount of processor time.

Resource Monitor confirmed that CPU usage was consistently very high and showed additional background processes contributing to the overall load.

## Troubleshooting Process

I started by checking Task Manager to get a quick overview of system performance.

I reviewed:

- CPU utilization
- Memory usage
- Disk activity
- Network activity

Since CPU usage was significantly higher than the other resources, I focused on identifying which processes were responsible.

I then used Resource Monitor for a more detailed view of running processes and system activity.

This helped confirm that the slowdown was mainly related to high CPU usage rather than a disk or network problem.

## Remediation

I closed Outlook first because it was one of the main CPU consumers.

After closing Outlook, CPU usage dropped from near 100% to below 40%, and memory usage decreased from around 83% to approximately 65%.

I then closed several other unnecessary applications that were still running in the background.

After that, CPU usage returned close to idle levels, and memory usage dropped further to approximately 48%.

## Result

The performance issue improved significantly after closing the applications that were using the most system resources.

This confirmed that the slowdown was application-driven rather than being caused by disk, network, or hardware failure.

## What I Learned

This lab helped reinforce the difference between Task Manager and Resource Monitor.

Task Manager is useful for quickly identifying which system resource is under pressure and which applications are using the most CPU, memory, disk, or network bandwidth.

Resource Monitor provides a more detailed view and makes it easier to investigate individual processes and resource usage in more depth.

The main takeaway from this lab was that it is better to identify the actual bottleneck first instead of assuming the system is slow because of memory, disk, or network issues.

## Skills Demonstrated

- Windows performance troubleshooting
- Task Manager
- Resource Monitor
- CPU and memory analysis
- Process-level troubleshooting
- Performance remediation and verification
