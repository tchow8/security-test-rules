Security Test rules for ZAP

This repository consists of rules that are used for for nightly security tests

Usage:

When executing the security scan using "zap-api-scan.py" use this rules by configuring like below

zap-api-scan.py -t ${TEST_URL}/v2/api-docs -f openapi -u ${SecurityRules} -P 1001
