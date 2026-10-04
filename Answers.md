# Answers to Part 3

Add your answers to the questions in Part 3, Step 2 below.

## Vulnerability Remediation:
### Vulnerability 1:
1. Which package or library are you addressing?

   Pillow 9.4.0

2. Which CVE is linked to this vulnerability?

   CVE-2023-50447

3. What remediation steps do you suggest?

   Upgrade Pillow to version 10.2.0 or later. This version contains the security fix for the arbitrary code execution vulnerability. The Pillow version in requirements.txt should be updated to a non-vulnerable version.

### Vulnerability 2:
1. Which vulnerability are you addressing?

   PyYAML 5.1

2. Which CVE is linked to this vulnerability?

   CVE-2019-20477

3. What remediation steps do you suggest?

   Upgrade PyYAML from version 5.1 to version 5.2 or later. This addresses the unsafe deserialization vulnerability caused by insufficient restrictions in the load and load_all functions when processing YAML content.