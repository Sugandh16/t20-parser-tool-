This project implements a T20 command parser in Python that decodes and interprets hexadecimal command strings used in Conditional Access (CA) / Set-Top Box (STB) systems. Each command contains an action code followed by structured fields like Card Number, Profile ID, Service ID, Expiry Dates, and Signatures.

The parser dynamically looks up action codes, extracts fields based on predefined formats, validates input, and returns human-readable outputs with error handling.
