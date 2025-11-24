# Anh Trai C2

**Category:** Network Forensics / Traffic Analysis  
**Difficulty:** Medium

## Scenario

> "I just wanted to calculate the budget!"

Mai, a senior accountant at *Global Corp*, downloaded a software tool that promised to help with her complex financial calculations. She ran the program, and for a moment, it seemed to work. However, shortly after, she noticed that the values in her important company files had been changed, and strange encrypted files started appearing in her documents folder.

The security team quickly isolated her machine and captured the network traffic during the incident. We believe the tool was actually a Trojan communicating with an external server controlled by the attacker.

## Questions

1. What suspicious file did the victim download?
2. Which DLL did the malicious program load?
3. Into which process did the malicious program load the DLL?
4. Which C2 framework did the attacker use?
5. What was the first command the attacker ran on the victim’s machine?
6. What files did the attacker upload to the victim’s machine? (List in chronological order, earliest-latest. Format: `filename1-filename2-...`)
7. There is a secret in one of two files. Find it.
    
## Files

- **Challenge Files:** Located in the `sources` folder.
- **Solution:** Located in the `solution` folder. Note that the solution is encrypted with the flag itself.

