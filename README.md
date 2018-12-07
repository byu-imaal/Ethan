# Ethan
Syntax: ConvReader.py pcap_filename.pcap dns-query-logs-minimal.txt
It's of import that the program is currently set up to parse dns query logs in minimal format only.

Output files:
conv_sum2 - spf protocol evaluations
conv_summary - a more in depth summary
lazy_spf,no_spf,parallel_spf,serial_spf,soft_dmarc_spf,strict_dmarc_spf - dumps for spf conversations of the described categories.
