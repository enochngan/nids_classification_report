# nids-classification-report

## Introduction:
The classification report for this project evaluates the performance of the Snort Network Intrusion Detection System (NIDS) in distinguishing between malicious and legitimate traffic across various scenarios. The report highlights key metrics such as precision, recall, F1-score, and accuracy to quantify the effectiveness of predefined Snort rules in detecting simulated cyberattacks and normal user activities.

## Goals:
Precision: Indicates Snort's ability to correctly identify malicious traffic without flagging legitimate activity. High precision reflects fewer false positives, ensuring that legitimate actions (e.g., normal SSH logins) are not incorrectly flagged as intrusions.

Recall: Measures Snort's success in detecting malicious traffic, even in complex scenarios like SQL injection or port scans. High recall suggests that most attack attempts were accurately identified.

F1-Score: Balances precision and recall, providing a comprehensive metric to evaluate rule performance.

Accuracy: Overall effectiveness of Snort in correctly classifying traffic.

The classification report further compares the results of multiple rule sets, demonstrating how rule tuning affects Snort's ability to minimize false positives (FPs) and false negatives (FNs). These findings are essential for improving rule specificity and balancing detection capabilities, ensuring robust protection against cyber threats while maintaining normal network functionality.

## Purpose:
This analysis provides actionable insights for refining intrusion detection rules to optimize the trade-off between sensitivity and specificity.
