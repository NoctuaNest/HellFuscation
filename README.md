
# Hellfuscation

Hellfuscation (HF) is currently in phase 1 of development, only its base features has been developed and tested, Phase 1 features a Semi-Fileless Visual Basic Script (VBS) obfuscator. After HF ingests a VBS file, it will output a semi-fileless version of them. This allows it to run from the physical VBS file will keeping important runtime information in memory. Meaning if it's stopped for any reason, the runtime information is lost, the file can not run again, and it will become harder to de-obfuscate as variables will not have any values.

