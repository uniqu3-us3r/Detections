# Detections

Sigma detection rules and research for emerging threats and vulnerabilities.

Each detection is grounded in real exploit traffic, log artifacts, or
proof-of-concept behavior, and organized one folder per CVE.

## Conventions

- **Format:** [Sigma](https://github.com/SigmaHQ/sigma); multi-stage detections use correlations over small base rules.
- **Filenames:** `<source>_cve_<year>_<number>_<descriptor>.yml` — `web_`, `host_`, `proc_`, or `net_` by telemetry source.
- **Status:** all rules are `experimental` — baseline and tune before alerting.

## Disclaimer

Provided as-is, without warranty. Any proof-of-concept or test scripts are for
authorized security testing only.

## License

See [LICENSE](LICENSE).