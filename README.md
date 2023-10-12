# security-dashboards

This is a demonstration of how to build a dataset of active security incidents. The python file requires a GitHub personal access token to pull the security advisories in an org and then filters down to unpublished incidents. The personal access token requires the following rights: `Read access to metadata and repository advisories`

Another access token is required for Grafana to read the csv file. The token needs the following permissions: `Read access to code and metadata`
