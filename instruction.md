Please write a Python script to analyze the Apache-style access log located at `/app/access.log` in the current working directory. 

Your script should parse the file and generate a JSON summary report at exactly `/app/report.json`.

The output JSON file must strictly contain the following keys:
1. "total_requests": The total count of all valid, non-empty log entries.
2. "unique_ips": The count of distinct client IP addresses present in the log.
3. "top_path": The most frequently requested URL path (e.g., "/index.html").

Ensure the JSON report is well-formed, contains the exact matching keys, and that all counts are computed accurately.
