# Data-Science-Projects
Title: Unsupervised Network Intrusion Detection System using Isolation Forest
Abstract & Project Overview
Network Intrusion Detection Systems (NIDS) are critical defense mechanisms designed to identify malicious activity and unauthorized access across modern computing infrastructure. Traditional signature-based detection models struggle against novel threats ("zero-day" attacks) because they rely on pre-existing attack signatures. To address this limitation, this project implements an unsupervised machine learning approach using the Isolation Forest algorithm.

By operating in an unsupervised capacity, the Isolation Forest model models baseline network behavior using normal or mixed traffic from a training dataset, isolating anomalies based on how quickly data points can be partitioned within decision trees. Because anomalous network intrusions typically possess distinct feature profiles compared to normal traffic, they require fewer random splits to isolate, making this algorithm uniquely efficient for high-dimensional network telemetry.
